The team at [FiveThirtyEight](https://fivethirtyeight.com/) 
became interested in answering some questions about Star Wars fans. 
In particular, they wondered: does the rest of America realize that 
“The Empire Strikes Back” is clearly the best of the bunch?

The team needed to collect data addressing this question. 
To do this, they surveyed Star Wars fans using the online 
tool SurveyMonkey. They received 835 total responses, 
which you download from 
[their GitHub repository]
(https://github.com/fivethirtyeight/data/blob/master/star-wars-survey/README.md).

The data has several columns, including:

- `RespondentID` - An anonymized ID for the respondent (person taking the survey)
- `Gender` - The respondent's gender
- `Age` - The respondent's age
- `Household Income` - The respondent's income
- `Education` - The respondent's education level
- `Location (Census Region)` - The respondent's location
- `Have you seen any of the 6 films in the Star Wars franchise?` - Has a `Yes` or `No` response
- `Do you consider yourself to be a fan of the Star Wars film franchise?` - Has a `Yes` or `No` response

The purpose of this project is to clear the data presented in 
order to answer the following questions:

Question 1. Among the Star Wars and Star Trek franchise, which has more balance between fans gender?
Question 2. Rank favorite episodes according to the opinion of users.
Question 3.
	a) Which character do respondents like the most?
    b) Which character do respondents dislike the most?
    c) Which character is the most controversial (split between likes and dislikes)?
Question 4. Which region has the most fans who prefer Episode 1 over the rest?