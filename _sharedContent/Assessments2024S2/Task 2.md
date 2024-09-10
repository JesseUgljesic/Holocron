## Project Overview

### Project Introduction

For this section, you should introduce the whole project, not just the coding requirements, but also the time management and project management. 

Time management could include:
- weeks involved
- how the tasks were organised into the different stages etc.

Project Management could focus on:
- How GitHub was used.

### Requirements

In this part detail and analyse the hardware **and** software requirements for the project.

### Intended Outcomes

Analyse what the outcomes of the project were, focusing on the end-user experience.

### Purpose

In this part, focus on the purpose of the project (not just the end product). For instance what learning outcomes could come from project etc.

## Code

In this section, focus **only on the aspect identified**. 

Analyse the code, and explain how that code operates and the purpose of each block of code. You should also analyse how this code interacts with other sub-systems within the project.

> [!tip] You **don't** need to explain every single line of code.

Pick a complex route and analyse that to demonstrate an understanding of the whole script.


## Data

Focus on how data is transmitted within the project from one sub-system to another, within the focus given in the assessment documentation.

## Development Process

- Brief 2-4 sentence summary for each week of what that week of development involved
	- What did you add to the Website?
	- How does your addition fit into the grand scheme of the project?
	- What new skills were required to make these additions?
	- Explain how previous learning and work contributed to your ability to complete this week or work.
<strong>Screenshots as evidence is always good</strong>
Remember this entire section is meant to amount to around 1000 words so if you have 10 weeks worth of development process those summaries either need to be combined or need to be ~100 words each.
This weekly summary may not work depending on your project. It may be worthwhile to use this scaffold to put into words what was done to complete the project. However you may want to reorder or combine sections depending on how it will be best displayed. 

Example for notes taken during week 8, could be copy pasted into assessment document (do not copy this, that is plagiarism):
During the 8th week of the development process I began implementing a new page in the A New Hope website that would allow a user to create shopping lists that they could add a series of items to. This step in the implementation only allowed for new shopping lists to be created, this page will be later iterated on by adding functionalities that allow for items to be added to the shopping lists. This page also used the `shopping_lists` table created previously. I used the baseline template structure I have used to create previous websites but adjusted the `{% block rowTwoColOneContent %}` and `{% block rowTwoColTwoContent %}` contents to add an input space for users to input their shopping list names and a display to have the website continually display the list of shopping lists. I then updated `app.py` to include a route that can use the `GET` and `POST` methods to take data from the `shopping_lists` table to display on the page and also send data to that table.

## Technical Analysis

TBA

## Work Skills

TBA