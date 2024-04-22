# Love-Calculator

Hello everybody! 👋 </br>

✨Welcome to the Love Calculator project! This simple web application allows users to calculate the compatibility between two people based on their names. It's a fun way to see how well you match with your crush or partner!
## 👀 Overview

### 📷 Screenshot
![screencapture-tucecifci-github-io-Love-Calculator-2024-04-15-17_54_49](https://github.com/tucecifci/Love-Calculator/assets/151346784/5f6b400b-0db7-4db6-af5c-b4311efc3115)


![screencapture-tucecifci-github-io-Love-Calculator-2024-04-15-17_55_15](https://github.com/tucecifci/Love-Calculator/assets/151346784/f9b86e84-d354-4076-817d-8c0ac091f9ea)


### 🔗 Links

- https://tucecifci.github.io/Love-Calculator/

## My process

### 💡 Built with

The Love Calculator project is built using the following technologies:

- HTML: Used for creating the structure and layout of the web page.
- CSS: Used for styling the visual elements and layout of the web page.
- JavaScript: Used for implementing the interactive features, such as input validation and compatibility calculation logic.
These technologies work together to create a simple yet interactive web application that allows users to calculate the compatibility between two people based on their names.

### 🧠 What I learned

What I Learned
While working on the Love Calculator project, I gained valuable experience and learned several key concepts, including:

- DOM Manipulation: I learned how to interact with the Document Object Model (DOM) using JavaScript to dynamically update the content and behavior of the web page.
- Event Handling: I learned how to handle user interactions, such as button clicks, and respond to them appropriately using event listeners in JavaScript.
- Form Input Validation: I learned how to validate user input from form fields to ensure that the data entered is correct and meets certain criteria.
- Algorithm Implementation: I learned how to implement algorithms, such as the compatibility calculation logic, in JavaScript to perform specific tasks and generate meaningful results.
- Responsive Design: I learned how to create a responsive web design that adapts to different screen sizes and devices using CSS media queries.
- Version Control: I gained experience in using version control with Git and GitHub to track changes, collaborate with others, and manage the project's codebase efficiently.
Overall, working on the Love Calculator project provided me with hands-on experience in front-end web development and helped me sharpen my skills in HTML, CSS, and JavaScript.

```javascript
  window.onload = function () {
  let button = document.getElementById("calculate");
  button.addEventListener("click", calculateLove);
};
```

```javascript
 if (yourName != "" && crushName != "") {
    let percentage = Math.floor(Math.random() * 101);
    document.getElementById(
      "result-message"
    ).innerText = `${yourName} and ${crushName}'s change of love: `;
    document.getElementById("result-percentage").innerText =
      percentage.toString() + "%";
  }
```

### 👩🏼‍💻 Features

- Input Form: Users can enter their names into the input fields.
- Calculate Button: Clicking the "Calculate" button will trigger the compatibility calculation.
- Result Display: The result of the compatibility calculation is displayed on the screen.
- Responsive Design: The application is designed to work well on various screen sizes, including mobile devices.

### 🤔 How to Use

- Clone the repository to your local machine.
- Open the index.html file in your web browser.
- Enter the names of two people into the input fields.
- Click the "Calculate" button to see the compatibility result.

 Example <br />
Here's a brief example of how to use the love calculator:

- Enter the name "John" into the first input field.
- Enter the name "Jane" into the second input field.
- Click the "Calculate" button.
- The result "85%" is displayed on the screen, indicating a high level of compatibility between John and Jane.

  
### 🤌🏻 Useful resources

- https://www.youtube.com/watch?v=gkby8r-3soc&list=PLnKe36F30Y4bLhA-st9sC4ZthyV7nsL2Q&index=25

## 🏳️‍🌈 Author

- Tuğçe Çifci - [@tucecifci](https://github.com/tucecifci)
- Frontend Mentor - [@tucecifci](https://www.frontendmentor.io/profile/tucecifci)
