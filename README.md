Zeyuan Liu

this repo is a clone of https://github.com/nelaturuk/education_pathways.

# CARTE Education Pathways

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

Activity 1:
![act1](https://raw.githubusercontent.com/Liuzysjtu/ECE444-F2021-Lab5/main/screenshots/repository.png)

Activity 2-5:
![act2_1](https://raw.githubusercontent.com/Liuzysjtu/ECE444-F2021-Lab5/main/screenshots/Home_Page.png)
![act2_2](https://raw.githubusercontent.com/Liuzysjtu/ECE444-F2021-Lab5/main/screenshots/Form.png)
![act2_3](https://raw.githubusercontent.com/Liuzysjtu/ECE444-F2021-Lab5/main/screenshots/Results_Table.png)

Activity 6:
in old style, for home page, the search item is just in plain text and doesn't look like a form
in new style, there is border around the search form nad each item displays clearly and beautiful
