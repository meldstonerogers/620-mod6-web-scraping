# 620-mod6-web-scraping
WMNLP, Project 6
Melissa Stone Rogers, [GitHub](https://github.com/meldstonerogers/620-mod6-web-scraping)

## Introduction
Professional project praciting Web Scraping and NLP with Requests, BeautifulSoup, and spaCy.
Commands were used on a Mac machine running zsh. This project was created via a copy of the jupyter notebook provided by Northwest Missouri State University's School of Computer Science and Information Systems repository: [web-scraping](https://github.com/wmnlp-materials/web-scraping). 

## Project Set Up and Dependency Management 
Fork the following repository by Dr. Denise Case: [620-mod6-web-scraping](https://github.com/denisecase/620-mod6-web-scraping). Clone repository to your machine. Open project in VS Code. 
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
python -m spacy download en_core_web_sm
```
### Initial Project Save
```zsh
git add .
git commit -m "initial"                         
git push origin main
```
## Project Work
Complete the [web-scraping](https://github.com/denisecase/620-mod6-web-scraping/blob/main/web_scraping.ipynb) jupyter lab notebook to familiarize yourself with various web scraping tools. Once completed, download the [web-scraping project file](https://github.com/wmnlp-materials/web-scraping/blob/master/web-scraping.ipynb) from the NWSU [web-scraping repository](https://github.com/wmnlp-materials/web-scraping). Move web-scraping.ipynb file into your 620-mod6-web-scraping respository folder on your local machine. Open the downloaded file in VS Code. 

Complete the project, regularly pushing changes to your project repository.

## Finalize Your Project
Save your project and push back to your repository. 
```zsh
git add .
git commit -m "final"                         
git push origin main
```