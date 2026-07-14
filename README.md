 
# Through the Tomes of Shodhganga: The Queen of the Arabian Sea as a 'Subject' of Research

### Lede Program - Project 2 

## Overview

Project webpage: [Through the Tomes of Shodhganga: The Queen of the Arabian Sea as a 'Subject' of Research](https://vimalkrishnanr.github.io/phd-kochi/)

In this project, I explore data to show how academics have studied my home city of 'Kochi', also known as 'Cochin', and 'Ernakulam'. Kochi is a coastal city in Kerala and it is famously called 'The Queen of the Arabian Sea', bringing to the fore its historic natural harbour and a legacy of spice trade. Here, I present a data-backed narrative to show how Kochi is understudied and presents immense potential for a diverse range of academic research.

## Data Collection Process 
The primary source of my data is the open access repository named Shodhganga, maintained by the INFLIBNET Centre, an autonomous inter-university centre of the University Grants Commission (UGC):

https://shodhganga.inflibnet.ac.in/

I scraped thesis titles containing the toponyms 'Ernakulam', 'Cochin', and 'Kochi' available on Shodhganga and consolidated them into a single dataset. 

Note: The dataset excludes thesis titles do not contain one of these three toponyms. While acknowledging that other research studies may concentrate on this region without incudling its name in their titles,  this dataset has been selected based on the assumption that thesis titles that explicitly include the place name are those most likely to feature the city as the primary focal point. 

## Data Analysis Process
After removing duplicate thesis title entries, I manually coded the subcategories(topics) of the titles. These subcategories were then grouped into defined superordinate categories using an AI model. After training the model on a random sample of the data, I evaluated its accuracy using a confusion matrix. Finally, the AI model classified all subcategories into superordinate categories, which I further refined manually.   

Some of the primary questions that I wanted to answer are as follows: 
1. Is there a dominant research framework that analyses Kochi?  
2. What is the distribution of research topics?  
3. Are there significant domains that are under-represented in the academic research on Kochi?

Using python and Pandas, I analysed the counts of titles, their subcategories and superordinate categories. The data was visualised in the form of bar charts, stacked barcharts, and hierarchy gaphs. 

## Skills learnt 
This project has been an enriching experience. I could refine my technical skills in the application of python, pandas, HTML, CSS, and data visualisation tools like Datawrapper and RawGraphs. 

## Tools used
 -  Python and various Python pacakges
 -  Jupyter Notebooks
 -  VS code
 -  Flourish
 -  Datawrapper
 -  RawGraphs
 -  Adobe Illustrator

## Future Work
I hope to return to this project to do deeper analysis in pandas and to design a website that is more visual and interactive. I also plan to explore libaries like D3 for visualisng data, especially the hierarchy graphs. I also plan to use the project further develop my graphic and web design skills.

## References: 

1. [Shodh Ganga : A reservoir of Indian Theses. The Indian Librarian Blog.](https://theindianlibrarian.blogspot.com/2019/06/shodh-ganga-reservoir-of-indian-theses.html)
2. [Shodhganga, INFLIBNET Centre](https://shodhganga.inflibnet.ac.in/)
3. [A bachelor’s in rare earths? In China, there are schools for that](https://www.reuters.com/graphics/CHINA-RAREEARTHS/UNIVERSITIES/zgpolorrwvd/) 
4. Kerala Tourism Website (https://www.keralatourism.org/faq/is-kochi-and-ernakulam-same) 
5. [Page Templates](https://jsoma.github.io/page-templates/)
 
## Acknowledgements: 
I thank my intstructors, Jonathan Soma and Jeremy B. Merrill, for guidance on workflows related to scraping and AI-enabled data classification, and Youyou Zhou, for lectures on the D3 library and the creative applications of SVG graphics in visual journalism. I acknowledge Jui Sarwate's mentorship during this project, and I must also thank my friend, Nandakumar R, for nurturing in me an interest in the cultural heritage of Kochi! 



