---
layout: page
title: Setup
permalink: /setup/
root: ..
---

In preparation for this lesson, you will need to download a zipped file.

1. Download [python-novice-inflammation.zip][zipfile] and move it to your Desktop.
2. If the file isn't unzipped yet, double-click to unzip it. You should end up with a folder called `python-novice-inflammation` that contains two folders called `data` and `code`.
3. To get started, open a terminal or git bash. Go into the `data` folder by typing:

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

[zipfile]: {{ page.root }}/files/python-novice-inflammation.zip
[startnotebook]: {{ page.root }}/assets/img/startnotebook.jpg