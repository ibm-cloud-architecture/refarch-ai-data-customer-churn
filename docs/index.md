# Customer Churn - An example of Reference Implementation of Data & AI

The goals of this implementation is to illustrate how to build an intelligent application using:

* Data Ingestion and Organization
* Model Development and Deployment
* Batch Scoring
* Model MOnitoring
* Cognitive service like Tone Analyzer and Chatbot
* Integrate with Customer Data base and unstructured data to build a customer churn predictive scoring model
* Deploy and monitor the model

Modern applications are leveraging a set of capabilities to do a better assessment of customer characteristics and deliver the best actions or recommendations. The technologies involved, include artificial intelligence, data governance, ingestion, enrichment, storage, analysis, machine learning, unstructured data classifications, natural language understanding, tone analysis, and hybrid integration....

Update 09/17/19

## Target audiences

* IT Architects who want to understand the components involved and the architecture constraints and design considerations
* Developers who want to get starting code, and educate themselves on the related technologies
* Data Scientists who want to complement machine learning with cognitive output like classification  

## Key points

* Data scientists need different source of data, structured from traditional SQL based database (e.g. the customers and accounts data) and unstructured output of new cognitive services.
* Data Scientists work hand by hand with application developers to quickly deliver solution to the business.
* Data access layer to traditional relational data should be done with a micro service approach exposing RESTful API or using modern z OS Connect application.
* Cloud native apps, microservices, can be deployed in public or private cloud, like IBM Cloud private or IKS based on Kubernetes and containers.
* Public services like the Watson services can be easily integrated within the solution: Watson Data Platform, Tone Analyzer, Watson Assistant.
* API management is used to present a unique API for customer data, standardize for consumers like the webapp, even if the back end is Java based or z Connected based.
* Product recommendations may be added to the solution to support business decision from a chatbot conversation taking into account the churn scoring risk. See this note to explain how to leverage IBM Operational Decision Management for that.
