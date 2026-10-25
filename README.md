Assignment #5: JavaScript Basics (DOM Manipulation & Events)

Name: Amirkhan Abai
Group: IT-2503  

Overview
This project demonstrates foundational JavaScript concepts including object definitions, primitive data types, 
arithmetic operations, HTML DOM manipulation, and dynamic event handling.


Assignment Parts & Tasks

Part 1: Profile Object, Data Types & Arithmetic
Task 1: Created a `userProfile` object holding string, number, boolean, and array properties.
<img width="647" height="147" alt="image" src="https://github.com/user-attachments/assets/154449ce-51dc-4f0a-930d-a02b161eb1ab" />

Task 2: Applied dynamic age calculations (`currentYear - birthYear`) and computed additional metrics (`ageInMonths` and `hobbiesCount`). Outputs are rendered to the DOM and logged to the console.
<img width="556" height="151" alt="image" src="https://github.com/user-attachments/assets/606461d7-f369-43de-99cb-6a9739b94125" />



Part 2: Form Input & Event Responses
Task 3: Designed an HTML form with input fields for Username and Birth Year, along with a submit button.
<img width="892" height="411" alt="image" src="https://github.com/user-attachments/assets/ae0cd74b-046e-4d50-bd2f-aa3e38f614ce" />

Task 4 Added a `submit` event listener to capture form input and update the `userProfile` object dynamically without reloading the page.
<img width="640" height="511" alt="image" src="https://github.com/user-attachments/assets/38e56d24-6b90-4287-a5ae-da84e898db63" />


Part 3: DOM List Manipulation
Task 5 Implemented an unordered list (`<ul>`) to show items dynamically from the hobbies array. Added event listeners to the "Add Item" and "Remove Item" buttons to manipulate the array and list nodes in real time.
<img width="503" height="228" alt="image" src="https://github.com/user-attachments/assets/cd6e9606-e596-4ec8-b814-06d13cb3b79d" />

Summary:
1. Defined the core JavaScript structure using a `userProfile` object storing various data types.
2. Built a responsive HTML user interface styled with CSS to separate form actions, user metrics, and list elements.
3. Written modular JavaScript functions (`calculateMetrics`, `renderProfile`, and `renderList`) to keep data synchronized between the JS state and the DOM.
4. Integrated form submit events and button click listeners to execute dynamic node creation (`document.createElement`) and removal (`pop()` and re-rendering).
