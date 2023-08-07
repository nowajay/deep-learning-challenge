# deep-learning-challenge

# Analysis Overview

The purpose of this analysis was to find out if applicants will be more successful if funded by Alphabet Soup.

# Results 

* Data Prprocessing 
    * The target for the model is "IS_SUCCESSFUL"
    * The variables featured are "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", "ASK_AMT", and "IS_SUCCESSFUL". "NAMES" was later added back in as an experiment to get the accuracy higher. 
    * "EIN" should be removed from the data as well as "NAMES" unless needed/

* Compiling, Training, and Evaluating the Model 
    * I used 'relu' and 'sigmoid' as well as two hidden layers in the end. I changed around the nodes a lot to try to get different results on the accuracy but most commonly used 80 and 30. I tried adding multiple layers as well but in the end I just ended up sticking with two.
    * I was not able to achieve the target model. the closest I got was 74% accuracy and that was with two hidden layers in the end and "NAMES" being used in the data. 
    * I added "NAMES" back into the data and aslo tried bring in more hidden layers while switching around the nodes. 

# Summary 

By keeping the hidden layers at two and increasing the nodes I was able to get a slight increase from 72% to 74% while "NAMES" were added back in the data but ultimatley failed to get the accuracy to 75%. 
