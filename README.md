# Neural Network Charity Analysis

OVERVIEW

The purpose of this challenge was to identify which charitable organizations would be good candidates for funding from Alphabet Soup.  Several characteristics - including use case for funding, income, active status, and type of organization - were taken into consideration.
After processing the charity data (in CSV format) and creating a model for evaluation, the model was optimized for a high accuracy rate.



RESULTS

1. For this model, the is_successful column was considered the target.
2. For this model, "status", "ask amount", "use case", and "organization" were considered variables, among other characteristics unique to each charity.
3. The name of each charitable organization, as well as the EIN (or unique ID code) were removed from consideration as they do not affect whether a charity is a good candidate for funding.
4. I selected 80 neurons in the first layer, and 20 in the second.

![image](https://user-images.githubusercontent.com/99574730/176327207-380b7d08-2f47-4f44-b304-596833431e91.png)

5. Were you able to achieve the target model performance?
Unfortunately I was not able to achieve the target model performance - my model had an accuracy rate of 73%, as shown below:

![image](https://user-images.githubusercontent.com/99574730/176326719-0c04d83e-a037-4ee2-a6e8-81e93cc93426.png)



SUMMARY

Overall, despite optimizing the model, we were not able to reach the target accuracy of 75% or higher.  A different type of model, such as a random forest classifier, may be able to generate a higher accuracy rate and truly select the most promising charities.
