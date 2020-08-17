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
 
 
Scenario: Addition of fractions
Given The calculator with on
When I type in "first fraction number"
And I press "plus"
And I type in "Second fraction number"
And I press "equals"
 Then I see the "added number" as the result

Scenario: Addition of +ve and -ve number
Given The calculator with on
When I type in "positive number" or "negative number"
And I press "plus"
And I type in "negative number" or "positive number"
And I press "equals"
 Then I see the "added number" as the result
  
Scenario: Addition of decimals
Given The calculator with on
When I type in "first decimal number"
And I press "plus"
And I type in "Second decimal number"
And I press "equals"
 Then I see the "added number" as the result


Scenario: Typing operator more than once
Given The calculator with on
When I type in "first number"
And I press "plus"
And I press "plus"
When I type in "second number"
And I press "equal"
 Then I see the "last press operator will work" as the result
 


Scenario: Addition of more than 2 numbers
Given The calculator with on
When I type in "first number"
And I press "plus"
When I type in "second number"
And I press "plus"
When I type in "third number"
And I press "equal"
 Then I see the "added number" as the result
 


Scenario: Adding numbers where the result goes out of range
Given The calculator with on
When I type in "first number"
And I press "plus"
And I type in "Second number"
And I press "equals"
 Then I see the "out of range exception" as the result
 
 
Scenario: 6+* is provided as input?
Given The calculator with on
When I type in "six"
And I press "plus"
And I press "multiplication"
And I press "equals"
 Then I see the "invalid operation" as the result



Scenario: Identify operation


Scenario: Converse operation
Given The calculator with on
