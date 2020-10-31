# Troubleshooting Tips 👩‍🏭

## General Tips 👩‍🏫

- If you're spending more than 20-30 minutes on an issue or project goal...Google it!
- Always include the applicable language in the Google search (ex. JavaScript, react, mysql).
- If you are seeing a specific error in the console or on the page, copy the non-user-specific parts directly into the Google search.
- Use the following framework to assess a search result's applicability:
  - Is this article using the same tech stack?
  - Is this article within a similar level of complexity as to my current knowledge or goal? As in, is 60-80% of the code recognizable?
  - Is this article at least 75% related to my current issue or goal?
- If an article has passed the test above, then carefully review the material from the top.
- It's okay to have to look up unfamiliar terms in another tab while you work through the main article, as long as the amount of familiar terms stays within the 60-80% recognizable range.

Lastly, if you get stuck and are spending more than a few hours on an issue or goal:
- Reach out to a classmate, TA or instructor!
- Ask your SSM about the AskBCS Learning Assistant tool!
- Reach out to your tutor!

<br>

## Top Websites for Troubleshooting and Learning 🏆

### 1. [W3Schools](https://w3schools.com)

W3Schools is an excellent first-line resource when you want a high-level understanding of a particular topic.

### 2. [Stack Overflow](https://stackoverflow.com)

Stack Overflow articles are also excellent resources for very specific use cases.

### 3. [Mozilla Documentation Network (MDN)](https://developer.mozilla.org/en-US/docs)

MDN Web Docs are an excellent resource for a more technical deep-dive understanding of a particular topic, especially for JavaScript functions and APIs.

<br>

## `console.log` is your friend 🥂
- Do not forget the importance of entering `console.log` throughout your code to troubleshoot unexpected behavior!
- This means that when you are not seeing a certain line of code execute, attempt to place a `console.log` statement of the important variables to determine why your code is not functioning.
- example:
    - ```js
      var x = 5
      var y = "5"
      // place console.logs here to pre-analyze the operands in the conditional
      console.log("x is ", x);
      console.log("y is ", y);
      if (x === y) {
          // check if this is executing by placing a console.log at the top.
          console.log("from conditional comparing x and y");
          document.getElementById("mainPage").innerHTML = "Hola Mundo!";
      }
      ```

<br>



<hr>

## [Back to Table of Contents](./README.md)