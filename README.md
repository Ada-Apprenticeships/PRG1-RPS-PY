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

| Marks | Programming Conventions and Code Quality |
| :---- | :---- |
| **Outstanding (80%+)** | The submitted code represents an **exceptional, highly optimised, and genuinely elegant solution** that demonstrates the student has **gone the extra mile** and exceeded the brief. The implementation utilises **advanced or creative methods** (e.g., highly efficient data structures or advanced Pythonic idioms) which may not have been explicitly taught, showcasing near-professional **software engineering principles**. The solution is perfectly clean, robust, and is structured with **pure functions** and **minimal nesting (ideally max 1 level)**. The response is sophisticated, achieving **conciseness and clarity without sacrificing readability**. |
| **Distinction (70-79%)** | The submitted code is an **outstanding, elegant, and efficient solution**, fully reflecting **industry-standard practice (e.g., PEP 8\)**. The design demonstrates a strong command of software design principles, adhering to **DRY** (Don't Repeat Yourself) and **KISS** (Keep It Small and Simple) while prioritising **readability**. The function structure is highly discrete, following a **'pure functions' paradigm** where appropriate, and **deep nesting is entirely avoided**. A **comprehensive, correctly formatted Docstring** is provided. **Comments are judiciously rare** and strictly informational. |
| **Merit (60-69%)** | Code is **highly competent**, well-structured, and aligns closely with industry best practices. There is **considerable evidence** of applying **DRY and KISS principles**, with functions being discrete and manageable. **Deep nesting is generally avoided**. The primary function includes a **clear and appropriate Docstring**. The solution uses clear naming and consistent formatting. **Comments are used sparingly** to clarify non-obvious logic. |
| **Pass (40-59%)** | Code is **functional and competently organised**, showing a developing understanding of professional conventions. There are areas for **further refinement** in adherence to style guides (e.g., minor inconsistencies in naming or formatting). Logic may be **somewhat repetitive (DRY issues)**, and structural complexity is occasionally present due to **moderate nesting (3+ levels)**. A **Docstring may be incomplete, poorly formatted, or missing**. **Comments may be redundant** or inconsistent. |
| **Fail (\<40%)** | Code requires **substantial work** to improve clarity, maintainability, and structural design. There are **repeated violations of core principles (DRY, KISS)**, and structural complexity is high. This suggests a **need for further development** in professional coding standards. Key elements like a **Docstring are missing**, and the use of comments is unhelpful. |
| **0%** | No attempt |


