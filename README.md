# SR-Wiki
A collection of information for Speedrunners the game accessible [here.](https://starfilledsky.github.io/SR-Wiki/)  




## Ways to contribute

### Sending through form

Todo google forms:  
- Submission link  
- General inquiry link(suggestions, concerns, corrections, etc..)

### Contributing more directly

You can edit the markdown files in src/ directory and submit a pull request through the Github web interface.

### Building the project locally

The wiki is created by making [markdown](https://www.markdownguide.org/getting-started/) files and [material](https://squidfunk.github.io/mkdocs-material/) for [mkdocs](https://www.mkdocs.org/) turning them into webpages. Instructions for if you wanted to build it locally for some reason:

> [!Note]  
> This assumes you already have python installed and have familiarity with the terminal.

Clone the repository.  
``git clone https://github.com/StarFilledSky/SR-Wiki``  

Create a python virtual environment in the directory.  
``python -m venv venv``  

Activating the virtual enviroment.  
Windows  
``./venv/Scripts/Activate.ps1``  
Linux / MacOS  
source myvenv/bin/activate``

Install the requirements for building the project.  
``pip install -r requirements.txt``

You can now edit files in the src/ directory and use `mkdocs build` to generate files in the docs/ directory and `mkdocs serve` if you wanted to view the files served from a local webserver.
