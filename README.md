# 354FinalProject

Original Source: https://github.com/MHDBST/PerSenT
Link to our code: https://github.com/Arafat04H09/354FinalProject

From the original source link provided above, we used the Train.CSV file for the input for our models. It was an extremely extensive file without thousands upon thousands of inputs.

The implementation for the models was done with online resources such as the HuggingFace website. We made API requests with an API key for each of the three different models. Implementation may not be 100% correct. Due to rate limiting and limited time, we decided against using the entire Train.csv file, rather only using an extremely small subset of it. 

If this file is opened on Google Colab, there is no need to worry about system requirements. 

Running the code is a simple endeavor. Download the notebook. Upload it to either Google Colab or VSCode, although Google Colab is much easier to use.
From there, you may notice that the first few boxes deal with importing libraries and determining the number of rows of the Train CSV you would like to use.
We set the default to be 25, but if need be, this amount can be changed to a much larger number depending on the range of which the user wants the models to run on. 
From there we simply run the cells until we get to the Cell that needs an API key. This API key is acquired from the Hugging Face website. Make an account,
navigate to settings, find the "Access Tokens" tab and click "create token." Chose the "write" option and then paste the token into the designated area. From there,
the code should run without a cinch. The evaluation metrics that we set up may not be entirely correct, for the purposes of our report, we calculated a lot of the 
metrics ourself because we were not getting the proper numbers. The last section is the hypothesis testing section where we tested whether or not our models worked 
as we thought they did. If need be, the text section of these hypothesis can easily be changed to allow for the user to test their own hypothesis and see how the 
sentiment either changes or stays the same. 
