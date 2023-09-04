# Personalized HackerNews Feed

Automated Recommendation Feed for Hacker News

## Description

This project automates the recommendation feed from Hacker News using Naive Bayes from scikit-learn. It parses the [Hacker News](https://news.ycombinator.com/) website to populate the local database. The project consists of two parts: a basic feed where users can like and dislike news articles, and a personalized feed built upon the user's preferences. The recommendation system uses NBC (Naive Bayes Classifier) to calculate the likelihood of a particular article being interesting to the user.

## Table of Contents

- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Acknowledgments](#acknowledgments)

## Getting Started

To get started with the Personalized HackerNews Feed, make sure you have **Python** and the required dependencies installed. Clone the repository to your local machine and follow the installation instructions below.

## Installation

Use the following commands to set up the project:

```bash
# Clone the repository
git clone https://github.com/pol3et/automated-feed.git

# Navigate to the project directory
cd automated-feed

# Install the required dependencies
pip install -r requirements.txt
```

## Usage

To use the project, follow these steps:

1. Parse HackerNews to populate the local database:

```bash
python populate_db.py
```

2. Run the local server:

```bash
python hackernews.py
```

3. Open your web browser and visit [localhost:8080/news](http://localhost:8080/news) to like or dislike articles and train the recommendation model. Then, navigate to [localhost:8080/feed](http://localhost:8080/feed) to see personalized suggestions.

## Features

- Automatically scrapes and renders website into a database.
- Utilizes Naive Bayes from scikit-learn.
- Provides a simple and effective base to build upon.

## Acknowledgments

This project was completed as part of the tasks from [Pybook by Dementiy](https://github.com/Dementiy/pybook-assignments).

<img src="https://itmo.ru/file/pages/213/logo_osnovnoy_russkiy_belyy.png" width="100">
