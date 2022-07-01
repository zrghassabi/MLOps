# MLOps


https://algorithmia.com/mlops

With Machine Learning Model Operationalization Management (MLOps), we want to provide an end-to-end machine learning development process to design, build and manage reproducible, testable, and evolvable ML-powered software.


MLOps Infrastructure Stack:

https://ml-ops.org/content/state-of-mlops

Before any machine learning model can be put in production, many experimentation cycles are needed to identify the right ML model to achieve the business goal. This experimentation phase adds additional complexity in any ML project because it includes three main artifacts: Data, Model, and Code. To manage this complexity, we need well-defined structures, processes, and proper software tools that manage ML artifacts and cover the machine learning cycle.

The MLOps technology stack should include tooling for the following tasks:

          data engineering,

          version control of data, ML models and code,

          coninuous integration and continuous delivery pipelines,

          automating deployments and experiments,

          model performance assessment, and

          model monitioring in production.
          
Existing cloud providers already working on offering machine learning platforms such as AI Platform by Google Cloud, AzureML, and SageMaker by AWS. Initiated at Google, the Kubeflow project presents an option to manage a set of open-source tools for MLOps and assemble them on Kubernetes. The adoption of such ML platform depends on the cloud strategy of the organization. In case, when an in-house hosted solution for MLOps is preferred, non-cloud systems like MLFlow, Sacred, or DVC might be a tool of choice.



The Data Engineering pipeline includes a sequence of operations on the available data that leads to supplying training and testing datasets for the machine learning algorithms:

 -Data Ingestion - Collecting data by using various frameworks and formats, such as Spark, HDFS, CSV, etc. This step might also include synthetic data generation or data enrichment.

 -Exploration and Validation - Includes data profiling to obtain information about the content and structure of the data. The output of this step is a set of metadata, such as max, min, avg of values. Data validation operations are user-defined error detection functions, which scan the dataset in order to spot some errors.

 -Data Wrangling (Cleaning) - The process of re-formatting particular attributes and correcting errors in data, such as missing values imputation.

 -Data Labeling - The operation of the Data Engineering pipeline, where each data point is assigned to a specific category.

 -Data Splitting - Splitting the data into training, validation, and test datasets to be used during the core machine learning stages to produce the ML model.




