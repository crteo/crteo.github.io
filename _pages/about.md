---
permalink: /
title: "👋 Hello, I'm Cheng Ren (some call me CR or Cheng)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
A few facts about me:

🏫 I am a penultimate Mechanical Engineering student at National University of Singapore. 

📚 I enjoy learning new things in my free time. Current skills I'm pursuing are 💻 Data Science and Machine Learning, as well as 📈 Investment and Portfolio Management.

👨‍🏫 I love to educate and I used to teach Physics (GCE 'O' and 'A' Levels) full-time at a tuition centre while I was in my first two years of University.

What is this personal website for?
======
It's for myself, really, and for a multitude of reasons.

In my free time, I pick up new skills from online platforms, and I would love to have a place to:

✍ Reflect on my experiences and truly think about the importance of why I'm doing what I'm doing(a strong purpose is crucial to retaining information)

👨🏻‍💻 Interact with my learnings by having a platform to apply what I learn through sharing

📚 Share about my learning in as simple a way as possible, to re-teach the future me, who might've forgotten what I've learnt or what I've experienced (this is applying Feynmann's Learning Method, but for my future self).

🤝 A side bonus, is that whoever is reading this, can get to know me better.

Navigating
======
I've spent the bulk my time in 2022-2023 teaching. You can find my reflections and testimonials from teaching under the "Teaching" Tab.

As I make some minor attempts at applying what I've learnt from the online courses I'm taking (through both projects and posts to educate), you can find my projects under "Personal Projects". 

I've spent most of 2024 working overseas and travelling. Alongside this experience, posts regarding the explanation of a certain concept I've learnt can all be found under "Blog Posts".

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
