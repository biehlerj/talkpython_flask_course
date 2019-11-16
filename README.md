# talkpython_flask_course

## Introduction

Code from the [Flask and SQLAlchemy](https://training.talkpython.fm/courses/explore_flask/building-data-driven-web-applications-in-python-with-flask-sqlalchemy-and-bootstrap) course taken on [Talk Python Training](https://training.talkpython.fm/).

## Table of Contents

- [talkpython_flask_course](#talkpythonflaskcourse)
  - [Introduction](#introduction)
  - [Table of Contents](#table-of-contents)
  - [About](#about)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Author](#author)

## About

All the code written while completing the aforementioned course. All the commits go through the chapters with the final code being the completion of the course.

## Installation

To install the code on your computer with all the required packages run the following commands on the command line:

```bash
git clone https://github.com/biehlerj/talkpython_flask_course.git
cd talkpython_flask_course
python3 -m venv venv && . venv/bin/activate && pip install --upgrade pip setuptools > /dev/null
pip install -r requirements-dev.txt
```

Alternatively you can alias the 3rd line in the above command by doing `alias venv="python3 -m venv venv && . venv/bin/activate && pip install --upgrade pip setuptools > /dev/null"` and then replacing the above command with this:

```bash
git clone https://github.com/biehlerj/talkpython_flask_course.git
cd talkpython_flask_course
venv
pip install -r requirements-dev.txt
```

## Usage

To run the code type the command `python app.py` to start up the app and then open the website by clicking or copying the URL the output gives you.

## Author

[Jacob Biehler](https://www.linkedin.com/in/jacob-biehler-475573139/)

[Twitter](https://twitter.com/Biehlerj)

[GitHub](https://github.com/biehlerj)
