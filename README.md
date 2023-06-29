Ideally a new data science hire would go through these resources in the first 30-60 days. I started this with a junior data scientist in my mind working for a data science team using Python and GCP. This is roughly ordered.

# Computer & Environment Setup

## Productivity

[Rectangle](https://rectangleapp.com/): A window management app for macOS, Rectangle enables you to quickly and effortlessly resize and organize your windows using keyboard shortcuts or by dragging windows to screen edges. Iused to use ShiftIt which did something similar but Rectangle does the same thing but works on the latest versions of macOS.

[Stats](https://github.com/exelban/stats): An open-source system monitor for macOS, Stats provides you with detailed information on your CPU, memory, disk, network, and battery usage, all accessible from your menu bar. I used to pay for iStat Menus but stats is an open source version.

[Amphetamine](https://apps.apple.com/us/app/amphetamine/id937984704?mt=12): Keep your Mac awake and prevent it from sleeping with Amphetamine, a powerful and customizable app that allows you to set rules based on applications, time, or power source. Similar to the Caffiene app.

[Be Focused](https://apps.apple.com/us/app/be-focused-focus-timer/id973134470?mt=12): A productivity-enhancing time management app, Be Focused utilizes the Pomodoro Technique to help you break work into manageable intervals, maintain focus, and stay on track. I find using Pomodoros, setting 25 minute timers of focused work to be incredibly helpful.

[Hidden Bar](https://github.com/dwarvesf/hidden): A minimalist app that allows you to declutter your Mac's menu bar by hiding icons you don't need to see all the time, Hidden Bar lets you access these icons with a simple click whenever needed.


## Developer Tools

[Homebrew](https://brew.sh/): A must-have package manager for macOS, Homebrew makes it easy to install, update, and manage software packages, including command-line tools and graphical applications.

[Visual Studio Code](https://code.visualstudio.com/): A versatile and free source code editor developed by Microsoft, Visual Studio Code supports a wide range of programming languages and comes with built-in support for Git, intelligent code completion, and a plethora of extensions to customize your coding environment.

[iTerm2](https://iterm2.com/): A highly customizable and feature-rich terminal emulator for macOS, iTerm2 improves upon the default Terminal app with features like split panes, search functionality, and extensive customization options.

[Anaconda/Miniconda](https://docs.anaconda.com/anaconda/install/index.html): Anaconda is a powerful Python and R distribution that simplifies package management and deployment, while Miniconda is its lightweight counterpart. Both options provide you with the essential tools to set up and manage your data science and machine learning environments.

[zsh](https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH): zsh has become my bash replacement.

[Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh): Makes zsh more useful with a bunch of plugins.

[Sublime Text](https://www.sublimetext.com/): A sophisticated and lightning-fast text editor designed for code, markup, and prose, Sublime Text offers a sleek interface, multiple selections, and a highly extensible plugin API.

# Technical

## Reading through Foundations sections of [madewithml](https://madewithml.com/):

<table class="table table-striped table-bordered table-vcenter">
    <tr>
        <td align="center"><b>🛠&nbsp; Toolkit</b></td>
        <td align="center"><b>🔥&nbsp; Machine Learning</b></td>
        <td align="center"><b>🤖&nbsp; Deep Learning</b></td>
    </tr>
    <tr>
        <td><a href="https://madewithml.com/courses/foundations/notebooks/">Notebooks</a></td>
        <td><a href="https://madewithml.com/courses/foundations/linear-regression/">Linear Regression</a></td>
    </tr>
    <tr>
        <td><a href="https://madewithml.com/courses/foundations/python/">Python</a></td>
        <td><a href="https://madewithml.com/courses/foundations/logistic-regression/">Logistic Regression</a></td>
    </tr>
    <tr>
        <td><a href="https://madewithml.com/courses/foundations/numpy/">NumPy</a></td>
        <td><a href="https://madewithml.com/courses/foundations/neural-networks/">Neural Network</a></td>
    </tr>
    <tr>
        <td><a href="https://madewithml.com/courses/foundations/pandas/">Pandas</a></td>
        <td><a href="https://madewithml.com/courses/foundations/data-quality/">Data Quality</a></td>
    </tr>
    <tr>
        <td><a href="https://madewithml.com/courses/foundations/pytorch/">PyTorch</a></td>
        <td><a href="https://madewithml.com/courses/foundations/utilities/">Utilities</a></td>
    </tr>
</table>

Left out MadewithML's material on Attention, Embeddings and Transformers because Jay Alammar's blog posts are better.

## Command Line
There's many tutorials but this one is decent https://www.freecodecamp.org/news/command-line-for-beginners/

## Cloud - GCP

- [gcloud](https://cloud.google.com/sdk/docs/install-sdk)
- [gsutil](https://cloud.google.com/storage/docs/gsutil_install)
- Big Query - Read through and run through the examples in these Big Query documentation pages:
    - Introduction: https://cloud.google.com/bigquery/docs/query-overview
    - Query BigQuery data (15 subpages) https://cloud.google.com/bigquery/docs/running-queries
    - Query data with SQL (10 subpages) https://cloud.google.com/bigquery/docs/introduction-sql

## Git & Bitbucket/Github
Read through Reproducibility section of madewithml's MLOps course

<table>
	<tbody>
		<tr>
			<td><strong>♻️&nbsp; Reproducibility</strong></td>
		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/git/">Git</a></td>
		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/pre-commit/">Pre-commit</a></td>
		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/versioning/">Versioning</a></td>
		</tr>
	</tbody>
</table>

## Docker

- https://valohai.com/blog/docker-for-data-science/
- madewithml Docker guide: https://madewithml.com/courses/mlops/docker/

## Kubeflow

- [Introduction to Vertex AI Pipelines](https://www.youtube.com/watch?v=gtVHw5YCRhE)

# Data

Hadley Wickham's [tidy data paper](https://vita.had.co.nz/papers/tidy-data.pdf) first introduced me to the idea of tidy data. I first read it around 2017 when I first was getting into data analytics. Totally changed how I thought about representing data and put categories to shapes of data like "wide" and "long" data.

Read the original paper: https://vita.had.co.nz/papers/tidy-data.pdf
Work through some Python examples: https://byuidatascience.github.io/python4ds/tidy-data.html

# SQL

This is one of the most important skills for a data scientist as most of the data lives in databases. Therefore, being able to extract and manipulate data using SQL is crucial. Mode Analytics provides a good tutorial. Start with the intermediate one. https://mode.com/sql-tutorial/

# madewithml (parts 1, 2 and 3)


<table>
	<tbody>
		<tr>
			<td><strong>🎨&nbsp; Design</strong></td>
		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/design/">Product</a></td>
		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/design/#engineering">Engineering</a></td>
		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/design/#project-management">Project</a></td>
		</tr>
		<tr>
			<td><strong>🔢&nbsp; Data</strong></td>
		</tr>
		<tr style="height: 23.5px;">
			<td style="height: 23.5px;"><a href="https://madewithml.com/courses/mlops/exploratory-data-analysis/">Exploration</a></td>
		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/labeling/">Labeling</a></td>
		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/preprocessing/">Preprocessing</a></td>
		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/splitting/">Splitting</a></td>
		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/augmentation/">Augmentation</a></td>
		</tr>
		<tr>
			<td><strong>📈&nbsp; Modeling</strong></td>
		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/baselines/">Baselines</a></td>
		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/evaluation/">Evaluation</a></td>
		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/experiment-tracking/">Experiment tracking</a></td>
		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/optimization/">Optimization</a></td>
		</tr>
	</tbody>
</table>

# Python

## scikit-learn

Understand the sklearn API through this [example notebook](https://nbviewer.org/github/donnemartin/data-science-ipython-notebooks/blob/master/scikit-learn/scikit-learn-intro.ipynb). 
- fit
- transform
- predict
- fit_transform

## torch

Work through Steps 0-7 in the official PyTorch guide: https://pytorch.org/tutorials/beginner/basics/intro.html

## Packaging

- Use the cookiecutter data science project template for new projects: https://drivendata.github.io/cookiecutter-data-science/
- Read through the developing section of madewithml:
<table>
	<tbody>
		<tr>
			<td><strong>💻&nbsp; Developing</strong>&nbsp;</td>
		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/packaging/">Packaging</a></td>
		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/organization/">Organization</a></td>
		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/logging/">Logging</a></td>
		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/documentation/">Documentation</a></td>
		</tr>
			<td style="height: 23.5px;"><a href="https://madewithml.com/courses/mlops/styling/">Styling</a></td>
		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/makefile/">Makefile</a></td>
		</tr>
	</tbody>
</table>

## Jupyter

- Similar to [@radekosmulski](https://twitter.com/radekosmulski/status/1638882676596948997), I use VS Code exclusively in order to use Github Copilot in Jupyter
- You can [remote SSH](https://code.visualstudio.com/docs/remote/ssh) to connect to a server and run Jupyter on the server and use Copilot there as well (bare metal VMs, Cloud VMs, etc)
- Learn [hotkeys](https://towardsdatascience.com/jypyter-notebook-shortcuts-bf0101a98330) 

## Streamlit

- Learn by working through the [official example](https://docs.streamlit.io/library/get-started/create-an-app)
- [Streamlit Cheatsheet](https://docs.streamlit.io/library/cheatsheet)

# Github Copilot

Use [Github Copilot](https://github.com/features/copilot) for all coding (Python, Jupyter, SQL, etc.). I estimate it makes me 20% more productive for all programming tasks.

# madewithml (parts 5 and 6)

<table>
	<tbody>
		<tr>
			<td><strong>📦&nbsp; Serving</strong></td>		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/cli/">Command-line</a></td>
		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/api/">RESTful API</a></td>
		</tr>
		<tr>
			<td><strong>✅&nbsp; Testing</strong></td>
            </tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/testing/">Code</a></td>
		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/testing/#data">Data</a></td>
		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/testing/#models">Models</a></td>
		</tr>	
	</tbody>
</table>

# NLP

## Embeddings

- http://jalammar.github.io/illustrated-word2vec/
- Read through [Vicki Boykis' embeddings guide](https://vickiboykis.com/what_are_embeddings/)


## Transformers

- http://jalammar.github.io/illustrated-transformer/

# Language Models / Gen AI

## Prompt Engineering
- https://help.openai.com/en/articles/6654000-best-practices-for-prompt-engineering-with-openai-api
- https://www.promptingguide.ai/

# madewithml (parts 8 and 9)


<table>
	<tbody>
			<td style="height: 23.5px;"><strong>🚀&nbsp; Production</strong></td>
		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/dashboard/">Dashboard</a></td>
		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/cicd/">CI/CD</a></td>
		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/monitoring/">Monitoring</a></td>
		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/systems-design/">Systems design</a></td>
		</tr>
		<tr>
			<td><strong>⎈&nbsp; Data engineering</strong></td>
		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/data-stack/">Data stack</a></td>
		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/orchestration/">Orchestration</a></td>
		</tr>
		<tr>
			<td><a href="https://madewithml.com/courses/mlops/feature-store/">Feature store</a></td>
		</tr>
	</tbody>
</table>


# Extras

- [MIT: The Missing Semester of Your CS Education](https://missing.csail.mit.edu/)
- Great example of a full ML project ([Part 1](https://github.com/WillKoehrsen/machine-learning-project-walkthrough/blob/master/Machine%20Learning%20Project%20Part%201.ipynb), [Part 2](https://github.com/WillKoehrsen/machine-learning-project-walkthrough/blob/master/Machine%20Learning%20Project%20Part%202.ipynb), [Part 3](https://github.com/WillKoehrsen/machine-learning-project-walkthrough/blob/master/Machine%20Learning%20Project%20Part%203.ipynb)) from Will Koehrsen. Steps 1-3 is in Part 1, Steps 4-6 is in Part 2 and Steps 7-8 is in Part 3.

	1. Data cleaning and formatting
	2. Exploratory data analysis
	3. Feature engineering and selection
	4. Compare several machine learning models on a performance metric
	5. Perform hyperparameter tuning on the best model to optimize it for the problem
	6. Evaluate the best model on the testing set
	7. Interpret the model results to the extent possible
	8. Draw conclusions and write a well-documented report


# Continue to Learn

Remember, the field of data science is vast and constantly evolving. The most important skill to develop is the ability to learn and adapt to new tools, technologies, and techniques. Here are some resources to help you continue to learn:

## YouTube

- [@lexfridman](https://www.youtube.com/@lexfridman) - and associated [transcripts](https://karpathy.ai/lexicap/)
- [@AndrejKarpathy](https://www.youtube.com/c/AndrejKarpathy)
- [@jamesbriggs](https://www.youtube.com/@jamesbriggs)
- [@ai-explained-](https://www.youtube.com/@ai-explained-)

## Twitter

- [@jeremyphoward](https://twitter.com/jeremyphoward)
- [@radekosmulski](https://twitter.com/radekosmulski)
- [@omarsar0](https://twitter.com/omarsar0)

## Blogs

- [Jay Alammar](http://jalammar.github.io/)
- [Eric J Ma](https://ericmjl.github.io/)
- [Brandon Rohrer](https://e2eml.school/blog.html)