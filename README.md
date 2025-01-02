# T81 558:Applications of Deep Neural Networks

[Washington University in St. Louis](http://www.wustl.edu)

Instructor: [Jeff Heaton](https://sites.wustl.edu/jeffheaton/)

- Section 1. Spring 2025, Wednesday, 2:30 PM, Location: Mallinckrodt / 305

# Course Description

Deep learning is a group of exciting new technologies for neural networks. Through a combination of advanced training techniques and neural network architectural components, it is now possible to create neural networks that can handle tabular data, images, text, and audio as both input and output. Deep learning allows a neural network to learn hierarchies of information in a way that is like the function of the human brain. This course will introduce the student to classic neural network structures, Convolution Neural Networks (CNN), Long Short-Term Memory (LSTM), Gated Recurrent Neural Networks (GRU), General Adversarial Networks (GAN) and reinforcement learning. Application of these architectures to computer vision, time series, security, natural language processing (NLP), and data generation will be covered. High Performance Computing (HPC) aspects will demonstrate how deep learning can be leveraged both on graphical processing units (GPUs), as well as grids. Focus is primarily upon the application of deep learning to problems, with some introduction to mathematical foundations. Students will use the Python programming language to implement deep learning using PyTorch. It is not necessary to know Python prior to this course; however, familiarity of at least one programming language is assumed. This course will be delivered in a hybrid format that includes both classroom and online instruction.

# Objectives

1. Explain how neural networks (deep and otherwise) compare to other machine learning models.
2. Determine when a deep neural network would be a good choice for a particular problem.
3. Demonstrate your understanding of the material through a final project uploaded to GitHub.

# Syllabus

This syllabus presents the expected class schedule, due dates, and reading assignments. [Download current syllabus](https://s3.amazonaws.com/data.heatonresearch.com/wustl/syllabus/jheaton-t81-558-spring-2025-syllabus.pdf)

| Module                                                                      | Content                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| --------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Module 1](t81_558_class_01_1_overview.ipynb)<br>**Meet on 01/15/2025**     | **Module 1: Python Preliminaries**<ul><li>1.1: Course Overview<li>1.2: Introduction to Python<li>1.3: Python Lists, Dictionaries, Sets & JSON<li>1.4: File Handling<li>1.5: Functions, Lambdas, and Map/ReducePython Preliminaries<li>**We will meet on campus this week! (first meeting)**</ul>                                                                                                                                               |
| [Module 2](t81_558_class_02_1_python_pandas.ipynb)<br>Week of 01/22/2025    | **Module 2: Python for Machine Learning**<ul><li> 2.1: Introduction to Pandas for Deep Learning<li>2.2: Encoding Categorical Values in Pandas<li>2.3: Grouping, Sorting, and Shuffling<li>2.4: Using Apply and Map in Pandas<li>2.5: Feature Engineering in Padas<li>[Module 1 Program](./assignments/assignment_yourname_t81_558_class1.ipynb) due: 01/23/2025<li> Icebreaker due: 01/23/2025</ul>                                            |
| [Module 3](t81_558_class_03_1_neural_net.ipynb)<br>Week of 01/29/2025       | **Module 3: PyTorch for Neural Networks**<ul><li>3.1: Deep Learning and Neural Network Introduction<li>3.2: Introduction to PyTorch<li>3.3: Encoding a Feature Vector for PyTorch Deep Learning<li>3.4: Early Stopping and Network Persistence<li>3.5: Sequences vs Classes in PyTorch<li>[Module 2: Program](./assignments/assignment_yourname_t81_558_class2.ipynb) due: 01/30/2025</ul>                                                     |
| [Module 4](t81_558_class_04_1_kfold.ipynb)<br>Week of 2/5/2025              | **Module 4: Training for Tabular Data**<ul><li>4.1: Using K-Fold Cross-validation with PyTorch<li>4.2: Training Schedules for PyTorch<li>4.3: Dropout Regularization<li>4.4: Batch Normalization<li>4.5: RAPIDS for Tabular Data<li>[Module 3 Program](./assignments/assignment_yourname_t81_558_class3.ipynb) due: 02/6/2025</ul>                                                                                                             |
| [Module 5](t81_558_class_05_1_python_images.ipynb)<br>**Meet on 2/12/2025** | **Module 5: CNN and Computer Vision**<ul><li>5.1 Image Processing in Python<li>5.2 Using Convolutional Neural Networks<li>5.3 Using Pretrained Neural Networks<li>5.4 Looking at Generators and Image Augmentation<li>5.5 Recognizing Multiple Images with YOLO<li>[Module 4 Program](./assignments/assignment_yourname_t81_558_class4.ipynb) due: 02/13/2025<li>**We will meet on campus this week! (second meeting)**</ul>                   |
| [Module 6](t81_558_class_06_1_transformers.ipynb)<br>Week of 2/19/2025      | **Module 6: ChatGPT and Large Language Models**<ul><li>6.1: Introduction to Transformers<li>6.2: Accessing the ChatGPT API<li>6.3: LLM Memory<li>6.4: Introduction to Embeddings<li>6.5: Prompt Engineering<li>[Module 5 Program](./assignments/assignment_yourname_t81_558_class5.ipynb) due: 2/20/2025</ul>                                                                                                                                  |
| [Module 7](t81_558_class_07_1_img_generative.ipynb)<br>Week of 2/26/2025    | **Module 7: Image Generative Models**<ul><li>7.1: Introduction to Generative AI<li>7.2: Generating Faces with StyleGAN3<li>7.3: GANS to Enhance Old Photographs Deoldify<li>7.4: Text to Images with StableDiffusion<li>7.5: Finetuning with Dreambooth<li>[Module 6 Program](./assignments/assignment_yourname_t81_558_class6.ipynb) due: 2/27/2025</ul>                                                                                      |
| [Module 8](t81_558_class_08_1_kaggle_intro.ipynb)<br>**Meet on 3/5/2025**   | **Module 8: Kaggle**<ul><li>8.1 Introduction to Kaggle<li>8.2 Building Ensembles with Scikit-Learn and PyTorch<li>8.3 How Should you Architect Your PyTorch Neural Network: Hyperparameters<li>8.4 Bayesian Hyperparameter Optimization for PyTorch<li>8.5 Current Semester's Kaggle<li>[Module 7 Program](./assignments/assignment_yourname_t81_558_class7.ipynb) due: 3/6/2025<li>**We will meet on campus this week! (third meeting)**</ul> |
| [Module 9](t81_558_class_09_1_faces.ipynb)<br>Week of 3/19/2025             | **Module 9: Facial Recognition**<ul><li>9.1 Detecting Faces in an Image<li>9.2 Detecting Facial Features<li>9.3 Image Augmentation<li>9.4 Application: Emotion Detection<li>9.5 Application: Blink Efficiency<li>[Module 8 Assignment](./assignments/assignment_yourname_t81_558_class8.ipynb) due: 3/20/2025</ul>                                                                                                                             |
| [Module 10](t81_558_class_10_1_timeseries.ipynb)<br>Week of 3/26/2025       | **Module 10: Time Series in PyTorch**<ul><li>Time Series Data Encoding for Deep Learning, PyTorch<li>Seasonality and Trend<li>LSTM-Based Time Series with PyTorch<li>CNN-Based Time Series with PyTorch<li>Predicting with Meta Prophet<li>[Module 9 Program](./assignments/assignment_yourname_t81_558_class9.ipynb) due: 3/27/2025</ul>                                                                                                      |
| [Module 11](t81_558_class_11_1_hf.ipynb)<br>Week of 4/2/2025                | **Module 11: Natural Language Processing**<ul><li>11.1 Introduction to Natural Language Processing<li>11.2 Hugging Face Introduction<li>11.3 Hugging Face Tokenizers<li>11.4 Hugging Face Data Sets<li>11.5 Training a Model in Hugging Face<li>[Module 10 Program](./assignments/assignment_yourname_t81_558_class10.ipynb) due: 4/3/2025</ul>                                                                                                |
| [Module 12](t81_558_class_12_1_ai_gym.ipynb)<br>Week of 4/9/2025            | **Module 12: Reinforcement Learning**<ul><li>Introduction to Gymnasium<li>Introduction to Q-Learning<li>Stable Baselines Q-Learning<li>Atari Games with Stable Baselines Neural Networks<li>Future of Reinforcement Learning</ul>                                                                                                                                                                                                              |
| [Module 13](t81_558_class_13_1_auto_encode.ipynb)<br>Week of 4/16/2025      | **Module 13: Deployment and Monitoring**<ul><li>13.1: Using Denoising AutoEncoders <li>13.2: Anomaly Detection<li>13.3: Model Drift and Retraining<li>13.4: Tensor Processing Units (TPUs)<li>13.5: Future Directions in Artificial Intelligence<li>Kaggle Assignment due: 4/17/2025 (approx 4-6PM, due to Kaggle GMT timezone)</ul>                                                                                                           |
| Week 14<br>**Meet on 4/23/2025**                                            | **Week 14: Kaggle Presentations**<ul><li>Top Kaggle teams will present<li>**We will meet on campus this week! (fourth meeting)**<li>Final project due: 4/24/2025</ul>                                                                                                                                                                                                                                                                          |

# Datasets

- [Datasets can be downloaded here](https://data.heatonresearch.com/data/t81-558/index.html)
