---
permalink: /
title: " "
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an Associate Professor in Computer Science at [Université Paris Dauphine-PSL](https://dauphine.psl.eu/). I am a member of the [Data Science](https://www.lamsade.dauphine.fr/en/research/groups/data-science.html) group at [LAMSADE](https://www.lamsade.dauphine.fr/) research center.

My research interests include Service Oriented Computing, Software and Process Mining. 

Deputy Director of [LAMSADE](https://www.lamsade.dauphine.fr/) CNRS UMR 7243 research center.


Research 
------
Until 2020, my research work focuses on <font color="#A628A0"><i>automatic service composition</i></font>, taking into account their <font color="#A628A0"><i>non-functional properties</i></font>. It mainly concerned the study of the problems of discovery, selection and execution of a service composition. The results obtained mainly concern the study of the exact complexity of the problem of optimal service selection for both single and multi-criteria Quality of Service (QoS), the consideration of trust in service providers as a criterion for discovery and selection, and the reliability of the execution of a service composition.

Since 2021, my research work has evolved towards contract management for the <font color="#A628A0"><i>deployment and execution of microservices</i></font> in the Cloud. Furthermore, with the rise of artificial intelligence, I have oriented my research towards <font color="#A628A0"><i>process and software mining</i></font>. 

*All of my research results have been achieved in the context of local, national or international collaborations.*


**Publications**: [dblp](https://dblp.org/pid/91/6045.html), [HAL](https://hal.science/search/index?q=joyce+el+haddad)

**Supervision of PhD students**

**test** this is a test to no menu page [/non-menu-page/](https://joyceelhaddad.github.io/non-menu-page/)

Some recent duties 
------
- Member of the National Council of (French) Universities (CNU 27) for computer science (2019-2023).
- Elected member of the Board of Governors (Conseil d'Administration) of Université Paris Dauphine-PSL (since 2024).
- Elected member of the representative advisory committee on computer science at Univ. Paris Dauphine (since 2019). 
- Vice-Chair of the associate professor recruiting committee for computer science at Univ. Paris Dauphine (2023)

- Deputy Director of LAMSADE CNRS UMR 7243, Univ. Paris Dauphine University (since January 2024).
- Member of the Laboratory Council (conseil de laboratoire) of LAMSADE CNRS UMR 7243, Univ. Paris Dauphine – PSL (since 2023).
- Co-head of the Data Science group, LAMSADE CNRS UMR 7243, Univ. Paris Dauphine– PSL (2020-2024).
- Co-organization and Co-chairing a round table for the 50th anniversary of LAMSADE with Jérôme Lang, January 2025. We invited experts including Serge Abitboul, Claire Mathieu, Isabelle Bloch, and Dominique Meda to discuss future challenges in AI, algorithms, data science and decision-making. [Watch the replay](https://www.lamsade.dauphine.fr/fr.html)


Teaching 
------



<!--This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the repository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. Incidentally, these same features make it a great template for anyone that needs to show off a professional template!

 You can fork [this template](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and Markdown files, add your own PDFs and other content, and have your own site for free, with no ads! 

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured Markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various Markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your Markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the Markdown files! You can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](https://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
-->
