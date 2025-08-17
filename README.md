# Pet-Feeder-Project

An automated pet feeder system that dispenses food based on scheduled feed times, checks if pet has eaten, and monitors food levels.

## Table of Contents
    Part 1: Analysis
        Overview of the problem, Goals and constraints, Initial assumptions, Block Diagram
    Part 2: Description of Data
    Part 3: Flowchart
        Logical flow of the automated feeding process
    Part 4: Word Coding
    Part 5: Test and Refine the Solution
        Test scenarios, Expected vs. actual outputs, Suggested improvements and refinements
    Reflection
        AI reflection
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

