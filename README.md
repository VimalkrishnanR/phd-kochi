 
# Through the Tomes of Shodhganga: The Queen of the Arabian Sea as a 'Subject' of Research

### Lede Program - Project 2 

## Overview

Project webpage: [Through the Tomes of Shodhganga: The Queen of the Arabian Sea as a 'Subject' of Research](https://vimalkrishnanr.github.io/phd-kochi/)

In this project, 

## Data Collection Process 
The primary source of my data is the open access repository named Shodhganga, maintained by the INFLIBNET Centre, an autonomous inter-university centre of the University Grants Commission (UGC):

https://shodhganga.inflibnet.ac.in/

Scraping 

## Data Analysis Process

Some of the primary questions that I wanted to answer are as follows: 
1. What is the overall current composition of the Greek and Roman Art Department, at CMA? 
2. What are the different types of artworks held by the department? 
3. What are they made out of? 
4. Exhibition and Citation history: 
 - 4.1: Compared to other departments, how widely have artworks in the Greek and Roman Art Department been exhibited? 
 - 4.2: Which is the most cited and most exhibited artwork within the Greek and Roman Art Department and within the museum's entire collection?
 - 4.3: Which are the artworks, currently held by Greek and Roman art Department, that constituted the exhibits in the inaugural exhibition?

To allow for deeper practice with pandas, I streamlined the scope of the project. I focused on questions 1, 2, 3, and 4.3. 

The data analysis involved identifying the categories/columns that were relevant for my questions and making subsets of the dataframe. I used the pandas package for casting the json data into a dataframe. By filtering relevand columns, I did further analysis like value counts (for pictogram) and cross tabulations (for sankey chart). To make a list of artworks that were exhibited in the inaugural exhibition, I filtered the  'exhibition' column by applying the string value 'Inaugural Exhibition'.

## Skills learnt 
This project has been an enriching experience. I could refine my technical skills in the application of python, pandas, HTML, CSS, and data visualisation tools like Flourish. I also learnt how data analysis and visualisations work best when they complement an overarching narrative.

## Tools used
 -  Python and various Python pacakges
 -  Jupyter Notebooks
 -  VS code
 -  Flourish
 -  Datawrapper
 -  RawGraphs
 -  Adobe Illustrator

## Future Work
I hope to return to this project to do deeper analysis in pandas and to design a website that is more visual and interactive. I also plan to explore libaries like D3, three.js and and further develop my graphic and web design skills.

## References: 

1. [Shodh Ganga : A reservoir of Indian Theses. The Indian Librarian Blog.](https://theindianlibrarian.blogspot.com/2019/06/shodh-ganga-reservoir-of-indian-theses.html)
2. [Walt Disney Studio's Drawing on the Past](https://www.reuters.com/graphics/DISNEY-100/HISTORY/znvnzmzgjvl/)
3. [Shall we call it the Metropolitan Meow-seum of Art? Cats rule the canvas in art galleries at The Met museum](https://surbhi-bh.github.io/cats-at-the-met-museum/)
4. [Page Templates](https://jsoma.github.io/page-templates/)
5. [1970.16 Neck Amphora](https://sketchfab.com/3d-models/197016-neck-amphora-0bb2525bdd734bf69d5a7b2b051928ad)
6. [Catalogue of the inaugural exhibition, June 6-September 20, 1916](https://library.si.edu/digital-library/book/catalogueinaugu00clev)
7. [Catalog of the inaugural exhibition : June 6-September 20, 1916](https://library.si.edu/digital-library/book/catalogofinaugur00clev)
## Acknowledgements: 
I thank my intstructors Jonathan Soma and Jeremy Merill for guidance on workflows related to scraping and AI-enabled data classification. I also thank Jui Sarwate for project mentorship.  



