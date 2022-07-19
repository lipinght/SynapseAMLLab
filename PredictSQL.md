# Use PREDICT in Synapse Dedicated SQL Pool

PREDICT in Synapse Dedicated SQL Pool can only work with ONNX models, the ONNX model can be either trained within AML or use the autoML integration in Synapse Spark Pool.

## Lab 1 Train an ONNX model using AML

Follow this [tutorial](https://docs.microsoft.com/en-us/azure/synapse-analytics/machine-learning/tutorial-sql-pool-model-scoring-wizard) 


## Lab 2 Train an ONNX model using AutoML integration in Synapse Spark Pool

1. For model training, follow this [tutorial](https://docs.microsoft.com/en-us/azure/synapse-analytics/machine-learning/tutorial-automl) for code free approach, or this [tutorial](https://docs.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-azure-machine-learning-tutorial) for code first approach.

2. For scoring, follow the [tutorial](https://docs.microsoft.com/en-us/azure/synapse-analytics/machine-learning/tutorial-sql-pool-model-scoring-wizard#launch-predictions-with-the-sql-scoring-wizard) when selecting the model to predict with, select the model created by the AutoML process. 