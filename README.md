# Git Learning Journal

My first GitHub project while preparing for a career in QA Automation while continuing to explore live coding and creative coding.

## About this repository

This repository documents my learning journey with:

- Git and GitHub
- JavaScript fundamentals
- Test automation
- Software Quality Assurance (QA)
- Live coding and generative visuals

## Day 1

Completed:

- Installed my development environment
- Configured Git
- Created my first GitHub repository
- Made my first commit and push 🚀

## Day 2

Completed:

- Created a new repository: javascript-playground
- Wrote and executed my first JavaScript program using Node.js
- Connected a local repository to GitHub
- Solved a GitHub authentication issue by switching from HTTPS to SSH
- Successfully pushed my project to GitHub

### What I learned

Although I spent time troubleshooting, I now have a much better understanding of how Git and GitHub work together.

## Day 3

Today I started learning JavaScript fundamentals.

Completed:

- Created my first JavaScript variables
- Learned how the `let` keyword works
- Learned how variables store values
- Practiced using `console.log()` to display information
- Learned how to update variable values
- Created a small personal introduction program
- Debugged my first JavaScript issue
- Updated my code and pushed the changes to GitHub

## Day 4

Playwright Project Setup & First Test Run

Completed:

- Created Playwright TypeScript project
- Configured Git repository
- Installed Playwright with TypeScript support
- Configured the test environment
- Installed Chromium browser
- Executed first automated Playwright tests successfully
- First test run result: 2 passed

Next Steps:
  
- Understand Playwright project structure
- Learn the role of:
    - playwright.config.ts
    - test files
    - locators
    - assertions
- Create the first automated login test
- Refactor the login test using the Page Object Model (POM)

## Day 5 - JavaScript Playground: Operators and If/Else Logic

Today I continued building my JavaScript Playground project and practiced how programs can make decisions.

I learned how operators work in JavaScript:

* Mathematical operators:

  * `+` addition
  * `-` subtraction
  * `*` multiplication
  * `/` division

I also practiced comparison operators:

* `===` checks if two values are exactly the same (value and type)
* `!==` checks if two values are different
* `>` and `<` compare numbers

A very important lesson was understanding that data types matter. For example:

```javascript
10 === 10
```

returns `true`, but:

```javascript
10 === "10"
```

returns `false` because one is a number and the other is a string.

After operators, I started learning conditional logic with `if` and `else`.

I created my first simple login validation example:

```javascript
let password = "12345";

if (password === "12345") {
    console.log("Login successful");
} else {
    console.log("Wrong password");
}
```

This helped me understand how a program can check a condition and choose different actions depending on whether the result is `true` or `false`.

I also tested different cases:

* correct password → Login successful
* wrong password → Wrong password
* empty password → Password is required

This was interesting because it feels closer to real QA automation thinking: checking expected results for different inputs.

Today I connected several JavaScript basics together:

* variables
* data types
* booleans
* comparison operators
* logical operators
* if/else decisions

The next step will be making the logic more realistic with `else if` and building towards a small login validator project.

