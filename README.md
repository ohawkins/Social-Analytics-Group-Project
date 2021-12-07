# Social-Analytics-Group-Project

This project is completed at December 8th, 2021 by Social Analytics Project Group 3.
Members include Ben Facio, Olivia Hawkins, Chenxi Li, and Shen Lim.

Here are list of files we generated in each steps.

1) Data Sourcing
    - datasets_cleaned:     folder containing 23 trailers and 23 released movies' comment .csv files
    - movies_original.csv:  basic movie info
    - movies_new.csv:       basic movie info + trailer info
    - movies_0_trailer.csv: basic movie info + scraped trailer info
    - movies_1_release.csv: basic movie info + scraped released info

2) Collect Sentiment Score
    - Sentiment:            folder containing 46 files with sentiment score + 1 trailer file for prediction
    - CL_sentiment.Rmd:     r script with for-loop getting sentiment score
    - OH_work.Rmd:          r script with further sentiment analysis
    - movie_sent_mean.csv:  summary data based on sentiment dataset
    - movies_trailer.csv:   movie_1_release + summary data for trailer
    - movies_release.csv:   movie_0_trailer + summary data for released
    

3) Modeling
    - Final Presentation.pptx
    - mean_df.csv:                      summary data for prediction
    - movies_trailer_regression.xlsx:   regression model based on movies_trailer (including tuning process)
    - movies_release_regression.xlsx:   regression model based on movies_release (including tuning process)

