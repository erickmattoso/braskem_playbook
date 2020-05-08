# Goals

### Determine the optimal data features for the machine-learning model.
### Create an informative machine-learning model that predicts the target most accurately.
### Create a machine-learning model that's suitable for production.

## Feature engineering

Feature engineering involves the inclusion, aggregation, and transformation of raw variables to create the features used in the analysis. If you want insight into what is driving a model, then you need to understand how the features relate to each other and how the machine-learning algorithms are to use those features.

This step requires a creative combination of domain expertise and the insights obtained from the data exploration step. Feature engineering is a balancing act of finding and including informative variables, but at the same time trying to avoid too many unrelated variables. Informative variables improve your result; unrelated variables introduce unnecessary noise into the model. You also need to generate these features for any new data obtained during scoring. As a result, the generation of these features can only depend on data that's available at the time of scoring.

For technical guidance on feature engineering when make use of various Azure data technologies, see Feature engineering in the data science process.

## Model training

Depending on the type of question that you're trying to answer, there are many modeling algorithms available. For guidance on choosing the algorithms, see How to choose algorithms for Microsoft Azure Machine Learning. Although this article uses Azure Machine Learning, the guidance it provides is useful for any machine-learning projects.

The process for model training includes the following steps:

Split the input data randomly for modeling into a training data set and a test data set.
Build the models by using the training data set.
Evaluate the training and the test data set. Use a series of competing machine-learning algorithms along with the various associated tuning parameters (known as a parameter sweep) that are geared toward answering the question of interest with the current data.
Determine the “best” solution to answer the question by comparing the success metrics between alternative methods.

_Note_

_Avoid leakage: You can cause data leakage if you include data from outside the training data set that allows a model or machine-learning algorithm to make unrealistically good predictions. Leakage is a common reason why data scientists get nervous when they get predictive results that seem too good to be true. These dependencies can be hard to detect. To avoid leakage often requires iterating between building an analysis data set, creating a model, and evaluating the accuracy of the results._

We provide an automated modeling and reporting tool with TDSP that's able to run through multiple algorithms and parameter sweeps to produce a baseline model. It also produces a baseline modeling report that summarizes the performance of each model and parameter combination including variable importance. This process is also iterative as it can drive further feature engineering.