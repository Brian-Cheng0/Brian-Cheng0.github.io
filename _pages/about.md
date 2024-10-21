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
Aplus Consultant    (March 2024 - June 2024)

Software Engineer Intern (Machine Learning)

• Developed patient data analysis tools using Python, engineered interfaces for large language models to analyze, predict, and visualize the future trends in patient health scenarios and the associated costs of treatments, enhancing predictive accuracy and operational efficiency in clinical settings.

• Implemented a dynamic web interface using Next.js and React, Led the design and development of a responsive web application to display various health indicators, utilizing CSS for styling. Integrated Recharts to create interactive bar charts that visualize both current and predicted patient data, improving user engagement and data accessibility.

China International Capital Corporation Limited    (June 2024 - August 2024)

Software Engineer Intern (Machine Learning)

• Enhanced financial reporting tools using Python and Bert-Base-Chinese, developed and optimized a large language model to classify financial report segments accurately, increasing classification accuracy to 65% across more than 100 categories and accelerating report processing.

• Monitored model performance using advanced analytics platforms, utilized MLflow, Tensorboard, and Weights and Biases to track large language model performance, creating detailed visual presentations that facilitated effective communication and decision-making among team members.

Emory University

Research Assistant

• Collaborating with research professors to manage and optimize computational resources using Slurm Workload Manager, Postgresql to load the data, and Hydra to configure complex application. Accessing and analyzing the MIMIC-IV dataset, focusing on complex event sequences, and employ a data pre-processing and modeling library for Generative Pre-trained Transformers (GPTs) to work with continuous-time sequences.

Project Experience
======
2D Zelda Game[Code](https://github.com/Brian-Cheng0/osu-coding/tree/main/cse3902), OSU(             January 2023 – April 2023) 

Software Development Engineer, CSE 3902

• Developed an interactive system for 2D Zelda games using C#, implementing UI design and design patterns such as factory, decorator, and command to enhance gameplay. Improved efficiency by assigning tasks like character movement, scene layout, increasing game diversity by adding various weapon choices.

Crypto Currency Search Platform [Code](https://github.com/Brian-Cheng0/osu-coding/tree/main/CSE5914), OSU ( January 2024 – April 2024)

Software Development Engineer, CSE 5914

• Built a cryptocurrency search platform using Python and ElasticSearch, integrating third-party APIs to retrieve the latest data. Designed the website UI with CSS, HTML, and JavaScript to facilitate user account management and data visualization.

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
