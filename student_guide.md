<h1 align="center">Student Bootcamp Recommendations Guide</h1>

> The best way to view this guide is to use VSCode's built-in Preview feature.
>
> - Open this document in VSCode and right-click on the current text editor's tab and select `Open Preview`.
>   Also: Shift + Cmd(Mac)/Ctrl(Win) + V
>   <br>

# Homework Workflow

## 1. Initialize Repo

- When beginning a homework assignment, I strongly recommend starting with creating a GitHub repository.
- There should be instructions within the **04-Important** folder of the first unit folder within your class repository titled, **Steps To Upload to Github**.

> Pro-Tip: I also recommend that all of your projects be stored in a **Projects** folder from within your user's root directory.
>
> - On a Mac: /Users/(username)/Projects
> - Windows: C:\Users\\(username)\Projects

## 2. Find Starter Code

- Navigate to your Class Repository.
- For most bootcamps, the Class Repo is structured as:

> Class-Code >> ##-Unit-Name >> 02-Homework >> Develop

- Aside from the first few homework assignments, the Develop folder has important starter code to support your progress in the assignment.
- If you are in a virtual bootcamp, your starter code should be located within your modules.

## 3. Copying Files from Develop

- Once you have a repo cloned into your **Projects** folder, copy all the files from the Develop folder into this new repo.
- Once the starter code files are copied to their destination, perform the `git add`, `git commit`, and `git push` steps.

<br>

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

# Google Search & Top Websites

## Tips for Troubleshooting and Searching

- If you're spending more than 20-30 minutes on an issue or project goal...Google it!
- Always include the applicable language in the Google search (ex. JavaScript, react, mysql).
- If you are seeing a specific error in the console or on the page, copy the non-user-specific parts directly into the Google search.
- Use the following framework to assess a search result's applicability:
  - Is this article using the same tech stack?
  - Is this article within a similar level of complexity as to my current knowledge or goal? As in, is 60-80% of the code recognizable?
  - Is this article at least 75% related to my current issue or goal?
- If an article has passed the test above, then carefully review the material from the top.
- It's okay to have to look up unfamiliar terms in another tab while you work through the main article, as long as the amount of unfamiliar terms stays within the 60-80% recognizable range.

Lastly, if you get stuck and are spending more than a few hours on an issue or goal:
- Reach out to a classmate, TA or instructor!
- Ask your SSM about the AskBCS Learning Assistant tool!
- Reach out to your tutor!

## Top Websites for Troubleshooting and Learning

### 1. [W3Schools](https://w3schools.com)

W3Schools is an excellent first-line resource when you want a high-level understanding of a particular topic.

### 2. [Stack Overflow](https://stackoverflow.com)

Stack Overflow articles are also excellent resources for very specific use cases.

### 3. [Mozilla Documentation Network (MDN)](https://developer.mozilla.org/en-US/docs)

MDN Web Docs are an excellent resource for a more technical deep-dive understanding of a particular topic, especially for JavaScript functions and APIs.


<br>

# VSCode Pro-Tips

### Auto-Save

### Previewing .md files

### Favorite Shortcuts

### Best VSCode Extensions (highlight matching tag, auto rename tag)

### Split Down/Right

https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf

<br>

# JavaScript 101s

### equal sign as assignment operator

### console is your friend

### java != javascript

<br>

# Backend ProtTips

### nodemon

<br>

# Command Line Tips

```
./
..
~
up arrow
```

<br>

# Post-Bootcamp & Career Life

### [Biggest Fears Post-Bootcamp](https://docs.google.com/document/d/12PU7WN6YTF-XAswPaYOBFMwfJDoGDbtaaxMvhGj2xMQ/edit)

### [LinkedIn](https://www.linkedin.com)

### Code for America/City

### Exceptions Welcome Podcast

### Civic Tech

### Techies for Good

### Resume / BC Action

### Crash-course computer science

<br>

# Data Structures & Algorithms

### Algorithms folder

### [LeetCode](https://www.leetcode.com)

<br>

# Tech & Software Careers to Search

sales engineering, implementation, infrastructure, secdev, integration, or network engineering
technical writing and  web accessibility
support engineering
