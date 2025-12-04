# Task 1 - Rock Paper Scissors  

Create a single function (the skeleton has been provided for you). The function must be capable of 'playing' a single round of the classic game 'Rock, Paper, Scissors':

**Rock beats Scissors, Scissors beats paper, Paper beats rock**

When called, the function should return the winning player reference (i.e., 'player1' or 'player2' or 'draw') as a single string.

You should test your solution yourself by making your own sufficient calls to your function so that you are positive that it works as expected, regardless of the included tests.

Your final version should demonstrate evidence of being refactored; please note, refactoring is not bug-fixing - essentially it is reducing complexity and simplifying your codebase such that it is as efficient, readable, structured and as manageable as possible.

Some example calls to the function:

```python
rock_paper_scissors("paper", "paper")    # should return "draw"
rock_paper_scissors("scissors", "paper")  # should return "player1"
rock_paper_scissors("paper", "scissors")  # should return "player2"
```

## Additional criteria.

Once you have the basic version working, extend your function so that it supports Sheldon Cooper's 'Big Bang' version 'Rock, Paper, Scissors, Lizard, Spock'. Remember to carry out your own tests by calling the function. Here are the rules:

* Rock beats Scissors.
* Paper beats Rock.
* Scissors beats Paper.
* Lizard beats (poisons) Spock.
* Spock beats (smashes) Scissors.
* Rock beats (crushes) Lizard.
* Paper beats (disproves) Spock.
* Scissors beats (decapitates) Lizard.
* Lizard beats (eats) Paper.
* Spock beats (vaporises) Rock.
  
  
## Submission Checklist

Prior to actually submitting your final attempt you should ensure you have reviewed and considered the following checklist.


1. Refactored ```rock_paper_scissors``` function.
2. Appropriate Docstring for the `rock_paper_scissors` function.
3. Does your solution follow accepted coding conventions?




## Tasks 1-4 Coding Standards rubric

| Marks | Criteria |
| :---- | :---- |
| **Outstanding (80%+)** | The submitted code is highly optimised and a very clean, robust solution that goes beyond the basic requirements. Implementation shows advanced or creative methods (like efficient data structures or advanced Python features) demonstrating professional software principles.  The code uses pure functions and minimal nesting (max 1 level).  The Version Control history is clear, showing small, logical, and descriptive commits with a smooth development path from start to finish. |
| **Distinction (70-79%)** | Code is an elegant and efficient solution that matches industry-standard practice (e.g., PEP 8).  The design shows a solid understanding of software principles (DRY, KISS) and prioritises readability.  Functions are discrete, and deep nesting is avoided.  A comprehensive, correctly formatted Docstring is included.  Comments are rare and only for information.  Commits are regular and timely, clearly showing the solution's gradual development. Commit messages are consistently descriptive and helpful. |
| **Merit (60-69%)** | Code is well-structured and follows industry best practices.  DRY and KISS principles are applied, and functions are discrete.  Deep nesting is generally avoided. A clear and appropriate Docstring is included for the main function.  Naming is clear and formatting is consistent.  Comments clarify non-obvious logic.  Commits are generally regular, showing a clear progression. Commit messages are mostly descriptive but may lack consistency or focus at times. |
| **Pass (40-59%)** | Code is functional and organised, but needs refinement on professional conventions (e.g., minor issues in naming or formatting).  Logic may be repetitive (DRY issues), and there's some structural complexity due to moderate nesting (3+ levels).  A Docstring may be incomplete, poorly formatted, or missing.  Comments can be redundant or inconsistent.  Commits are present but can be irregular, with some large jumps in functionality. Commit messages are often brief or generic. |
| **Fail (\<40%)** | Code needs significant work on clarity, maintainability, and structural design.  There are repeated violations of core principles (DRY, KISS), and structural complexity is high.  Docstrings are missing, and comments are unhelpful.  The Version Control history contains long gaps, or the repository has only one or two large commits that don't show how the project developed over time. |
| **0%** | No attempt, or no code submitted. |


