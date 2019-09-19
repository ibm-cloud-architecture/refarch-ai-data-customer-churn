# Model Deployed in MMD further deployed as Python Function in WML

This is to showcase the situation where Model deployed in any arbitrary environment (say Amazon Sage Maker, Azure Ml, Custom Environment, IBM WML in Cloud, etc.) needs to be further deployed in WML in Cloud Pak for Data. This is needed for Watson Open Scale being able to monitor models deployed in any arbitrary deployment environment for AI models. Here we are using MMD as example of that arbitrary Model deployment environment.

Navigate to the ‘Notebooks’ tab of your project and open ‘Deploy MMD Model as Python Function in WML’ notebook using Jupyter with latest/highest version of Spark environment. You can select the environment by clicking the 3 vertical dots at the right of the name of the Notebook. 

Follow the notebook instructions and execute all cells as directed.

Please note following -

1. While saving and deploying the Python Function use a name with a prefix of your name/user-id. This is just to ensure that you are not saving the same with a name same as others used.

2. Whereever, user credentials are needed please use your user if and password

3. Wherever, urls are needed use the Cloud Pak for Data URL (ip/host name and port) provided to you.

4. While creating the Python Function use the scoring URL and access token you got when you deployed the MMD model in one of the previous steps.
