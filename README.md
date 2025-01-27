# End-to-End Wine Quality Prediction

This project provides a comprehensive pipeline for predicting wine quality using machine learning techniques. It encompasses data ingestion, preprocessing, model training, evaluation, and deployment through a Flask web application.

## Workflows
1. Update config.yaml
2. Update schema.yaml
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline
8. Update the main.py
9. Update the app.py


- To create environment = `conda create -p wineproj python=3.8 -y`
- To check available envs = `conda env list`
- To check available envs = `conda info --envs`
- To activate environment = `conda activate visa`
- To install requirements.txt = `pip install -r requirements.txt`
- To check install packages = `pip list`
- To check detailed about package = `pip show package_name`
- To install package = `pip install package_name`
- To uninstall package = `pip uninstall package_name`

## Path

```
>>> from pathlib import Path
>>> path = "test/test.py"
>>> Path(path)
WindowsPath('test/test.py')
>>> import os
>>> os.path.split(path)
('test', 'test.py')
```

## Git commands

- To add all file = `git add .`
- To add any particular file = `git add <file_name>`
- To commit = `git commit -m "commit message"`
- To push the code = `git push origin main`









**When I run "pip install -r requirements.txt" using terminal in VS code, I got this error:**

```
× Preparing metadata (pyproject.toml) did not run successfully.
  │ exit code: 1
  ╰─> [6 lines of output]
  ```
  when i try to install python latest verion by running `pip install python', it's giving error, although i have already installed it while creating the environment but showing version while running `python --version`

**Solution:**

To solve this issue, I install python lateset version by running `conda install Python` and its solved my problem.\
Then I run `pip install -r requirements.txt` and it's installed all the packages from the requirements.txt