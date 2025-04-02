# TMDB Movie Data Scraper  

A Python script to scrape movie data from The Movie Database (TMDB) and export it to Excel.  

## Features  
### Data Collected per Movie  
- **Movie Name**: Title of the movie.  
- **Ratings**: TMDB user rating.  
- **Genres**: Associated categories (e.g., Action, Comedy).  
- **Release Date**: Official release date.  
- **Runtime**: Duration in minutes.  
- **Director**: Name of the director.  
- **URL**: Direct link to the movie's TMDB page.  

### Functionality  
- **Multi-Page Scraping**: Collects data across multiple TMDB pages.  
- **HTML Parsing**: Uses BeautifulSoup to extract data from HTML content.  
- **Data Export**: Compiles data into a pandas DataFrame and saves as `MovieProject.xlsx`.  

## Technologies Used  
- **Python**: Scripting language.  
- **Requests**: Handles HTTP requests to TMDB.  
- **BeautifulSoup4**: Parses HTML for data extraction.  
- **Pandas**: Manages data and exports to Excel.  

