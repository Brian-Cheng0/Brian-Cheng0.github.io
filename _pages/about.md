---
permalink: /
title: "Yiming Cheng's Homepage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi There! I'm a graduate student at Emory University. I finished my BS degree at the Ohio State University at Spring 2024. My major is Computer Science, I have studied multiple classes during my undergradaute studies. I have learnt data structure & algorithm, discrete structures, databases design, linear algebra, higher mathematics, computer networking, artificial intelligence at my undergraduate studies. 

Internship Experience
======
Aplus Consultant                                                                  March 2024 - June 2024
Machine Learning Intern

• Participate in invoking large model interfaces to analyze the overall patient situation, analyze the overall patient situation, the future trend of the situation, and predict the cost of cure or delay.

• The overall website was made with NEXTJS and REACT, the website was decorated with CSS to display various patient indicators on the page, and the bar chart was realized with RECHART to visualize the existing patient data and the content of the predicted patient number in the future.

China International Capital Corporation Limited                                    June 2024 - Present
Project Internship

• Participated in the production of the company's large model and used Bert-base-Chinese to classify different segments of the financial report, which significantly improved the accuracy and speed of analysis of the report.

Project Experience
======
2D Zelda Game[Code](https://github.com/Brian-Cheng0/osu-coding/tree/main/cse3902), OSU                                                      January 2023 – April 2023 Team Leader, CSE 3902
• Develop an interactive system for 2D Zelda games in C#, incorporating UI design and implementing multiple design patterns such as factory, decoration, and command modes to improve gameplay.
• By assigning different tasks such as character movement direction, scene room layout, game props design, etc., the whole group can effectively complete corresponding tasks. Compared with the original work, different weapon choices are added to increase the diversity of the game.

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
