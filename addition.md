# Addition

Scenario: Addition of two positive numbers

Given The calculator with on

When I type in "positive number" And I press "plus" 
And I type in "positive number" And I press "equals"

Then I see the "added number" as the result

Scenario: Addition of fraction

Given The calculator with on

When I type in "fraction number" and I press "plus" and I type in "fraction number" and I press "equals"

Then I see the "added number" as the result

Scenario: Addition of positive and negative number

Given The calculator with on

When I type in "positive number" and I press "plus" and I type in "negative number" and I press "equals"

Then I see the "added number" as the result based on values

Scenario: Addition of decimals

Given The calculator with on

When I type in "decimal number" and I press "plus" and I type in "decimal number" and I press "equals"

Then I see the "added number" as the result

Scenario: Addition of more than 2 numbers

Given The calculator with on

When I type in "positive number" and I press "plus" and I type in "positive number" and I press "plus" and add till I press "equal"

Then I see the "added number" as the result

Scenario: Adding numbers where the result goes out of range

Given The calculator with on

When I type in "positive number" and I press "plus" and I type in "positive number" and I press "equals"

Then I see the "ERROR out of range" as the result 
