# Problem Statement

## Freelance Quote Builder

A freelance designer prepares project estimates for clients. At the moment, the designer calculates costs manually and writes each quote separately. This can cause calculation errors and inconsistent presentation, especially when a project includes partial hours of work.

The designer needs a simple terminal tool that prepares a readable, consistent project estimate from the information entered for one project.

### Estimating Rules

- Collect the client name, project title, estimated work hours, hourly rate, and estimated materials or other direct expenses.
- Work hours may include partial hours.
- Calculate labor cost by multiplying estimated work hours by the hourly rate.
- Calculate the total estimate by adding direct expenses to labor cost.
- Remove surrounding whitespace from both text inputs using `.strip()`.
- Use `.title()` for the client name as a simplified lab convention. Preserve the project title's capitalization.
- Display the client name, project title, hours, hourly rate, labor cost, direct expenses, and total estimate.
- Display monetary amounts in dollars with two decimal places, including the hourly rate.
- Clearly label the quote as an **estimate**. It is not a final bill.

### The Need

The solution should be simple to use from a computer terminal and help the designer communicate the expected project cost clearly. The designer should be able to enter the project information once and see the complete estimate.

Here is one illustrative interaction:

```text
Client name:   aLEX tAYLOR  
Project title:   Website Refresh  
Estimated work hours: 7.5
Hourly rate: 40
Direct expenses: 25

PROJECT ESTIMATE
Client: Alex Taylor
Project: Website Refresh
Estimated hours: 7.5
Hourly rate: $40.00
Labor cost: $300.00
Direct expenses: $25.00
Total estimate: $325.00
```

The text entries above include surrounding spaces. Your prompts and quote layout may differ from this example as long as they follow the estimating rules.

### Implementation Expectations

Keep your implementation within CS50P Week 0: functions and variables.

- Use a `main()` function to organize the interaction, and call it to start the program.
- Include at least one calculation function that accepts multiple parameters and returns a numeric result.
- Include a separate function that displays the quote.
- Choose your own function names and decide how to organize the remaining logic.
- Pass information between functions through parameters and return values. Plan for variables to be local to the function where they are created.
- Use readable names and formatting. Write pseudocode during planning before implementing your design.

### Assumptions and Limitations

Assume users enter valid, nonnegative numeric values without dollar signs or commas. Direct expenses may be zero. The tool prepares one estimate per run.

You do not need conditionals, loops, exception handling, libraries, file storage, or automated tests. Invalid numeric input may cause the program to crash; document this limitation in your planning and submission rather than adding input validation. Title capitalization is a lab convention and may not reflect every client's preferred name formatting.
