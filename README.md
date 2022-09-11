# From PHAT to DEADASS
An look at how the New York Times uses slang in crossword puzzles and what it reveals about the publication's culture.

#### <a href = "https://aishichandra.github.io/Slang_NYT_XWord/"> Read the article! </a>

##### BACKGROUND
I enjoy solving the New York Times crossword puzzles, and I am always amused when I come across phrases like 'DRIP,' 'ACIDTRIP,' or 'DEADASS,' because I imagine a respectable, educated, cultured white man uttering these words as I find them in the puzzle. 

##### 1. Data Collection
I wrote a method that scrapes the data using <b>BeautifulSoup</b> from XWordInfoTo for the years 1976-2022. To see how I scraped data from XWordInfo, see Python Analysis/XWordInfo_scraping.ipynb. I saved the dataframes into a csv (crossword_year_2015_2021.csv and crossword_year_2022). I chose these years because I wanted to examine how the puzzle changed after Shortz assumed his position as editor but I didn't think it was necessary to collect it all the way from 1940's (the scraping process was very slow). 

##### 2. Data Analysis
The data analysis was done using the Python library <b>Pandas.</b> Some of the graphs were created using <b>Altair</b>. Crosswords.ipynb was my prelim analysis (this notebook only analyzes a subset of the whole data)- most of the analysis isn't focused on the story that I wrote, rather it was the path to the analysis I did for my story - but this notebook is more interesting than the other ones. "More Crossword Analysis.ipynb" was what I used for the story: I expanded the dataset to include all the years till 2022 and used it to create .csv's to create visuals on <b>Datawrapper</b>. 

##### 3. Visuals
Graph1, Graph2 and Graph3 are the visuals in the order as they are seen in the report. They were created in <b>Datawrapper</b>, edited in <b>Adobe Illustrator</b> and uploaded to html using <b>ai2html.js</b>. 

##### 4. Sources

<b> Sources: </b><br/>
“Crossword Editor Opens the Door to Innovation across the Board Shortz Story.” Baltimore Sun, https://www.baltimoresun.com/news/bs-xpm-1993-11-22-1993326127-story.html. <br/>
“In the CROSS-FIRE.” Chicago Tribune, https://www.chicagotribune.com/news/ct-xpm-1993-11-07-9311080002-story.html. <br/>
Aronow, Isaac. “How Word Lists Help - or Hurt - Crossword Puzzles.” The New York Times, The New York Times, 6 Oct. 2021, https://www.nytimes.com/2021/10/06/crosswords/wordlists-for-constructing-puzzles.html. <br/>
Zhou, Yanchun, and Yanhong Fan. “Home-Academy Publication.” Home-Academy Publication, Changchun University of Science and Technology, Changchun, China, https://academypublication.com/. <br/>
“Unpack.” GRAMMARIST, 16 Apr. 2022, https://grammarist.com/new-words/unpack/. <br/>

Apart from the sources that I have listed, I messaged a few NYT Crossword constructors on <b>Twitter</b> who were incredibly kind with their time: Aimee Lucido, Will Nediger and Robyn Weintraub. While Aimee and Will are featured in the story, Robyn's comments were about social media and word lists -> an angle I didn't have too much time to research and explore for this piece but a important topic to address in the future



##### 5. And so much gratitude to Jessie Blaeser and Rodrigo Menegat helping me throughout this project - from brainstorming graphic ideas to editing my drafts.




