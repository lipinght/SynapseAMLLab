# Synapse + AML Integration Labs
This is a series of hands-on labs for Synapse + AML integration


## Prerequisites
1.	[Create a Synapse workspace](https://docs.microsoft.com/en-us/azure/synapse-analytics/quickstart-create-workspace) 
2.	[Create a  Synapse Dedicated SQL Pool](https://docs.microsoft.com/en-us/azure/synapse-analytics/quickstart-create-sql-pool-studio) 
3.	[Create a Synapse Spark Pool](https://docs.microsoft.com/en-us/azure/synapse-analytics/quickstart-create-apache-spark-pool-studio) 
4.	[Create AML workspace](https://docs.microsoft.com/en-us/azure/machine-learning/quickstart-create-resources#create-the-workspace) 
5.	[Create Compute Instance within AML](https://docs.microsoft.com/en-us/azure/machine-learning/quickstart-create-resources#instance) 
6.	[Create a AML linked service in Synapse](https://docs.microsoft.com/en-us/azure/synapse-analytics/machine-learning/quickstart-integrate-azure-machine-learning) 



## Labs

| Lab | Description | 
|:------:|:-----:|
| [PREDICT in Dedicated SQL Pool](PredictSQL.md) | This is a lab to train an Onnx model and score the model using PREDICT in dedicated SQL Pool |
| [Orchestrate AML batch pipelines](Ochestration.md) | This is a lab to publish a AML Batch Inferencing Service and execute it within Synapse data integration pipeline |
| [Using Synapse Spark Pool in AML](SparkinAML.md) | This is a lab that covers two different ways to use Synapse Spark pool in Azure Machine Learning | 
| [PREDICT in Synapse Spark Pool](PredictSpark.md) | This is a lab that goes through how to see PREDICT in Synapse Spark Pool to score a MLFlow packaged model |