---
permalink: /
title: "Peng Tang"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Peng Tang, male, is an Engineer at the Institute of Intelligent Systems and Applications Innovation, Network Intelligence Department, Peng Cheng Laboratory. He received a PhD in Control Science and Engineering from the University of Science and Technology Beijing; a Master's degree in Control Science and Engineering from North China University of Technology; and a Bachelor's degree in Automation from Changsha University of Science and Technology. His current research focuses on industrial process fault diagnosis and industrial large model application technology research.

Educational Background
======
Here is the professional English translation of the academic and professional timeline:

| Period (Year/Month) | Institution/Organization | Major/Field | Supervisor | Degree/Position |
| :------------------ | :----------------------- | :---------- | :--------- | :-------------- |
| 2021.09-2023.06     | Peng Cheng Laboratory    | Control Science and Engineering | Academician Gui Weihua | Postdoctoral Researcher |
| 2016.09-2021.06     | University of Science and Technology Beijing | Control Science and Engineering | Prof. Peng Kaixiang | Ph.D. |
| 2013.09-2016.06     | North China University of Technology | Control Science and Engineering | Prof. Li Xiaojian | Master's Degree |
| 2009.09-2013.06     | Changsha University of Science and Technology | Automation | - | Bachelor's Degree |

Research Achievements
======
[1] Peng Tang, Kaixiang Peng, et. al. A novel distributed CVRAE-based spatio-temporal process monitoring method with its application, IEEE Transactions on Industrial Informatics, 2023. (SCI 1区, IF 11.648)
[2] 唐鹏, 彭开香, 董洁. 一种新颖的深度因果图建模及其故障诊断方法, 自动化学报, 2021. (国内自动化领域顶级期刊, IF 2.656)
[3] Peng Tang, Kaixiang Peng, Jie Dong. Nonlinear quality-related fault detection using combined deep variational information bottleneck and variational autoencoder, ISA Transactions, 2021 (SCI 2区, IF 5.911) 
[4] Peng Tang, Kaixiang Peng, Ruihua Jiao. A process monitoring and fault isolation framework based on variational autoencoders and branch and bound method, Journal of the Franklin Institute, 2021 (SCI 2区, IF 4.246) 
[5] Peng Tang, Kaixiang Peng, et. al. Monitoring of nonlinear processes with multiple operating modes through a novel gaussian mixture variational autoencoder model, IEEE Access, 2020 (SCI 2区, IF 3.476) 

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
