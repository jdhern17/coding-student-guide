# Pseudocoding & Learning Code

## How to start coding from scratch

A common questions many students have is how to begin an assignment or algorithm without a starting point. Here is a process that may help you build momentum.

### 1. Requirements Gathering

- Re-write the project's high-level goals in your own words in a `.js` file.

  - Ideally, break down each requirement into a short sentence as a comment.
  - To create a comment in javascript, begin the line with two forward slashes (`//`).
  - example:

    - ```js
      // need to create a rock-paper-scissors game

      // user will choose rock, paper or scissors
      // computer will make a choice
      // user sees result of whether they won or lost
      ```

### 2. Requirements Analysis

- Under each comment, add a prediction or user-interface description as to how each goal will be achieved:
  - You do not have to begin coding yet.
  - example:
    - ```js
      // user will choose rock, paper or scissors
      //// will the user select this from a dropdown? prompt?
      ```

### 3. Technical Details

- Once you have more detailed set of steps described, review your pseudocode and add more technical details where you can.
  - If you are unsure how to achieve a particular goal, write a note that you will research it later.
  - example
    - ```js
      // computer will make a choice
      // will this be done automatically? for loop?
      //// NOTE: need to research this
      ```

### 4. Research

- Review in-class activities or Google as necessary to address a technical goal.

### 5. Examples

- Run through an example user story or data set.
  - example
    - ```js
      // user chooses rock, computer chooses scissors
      ```

### 6. Grooming

- Continue reviewing and adding technical detail to your psuedocode until coding feels like a logical next step.

> Pro-tip: The main goal of this pseudocoding strategy is to continue pushing through the wall of doubt by adding more and more detail to your pseudocode.

## Coding for others

Ideally, your code should be heavily commented.

- The style of coding where you have a line of comment followed by a line of code is a great way for learners to make commenting and planning before coding a habit.
- Your comments should be easily readable by other developers, technical writers and your future self.
- Your variable names should be unique and descriptive.

```js
// prompt user for rock, paper or scissors
var userDecision = prompt("Would you like rock, paper or scissors");

// computer chooses at random from array
var compArr = ["rock", "paper", "scissors"];
```

## Using code found online

In a learning environment such as the coding bootcamp, it is challenging to know when code found online can be considered usable in projects. Following tutorials or using code snippets for your homework assignments is okay! However, you should take the following steps to ensure you are avoiding plagiarism:

- Give credit to the source.
  - Copying code found online and not attributing the source is plagiarism.
- Type out the code separately in your IDE (ex. VSCode)
  - Do not simply copy and paste the code.
- Customize the code to your needs.
  - Writing variable and function names as they relate to your current project.
- Comment the code heavily with your understanding of the functionality.
  - You should never copy the code from a tutorial or online repo without understanding `line-by-line` how it works. 
  - You should be able to explain to anyone, technical or non-technical, what the code is doing.

<br>
