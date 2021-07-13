# ShamsAwais - Subjective Answer Evaluation System


Conducting examination and answer sheet evaluation are hectic testing tools for assessing
academic achievement, integration of ideas and ability to recall, but are expensive, resource
and time consuming to generate question and evaluate response manually. Manual evaluating
of answer sheet takes up a significant amount of instructors' valuable time and hence is an
expensive process. Also different security concerns regarding paper leakage is one of the other
challenges to conquer. This project aims to build an automated examination system using
machine learning, natural language toolkit (NLTK), python environment, flask framework,
and web technologies to provide an inexpensive alternative to the current examination system.
We implement a model to automatically generate questions with their respective answers and
assess user responses.

![Homepage](https://raw.githubusercontent.com/ShamsAwais/Subjective-Answer-Evaluation/main/src/static/images/homepage.png)

## Getting started

Download or clone the project from github

```
$ git clone https://github.com/ShamsAwais/Subjective-Answer-Evaluation.git
```

Create a project environment (Anaconda recommended)
```
$ conda create --name envname python
$ conda activate envname
```

Install prerequisites
```
$ pip install -r REQUIREMENTS.txt

$ python

>>> import nltk
>>> nltk.download("all")
>>> exit() # after download is complete, exit python
```

Run project
```
$ cd ShamsAwais

$ python runserver.py
```

**Login Board**
![Login Board](https://raw.githubusercontent.com/ShamsAwais/Subjective-Answer-Evaluation/main/src/static/images/pic2.jpg)

**Result Board**
![Result Board](https://raw.githubusercontent.com/ShamsAwais/Subjective-Answer-Evaluation/main/src/static/images/pic5.png)

## Support

If you like the work I do, show your appreciation by 'FORK', 'STAR' and 'SHARE'.

Open to all types of collaboration. Feel free to raise a PR.
