# Disney-Viz-Jupyter-Notebooks

This project is designed to gather clean and sort data in preperation to create several visualizations to answer specific questions.

## Questions:

### Pixar Box Office Sales
  1. Which Pixar movie has grossed the most worldwide.
  2. Has Disney's purchase of Pixar on January 26, 2006 affected the production of Pixar movies?
  3. Do sequels have a higher gross than the first movie in a series?
  
### Disney Stock Prices (In Progress)
  1. How do Box office sales numbers on newly released videos affect the Disney Stock Price?
  2. How does the Critic Reception of a newly released movie affect the Disney Stock Price?
  3. How does viewer perceptions of a movie affect the Disney Stock Price?
  4. Which Movie Studio 

## Jupyter Notebook:

### Pixar Box Office Sales
This Jupyter Notebook contains the code used to scrape a IMDB Pixar major movie list page for movie data.

To create the dataset for the Pixar Viz just run the code. It will add all theatrical release movies that Pixar has created ending with Onward. There are two issues with the data displayed on the movie list page. First the date only includes the year, as there are some years with mulitple releases we will want to update this with the full date on the individual movie listing page. Second the gross sales only account for domestic sales. We want to look at worldwide numbers and must update that value individually as well.

Once the data is collected we can move it in to Tableau to visualize.

### Disney Stock Prices (In Progress)
This Jupyter Notebook contains the code used to Scrape a IMDB Disney Movie list page for the movie data.

First we need to refine the questions slightly to give us clear direction on how to obtain data that can be used to answer the questions. First what constitutes a newly released film? We will look at five days before the release to 2 weeks after so that we can account for critics embargo ending and their reviews being published before the release of the film As well as the user ratings to start coming in after they watched the film. Second how do we judge critic reception? We will use the metascore which is a weighted average of curated critics. Finally to quantify viewer perception we will use the IMDB user ratings.

To create the Disney movie data we will run the code from the notebook. It will show all Disney movies released from all Disney studios up to Onward. We have a similar problem as with the Pixar movie list as that the box office sales only shows domestic prices. Also the release date only shows year and we will need days.
