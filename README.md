# Relax Data Science Challenge

This is an analysis of user data to understand how many adopted users there are and what is indicative of user adoption. An "adopted user" is defined as a user who has logged into the product on 3 separate days in at least one 7-day period.

### Data

1. Users
2. User engagement

### Analysis

Out of the 12,000 users in the dataset, 1,445 (roughly 12%) were found to be adopted users. With the available data, the 3 most predictive features of user adoption were creation source (5 different methods in which the account was created), domain of the signup email (there were 6 common domains and over a thousand uncommon ones), and the organization the user is from. Whether the user opted into the mailing list or was enabled for the marketing drip was not important in predicting user adoption.

I considered a few other aspects such as the user's signup month and the user's first login from account creation but there seemed to be no inherent pattern. I thought if a user logged in within the same day, week, or even month, they might be more inclined to become an adopted user, but this was not the case. There was a similar adoption rate amongst these groups. I also tried the number of logins but the correlation was not ideal due to the different lengths of each user's account.

Additional features would be very helpful as there was not many features to work with here, especially with the usage data. Some ideas include the length of each use or some kind of metric to measure user satisfaction. The data is also lacking "actionable" features the company can act on in order to improve the user adoption rate. I feel data collection with more features would be able to improve predictions quite a bit.