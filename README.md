
<h1 align="center">Tool/App User Documentation Template</h1>
Yvonne Beirnee FitzGerld  

10 July 2022



<h4 align="center">“It doesn’t matter how good your software is,“</h4>
<h4 align="center">“ because if the documentation is not good enough, people will not use it.“</h4>
<h6 align="center">— Daniele Procida</h6>

---



Template for creating user-centric user documentation. This Template is influenced/inspired by [The Documentation and Usability course](https://jhudatascience.org/Documentation_and_Usability/) and is a part of [The Informatics Technology for Cancer Research (ITCR) Education Resource training series](https://www.itcrtraining.org/courses). Click for a preview of this Template.


<h3 align="center">How To Use This Repository</h3>

- Click 'Use This Template' button on the right (Note: sometimes this button is colored green)
- Name your copy of the Template a name related to your Tool/app 

_Go to your computer's command line_:







What does this Doc need to say?

- What it is
- WHy it is important
- How to use
    - How use template
    - How to use MkDoc
    - Also can use in webpage
- Why use
- Who influecence




---
---
---


# Tool-App-Documention-Templates
Templates for creating user centric documentation.

“It doesn’t matter how good your software is, because if the documentation is not good enough, people will not use it.“

— Daniele Procida

“Code tells you how; Comments tell you why.”

— Jeff Atwood (aka Coding Horror)


---
add from class 

https://github.com/jhudsl/template-documentation

# Template Documentation

This is a companion tool for the creating your own documentation for an informatics tool following our [Documentation and Usability course](https://jhudatascience.org/Documentation_and_Usability/) as a part of an [ITCR training series](https://www.itcrtraining.org/).

To see a preview of what this demo documentation website looks like go here:
http://jhudatascience.org/template-documentation/

### To get started with this repository:

- Click `Use this Template` to get started.  
- Name your repository something that relates to your tool.  

_On your computer's command line_:    
- [`git clone` your new repository](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) you made from our template.   
- Navigate to your the root of your local version of this repository.   
- [Install mkdocs following their instructions.](https://www.mkdocs.org/#installation).  
- Run `mkdocs serve` to see a preview of your docs   
- Edit the template pages we've provided in the `docs/` folder to pertain to your own tool.  
- As you make changes you can run `mkdocs build` and then `mkdocs serve` to see a preview.  
- When you are ready to publish your documentation to its own website, run [`mkdocs gh-deploy`](https://www.mkdocs.org/user-guide/deploying-your-docs/), it will return the web address of your new site.
- Go to the address it returned and bask in the success of your newly made documentation!  
- Make sure to add plenty of links to this documentation to your Github repository for your tool or your tools' GUI.

As you continue to edit your documentation, continue to use `mkdocs serve` to see a preview and `mkdocs gh-deploy` to publish your changes to your website.

### Using the template files individually:

- Download the [folder of template files here](https://raw.githubusercontent.com/jhudsl/itcr-template-documentation/master/templates.zip) and the checklist itself [here](https://raw.githubusercontent.com/jhudsl/itcr-template-documentation/master/docs/well_documented_checklist.md).
- Complete each markdown template, filling in the blanks as you go along with the course.  
- File a pull request to your own repository to add these files.  


-----
example stuff
https://github.com/Descent098/ezcv

ezcv
A python-based static site generator for setting up a CV/Resume site

Table of Contents
What does ezcv do?
Features & Roadmap
Why should I use ezcv?
Who is ezcv for?
Quick-start
No-code setup
Installation
From PyPi
From source
Getting started
Default File structure
CLI
Additional Documentation
Examples and resources
What does ezcv do?
ezcv is a purpose built static site generator for creating personal resume/portfolio/cv sites

Features & Roadmap
A large collection of built in themes
Flexible templating with Jinja2
Fully customizable configuration files and sections
Simple markdown syntax for content building
Why should I use ezcv?
ezcv is a great choice if:

You are fond of one of the built in themes
You want a free and open source static site generator
If you want a simple to use static site generator based on Jinja
If you are familiar with markdown and yaml, and want a system that can be extended
You are not familiar with static site generators and want a simple one to try out
You want a static site generator with a built in github pages deploy pipeline
ezcv is not a great choice if:

You want a widely used industry solution (something like hugo or jekyl would be better for this)
You need low level access to the API for complicated extensions that are not possible within jinja
You are not familiar with markdown, yaml and jinja and want a frontend to edit your site with ( netlify, squarespace or wix would be better for this)
Who is ezcv for?
People who are not necessarily familiar with coding, let alone web development
People who are familiar with web development and want a very simple to use static site generator
People who are familiar with web development but don't want to bother writing pure html for their site
Quick-start
Here's everything you need to know to get started with ezcv.

No-code/remote setup
Note that there is an option to develop a site completely on your browser without needing to install anything or know how to use git. For details on setting this up, please visit https://ezcv.readthedocs.io/en/latest/quick-start/#remote-editing.

Installation
To use ezcv you will need python 3.6+ (earlier versions wont work) and pip for python 3.

From PyPi
Run pip install ezcv
From source
Clone this repo: https://github.com/Descent098/ezcv
Run pip install . or sudo pip3 install .in the root directory
Getting started
The easiest way to get started is by running:

ezcv init <name>

Replacing the <name> argument with your name (use "" if you want to use your full name i.e. ezcv init "Kieran Wood").

File structure
When you run the command a new folder will be created with your name, and some starter files like this:

Legend

Icon	Meaning
📁	File Folder
📷	Image file
📝	File you should edit/delete
📄	File you don't need to edit/shouldn't delete
📁<name>/
├── 📁.github/
│   └── 📁workflows/
│       └── 📄ezcv-publish.yml
├── 📁content/
│   ├── 📁education/
│   |   ├── 📝example-current.md
│   |   └── 📝example-old.md
│   ├── 📁projects/
│   |   └── 📝example.md
│   ├── 📁volunteering_experience/
│   |   ├── 📝example-current.md
│   |   └── 📝example-old.md
│   └── 📁volunteering_experience/
│       ├── 📝example-current.md
│       └── 📝example-old.md
├── 📁images/
│   ├── 📷 abstract-landscape.jpg
│   └── 📷 ice-caps.jpg
├── 📄.gitignore
└── 📝config.yml
From here you can go into your config.yml file and pick a theme, then start filling out your content according to what's available for the theme.

To preview your content use:

ezcv -p

If you're on github then pushing the contents to master/main will activate the publish workflow and automatically publish the site to <username>.github.io.

CLI
Usage:
    ezcv [-h] [-v] [-p]
    ezcv init [<name>] [<theme>]
    ezcv build [-d OUTPUT_DIR] [-o]
    ezcv theme [-l] [-c] [-m] [-s SECTION_NAME] [<theme>]


Options:
-h, --help            show this help message and exit
-v, --version         show program's version number and exit
-l, --list            list the possible themes
-c, --copy            copy the provided theme, or defined site theme
-p, --preview         preview the current state of the site
-o, --optimize        Optimize output files (takes longer to run)
-d OUTPUT_DIR, --dir OUTPUT_DIR The folder name to export the site to
-m, --metadata        Generate metadata for the theme
-s SECTION_NAME, --section SECTION_NAME The section name to initialize
See the CLI Documentation for additional details

Additional Documentation
User Docs

API Docs

Examples and resources
Template repository for bootstrapping projects

Template repository for ezcv integrated with flask

See documentation for included themes for examples of each of the included themes
---
_Add Tool/App Contact Info_
<center>Yvonne M. Beine FitzGerald | [theYvonne.com](https://theyvonne.com) | hi[@]theyvonne.com </center>  

_Add Links_

<center>Terms | Privacy Policy | App/Tool </center>

<center>Lasted Update: 7 July 2022 </center>
