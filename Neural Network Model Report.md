Neural Network Model Report
Step 4: Write a Report on the Neural Network Model

For this part of the assignment, you’ll write a report on the performance of the deep learning model you created for Alphabet Soup.

The report should contain the following:

    Q.Overview of the analysis: Explain the purpose of this analysis.
    A. Using your knowledge of TensorFlow, you’ll design a neural network, or deep learning model, to create a binary classification model that can predict if an Alphabet Soup-funded organization will be successful based on the features in the dataset. You’ll need to think about how many inputs there are before determining the number of neurons and layers in your model. Once you’ve completed that step, you’ll compile, train, and evaluate your binary classification model to calculate the model’s loss and accurac

    Results:  address the following questions:

    Data Preprocessing
        Q.What variable(s) are the target(s) for your model?
        A.The target variable is the 'IS_SUCCESSFUL' column from the categorical_num_df

        Q.What variable(s) are the features for your model?
        A.The feature variables are every other column from application_df. This was accomplished by dropping the 'IS_SUCCESSFUL' column from the original dataframe

        Q.What variable(s) should be removed from the input data because they are neither targets nor features?
        A.'EIN' and 'NAME' columns were dropped/removed.

    Compiling, Training, and Evaluating the Model
        Q.How many neurons, layers, and activation functions did you select for your neural network model, and why?
        A.My first attempt I used 80 hidden nodes in layer 1, 30 hidden in 2 and 1 hidden in layer 3. Just trying to get a base line to make adjustments later in the project.

        Q.Were you able to achieve the target model performance?
        A.I was unable to achieve 75% moddel accuracy.


        Q.What steps did you take in your attempts to increase model performance?
        A.I added more layers, added additional hidden nodes, and switched up the activation functions associated with each layer in an attempt to achieve higher model accuracy.

    Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.


     In summary overall, the deep learning model was around 72% accurate in predicting the classification problem. Using the model with closer correlation between input and output should result in higher prediction accuracy. It would give you the capabilites to get more accurate information and better train the model to get even above 75% accurate.
