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

## Activity 5
A functional requirement that I would like to improve upon is the web app's response to a user query that does not involve a keyword. I have noticed when I was using the tool that you can have all the filters for Year, Division/Department and Campus selected but if you do not have a keyword then no results will display once pressing "search". This may be the intended behaviour but I believe it would be useful if you could find all relevant results according to the applied filters even when entering no keywords. A user might actually want to explore all courses within a specific department to learn more about the department as a whole rather than look for specific courses right away.
A non-functional requirement that I would like to touch upon is the readability and convenience of a search result page. When you choose to display a large number of results per block (e.g. 10 results per block), the text that is displayed, specifically in the Description column, can appear very crowded due to the large volumn of text. I would put a bit of padding in-between each row so that they are easy to distinguish. Also each block is not on a page-to-page basis similar to Google's web browser search results. For Education Pathways, all the results appear on one page and each block is separated by a horizontal line. It may be preferable to have a page system so that a user does not have to scroll through one long web page in order to see all the results.


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
