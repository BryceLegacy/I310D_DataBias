# I310D_DataBias

what you are testing

Today I am using the perspective API to test the toxicity of comments from a sample data set called "Sample_Labaled_data.csv". This dataset was prelabled and is anonomys it has unique IDs for each comment and a "yes" or "no" for each comment relating to its toxicity. My toxicity threshold will be anything .5 and above, so anything recieveing a toxicity threshold above .5 will be labeled as toxic. 

your hypotheses

I believe that the perspective API will be less accurate on Spanish content versus English content.

your results

I found that the perspective API did in fact score the Spanish text lower in every single instance that I tried. 

I have learned a little more about using APIs in this project. I would like to dive deeper when I have more time of how I can translate the data from the csv file and run it through the API and analyze the data in this way. I found it really interesting how the spanish text was less toxic every single time. I believe this is because there is a lesser amount of Spanish training data behind the Perspective algorithm than English. I also found that the use of curse words and certain phrases will increase toxicity score by much higher margins than just purely negative texts. I am intersted in looking deeper in how race and religon play into the toxcicity score factoring as well as gender. 
