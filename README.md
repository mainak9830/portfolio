# Software Engineer | ML Systems Enthusiast 

#### Languages: C++, Python, Java, Go, C, HTML, CSS, JavaScript, TypeScript, GNU Octave
#### Frameworks/Runtime Environment: Flask, ReactJs, ExpressJs, NodeJs, Redux, Tensorflow, Keras, Pytorch
#### Databases/Others:  MySQL, PostgreSQL, MongoDB, GCP, AWS, Docker, Linux

## Education							       		
- M.S., Computer Science	| Stony Brook University (_May 2024_)	 			        		
- B.Tech, Computer Science | Institute of Engineering and Management (_August 2022_)

## Work Experience
**Research Intern @ Performance Analysis of Computer Systems Lab (_January 2024 - Present_)**
- Conducted detailed CPU and GPU metrics profiling at millisecond interval using pynvml in training and inference workloads using power monitors. Set up and built an automated distributed-inference energy profiling system using DeepSpeed in a 2 GPU workload for configuration like tensor-parallelism.
- Worked on estimating the energy of a ML model by parsing the PyTorch JIT computational graph, breaking it down to ML and non-ML level primitives and leveraging features like Flops, mem-bytes, and power consumption of a primitive.
- Technologies: Python, PyTorch, DeepSpeed, pynvml, LLM

**Research Intern @ Roblox | Performance Analysis of Computer Systems Lab(_January 2023 - September 2023_)**
- Preprocessed 40 Million records of distributed tracing data of microservices RPC execution, CPU-Memory-Network-I/O log files and call graphs collected by Prometheus, stress-ng tool and Jaeger in a 17 node Kubernetes cluster.
- Implemented multi-feature custom join operations to combine VM level and microservice level I/O and network data. Developed end-to-end ML pipeline for anomaly detection and multi-localization.
- Implemented GAMMA, an attention based graph convolution network and achieved a 4 times enhancement in anomaly detection and 46% improvement in bottleneck-localization in microservices compared to current state of the art models.
- Technologies: Python, PyTorch, Distributed Tracing, Graph Neural Network, MLOps


**Software Intern @ Nottingham Trent University (_June 2021 - Huly 2022_)**
- Developed an android application (iConDet2.0) for conjunctivitis detection powered by a machine learning model and improved on the prior research work iConDet by optimizing the accuracy from 84% to 95%.
- Built a custom free-hand and rectangular image annotator feature which acts as an image segmentation system.
- Encapsulated the end-to-end pipeline which includes image capturing, pre-processing, and ML model prediction.
- Technologies: Android, Java, Python, PyTorch, Deep Learning

## Projects
### FairGPT: Examine the Intersectional Bias in GPT-3.5 | Python, PySpark, PyTorch
[GitHub Link](https://github.com/mainak9830/FairGPT)

- Generated 80,000 stories utilizing the extracted names on GCP VM instances using openAI API and conducted chi-square and t-tests to test for Gender Bias, Racial Bias and Intersectional Bias.
- Trained a bidirectional LSTM model to predict gender from US names, achieving a 93.7% testing accuracy.
- Preprocessed 22 GB of Wikipedia data on GCP Dataproc cluster and employed a pre-trained BERT model for Named Entity Recognition (NER) to extract names from text articles.

### BusTubDB | C++, Database
[GitHub Link](https://github.com/mainak9830/bustub-20221128-2022fall-Database)

- Built thread-safe Page-Table, Buffer Pool Manager and added B+ Tree Index, concurrent-index operator support.
- Developed query-execution for concurrent transactions utilizing 2-phase Locking and graph-based deadlock detection.

### Fault Tolerant Key-Value Store | C++, Distributed Systems

- Developed a sharded and replicated fault-tolerance key-value store based on raft protocol.
-  Improved fault-tolerance and efficiency by implementing log persistence and snapshotting. Implemented cross-shard transactions with optimistic concurrency control (OCC).

### TFS: Unix File System | C++, Operating Systems
[GitHub Link](https://github.com/mainak9830/Operating-Systems-Project/tree/main/lab3)

- Implemented a Unix-like file system providing interfaces for creating, deleting, reading, writing, and listing files using
block partition and inode structure.

### Life Expectancy Analysis Dashboard | HTML, CSS, JavaScript, D3.js, Python, Flask
- Developed a dashboard supporting interactive Geo maps, histograms, scatter plots, and stacked area charts for data exploration and analysis. Added interactions like filtering, brushing, linking and hovering to further analyze the data.

### Sociopedia | React.js, Node.js, Express.js, Bcryptjs, Axios, Jsonwebtoken, Materialize, Heroku
[GitHub Link](https://github.com/mainak9830/Sociopedia-Project)
- Built and deployed a web application in which users can post images, like other users’ posts, comment on their posts, follow other users, view other users’ profiles, delete posts.

### Student Resource Management | Java, Java Swing
[GitHub Link](https://github.com/mainak9830/Xsociety)
- Developed a java GUI application for economically and swiftly sharing books, notes and equipments amongst students.
- Collaborated with other team members to determine the best design specifications and details. Followed MVC design pattern and Iterative Waterfall model for the project.


## Publications
1. GAMMA: Graph Neural Network-Based Multi-Bottleneck Localization for Microservices Applications. ACM Web Conference 2024.
2. iConDet2: An Improved Conjunctivitis Detection Portable Healthcare App Powered by Artificial Intelligence. Applied Intelligence and Informatics. AII 2022.


