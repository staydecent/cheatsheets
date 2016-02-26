---
title: virtualenv
---

### Create a virtual environment
    
    $ virtualenv --no-site-packages yourenv  

If you build with the optional `--no-site-packages` switch, your virtual environment will not inherit any packages from your "global" site-packages directory.

### Activate the virtual environment
    
    $ source yourenv/bin/activate

or, for fish

    $ source yourenv/bin/activate.fish

### Installing dependencies

    (yourenv)$ pip install YourFancyModule

### Saving installed depencies

    (yourenv)$ pip freeze > requirements.txt

### Installing dependencies from pip requirements file

    (yourenv)$ pip install -r requirements.txt 

### Deactivate the virtual environment
    
    (yourenv)$ deactivate

