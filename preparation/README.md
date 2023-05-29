# Preparing to pretrain vision and language foundation models on AWS

### 1. Dataset analysis
- Working with [pandas](https://www.learndatasci.com/tutorials/python-pandas-tutorial-complete-introduction-for-beginners/)
- Working with Hugging Face [transformers](https://github.com/nlp-with-transformers/notebooks/blob/main/01_introduction.ipynb)
- Dataset augmentation suggestions from [DataCamp](https://www.datacamp.com/tutorial/complete-guide-data-augmentation)
### 2. Model analysis
- This relates to Chapter 3 in the book, which has a rich set of links and papers referenced. I'll update this with some [scaling law](https://arxiv.org/abs/2203.15556) examples soon.

### 3. Prepping your containers and accelerators
- This refers to Chapter 4 in the book, which also has some great references.
- Here's a [link](https://github.com/aws/deep-learning-containers) to the AWS Deep Learning Containers. Pro tip - all the frameworks and packages work really well here right off the bat! 
- Some documentation for using [Docker containers with SageMaker](https://docs.aws.amazon.com/sagemaker/latest/dg/docker-containers.html)
- Here are a few [notebook examples](https://github.com/aws/amazon-sagemaker-examples/tree/main/advanced_functionality/custom-training-containers) for building your own Training containers on SageMaker

### 4. Distribution fundamentals
