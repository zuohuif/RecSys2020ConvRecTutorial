---
permalink: /
title: "academicpages is a ready-to-fork GitHub Pages template for academic personal websites"
excerpt: "About me"
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---


<br/><img src='/images/first_page_v2.png'>

Abstract
======
Recent years have witnessed the emerging of conversational systems, including both physical devices and mobile-based applications. Both the research community and industry believe that conversational systems will have a major impact on human-computer interaction, and specifically, the RecSys community has begun to
explore Conversational Recommendation Systems. Conversational recommendation aims at finding or recommending the most relevant information (e.g., web pages, answers, movies, products) for users based on textual- or spoken-dialogs, through which users can communicate with the system more efficiently using natural language conversations. Due to users’ constant need to look for information to support both work and daily life, conversational recommendation system will be one of the key techniques towards an intelligent web. The tutorial focuses on the foundations and algorithms for conversational recommendation, as well as their applications in real-world systems such as search engine, e-commerce and social networks. The tutorial aims at introducing and communicating conversational recommendation methods to the community, as well as gathering researchers and practitioners interested in this research direction for discussions, idea communications, and research promotions.

Outline
======
* Introduction and Background
  * Introduction to Conversational Recommendation
  * A Brief History of Conversational Recommendation Research
  * The New Boom in Conversational Recommendation Research
  
* Problem Formalization
  * Basic Problem Formalization
  * Paradigm 1: System is Active, User is Passive (SAUP)
  * Paradigm 2: System is Active, User Engages (SAUE)
  * Paradigm 3: System is Active, User is Active (SAUA)
  * Challenges
* Datasets and Evaluation
  * Frequently Used Datasets
  * Evaluation Protocol
* Conversational Recommendation Methods
  * Three Architectures of Conversational AI Systems
  * Four Major Modules for Conversational Recommendation
  * Natural Language Understanding/Generation
  * Dialog State Managment
  * Recommendation
  * Explanation
* Tool-kits and Real-world Systems

Material
======
[Video]()  [Slides]()

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
