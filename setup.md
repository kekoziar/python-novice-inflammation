---
layout: page
title: Setup
permalink: /setup/
root: ..
---

In preparation for this lesson, you will need to download two zipped files and place them in the specified folder:

1. Make a new folder in your Desktop called `python-novice-inflammation`.
2. Download [python-novice-inflammation-data.zip][zipfile1] and move the file to this folder.
3. Also download [python-novice-inflammation-code.zip][zipfile2] and move it to the same folder.
4. If the files aren't unzipped yet, double-click to unzip them. You should end up with
two new folders called `data` and `code`.
5. To get started, open a terminal or git bash. Go into the `data` folder by typing:

~~~
$ cd
$ cd Desktop/python-novice-inflammation/data
~~~
{: .source}

We will be using the Jupyter (IPython) notebook for the lesson. You should have already
[installed Anaconda](http://swcarpentry.github.io/workshop-template/#python)
which includes the notebook.

To start the notebook, type the following command:

~~~
$ jupyter notebook
~~~
{: .source}

Jupyter should open in a browser window. 

Once it loads, select "New" --> "Notebook: Python 3" in the upper right corner of the Jupyter interface.

> ![screenshot of Jupyter interface showing "New" menu][startnotebook]

[zipfile1]: {{ page.root }}/data/python-novice-inflammation-data.zip
[zipfile2]: {{ page.root }}/code/python-novice-inflammation-code.zip
[startnotebook]: {{ page.root }}/assets/img/startnotebook.jpg