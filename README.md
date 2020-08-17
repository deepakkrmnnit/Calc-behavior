# Calculate Behavior

This project works out five features of a calculator:

1. Addition
1. Multiplication
1. Division
1. Subtraction
1. Power-on and power-off

Each feature would consist of scenarios.
Capture each scenario as:

- initial condition (Given...)
- event (When...)
- effect (Then...)

Each feature is in a different markdown file.
This template has one blank starting point.

As always, avoid passive voice :)

Scenario: Addition of two positive numbers
 Given The calculator with on
 When I type in "positive number"
And I press "plus"
And I type in "positive number"
And I press "equals"
 Then I see the "added number" as the result
 
 Scenario: Addition of two negative numbers
 Given The calculator with on
 When I type in "first negative number"
And I press "plus"
And I type in "Second negative number"
And I press "equals"
 Then I see the "added number" as the result
 
 
