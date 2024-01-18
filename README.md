# Quiz App

Welcome to the Quiz App repository! This simple quiz game is built using HTML, CSS, and JavaScript. Test your knowledge on various topics with a user-friendly and interactive interface.

## Table of Contents

- [Features](#features)
- [Usage](#usage)
- [How to Play](#how-to-play)
- [Customization](#customization)
- [Contributing](#contributing)

## Features

- Multiple-choice questions
- User-friendly interface
- Score tracking
- Responsive design

## Usage

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/uditpadhan98//Quiz-app
   ```

2. Open the `index.html` file in your web browser.

3. Start playing the quiz and test your knowledge!

## How to Play

- Click the "Start Quiz" button to begin the quiz.
- Answer each question by selecting the correct option.
- After answering all the questions, click the "Submit" button to see your score.
- Share your score with friends and challenge them to beat it!

## Customization

## Adding New Questions

1. Open the `questions.js` file.

2. Add a new question to the `questions` array following the existing format:

   ```javascript
   {
    question: 'What is 2 * 2 ?',
    answers: [
      { text: '4', correct: true },
      { text: '22', correct: false },
      { text: '5', correct: false },
      { text: '27', correct: false }
    ]
  
   ```

3. Save the file, and the new question will be included in the quiz.

## Contributing

If you'd like to contribute to this project, feel free to submit issues or pull requests. Your feedback and contributions are highly appreciated.

Happy coding! 🚀
