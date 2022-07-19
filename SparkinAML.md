# Use Synapse Spark Pool in Azure Machine Learning

## Lab 1 SynapseSparkStep in an AML pipeline

1. Open **Jupyter** in the compute instance you created in the prerequisites, download [spark_job_on_synapse_spark_pool.ipynb](https://raw.githubusercontent.com/azure/machinelearningnotebooks/master/how-to-use-azureml/azure-synapse/spark_job_on_synapse_spark_pool.ipynb) upload the notebook

2. Download [Titanic.csv](https://raw.githubusercontent.com/azure/machinelearningnotebooks/master/how-to-use-azureml/azure-synapse/Titanic.csv) and upload it to the same directory as spark_job_on_synapse_spark_pool.ipynb, and run every cell in spark_job_on_synapse_spark_pool.ipynb

**Note:** The notebook will use SDK to link synapse workspace to AML and attach synapse spark pool as AML compute target, instead of using SDK, you could also do this directly within AML studio by following this [tutorial](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-link-synapse-ml-workspaces#link-workspaces-via-studio) for link workspace and this [tutorial](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-link-synapse-ml-workspaces#attach-a-pool-via-the-studio) for attach spark pool.

## Lab 2 Running interactive Spark Session on Synapse Spark Pool

1. Open **Jupyter** in the compute instance you created in the prerequisites, download [spark_session_on_synapse_spark_pool.ipynb](https://raw.githubusercontent.com/azure/machinelearningnotebooks/master/how-to-use-azureml/azure-synapse/spark_session_on_synapse_spark_pool.ipynb) upload the notebook, 

2. Upload the Titanic.csv that downloaded in Lab 1 above to adls2 that is created together with Synapse as part of the prerequisites, and run every cell in spark_session_on_synapse_spark_pool.ipynb

**Note:** Optionally you could set up a service principal to access toe adls, the service principal will need at least **storage blob data reader role**