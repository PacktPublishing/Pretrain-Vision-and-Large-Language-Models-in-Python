# Pretrain Vision and Large Language Models in Python
Hi there! If you'd like some examples to get hands-on with pretraining your own foundation models 🧠, then you've come to the right place. This repository is meant to pair with my 2023 [book on the topic](https://bit.ly/dist-train-book), providing an end-to-end guide for foundation models on AWS. The book has detailed explanations and relevant examples of key topics in the lifecycle of foundation models, including where they come from, why you'd design your own, how to do that, and how to build it into an application.

This repository contains examples to help you implement that guidance at scale. 🚀

By July 1, 2023 I'll have some net new examples here for you to follow step-by-step across the whole lifecycle. To get you moving between now and then, you'll find in this repository links to hands-on examples elsewhere that explain how to implememnt everything you learned about in the book.

As mentioned earlier, everything in the book and this repository focuses on AWS and especially Amazon SageMaker. So let's get rolling! 🎸

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
12. Deploying your model
13. Prompt engineering
14. MLOps for foundation models
15. Future trends

You don't need coding examples for Chapters 1 and 15, because those are straightforward and high-level. That means you've got 12 more chapters to work through. I'll break these up into 3 groups for you: preparing your environment, training, and deploying. Your repository structure will then look like this.

## Repository structure 
I. [Preparation](https://github.com/PacktPublishing/Pretrain-Vision-and-Large-Language-Models-in-Python/tree/main/preparation)
- dataset analysis
- model analysis
- preparing your containers and accelerators on AWS
- basics of distribution

II. [Training](https://github.com/PacktPublishing/Pretrain-Vision-and-Large-Language-Models-in-Python/tree/main/training)
- distributed data loader
- hyperparameters
- SageMaker
- compilation and throughput

III. [Deployment](https://github.com/PacktPublishing/Pretrain-Vision-and-Large-Language-Models-in-Python/tree/main/deployment)
- fine-tuning and evaluating
- bias detection and mitigation
- prompt engineering
- MLOPs 

Each of these directories will start with just a list of links to helpful hands-on tutorials to dive into the content. In July, I'll update these with new examples for pretraining in Python across vision and language. 

Happy trails! ⛰️

### Asking questions and getting help
If you're stuck, feel free to log an issue in the repo here and I'll try to address it. You can also reach me on Twitch, I'm live every Monday at 9am PST / 12pm EST / 6pm CET right [here](https://www.twitch.tv/aws/schedule). Bring your question and come hang out with us! The show is called *** Build on Generative AI *** with Darko Mesaros.
