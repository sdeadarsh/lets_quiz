# Let's Quiz


This online quiz-organizing website project was developed using Python's web framework Django.


## Current Features

### Site access features:

- The user must be logged in to access the Quiz.
- For signup user is required to give _username_, _first name_, _last name_, _e-mail address_ and _password_.
- For login, the user must enter _username_ and _password_ only.

### Features of the quiz:

- All questions are multiple-choice questions.
- Each question is displayed only once per user.
- Questions are displayed randomly for every user.
- If the user by mistake presses refresh or go back to the previous page, there will be a new question for the user and the
  question he/she was on will be marked as attempted.
- A message will be displayed whether the answer was correct or incorrect after every attempted question.

### Leaderboard features:

- Leaderboard is a short list according to the score obtained by the users.
- If two users have the same score, the user who has signed up earlier will have a better ranking than the one who joined late.
- Leaderboard is open to all. No login is required.

### Administrative features:

- Only the admin can add questions.
- Admin can add questions and modify them until they are not marked as _Has been published?_
- Once a question has been published, it can neither be modified nor can be accessed. Admin can only see a list of questions.
- Admin can search questions by question text or choice text.
- Admin can filter questions based on whether the questions have been published or not.

## Getting started with development

### 1. Clone this repository

```bash
git clone https://github.com/akashgiricse/lets-quiz.git
cd lets_quiz
```

### 2. Install [Pipenv](https://pipenv.pypa.io/en/latest/)

### 3. Create the virtualenv

```bash
## run the following command from the `lets_quiz` directory
pipenv shell
```

### 4. Install python packages

```bash
pip install -r requirements.txt
```

### 5. Setup the database

_TODO - Add instructions for this when I start using the MySQL database._

### 6. Run database migrations

```bash
cd lets_quiz
python manage.py migrate
```

### 7. Create superuser

```bash
python manage.py createsuperuser
```

### 8. Run development server

```bash
python manage.py runserver
```

## Getting started with the website with its images 

### 1. Home Page 

![Image Alt text](/lets_quiz/images/Home.png "Home Page")
