# 620-mod6-web-scraping
WMNLP, Module 6
Melissa Stone Rogers, [GitHub](https://github.com/meldstonerogers/620-mod6-web-scraping)

## Introduction
Professional project using python, jupyterlab, and beautifulsoup4 to practice web scraping. 
Commands were used on a Mac machine running zsh. Project was forked by the following respository's by Dr. Denise Case: [620-mod6-web-scraping](https://github.com/denisecase/620-mod6-web-scraping). 

## Project Set Up and Dependency Management 
Fork the above repository in GitHub and clone to your machine. Open project in VS Code. 
```zsh
git clone project.url
```

Verify your Python version and create a virtual environment. 
```zsh
python3 --version

```
```zsh
python3 -m venv venv
source venv/bin/activate
```
### Install required packages and dependencies into virtual enviornment
```zsh
python -m pip install beautifulsoup4
python -m pip install html5lib
python -m pip install requests
python -m pip install spacy
python -m pip install spacytextblob
python -m pip install matplotlib
```
### Initial Project Save
```zsh
git add .
git commit -m "initial"                         
git push origin main
```


## Complete Your Project
Save your project and push back to your repository. 
```zsh
git add .
git commit -m "final"                         
git push origin main
```