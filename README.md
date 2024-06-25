

#Parallelization of Age and Gender Prediction using Apache Spark and PyTorch

Objective: Optimize model training performance by efficiently processing 50,000 X-ray images to predict age and gender.

Environment: Utilized the university’s high-performance cluster, “Discovery”.

Tools and Technologies:

Apache Spark: Managed and processed the large dataset in a distributed manner.
PyTorch: Applied data parallel and distributed data parallel techniques for model training.
High-Performance Cluster (Discovery): Leveraged computational resources for efficient data processing.
Approach:

Data Management: Utilized Apache Spark's capabilities to handle big data efficiently. Spark's distributed processing framework allowed the data to be split across multiple nodes, enabling parallel processing.
Model Training: Implemented data parallel and distributed data parallel techniques in PyTorch. These techniques enabled the distribution of data and model computations across multiple GPUs, thus speeding up the training process.
Optimization: Focused on optimizing the data pipeline to ensure that the data loading and preprocessing were efficient, minimizing bottlenecks during model training.
Challenges:

Handling a large volume of data (50,000 X-ray images) required efficient data management strategies to avoid memory overflow and ensure smooth processing.
Ensuring synchronization across multiple nodes and GPUs to maintain consistency during distributed training.
Achievements:

Performance Improvement: By leveraging Apache Spark and parallel computing techniques, significantly reduced the time required for model training.
Accuracy: Achieved a high accuracy of 93.45% in predicting age and gender from X-ray images.
Efficiency: Ensured fast and efficient data processing, crucial for handling the large dataset within the available computational resources.
