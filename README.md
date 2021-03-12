# Interactive Data Visualization with Python using Bokeh

This repository provides the data in support of the course Interactive Data Visualization with Python using Bokeh, provided by Cloud Academy.
You can contact the author directly on [Linkedin](https://www.linkedin.com/in/andrea-giussani-764816148/).

## Data

You can find the necessary data in the `data` folder. I suggest to follow the following steps in order you to be able to replicate the course steps on your local host.

Open your favourite terminal emulator, and then:

#### 1. Clone the repo
This action will clone the repo, including the data that is used for this course.
```bash
git clone https://github.com/cloudacademy/interactive-data-visualization-with-bokeh.git
```
#### 2. Create a python virtualenv
```bash
pip install virtualenvwrapper
mkvirtualenv - p python3 <NAME_ENV>
```
Please check the offical documentation for troubleshooting [here](https://virtualenvwrapper.readthedocs.io/en/latest/command_ref.html). I am assuming you are using a standard python environment. If, instead, you are using anaconda, then please check the offical documentaiton to create a virtual env specific for conda [here](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html). For example, you can create a conda virtual env with python 3.7 as follows:

```bash
conda create -n <NAME_ENV> python=3.7
```
#### 3. Install the necessary requirements:
```bash
pip install -r requirements.txt
```
or alternatively using conda
```bash
conda install --file requirements.txt
```
#### 4. Open a jupyter notebook by running:
```bash
jupyter notebook
```
You are now ready to get your hands dirty: enjoy!
