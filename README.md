# python_app_test

Trying some new stuff with python

## Start a project

In a terminal, create virtual environment, install scrapy and create a project.

Be sure to have a Python interpreter.

_ctrl-shift-p_ -> python venv

```bash
python -m venv venv
source venv/Scripts/activate
pip install scrapy
scrapy startproject [project_name]
```

## Usefull things todo in the terminal

#### Enter the website.

```bash
scrapy shell [url]
```

Return certain item from the web site.

```bash
response.css('title')
response.css('title::text').get()
```
