# CARTE Education Pathways


Adam Pietrewicz
This repo is a clone of https://github.com/nelaturuk/education-pathways

Activity 1 Screenshots (of the new repo with the readme file in github account):

![Activity1-screenshot1](https://user-images.githubusercontent.com/60241038/137662682-ffafac70-2808-4eef-9ab8-6099ccf53781.png)

![Activity1-screenshot2](https://user-images.githubusercontent.com/60241038/137662690-338efeab-a263-4ee4-8e79-336090f392bc.png)


Activity 2-5 Screenshots (Home page and results page styling):

![Activity2-5-screenshot-homepage](https://user-images.githubusercontent.com/60241038/137662731-a4a3f24a-b450-4a96-8bac-a2caa633faba.png)

![Activity2-5-screenshot-results](https://user-images.githubusercontent.com/60241038/137662743-41738c69-3a37-47ca-b7c7-9560ec5e0629.png)

![Activity2-5-screenshot-results-table](https://user-images.githubusercontent.com/60241038/137662750-68bceb20-39bd-4657-b790-97eab6c8edbe.png)


Activity 6:
The difference between the old EP UI and this new one is that the EP web-pages have multiple colours used for the background, text, and borders that have been added. The original UI did not include any CSS styling sheets, and the only colours used were black and white. It was not interesting to look at. But now this new UI has a blue background, beige coloured search boxes, and the results table's column names are coloured dark blue with white text.



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
