+++
title = """Turning PDFs into <span class="block md:inline"> Research <span class='test' data-words='Data,Tables,Analyses,Trends' data-shuffle='true'></span>
with Jack Collins"""
sort_by = "weight"
extra.full_hero = true
+++

{% block_2c(bg="white" left_text="Overview") %}Do you ever feel that the data you need for your research is accessible but it’s not in a convenient table, such as company reports or building plans? Perhaps the information you need is spread out across many different documents? 

 If only we could read and extract structured data from thousands of written documents.


In this course, we explore how to accomplish this task by combining web scraping, Optical Character Recognition (OCR), and Natural Language Processing (NLP). Over four weeks, we provide online lessons and interactive sessions to learn the fundamentals of these key technologies.
{% end %}


{% block_1c(title="Introduction" bg="grey")%}
## Welcome to the course “Turning PDFs into Research Data”!

 BERD Academy is part of BERD@NFDI; funded by the Deutsche Forschungsgemeinschaft (DFG, German Research Foundation) – 460037581

 If not indicated otherwise, the contents of this course are licensed under CC BY 4.0 NC
 <br> <br> <br>

## Topics
- Methods for extracting text and files from websites using tools such as Selenium and how to avoid common pitfalls.
- Methods for extracting text from images, such as scans of written documents.
- Exploring technologies that can help automate data extraction from harvested text, including Retrieval Augmented Generation (RAG), and a critical review of common data quality issues.
<br> <br> <br>

## Format
This is an online course.

- **Week 1:** Watch pre-prepared video lectures about relevant theory and demonstration of example exercises. The topic is web scraping and OCR (~45 min). Interactive Online Session (~60 min).

- **Week 2:** Applying last week’s lessons to the example coding exercise or your own project (~30 min). Interactive Online Session (~60 min).

- **Week 3:** Watch pre-prepared video lectures about relevant theory and demonstration of example exercises. The topic is NLP and common data extract issues (~30 min). Interactive Online Session (~60 min).

- **Week 4:** Applying last week’s lessons to the example coding exercise or your own project (~30 min). Interactive Online Session (~60 min).
<br> <br> <br>

## Weekly Meetings
The course includes 4 live Online Meetings, in which you will discuss the week’s contents with the instructor and fellow participants: 

- Meeting 1: Mar 13, 2025, 4:30pm – 5:30pm CET* 
- Meeting 2: Mar 20, 2025, 4:30pm – 5:30pm CET*
- Meeting 3: Apr 03, 2025, 4:30pm – 5:30pm CEST*
- Meeting 4: Apr 10, 2025, 4:30pm – 5:30pm CEST*
<br><br> 

*Please note the timezone and the change to summertime during the run of the course.
<br> <br> <br>
## About the Instructor
[John ‘Jack’ Collins](https://www.uni-mannheim.de/gess/programs/cdss/our-students/2022/john-jack-collins/) is a PhD Student in Sociology at the Graduate School of Economic and Social Sciences. He holds a Bachelor’s of Sociology with Honours from the Australian National University. Jack has a Master’s degree in Data Science from James Cook University. His Master’s project was regarding predictive modelling for student attrition from sub-tertiary courses in Australia. During his Master’s studies, he also assisted in research projects regarding social attitudes and voting behaviour in Australia. Before starting PhD, Jack was a Senior IT Consultant specialising in data engineering, analytics and software development. Jack is interested in applying Data Science and IT to sociological research, particularly with regard to machine learning, analytics, and web applications.
{% end %}

{% block_1c(title="Contents" bg="white")%}
## Prerequisites
- Basic programming knowledge (R, python, …)
   Note that the course will be in Python, but if you only know R, this is still ok! The code examples are simple and will run entirely on [Google Colab](https://colab.research.google.com/), meaning you will not have to install anything. This course will make a good opportunity to try Python for the first time and you can also try the self-paced [BERD introduction to Python course](https://www.berd-nfdi.de/berd-academy/data-science-with-python/).

- Willingness to learn new technical skills

- [A Google Account](https://support.google.com/accounts/answer/27441?hl=en)
<br> <br> <br>

## What to prepare
- If you want to code in Python, you will need a Google account so you can use [Google Colab](https://colab.research.google.com/). You may also need to use your Google Account to open an account with [Llama AI](https://console.llama-api.com/). We will do this together during the course if necessary, so no need to prepare beforehand.
<br> <br> <br>

## Course Materials
- [An example single PDF](https://github.com/BERD-NFDI/turning-pdfs-into-research-data.io/blob/e52796ed0800105ded224ec691ddaf0c415f128d/docs/Gemeinde_Kirchheim_Sportsfield.pdf)
- For those students who don;t have a particular project of their own, here’s a PDF you could practise with: [https://arxiv.org/abs/2205.14135](https://arxiv.org/abs/2205.14135)
- A zipped file of many examples PDFs
 <br> <br> <br>

## Readings and external resources
 - (optional content) If you want to understand Large Language Models (LLM) on a more technical level, this makes an excellent visual overview of the mathematics involved. <br><br> 3Blue1Brown (Director). (2024, April 1). But what is a GPT? Visual intro to transformers | Chapter 5, Deep Learning. [https://www.youtube.com/watch?v=wjZofJX0v4M](https://www.youtube.com/watch?v=wjZofJX0v4M) 

 - (optional content) If you want a more advanced discussion of web scraping, this is a dedicated textbook (not necessary for this course). <br> <br>Automated Data Collection with R: A Practical Guide to Web Scraping and Text Mining | Wiley. (n.d.). Wiley.Com. Retrieved 3 June 2024, from [https://www.wiley.com/en-us/Automated+Data+Collection+with+R%3A+A+Practical+Guide+to+Web+Scraping+and+Text+Mining-p-9781118834817](https://www.wiley.com/en-us/Automated+Data+Collection+with+R%3A+A+Practical+Guide+to+Web+Scraping+and+Text+Mining-p-9781118834817)

 - The applied examples from this course are based on work by a team of researchers from this project. <br><br> DSSGxMunich/land-sealing-dataset-and-analysis: This repo offers the code developed during DSSGx Munich 2023 for producing and analysing a comprehensive dataset about land parcels from the state of NRW in Germany. (n.d.). Retrieved 3 June 2024, from [https://github.com/DSSGxMunich/land-sealing-dataset-and-analysis](https://github.com/DSSGxMunich/land-sealing-dataset-and-analysis)

 - Using an AI ‘BERT’ to classify open-ended text with some pre-training of BERT involved. <br><br> Gweon, H., & Schonlau, M. (2024). Automated classification for open-ended questions with BERT. Journal of Survey Statistics and Methodology, 12(2), 493–504. [https://doi.org/10.1093/jssam/smad015](https://doi.org/10.1093/jssam/smad015)

 - Comparing LLMs to dedicated Named Entity Extraction Deep Learners <br> <br> How effective are large language models in named entity extraction compared to traditional machine learning algorithms? | 10 Answers from Research papers. (n.d.). SciSpace - Question. Retrieved 3 June 2024, from [https://typeset.io/questions/how-effective-are-large-language-models-in-named-entity-p29rfup468](https://typeset.io/questions/how-effective-are-large-language-models-in-named-entity-p29rfup468)[.](https://en.wikipedia.org/wiki/Kerry_Airport)

 - This researcher conducted the web scraping project which supplies many examples in this course. <br><br> ldmnch. (2024). Ldmnch/bavaria-building-plans-digitalization [Jupyter Notebook]. [https://github.com/ldmnch/bavaria-building-plans-digitalization](https://github.com/ldmnch/bavaria-building-plans-digitalization) (Original work published 2023)

 - Comparison of several OCR tools. <br><br>OCR in 2024: Benchmarking Text Extraction/Capture Accuracy. (n.d.). AIMultiple: High Tech Use Cases & Tools to Grow Your Business. Retrieved 3 June 2024, from [https://research.aimultiple.com/ocr-accuracy/](https://research.aimultiple.com/ocr-accuracy/)

 - Free web article providing detailed code examples of web scraping in Python. <br><br> Python, R. (n.d.). A Practical Introduction to Web Scraping in Python – Real Python. Retrieved 3 June 2024, from [https://realpython.com/python-web-scraping-practical-introduction/](https://realpython.com/python-web-scraping-practical-introduction/)

 - Website designed to help developers practice web scraping. <br><br> Test Sites | Web Scraper. (n.d.). Retrieved 3 June 2024, from [https://webscraper.io/test-sites](https://webscraper.io/test-sites)

 - Comparison of several industry solutions for extracting data from open text.<br><br>Top AI Apps & Tools for Document data extraction. (n.d.). Deepgram. Retrieved 3 June 2024, from [https://deepgram.com/ai-apps](https://deepgram.com/ai-apps)

 - Introduction to ‘Nougat’ an OCR model especially for parsing tables and equations in academic papers.<br><br> [https://facebookresearch.github.io/nougat/](https://facebookresearch.github.io/nougat/)
{% end %}

{{
mailchimp_form(top_text="Subscribe to receive our latest research updates.",subscribe_text="I would like to receive email communications from BERD and agree with the data protection regulations and the described processing of personal data there.")
}} 
