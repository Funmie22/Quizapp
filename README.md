# Quizapp
 This is a quiz app created using Html, Css and Javascript
HTML Structure:
Document Structure: The HTML document follows the standard structure with <!DOCTYPE html> declaration, <html>, <head>, and <body> tags.
In the head, I have the title and I also linked the Css stylesheets for styling.
CSS Styling:
Global Styles: Resetting default margins, padding, and box-sizing.
Layout Styling: Styling the header, navigation, main content, quiz sections, and popup info.
JavaScript Functionality:
Popup Info Interaction: JavaScript controls the behavior of the start button, exit button, and continue button for displaying instructions and starting the quiz.
Dynamic Question Rendering: Questions and options are stored as an array of objects. JavaScript dynamically populates the quiz section with questions and options.
Next Button Functionality: The next button allows users to navigate through questions sequentially.
Event Handling: Event listeners are used to trigger actions like starting the quiz, exiting the popup, continuing to the quiz, and moving to the next question.
Quiz Functionality:
Question Data Structure: Each question is represented as an object containing properties like question text, options, correct answer, and question number.
Question Rendering: JavaScript dynamically inserts question text and options into the HTML.
Next Question Navigation: Users can progress to the next question by clicking the next button.

Technical Improvements and Suggestions:
Scoring Mechanism: Implement logic to calculate and display scores based on user responses.
Answer Validation: Validate user-selected answers against the correct answer.
Feedback: Provide feedback to users on correct and incorrect answers.
Responsiveness: Enhance CSS for better responsiveness across different devices.
Code Optimization: Refactor code for better readability, maintainability, and performance.
