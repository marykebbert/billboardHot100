# Billboard Hot 100
This repository contains the code for my blog post, "Exploring the Billboard Hot 100 | Taylor Swift".  
  
The general structure is as follows:
- jupyter_notebooks: Contains all my python code for webscraping, using the Spotify API, data cleaning, and data visualization
    - billboard_hot_100: Code to scrape needed data from the Billboard Hot 100 site (warning: this took around two hours for my computer to run)
    - spotify_songs: Code to scrape needed data from the Spotify API (this only took a minute to run on my computer)
    - data_wrangling: Code to clean and format the data, including joining the spotify and billboard hot 100 data
    - exploratory_data_analysis: Code to create basic graphs exploring this data
- data: Contains all data needed to run the code without running billboard_hot_100.ipynb or spotify_songs.ipynb
    - all_songs.csv: data collected when the spotify_songs.ipynb is run
    - long_df_swift.txt: data collected when billboard_hot_100.ipynb is run
    - date_indexed_songs.csv: cleaned data saved after running data_wrangling.ipynb
- graphics_html: HTML code for the graphics produced in exploratory_data_analysis.ipynb
