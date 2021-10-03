# CARTE Education Pathways

Name: Kieun Joshua Park

Note: This repo is a clone of https://github.com/nelaturuk/education_pathways.

## Activity 1 Screenshot
![Alt text](https://github.com/kjoshuapark/ECE444-F2021-Lab3/blob/main/Screenshots/Screen%20Shot%202021-10-03%20at%206.35.17%20AM.png)

## Activity 2 Screenshot
![Alt text](https://github.com/kjoshuapark/ECE444-F2021-Lab3/blob/main/Screenshots/Screen%20Shot%202021-10-03%20at%209.55.06%20AM.png)

## Activity 3 Screenshot
![Alt text](https://github.com/kjoshuapark/ECE444-F2021-Lab3/blob/main/Screenshots/Screen%20Shot%202021-10-03%20at%2010.02.00%20AM.png)
Note: this was the screenshot taken after running the command docker build --network=host -t python-docker . a second time due to strange line formatting on the terminal from the first run of the command

## Activity 4 Screenshot
![Alt text](https://github.com/kjoshuapark/ECE444-F2021-Lab3/blob/main/Screenshots/Screen%20Shot%202021-10-03%20at%203.52.32%20PM.png)
![Alt text](https://github.com/kjoshuapark/ECE444-F2021-Lab3/blob/main/Screenshots/Screen%20Shot%202021-10-03%20at%203.53.26%20PM.png)



## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker



## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
