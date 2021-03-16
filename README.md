# Streamlit-Webapps
## Summarization App
A Web App for generating summaries from text using extractive summary (LexRank and TextRank)

+ Packages Used
```bash
pip install 
```
	- streamlit
	- pandas
	- seaborn
	- matplotlib
	- gensim
	- sumy
	- gensim_sum_ext 
	- rouge

#### App Structure
+ Home
+ About
	
 ------------------------------------------------------------------------------------------------
 
## NLP app with Streamlit & Spacy
A Simple NLP app for text analysis with drag and drop for files.


#### Requirement
+ pip install
	- streamlit
	- pandas
	- matplotlib
	- seaborn
	- spacy
		python -m spacy download en
	- textblob
	- neattext
	- wordcloud

+ File Processing
	- docx2txt
	- pyPDF2
	- pdfplumber

### Refactoring and Restructuring
+ radon: static code analysis
	-mi
	-cc
	- hal metric
+ black:format
+ vulture:unsused import
+ mypy
+ pycodestyle

--------------------------------------------------------------------------------------------

## MetaData Extraction App
A Data App for extracting metadata from images,audio files and pdf and docx.

+ Packages
```bash
pip install 
```
	- streamlit
	- pandas
	- pillow
	- exifread
	- seaborn
	- matplotlib
	- pyPDF2
	- mutagen
	- tinytag
	- docx2txt
	- python docx

#### App Structure
+ Home
+ Image
+ Audio
+ PDF/Docx
+ About
	- Monitor
	- Stats of Uploads



### Deploying with Docker
+ Docker is an open platform for developing, shipping, and running applications. 
+ Docker enables you to separate your applications from your infrastructure so you can deliver software quickly

#### Requirements
+ Install Docker
+ Dockerfile
+ App + Requirements.txt

#### Steps to get Requirements.txt
+ Using Pipreqs
```bash
pip install pipreqs
```
+ Point Pipreqs to folder
```bash
pipreqs path\to\folder
```

+ Using Pip or Pipenv
- pip freeze > requirements.txt
- pipenv -r lock > requirements.txt
