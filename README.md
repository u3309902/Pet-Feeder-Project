# Pet-Feeder-Project

An automated pet feeder system that dispenses food based on scheduled feed times, checks if pet has eaten, and monitors food levels.

## Table of Contents


## Features
- Scheduled feeding at 8 AM and 6 PM
- Bowl weight sensor to detect uneaten food
- Food level sensor to prevent empty dispensing
- Alerts for low food or uneaten meals

## Usage
- System checks time and feeds pet if bowl is empty
- Sends alerts if food is unavailable or pet hasn't eaten

## Testing Scenarios
| Scenario               | Expected Output                          |
|------------------------|------------------------------------------|
| Pet eats as expected   | Food dispensed and empty bowl, no alert  |
| Pet does not eat       | Alert: "Bowl still full – pet may not have eaten" |
| Food bin is empty      | Alert: "Food not available"              |

