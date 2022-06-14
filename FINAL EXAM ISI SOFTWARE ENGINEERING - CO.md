FINAL EXAM ISI SOFTWARE ENGINEERING - COMPUTER SCIENCE 2022
Instructor: Abdullah Wafy

Student Name (please type):

- There are 4 parts: DOM Concepts, JS DOM Methods, Mini-Project, GitHub Repo.
- Exam Format: MCQs, Short Answer Fill-in the Blank, Coding, Terminal Commands
- 26 points total
  
Part I: Conceptual Knowledge - DOM Questions (3 points total)

NOTE: DOM stands for 'DOCUMENT OBJECT MODEL'.

Mark answers with an asterisk "*" (i.e. shift + 8). E.g.:

```
How does one mark an answer?
*a) Shift + 8 (correct)
b) However you want
```

1. What is the DOM? (1 point)
a) It is an HTML file linked to a JavaScript file.
*b) It is a replica (i.e. copy) of the HTML file manipulated (i.e. changed) via JavaScript.
c) It is a JavaScript file linked the HTML file.
d) None of the above.

2. Where is the DOM? (1 point)
a) In your folder, on the your computer.
*b) On the browser which you may access via Chrome's Developer Tools (i.e. Inspect).
c) On Github in a repository.

3. How does one maniplate the DOM? (1 point)
a) You add HTML elements to the HTML file and can delete them.
b) You manipulate it via the browser using Chrome's Developer Tools (i.e. Inspect).
*c) Through a JavaScript file that is linked to an HTML file.

Part II: Practical Application Knowledge: JS DOM Methods (5 points total)

4. How does one create a new HTML element via JavaScript? (1 point)
const name = document.createElement();
______________________________________

5. How does one assign a new HTML attribute via JavaScript (just give one example)? (1 point)
name.setAttribute();

name.setAttribute("something", "something else")
______________________________________

6. How does one access an existing HTML element with an "id" using JavaScript? (1 point)
const name = document.getElementById();
_______________________________________

7. How does one add plain text to an HTML element? 
(1 point)
const para = document.createElement("p");
para.innerText = "plain text";
document.body.appendChild(para);
_______________________________________

1. How does one attach a newly created HTML element to a linked HTML file? (1 point)
<!-- <script src="file.name">

    </script> -->
_______________________________________

Part III: Mini-JS-Project (11 points total)

HINT: Make sure to store anything you create or access as 'variables' so you can use them later.

9. Follow all directions below:
- Create an HTML file with boilerplate code. Name it: `Final_Exam_ISI_CS_2022` with the correct file extension. (2 points - without this step you can't do the rest)
- Create a JavaScript file. Name it: `Final_Exam_ISI_CS_2022` with the correct file extension. (1 point - without this step you can't do the rest)
- Link (i.e. connect) your newly created HTML and JavaScript files together. (HINT: USE the `Script` element tag!) (1 point - without this step you can't do the rest)
- In your HTML file, add a `h1` HTML element tag with an `id` attribute of `my-final`. (2 points)
- In your JavaScript file "only", do all of the following using JS DOM methods:
  a) Create a new `div` element. (1 point)
  b) Give that newly created `div` element an `id` attribute of `new-div`. (1 point)
  c) Add filler code/dummy code (i.e. Lorem ipsum...) plain text to the newly created `div` element. (1 point)
  d) Attach the newly created `div` element to the `body` of your HTML element.(1 point)
  e) Access your paragraph element in your HTML with `id` of `my-final` and after accessing it add/insert the following plain text `Hello ISI, I am done!`. (1 point)

Part IV: GitHub Repository (7 points):

HINT: Be to sure to change directory (i.e. `CD`) in your terminal (command prompt) whenever you need to!

10. Follow all directions below:
  - Create a GitHub repository using your own account. Name it `Final_Exam_ISI_CS_2022`. Add a ReadMe file. Make it `public`. (1 point)
  - Clone it locally to your desktop.
  - Put your linked HTML and JavaScript final exam files in it. Also, put your final exam markdown file in it (meaing this file itself). (3 points)
  - CD into your local repo. (without this step you can't do the rest)
  - Do 3 git commands/operations to update your 'remote' repo with your 'local' one. (3 points)
  - Double check to see if your 'remote' repo is updated with all the necessary files. Your repo on GitHub should have the following 4 files:
  a) Readme file
  b) HTML file: Final_Exam_ISI_CS_2022
  c) JS file: Final_Exam_ISI_CS_2022
  d) Final_Exam_CS-2022.md file (this file itself)

NOTE BENE: If you haven't provided me your GitHub account URL address then make sure you do! (e.g. <https://github.com/your-github-account-goes-here>)