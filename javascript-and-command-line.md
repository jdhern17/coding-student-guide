# JavaScript 101s 📚

## Equal Sign `!=`  equals!
- The equals sign `=` in JavaScript is not the same thing as the equals sign in Math!
- The equals sign `=` is referring to the programming concept of assignment.
- This means that the program will evaluate the right side of the assignment operator `=` and assign the resulting value to the variable on the left side.

<br>

## `console.log` is your friend
- Do not forget the importance of entering `console.log` throughout your code to troubleshoot unexpected behavior!
- This means that when you are not seeing a certain line of code execute, attempt to place a `console.log` statement of the important variables to determine why your code is not functioning.
- example:
    - ```js
      var x = 5
      var y = "5"

      if (x === y) {
          // check if this is executing by placing a console.log at the top.
          console.log("from conditional comparing x and y");
          console.log("x is ", x);
          console.log("y is ", y);
          document.getElementById("mainPage").innerHTML = "Hola Mundo!";
      }
      ```

<br>

## `java` != `javascript`
- While it can be easy to confuse the two, please note that these are two separate languages!

<br>

# Command Line Tips 💻

Entering the following into the command-line or within a command-line statement reference the following:

- `./`: Current folder.
- `../`: Parent folder.
- `~`: Home/Root folder. 
- `↑` (up-arrow): Show previously entered command.


<br>

# Backend Tips 🛠

For later in the bootcamp,

## [nodemon](https://www.npmjs.com/package/nodemon)
- nodemon is a tool that helps you build the server-side applications by automatically researting the node application whenever any file changes are detected in the server-side files.

<br>
<hr>

## [Back to Table of Contents](./README.md)