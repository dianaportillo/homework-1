# Git Challenge Code Refactor
## Refactoring webage for Horiseon company.

--- Overview
Given a code we will improve the webpage without changing what it does. Make the webpage more accessible to meet specific requirments for users with disabilties. 

### The Challenge:
A company has given me a task to refactor their webpage to make it more accesible for people with accessibility needs. Therefore, I will make changes to the code without changing how the page looks. This should improve the webpage and create the accessible requirements the company is looking for. 

### User Story:
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

### Acceptance Criteria:
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title

### Screenshot:
Demo image provided by company:
https://github.com/dianaportillo/homework-1/issues/1#issue-1221908893

## My Process:
After thorough observation of the code I removed all the <div> tags. I replaced them with HTML semantic elements I improved the code by keeping it DRY eliminated repetitive CSS styles and grouped them together under a class. I added alt attributes to images as well as ensuring all images had the src attribute as well. 

### Built With:

- HTML Semantic Elements: 
<section>
<main>
<aside>
<header>
<nav>

- CSS:
Added aside classes to ensure images were properly displayed.
Used nav tags to give a navigation bar at the top of the page.

### What I learned:
From this challenge I learned that <div> usually has no meaning. To help read and follow the code it is best to use semantic elements. Refactoring a code is used to improve the code witout changing its function. Keeping a code DRY is eliminating things that are repetitive and useless. 

## Author
- Website - Diana Portillo (file:///Users/dianaportillo/Documents/bootcamp/homework/homework1/index.html)
