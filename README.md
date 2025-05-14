

# LA Times Crosswords: A Data Gathering Project


### Description
This is my Crossword Puzzle Project GitHub Repository. In this project, I have created a dataset based on the answers to the LA Times Crossword Puzzle between the years 2019-2024. The dataset is built off the [LAX](https://laxcrossword.com/) crossword blog that for over a decade has posted the answers to the LA Times Crossword Puzzles. The dataset I have created contains answers, authors, editors, and dates from *nearly* every LA Times Crossword from 2019 to 2024. I have then used this dataset to analyze thousands of crossword answers and identify the patterns and trends that occur in this daily puzzle.

### Rationale
Admittedly, the original impetus for this project was because I was mad that I kept seeing the same answers in my crossword puzzles and I wanted to have the data to back up and validate my indignation. Some have even gone so far as to describe it as a "spite project", a baseless claim that I refute. However, since work has begun, I now believe that the dataset I have created has actual merit beyond proving a point. I think is interesting to see the different trends that occur in these crossword puzzles that are a daily part of peoples' lives, and see what aspects of popular culture, current events, history, etc. have made it into these puzzles. 

### Workflow
- Scrape the crossword clues and relevant metadata from the past 5 years or so from the LAXCrossword blog using Python and BeautifulSoup and export it into a CSV using Pandas
- Clean the data into a usable dataset using a mixture of Pandas and Open Refine
- Analyze and visualize the dataset using tools like Pandas and the Voyant text analysis tool to search for trends and patterns
- Draw conclusions and prepare findings for presentation

### Further Uses
I believe that the crossword dataset will actually be very useful for a variety of projects moving forward. In my own project, I have only scratched the surface of the dataset, answering the most basic questions and doing initial analysis. I think there is ample opportunity for people to build on the dataset and possibly expand it. The code I used to scrape the data could easily be used to go even further back to 2012, which is when the blog was first created and could also be adapted to gather data from LAX' sister blog that gathers NYT Crossword answers for comparison. 

### Files

- BurkeCrosswordProject(1).ipynb : The python script I used to scrape data from the LAX Blog
- BurkeCrosswordDataAnalysis.ipynb : The python notebook I used to analyze my database
- LATimesCrosswordDataCSV.csv : The cleaned data including answers, authors, co-authors, co-co-authors, editors, dates, and URL
- Crossword Puzzle Project Images : My folder of visualizations I created from the dataset

