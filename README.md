# Sentiment Analysis Project

This is a project designed to execute a recurrent neural network for the purpose of determining the sentiment of a movie review using the IMDB data set.
The model was created using Amazon's SageMaker service, and included is a web app for the use of interacting with the deployed model.

In the final architecture AWS API Gateway and AWS Lambda functions is used as well. The application architecture diagram is:

![image](https://user-images.githubusercontent.com/77180350/113464014-50fa9b80-93ef-11eb-8bd5-7e228d4acfd1.png)

You can find the original code without solutions in the original [Udacity SageMaker Deployment repository](https://github.com/udacity/sagemaker-deployment).

# Setup instructions

Please see the original README in the root directory for instructions on setting up a SageMaker notebook and downloading the project files (as well as the other notebooks).
For the solutions only clone this repository:

- cd SageMaker
- git clone https://github.com/hjlopes/sagemaker-sentiment-analysis
- exit

# Web app final result

The final project will be executed in a simple html page which can be deployed anywhere.

You will see the following:

https://github.com/tech-trent/sentiment-analysis-project/blob/main/webapp.gif
