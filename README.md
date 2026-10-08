# Quizzler App

A True/False quiz app built in Python using object-oriented programming. Questions are loaded from a data file, converted into `Question` objects, and managed by a `QuizBrain` class that asks each question, checks the answer, and keeps track of the score.

## Features

- Loads a bank of True/False questions from a data file
- Uses classes to keep the code organized and reusable
- Checks each answer and tracks your score
- Shows your final score when the quiz ends
- Includes a graphical interface built with Tkinter (`ui.py`)

## Project Structure

```
quizzler-app/
├── main.py            # Entry point: builds the question bank and runs the quiz
├── data.py            # Question data (question text and correct answer)
├── question_model.py  # Question class
├── quiz_brain.py      # QuizBrain class: logic for asking questions and scoring
└── ui.py              # Tkinter user interface
```

## How It Works

1. `data.py` stores the questions and their correct answers.
2. `main.py` loops through the data and creates a `Question` object for each entry.
3. The list of `Question` objects is passed into `QuizBrain`.
4. `QuizBrain` serves one question at a time, checks the answer, and updates the score until no questions are left.

## Getting Started

### Requirements

- Python 3.8 or newer
- Tkinter (included with most Python installations)

### Run the project

1. Clone the repository:

```
   git clone https://github.com/vrushtimorabia21/quizzler-app.git
```

2. Move into the project folder:

```
   cd quizzler-app
```

3. Run the app:

```
   python main.py
```

## What I Learned

- Creating classes, attributes, and methods
- Separating code into multiple modules
- Using one class (`QuizBrain`) to control the logic of another (`Question`)
- Building a simple GUI with Tkinter

## Author

Vrushti Morabia  
[GitHub](https://github.com/vrushtimorabia21)
