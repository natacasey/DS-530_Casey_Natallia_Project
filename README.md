![IMDb](https://github.com/natacasey/IMDb_Movie_Rating_Analysis_with_Python/blob/master/_assets/movies_pic.jpg)

## Project description
The focus of this project is the analysis of the movie ratings given by users of a movie database IMDb. 
Hypothesis tests were performed to discover the types of relationships between variables “gross”, “budget”, “votes”, “runtime” and the variable “score”. 
The relationship of votes and score, runtime and score were found to be close to moderately significant positive linear.
The relationships of gross and score, budget and score appeared to be very weak positive linear. Scatterplots and Least Squares Fit were used to support the analysis. 
Hypothesis of scores of horror movies being rated lower vs other genres of movies was tested with the help of CDFs, PMFs, and a chi-square test. 
The choice of models for analysis was linear regression models. 

## Development
OS - Windows 10 Home. 
To complete this project Python libraries thinkstats and thinkplot among others were used. The analysis is based on the information from the book  ["Think Stats"](https://github.com/AllenDowney/ThinkStats2) by Allen B Downey.

## Models 

![movies](https://github.com/natacasey/IMDb_Movie_Rating_Analysis/blob/master/_assets/models.PNG)


## Permutation test

![permutation](https://github.com/natacasey/IMDb_Movie_Rating_Analysis/blob/master/_assets/permutation_test.PNG)


## Project challenges

This analysis was problematic because of the changes in the sign of coefficients of the variables that have high VIF, and have correlation close to high. 
The issue of multicollenearity was identified.
The decision to interpret the results only of the models with the variables staying stable overall was made.

## Project Limitations

The project has some limitations. Even though it provides results for effects of variables budget, gross, runtime and votes, it doesn’t explain other factors that could be influencing the outcome “scores”. 
Considering performing the analysis of other variables from the data set can allow for the discovery of additional factors influencing the outcome variable “score”.
Missing values significantly reduced the amount of observations available thus reducing the possibility of accounting for all of the information for the variables.
Looking for the sources containing the information that was missing could potentially solve this issue. 

## Considerations for the future

Additional analysis of all of the assumptions that multiple linear regression model should meet for valid results can be considered to double check the validity of the model and its results. 
The time frame for this analysis of the movies ratings is 1986-2016. Some new information could be added to the data set to make the results more up-to-date. 
