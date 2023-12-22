
### [Packt Conference : Put Generative AI to work on Oct 11-13 (Virtual)](https://packt.link/JGIEY)

<b><p align='center'>[![Packt Conference](https://hub.packtpub.com/wp-content/uploads/2023/08/put-generative-ai-to-work-packt.png)](https://packt.link/JGIEY)</p></b> 
3 Days, 20+ AI Experts, 25+ Workshops and Power Talks 

Code: <b>USD75OFF</b>

# Pretrain Vision and Large Language Models in Python
<a href="https://www.packtpub.com/product/pretrain-vision-and-large-language-models-in-python/9781804618257"><img src="https://m.media-amazon.com/images/I/41hiraOOzWL._SX403_BO1,204,203,200_.jpg" alt="Data Engineering with AWS" height="256px" align="right"></a>

This is the code repository for [Pretrain Vision and Large Language Models in Python](https://www.packtpub.com/product/pretrain-vision-and-large-language-models-in-python/9781804618257), published by Packt.

**End-to-end techniques for building and deploying foundation models on AWS**

## What is this book about?

Foundation models have forever changed machine learning. From BERT to ChatGPT, CLIP to Stable Diffusion, when billions of parameters are combined with large datasets and hundreds to thousands of GPUs, the result is nothing short of record-breaking. The recommendations, advice, and code samples in this book will help you pretrain and fine-tune your own foundation models from scratch on AWS and Amazon SageMaker, while applying them to hundreds of use cases across your organization.

With advice from seasoned AWS and machine learning expert Emily Webber, this book helps you learn everything you need to go from project ideation to dataset preparation, training, evaluation, and deployment for large language, vision, and multimodal models. With step-by-step explanations of essential concepts and practical examples, you’ll go from mastering the concept of pretraining to preparing your dataset and model, configuring your environment, training, fine-tuning, evaluating, deploying, and optimizing your foundation models.

You will learn how to apply the scaling laws to distributing your model and dataset over multiple GPUs, remove bias, achieve high throughput, and build deployment pipelines.

By the end of this book, you’ll be well equipped to embark on your own project to pretrain and fine-tune the foundation models of the future.

This book covers the following exciting features: 
* Find the right use cases and datasets for pretraining and fine-tuning
* Prepare for large-scale training with custom accelerators and GPUs
* Configure environments on AWS and SageMaker to maximize performance
* Select hyperparameters based on your model and constraints
* Distribute your model and dataset using many types of parallelism
* Avoid pitfalls with job restarts, intermittent health checks, and more
* Evaluate your model with quantitative and qualitative insights
* Deploy your models with runtime improvements and monitoring pipelines 

If you feel this book is for you, get your [copy](https://www.amazon.com/Pretrain-Vision-Language-Models-Beginners/dp/180461825X) today!

**Following is what you need for this book:**
If you’re a machine learning researcher or enthusiast who wants to start a foundation modelling project, this book is for you. Applied scientists, data scientists, machine learning engineers, solution architects, product managers, and students will all benefit from this book. Intermediate Python is a must, along with introductory concepts of cloud computing. A strong understanding of deep learning fundamentals is needed, while advanced topics will be explained. The content covers advanced machine learning and cloud techniques, explaining them in an actionable, easy-to-understand way.

### Software and Hardware List

| Chapter  | Software required                                                                    | OS required                        |
| -------- | -------------------------------------------------------------------------------------| -----------------------------------|
|  	1-15	   |   	AWS Web Services(AWS) with a recent version of a modern web browser(Chrome, Edge, etc.)                                  			  | Any OS | 		

<!--
## Errata
-->
<!--
* Page 212 (Paragraph 5, line 1): **s this a good thing? Honestly, I’m happy to fi nally see the shift ; I’ve been working on generating content with AI/ML models in some fashion since at least 2019, and as a writer and creative person myself, I’ve always thought this was the most interesting part of machine learning. ** _should be_ **Is this a good thing? Honestly, I’m happy to fi nally see the shift ; I’ve been working on generating content with AI/ML models in some fashion since at least 2019, and as a writer and creative person myself, I’ve always thought this was the most interesting part of machine learning.**
-->

  
## Get to Know the Author
**Emily Webber** is a principal machine learning (ML) specialist solutions architect at Amazon Web Services (AWS). In her more than five years at AWS, she has assisted hundreds of customers on their journey to ML in the cloud, specializing in distributed training for large language and vision models. She mentors ML solution architects, authors countless feature designs for SageMaker and AWS, and guides the Amazon SageMaker product and engineering teams on best practices in regard to ML and customers. Emily is widely known in the AWS community for a 16-video YouTube series (https://www.youtube.com/playlistlist=PLhr1KZpdzukcOr_6j_zmSrvYnLUt qsZz) featuring SageMaker with 211,000 views, and for giving a keynote speech at O’Reilly AI London 2019 on a novel reinforcement learning approach she developed for public policy.



# Note from Author 


Hi there! If you'd like some examples to get hands-on with pretraining your own foundation models 🧠, then you've come to the right place. This repository is meant to pair with my 2023 [book on the topic](https://bit.ly/dist-train-book), providing an end-to-end guide for foundation models on AWS. The book has detailed explanations and relevant examples of key topics in the lifecycle of foundation models, including where they come from, why you'd design your own, how to do that, and how to build it into an application.

This repository contains examples to help you implement that guidance at scale. 🚀

Eventually I'll have some net new examples here for you to follow step-by-step across the whole lifecycle. To get you moving between now and then, you'll find in this repository links to hands-on examples elsewhere that explain how to implement everything you learned about in the book. I'll start uploading these in July, and will be pushing them out slowly.

The concepts, theory, and examples discussed in the book are general and extend to any compute environment. However, all of the hands-on guidance will focus explicitly on AWS and especially Amazon SageMaker. So let's get rolling! 🎸

## Book structure 📖
The book is broken down into 15 chapters. Let's recap those here:
1. Introduction to pretraining foundation models
2. Picking the right use case and dataset
3. Picking the right model
4. Prepping your containers and accelerators on AWS
5. Distribution fundamentals: data and model parallel
6. Building a distributed data loader
7. Finding the right hyperparameters
8. Large-scale training on Amazon SageMaker
9. Advanced training concepts
10. Fine-tuning and evaluating models
11. Detecting and mitigating bias
12. Deploying your model on SageMaker
13. Prompt engineering
14. MLOps for foundation models on AWS
15. Future trends in pretraining foundation models

You don't need coding examples for Chapters 1 and 15, because those are straightforward and high-level. That means you've got 12 more chapters to work through. I'll break these up into 3 groups for you: preparing your environment, training, and deploying. Your repository structure will then look like this.

## Repository structure 
I. [Preparation](https://github.com/PacktPublishing/Pretrain-Vision-and-Large-Language-Models-in-Python/tree/main/preparation)
- Dataset analysis
- Model analysis
- Preparing your containers and accelerators on AWS
- Basics of distribution

II. [Training](https://github.com/PacktPublishing/Pretrain-Vision-and-Large-Language-Models-in-Python/tree/main/training)
- Distributed data loader
- Hyperparameters
- Training foundation models on SageMaker
- Compilation and throughput
- Fine-tuning and evaluating


III. [Deployment](https://github.com/PacktPublishing/Pretrain-Vision-and-Large-Language-Models-in-Python/tree/main/deployment)
- Bias detection and mitigation
- Hosting foundation models on SageMaker
- Prompt engineering
- MLOps 

Each of these directories will start with just a list of links to helpful hands-on tutorials to dive into the content. In July, I'll update these with new examples for pretraining in Python across vision and language on AWS.

Happy trails! ⛰️

### Asking questions and getting help
If you're stuck, feel free to log an issue in the repo here and I'll try to address it. You can also reach me on Twitch, I'm live every Monday at 9am PST / 12pm EST / 6pm CET right [here](https://www.twitch.tv/aws/schedule). Bring your question and come hang out with us! The show is called ***Build on Generative AI*** with myself and Darko Mesaros. You can also ping me on [LinkedIn right here.](https://www.linkedin.com/in/emily-webber-921b4969/)
