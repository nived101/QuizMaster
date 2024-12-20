# Quiz App
This is a simple quiz application that allows users to test their knowledge by answering questions from various categories. The app fetches questions from the Open Trivia Database API and provides a fun and interactive way to learn new things.

## Features
- Select quiz category, number of questions, difficulty level, and question type.
- Multiple choice and true/false questions.
- Real-time feedback on correct and incorrect answers.
- Display quiz results at the end.

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, etc.).

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/nived101/QuizMaster
   
## Usage

1.  **Open `index.html` in a web browser.** ![Starting Page](https://github.com/nived101/quiz-app/blob/main/readme_images/Screenshot_0.png)
    
2.  **Click "Play Now!" to start the quiz.**
    
3.  **Choose your quiz settings:**
    
    -   **Category:** Select the category of questions.
    -   **Number of Questions:** Set the number of questions (1-50).
    -   **Difficulty:** Choose the difficulty level (Easy, Medium, Hard).
    -   **Type of Questions:** Select the type of questions (Multiple Choice, True / False). ![Selection Page](https://github.com/nived101/quiz-app/blob/main/readme_images/Screenshot_1png.png)
4.  **Click "Start Quiz" to begin.** 
    
5.  **Answer the questions displayed.** ![Question Page](https://github.com/nived101/quiz-app/blob/main/readme_images/Screenshot_2.png)
    
6.  **At the end of the quiz, view your results and restart if desired.** ![Result Page](https://github.com/nived101/quiz-app/blob/main/readme_images/Screenshot_3.png)
    

## Project Structure

-   **`index.html`:** The main HTML file containing the structure of the app.
-   **`style.css`:** The CSS file for styling the app.
-   **`selection.js`:** Handles the display of the landing page, game category selection, and starting the quiz.
-   **`questions.js`:** Fetches questions from the Open Trivia Database API and displays them.
-   **`result.js`:** Handles the display of quiz results.

## About the API

This quiz app uses the Open Trivia Database API to fetch questions. The API provides a wide range of categories and allows for customization of the number of questions, difficulty level, and type of questions. The API endpoint used in the app is structured as follows:
```bash
`https://opentdb.com/api.php?amount={number}&category={category_id}&difficulty={difficulty}&type={type}`

-   **`amount`**: Number of questions.
-   **`category`**: Category ID for the questions.
-   **`difficulty`**: Difficulty level (easy, medium, hard).
-   **`type`**: Type of questions (multiple, boolean).
