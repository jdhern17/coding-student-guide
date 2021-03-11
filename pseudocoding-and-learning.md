# Pseudocoding & Learning Code 🧪

## How to start coding from scratch 🧩

A common questions many students have is how to begin an assignment or algorithm without a starting point. Here are two processes that may help you build momentum.

## Simplify then Complexify 🧮
### 1. Aim for a simple version of the app or algorithm.
- Once you have a rough idea of how the application or algorithm works, design a simple version of it.
- Shave off requirements that are secondary and focus on a simple version of the core product.
### 2. Add Complexity
- Once you have this simple version complete, add a layer of complexity.
### 3. Refactor
- Be comfortable refactoring! 
- This strategy will require you to constantly refactor your code, restructure functions and repurpose variables.
## Plan until Coding is Easy 📝
### 1. Requirements Gathering 🔊

- Re-write the project's high-level goals in your own words.
  - Break down each requirement into a short commented sentence.
  - Each comment should describe a small feature of the program.
  - example:

    - ```js
      // need to create a rock-paper-scissors game

      // user will choose rock, paper or scissors
      // computer will make a choice
      // user sees result of whether they won or lost
      ```

### 2. Requirements Analysis 📖

- Under each feature, add a user-interface description as to how the goal will be achieved.
  - You do not have to begin coding yet.
  - If you are not sure about how to achieve a goal, brainstorm an idea.
  - example:
    - ```js
      // user will choose rock, paper or scissors
      //// user will select this from a dropdown
      //// do we want a button here?
      ```
> Pro-tip: Imagine explaining how the program works to someone who cannot see the screen.

### 3. Technical Detailing ⚙️

- Once you have more thorough description of the program outlined, begin adding technical details.
  - You still do not need to be coding yet, but you may begin using technical terms learned in class.
  - If you are unsure how to achieve a particular goal, write a note that you will research it later.
  - example
    - ```js
      //// do we want a button here?
      //// we want an event listener

      // computer will make a choice
      // will this be done automatically? for loop? if statement?
      //// NOTE: need to research this
      ```

### 4. Grooming 🧹

- Continue reviewing and adding technical detail to your psuedocode until coding feels like a logical next step.
  - Clean up your comments with titles and by splitting features into technical solutions.
    - ```js
      // USER CHOICE SECTION
      // ...

      // COMPUTER CHOICE SECTION
      // ...
      ```

> Pro-tip: The main goal of this pseudocoding strategy is to continue pushing through the wall of doubt by adding more and more detail to your pseudocode.

### 5. Research 🔬

- Review in-class activities or Google as necessary to address a technical goal.

### 6. Examples 🎪

- Run through an example user story or data set.
- Write your program to solve a simpler version of a typical example, then begin solving for more complex scenarios.
  - example
    - ```js
      // example 1: user chooses rock, computer chooses scissors
      ```

### 7. Coding 💻

- Begin coding the simplest goals first, such as defining variables.
- Continue adding brainstorming thoughts and descriptions to more challenging requirements until you are ready to research a specific goal or begin coding.

> Pro-tip: Take the problem in pieces. Begin with easy examples and slowly add complexity to the task. For example, begin coding the program as if the user only selected one item instead of multiple. Then add complexity.

## Coding for others 🙌

Ideally, your code should be heavily commented and written for an audience.

- The style of coding where you have a line of comment followed by a line of code is a great way to make planning before coding a habit.
- Your comments should be easily readable by other developers and your future self.
- Your variable names should be unique and descriptive.

```js
// prompt user for rock, paper or scissors
var userDecision = prompt("Would you like rock, paper or scissors");

// computer chooses at random from array
var compDecisionArr = ["rock", "paper", "scissors"];
```

## Using code found online 🔍

In a learning environment such as the coding bootcamp, it is challenging to know when code found online can be considered usable in projects. Following tutorials or using code snippets for your homework assignments is okay! However, you should take the following steps to ensure you are avoiding plagiarism:

- Give credit to the source.
  - Copying code found online and not attributing the source is plagiarism.
- Type out the code separately in your IDE (ex. VSCode)
  - Do not simply copy and paste the code.
- Customize the code to your needs.
  - Rewrite variable and function names as they relate to your current project.
- Comment the code heavily with your understanding of the functionality.
  - You should never copy the code from a tutorial or online repo without understanding `line-by-line` how it works. 
  - You should be able to explain to anyone, technical or non-technical, what the code is doing.

<br>
<hr>


## [Back to Table of Contents](./README.md)