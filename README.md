# Distributed Training & HPC 
### Horovod 
1) Reference architectures for distributed training of deep learning models (on GPU) - this is an architecture for data-parallel distributed training with synchronous updates using [**Horovod**](https://github.com/horovod/horovod).<br> 
https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/ai/training-deep-learning  
https://github.com/microsoft/DistributedDeepLearning/

![alt text](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/ai/_images/distributed_dl_flow.png)

![alt text](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/ai/_images/distributed_dl_architecture.png)

2) Intro material for [**Horovod**](https://github.com/horovod/horovod):<br>
Main paper: [paper1](https://arxiv.org/pdf/1802.05799.pdf)<br>
Videos: [Video1](https://www.youtube.com/watch?v=SphfeTl70MI), [Video2](https://www.youtube.com/watch?v=4y0TDK3KoCA)<br>

3) A [notebook example](https://notebooks.azure.com/azureml/projects/azureml-getting-started/html/how-to-use-azureml/training-with-deep-learning/distributed-tensorflow-with-horovod/distributed-tensorflow-with-horovod.ipynb) of training a word2vec model in TensorFlow using distributed training via Horovod & AMLS.<br>

5) Databricks notebook [examples](https://databricks.com/tensorflow/getting-started-with-tensorflow-on-databricks#resources) for distributed training of NNs using Keras and Horovod (HorovodRunner): [Notebook1](https://docs.databricks.com/applications/deep-learning/distributed-training/mnist-tensorflow-keras.html), [Notebook2](https://pages.databricks.com/rs/094-YMS-629/images/keras-hvdrunner-mlflow-mnist-sample.html?_ga=2.69518672.1122370517.1566311733-1893883089.1566311733) <br>

6) [Distributed Tensorflow](https://www.tensorflow.org/guide/distribute_strategy) can be used to define the method for distributing the NN training jobs. <br>

7) Azure VMs with support of RDMA & InfiniBand:<br>
https://docs.microsoft.com/en-us/azure/batch/batch-pool-compute-intensive-sizes#main

8) HB and HC VM series: [link](https://azure.microsoft.com/en-au/blog/introducing-the-new-hb-and-hc-azure-vm-sizes-for-hpc/)

9) Azure batch [intro](https://docs.microsoft.com/en-us/azure/batch/batch-technical-overview). <br>
![alt text](https://docs.microsoft.com/en-us/azure/batch/media/batch-technical-overview/tech_overview_03.png)

9) How to use AML pipeline [steps](https://github.com/MicrosoftDocs/azure-docs/blob/master/articles/machine-learning/service/how-to-create-your-first-pipeline.md)<br>
![alt text](https://github.com/MicrosoftDocs/azure-docs/raw/master/articles/machine-learning/service/media/how-to-create-your-first-pipeline/run_an_experiment_as_a_pipeline.png)


10) Model interpretibility: [link](https://docs.microsoft.com/en-us/azure/machine-learning/service/machine-learning-interpretability-explainability)

11)

8) Azure HPC environment [repo](https://github.com/Azure/azurehpc) + CycleCloud [tutorials](https://github.com/CycleCloud/cyclecloud_tutorials) & azure batch [examples](https://github.com/tojozefi/azurebatch/blob/master/customcode/README2.md) 

9) BatchAI to AMLS migration [example](https://docs.microsoft.com/en-us/previous-versions/azure/batch-ai/how-to-migrate)

### Spark 
1) Native Apache [Spark MLlib](https://spark.apache.org/mllib/) for distributed ML<br>
2) Databrick example [notebooks](https://databricks.com/resources/type/example-notebook)<br>
3) [mmlspark](https://mmlspark.blob.core.windows.net/website/index.html): example [notebooks](https://github.com/Azure/mmlspark/tree/master/notebooks/samples) & [video](https://databricks.com/session/semi-supervised-object-detection-using-the-azure-cognitive-services-on-spark)

