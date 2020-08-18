# Ad Success Predictor

<img src='https://media.sproutsocial.com/uploads/2018/05/Facebook-Ad-Examples.png' width='400'>

<h2>Introduction</h2>
<p>Advertisements are a huge part of everyone's lives. We see them on TV's, on billboards, hear them over the radio, and even see them in video games. Each advertisements contains several features from the text description to the location and people the advertisement is place in front of. In this project, I try to analyze these features and use feature engineering/data science to train machine learning models to predict whether or not a viewer would click on the ad or not. I took into account factors such as the length of the description, the age of the viewer, the time spent on the internet, the time spent on the website, and more to try to train the machine learning models to be as accurate as possible.</p>

<h3>Machine Learning</h3>
<p>Through the feature engineering and data science, I created new features based on the original features that correlated with the binary label, whether they clicked on the ad or not. After completing the feature selection and engineering, I used pipelines to transform the data and create new csv called 'feature_engineered_cols.csv' containing this data. The machine learning models I trained include Support Vector Machines, Logistic Regression, Random Forest Classifier, and more.</p>
<p>The best model was the Logistic Regression with 96.5% accuracy, 93.7% precision, 98.89% recall, and 0.961 f1 score.</p>

<h3>Data Visualization</h3>
<p>In the data visualization file, I create and analyze various features huing them by whether the ad is clicked on or not. Using scatterplots, violinplots, countplots, and more, I analyzed both the numerical and categorical features against the label to find interesting insights.</p>
