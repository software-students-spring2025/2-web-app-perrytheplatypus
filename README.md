# Web Application Exercise

A little exercise to build a web application following an agile development process. See the [instructions](instructions.md) for more detail.

## Product vision statement

TaskXP transforms task management into an engaging, reward-based system that motivates users to stay productive. By integrating a gamified experience with XP points, task tracking, and a structured workflow, TaskXP makes completing daily tasks feel like leveling up in a game.

## User stories

[User Stories](https://github.com/software-students-spring2025/2-web-app-perrytheplatypus/issues)

## Steps necessary to run the software

## Initial setup

1. [Install Python](https://www.python.org/downloads/)

2. Virtual Environment Setup

```
pip install pipenv
pipenv shell
```

3. Install Dependencies

```
pip install -r requirements.txt
```

4. Install MongoDB

```
brew tap mongodb/brew
brew update
brew install mongodb-community@8.0
brew services start mongodb-community@8.0
```

5. Connect to database using mongosh

```
mongosh
use tasksxp
```

6. Create and populate your .env file in the project directory

```
MONGO_URI=mongodb://localhost:27017/
MONGO_DBNAME=taskxp
PORT=3000
```

## How to run

```
cd src
python3 app.py
```

### Page is located at http://127.0.0.1:3000

## Task boards

[Sprint 1](https://github.com/orgs/software-students-spring2025/projects/49/views/1)

[Sprint 2](https://github.com/orgs/software-students-spring2025/projects/106)
