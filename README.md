# Javascript-practice-termOne
https://www.codewars.com/
all amandep's material videos: 
https://www.loom.com/share/folder/f6a943b6af2c44c09209fd7033b2480c

Let's try to understand programming in a lay man language.
Your magic box — PC or Laptop — can do incredible things, but it only understands a special language called "code." Programming is the art of writing instructions (code) that tell the computer what to do.
Now, think of programming like making a recipe. You gather ingredients (input), follow steps (execute), and finally, you get a delicious dish (result). Similarly, in programming, we need input from users, perform actions based on those inputs, and then show the result.
To build a program that adds two numbers together. First, you'd ask the user to give you two numbers (input). Then, you'd add those numbers together (execute). Finally, you'd show the user the result, which is the sum of those numbers.
In this process, the user's input is crucial. It's like giving instructions to a chef—you tell them what ingredients to use. The computer follows these instructions step by step, just like a chef following a recipe. Once it's done, it presents the result, whether it's a sum, a message, or something else entirely.
Programming languages are tools that help us write these instructions in a way that the computer can understand. Each language has its own syntax and rules, but they all serve the same purpose: to communicate with the computer and make it do amazing things!
Overall, remember: it's all about input, execution, and showing the result.
GATHER INPUT >> EXECUTE >> DISPLAY RESULT

Programming language that we'll learn in this course is "JavaScript"
Why JAVASCRIPT!!! How does JavaScript fits in web designing?
JavaScript plays a crucial role in modern web design, contributing to both the functionality and interactivity of websites. As a client-side scripting language, JavaScript is executed by the user's web browser, enabling dynamic updates and interactions without needing to reload the entire web page.
Javascript is popular in web design due to its diverse features :
Browser Compatibility: JavaScript is supported by all major web browsers, making it a versatile choice for web design. Additionally, modern JavaScript frameworks and libraries (such as React, Angular, and Vue.js) help streamline development and ensure cross-browser compatibility.
Interactivity: JavaScript allows for the creation of interactive elements such as dropdown menus, sliders, and forms that respond to user input. This interactivity enhances user engagement and improves the overall user experience.
Event Handling: JavaScript enables developers to define actions in response to various events, such as user clicks, mouse movements, or keyboard inputs. This capability allows for the creation of responsive and interactive interfaces.
DOM Manipulation: JavaScript provides access to the Document Object Model (DOM), allowing designers to manipulate HTML and CSS dynamically. This enables tasks such as adding, removing, or modifying elements on a webpage based on user actions or other events.
Dynamic Content: With JavaScript, you can dynamically update content on a webpage without requiring a full page reload. This enables real-time updates, such as displaying live data feeds, updating news tickers, or refreshing parts of a page asynchronously.
🔹 Try listing some of websites where you believe JavaScript is used to perform one or more of the features mentioned above.

Introduction to JavaScript Programming
First, we need to get some software so we can write and run our code. We'll be using a popular tool called Visual Studio Code.
The code we write will work fine on any modern web browsers. But for this course, we'll stick with Google Chrome to keep things consistent. If you don't have Chrome installed on your computer yet, please install it.
Step 1: Download Visual Studio Code & Google Chrome
Visual Studio Code (Choose a version compatible with your OS - Windows, Mac or Linux)
Google Chrome (Choose a version compatible with your OS - Windows, Mac or Linux)
Step 2: Watch videos to understand VS code tool and see our first programming output
VS Code - Creating Files + Adding Extension
Linking JS file + alert + console.log
Prompt - Gathering user input
Step 3: Read the content from following links
JavaScript Info: Variables
Programiz: Data Types (For now focus on string, number, boolean, undefined & null)
Programiz: Operators (Arithmetic, Assignment, Comparison & Logical Operators)
Step 4: Summarize your readings by watching a video. 
WATCH Video - Variable & Data Types in JavaScript
Additional Resources Link:
MDN: JavaScript data types and data structures

++++++++++++++++++++++++++++++++++++++++++
ASSIGNMENT 1  : 
Download the starter file named "A1Starter.zip".
Extract the zip and rename the folder to "A1-firstname-lastname"
Open the folder in VS code.
Assignment Tasks
NOTE: You are only permitted to make changes to the JavaScript file. No modifications are allowed in the CSS and HTML files, except for linking the JavaScript file to the HTML file.
A short video explaining the tasks - Video Link
Task 1 - Display your full name (1 points)
In the header section of the HTML file, there is an <h2> element with the id fullName. Write the JavaScript code to display your full name inside this <h2> element.
Before:

After:
Of course, you use your own name, instead of Amandeep Singh


Task 2 - Hide the Error container (1 points)
Target the container with red background and text "Error". Write JavaScript code to hide it. (Do not delete the element, only hide it.)
Before:

After:


Task 3 - Apply "bordered" class (2 points)
Target the appropriate elements from the DOM and apply the "bordered" class to them. Pay close attention to screenshot to identify which DOM nodes (elements) needs to be targeted.
Before:

After:


Task 4 - Display the Total Score (4 points)
Create a variable to store calculated total marks.
Read the default values from the input field, add them and assign to variable created in previous step.
Create a paragraph element generated by javascript. 
Display the following text in the newly generated paragraph - "Your total score is XXX/ 500." XXX is to be replaced by total calculated earlier.
Add the newly generated paragraph to the section with an id "outputArea".
Hint -Ensure you perform type conversion when reading values from the input box. By default, values read from an input field are in string format. For example, "50" + "50" will result in "5050", instead of 100.


Task 5 - Display average % in Result Area (2 points)
Generate a new paragraph element using JavaScript and add it below the paragraph from the previous task. This new paragraph should display the text: "Your average is XX %" 
Replace "XX" with the actual average.


For Task 4 & 5 - Your code must function so that if the default values of the input elements are modified in HTML file and the page is reloaded, the displayed total and average will update to reflect the new default values specified in the HTML.

=======week 2 ===========
Follow the content in following order:
Understanding the DOM
DOM Manipulation
String Concatenation & Interpolation
Reading Values from Input Fields
Type Conversions in JavaScript
▶ ️ Video lectures are attached at the end of respected sections.

Additional Resources Link:
getElementById()
getElementsByClassName()
querySelector()
Download


===assignment : 
Download the starter file named "A2Starter.zip".
Extract the zip and rename the folder to "A2-firstname-lastname"
Open the folder in VS code.
Assignment Tasks
NOTE: You are only permitted to make changes to the JavaScript file. No modifications are allowed in the CSS and HTML files, except for linking the JavaScript file to the HTML file.
A short video explaining the tasks - Video Link
Functionality 1 - On Click of "Start Game" (5 points)
If user didn't enter the name in the input box, display a message - "Please enter your name to start game"
Replace the user entered name with "Player 1" on the track.
Disable the "START GAME" button
Enable the "Roll Dice" button
Functionality 2 - On Click of "Roll Dice" (20 points)
Generate a random number between 1 to 6; display the generated number on the screen
If the dice number is even, increment the position of player.
If the dice number is odd, decrement the position of player.
Highlight the player position on screen. (Read hint)
Player cannot step back the start line once the dice is rolled for the first time; so the minimum position allowed is "step1".
Player cannot cross the Finish mark; so the highest position should be set to "step26"
 If the player is on "Start" and we receive an odd number, move them to 1.
Once player reaches the Finish mark:
Disable the "Roll Dice" button
Highlight the player position on FINISH mark
Display the count of moves made to reach the FINISH mark.
Hint -
Player position is highlighted on screen, using the class "current".
To generate a random number between 1 to 6; watch lecture content -> Math Objects Method - random()
Use global variables when you need to access the value in multiple functions.
====WEEK 3 +====================
This week, we will explore the concepts of learning outcomes through video lectures. I have also provided additional resources at the end for further understanding.
Follow the content in following order:
Functions - Part 1 & 2
Part 1
Part 2
Click Events - Part 1 & 2
Part 1
Part 2
Conditional Statements
If / Else
Switch
Variable Scopes
Global, Function & Block Scope
Difference between var & let
Debugging using browser inspector tool
Part 1
Math Object Methods
round, floor, ceil, trunc & random

If you prefer a text version of these concepts, please refer to the resources linked below. Personally, I find that reviewing text versions helps me quickly revise concepts, rather than watching a long video. I recommend watching the video lectures and coding along with me at least once. Afterwards, when you need to revisit the material, skimming through the text will be quicker.
🔹 The links below might cover additional topics beyond what we've discussed in our video lecture. If you understand these advanced concepts, that's great! If not, feel free to skip them for now. I've tried to keep the material simple and accessible for you. As you gain more experience, you'll be able to grasp these advanced techniques as well.
Functions Basics
Function Expressions (Basics & Advanced)
Arrow Functions
Conditional Statements - If / else
Debugging techniques using browser
W3Schools - Math Object (Focus on round, floor, ceil, trunc & random only)
Concepts-DemoCode
Zip Compressed File
 

GuessGame-Starter
Zip Compressed File
 

GuessGame-ClassDemo
Zip Compressed File
 

Submission
Assignment 2 - Race Game
Assignment

 Overdue - June 1 at 9:00 AM
This week, we will explore the concepts of learning outcomes through video lectures. I have also provided additional resources at the end for further understanding.
Follow the content in following order:
Functions - Part 1 & 2
Part 1
Part 2
Click Events - Part 1 & 2
Part 1
Part 2
Conditional Statements
If / Else
Switch
Variable Scopes
Global, Function & Block Scope
Difference between var & let
Debugging using browser inspector tool
Part 1
Math Object Methods
round, floor, ceil, trunc & random

If you prefer a text version of these concepts, please refer to the resources linked below. Personally, I find that reviewing text versions helps me quickly revise concepts, rather than watching a long video. I recommend watching the video lectures and coding along with me at least once. Afterwards, when you need to revisit the material, skimming through the text will be quicker.
🔹 The links below might cover additional topics beyond what we've discussed in our video lecture. If you understand these advanced concepts, that's great! If not, feel free to skip them for now. I've tried to keep the material simple and accessible for you. As you gain more experience, you'll be able to grasp these advanced techniques as well.
Functions Basics
Function Expressions (Basics & Advanced)
Arrow Functions
Conditional Statements - If / else
Debugging techniques using browser
W3Schools - Math Object (Focus on round, floor, ceil, trunc & random only)
Download

100 %3 of 3 topics complete
Show data table for This chart displays the number of completed topics versus the total number of topics within module Content..
List of Topics and Sub-Modules for Content
Concepts-DemoCode
Zip Compressed File
 

GuessGame-Starter
Zip Compressed File
 

GuessGame-ClassDemo
Zip Compressed File
 


=========ASSIGNMENT 3 ; 





Download the starter file named "A3Starter.zip".
Extract the zip and rename the folder to "A3-firstname-lastname"
Open the folder in VS code.
Assignment Tasks
NOTE: You are only permitted to make changes to the JavaScript file. No modifications are allowed in the CSS and HTML files, except for linking the JavaScript file to the HTML file.
A short video explaining the tasks - Click Here
Functionality 1 - On Click of "Start Game" (5 points)
If user didn't enter the name in the input box, display a message in result area or an alert - "Please enter both player names".
Replace the user entered name with "Player 1" , "Player 2" respectively on the track.
Enable the "Roll Dice" button.
If the game is already under play or finished. Click on "Start Game" shall reset everything to initial position.
Functionality 2 - On Click of "Roll Dice" (20 points)
Generate two random numbers between 1 to 6; display the generated number on the screen with respect to players dice positions.
If the associated dice number to player is even, increment the position of player.
If the associated dice number to player is odd, decrement the position of player.
Highlight the player positions on screen.
Player cannot step back the start line once the dice is rolled for the first time; so the minimum position allowed is "step1".
Player cannot cross the Finish mark; so the highest position should be set to "step26"
 If the player is on "Start" and we receive an odd number, move them to 1.
Once player reaches the Finish mark:
Disable the "Roll Dice" button.
Highlight the player position on FINISH mark.
If both players reach the Finish mark in the same move, display message - "There's a tie" in the results section.
             
Otherwise, display the name of player in the result area with the message - "PlayerName Win !"
            

Week 4 
Print
This week, we will take a break from learning any new concepts. Instead, I want you to focus on getting comfortable with thinking about program logic and breaking tasks into modular parts to avoid code repetition. We will practice a few examples in class based on the concepts we've learned so far.
This is also a good opportunity to catch up if you were feeling behind, as there isn't any new content to review.
In class, you will practice two examples, and then work on the homework assignment.
Download









Assignment Tasks
NOTE: You are only permitted to make changes to the JavaScript file. No modifications are allowed in the CSS and HTML files, except for linking the JavaScript file to the HTML file.
Click here for the video explanation on tasks.
To Do List - Lite Version (80%)
CODE ALONG VIDEO SERIES: Assignment 4 - Code Along
When adding a new item to the list with an empty text value, the input text box should receive an "error" class.
Display the new item with the added text in the <ul>
A new item can be added to the list by pressing the Enter key while the input is focused or by clicking the "Submit" button.
After adding an item to list:
Clear the text from the input box.
Keep the focus on the input box.
Remove the error class, if present.
The "Remove All Tasks" button clears all tasks from the list.
Clicking the "Sort" button sorts the items alphabetically (ignoring numerical sorting).
Sort can be case insensitive.
Clicking the delete icon removes the specific item from the list.
As the user types in the search box, the list is filtered to display only relevant items. If no items match the search, display the message "No Tasks Found" as a list item.
Search MUST be case insensitive.
The "Clear Search" button resets the list to show all added tasks.
To Do List - Plus Version
Everything from lite version, plus below: (10%)
CODE ALONG VIDEO SERIES: Assignment 4 - Plus Version
Use "Sort" button as toggle between sorting tasks OR displaying them in the original entry order.
If the Sort is turned on, apply background colour "lightgreen" to sort button.
If the Sort is turned on, adding new item to list shall automatically be added to the appropriate sorted position. However, when sort is turned off, newly added item arrange itself in the order of entry.
Self Task for Plus version (10%)
Duplicate tasks are not allowed.
 If a duplicate task is added, display the message "XXXXXX already added to the list." XXXXX being the original task text.
When adding a new item, it should be incorporated into the displayed list based on the current status of the "Sort" button and any search text:
If there is text in the search box, the new item should be displayed in the list if it matches the search text.
If the new item does not match the search text, it should be added to the main list.
The new item will be displayed once the search text is either removed or matches the item.
Self Task Video Explanation - LINK

WEEK 5 
This week we will start with learning another crucial concept "Iteration" that makes developer/designer life easier by avoiding the code repetition and introducing dynamism to our code.
Another topic to explore is "Arrays", to learn how they provide flexibility to store multiple data as collection within a single variable.
 Iterations
"for" loop
"while" loop
"do-while" loop
"foreach" loop
Arrays & its associated methods
Array declaration
.push()
.pop()
.shift()
.unshift()
.splice()
Download
Expand All  Collapse All

25 %1 of 4 topics complete
Show data table for This chart displays the number of completed topics versus the total number of topics within module Week 5..
List of Topics and Sub-Modules for Week 5
Content
Video Lectures:
Iteration - for Loop
Iteration - while Loop
Iteration - do while loop
Arrays - Initializing
Arrays - push, pop, shift, unshift
Arrays - splice
Arrays - reading values using loops + ForEach loop

Notes:
Notes for "loops" and "arrays" is attached below as the BrightSpace files.
Iterations in JS
Web Page
 

Arrays in JS
Web Page
 
Updated
 
Concepts-VideoLecture-Code
Zip Compressed File
 

Submission
Assignment 4 - To Do List - Code Along
Assignment

 Overdue - June 17 at 9:00 AM





Assignment Tasks
Follow the video series and implement all functionalities
CODE ALONG VIDEO SERIES: W8 - Code Along Task
Functionalities:
Adding template card using JS
Adding form values to user and display on UI
Display correct total & percent values
Edit button enables the card input fields and save, discard buttons.
Make sure edit button only affects its current card fields.
Discard changes disable the input fields and save, discard button. Also, the edited values are reverted to their original state.
Save changes disable the input fields and save, discard button.
Edited values are saved in student object.
Total and Percent values are reflected on UI
Delete button removes the card from the UI and students array.


API 👍
This week, we will explore four new topics and develop a quiz application that showcases the use of these concepts. Let's start by understanding each topic individually. Please refer to the content provided on each attached webpage to go through topics.
Video Lectures:
setTimeOut & setInterval
API Introduction
Weather API - Signup
API - Read Data
Change Background Color
setTimeout
Web Page
 

setInterval
Web Page
 

API: Application Programming Interface
Web Page
 

Making API Request in JavaScript
Web Page
 

Wk10-CLASSWORK-Starter
Zip Compressed File
 
Assignment Tasks
NOTE: You are only permitted to make changes to the JavaScript file. No modifications are allowed in the CSS and HTML files, except for linking the JavaScript file to the HTML file.
Functionalities:
Click "New button" should load a new image and cat fact.
Random Image EndPoint - https://api.thecatapi.com/v1/images/search
Random Cat Fact End Point - https://catfact.ninja/fact
Loom video explaining the task: A6-Cat Fact Explanation


 














Week 12 Learning Outcomes
Understanding Version Control
Github and it's popularity
Version Control using Github
Interview prep resources
Expand All  Collapse All

0 %0 of 1 topics complete
Show data table for This chart displays the number of completed topics versus the total number of topics within module Week 12..
List of Topics and Sub-Modules for Week 12
Content
WEEK 12 Lecture - Introduction
Version Control Systems
Version control systems help you track changes to your code over time, allowing multiple people to work on a project simultaneously without overwriting each other's work and providing ability to revert the code to previous versions, if a bug is introduced or something goes wrong. 
Git & Github
Git is one of the most popular version control system today, especially in the context of software development and open-source projects. GitHub is a platform that hosts your repositories, making them accessible from anywhere.
Few Git Terminologies:
Repository (Repo): A directory that contains all the files and folders related to a project, along with the history of changes.
Commit: A snapshot of your project's files at a particular point in time. Each commit has a unique ID.
Branch: A parallel version of the repository. Useful for developing features, fixing bugs, or experimenting.
Merge: Combining changes from different branches.
Pull Request (PR): A request to merge changes from one branch to another, often used for code review.
Please follow the video series to understand file versioning in Git using an example. We will talk about all above terminologies through our video lecture. For this lecture, we are using Github Desktop application.
Github Desktop - Part 1
Adding Collaborator
Cloning Repository
Feature Branch - Create New and Merge
Development Branch and Merge
Encountering Conflicts
Resolving Conflicts
GitHub Desktop is a graphical interface for Git that simplifies many Git tasks. It's perfect for beginners who might find the command line intimidating. As you become familiarized with Git concepts, you will find working with command line is more powerful and faster way to perform same tasks.
Download link for Github Desktop application.

Additional Resources
Git Documentation


Git and GitHub Tutorial for Beginners by Kevin Stratvert
Github Desktop Docs - Creating Your First Repo
Few Interview Preparation Resources (FREE)
Edabit Challanges
Educative - Grokking-Coding-Interview-Patterns-JavaScript
Front End Interview Handbook
GreatFrondEnd
Leetcode
HackerRank
With the introductory knowledge we have covered this term, we may not yet be able to solve many problems from the provided resources. Next term, you will cover some additional topics in course, rest you have to learn in your free time. The purpose of sharing these resources now is to encourage you to start practicing these types of problems from Term 1. This way, by the time you graduate, you'll have a solid understanding of how to approach these questions.
Submission
Assignment 7 - Quiz Mania
Assignment

 Overdue - August 5 at 9:00 AM








Assignment Tasks
Please follow the video series and implement all the functionalities as shown. This is a comprehensive task that covers most of concepts from the midterm exam onward. Since it might take some time to complete, I recommend starting early and not waiting until the last day.
CODE ALONG VIDEO SERIES: QUIZ MANIA
Functionalities:
Starting the game loads the first question and activates the relevant buttons.
Each question is displayed with its options, and the timer is reset.
Displaying new question should reset the previous option selection.
Notification messages will display and then automatically hide.
A modal box appears with an updated message when appropriate.
The status of correctly answered questions is highlighted in the reward area.
If the user selects an incorrect option, chooses to leave the game, or if time runs out, the correct answer is highlighted alongside the user's selected option.
If the user selects "Leave game," the award money is based on their last correct question.
If the user selects an incorrect answer or time runs out, the award money is set to the nearest achieved milestone.
Players cannot proceed further if they win the jackpot amount.
BONUS TASK
Implement 50/50 lifeline - remove two incorrect answers (+1)
Implement light and dark mode theme. (+1)

All AMANDEEP VIDEOS FROM LOOM


https://loom.com/share/folder/f6a943b6af2c44c09209fd7033b2480c


















\\
