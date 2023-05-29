# Training foundation models on AWS

### 1. Building a distributed data loader
- Working with datasets and [dataloaders in PyTorch](https://pytorch.org/tutorials/beginner/basics/data_tutorial.html)
- Using the Hugging Face [`Dataset` object with PyTorch](https://huggingface.co/docs/datasets/use_with_pytorch)
- Profiling a data loader with [SageMaker Debugger](https://docs.aws.amazon.com/sagemaker/latest/dg/debugger-data-loading-time.html)
- SageMaker [processing jobs](https://docs.aws.amazon.com/sagemaker/latest/dg/processing-job.html)
- Example data pipeline in Python for [training GPT-2 on SageMaker](https://github.com/aws/amazon-sagemaker-examples/blob/main/training/distributed_training/pytorch/model_parallel/gpt2/data_pipeline.py)

### 2. Picking the right hyperparameters
- 10+ example notebooks for [hyperparameter tuning on SageMaker](https://github.com/aws/amazon-sagemaker-examples/tree/main/hyperparameter_tuning)
- Hyperband automatic model tuning for [distributed training example notebook](https://github.com/aws/amazon-sagemaker-examples/blob/2e60fb1522d1b228a77d4979a0c4ae269a4afe9c/hyperparameter_tuning/model_tuning_for_distributed_training/hyperparameter_tuning_for_distributed_training.ipynb#L7)
- More [guidance](https://docs.aws.amazon.com/sagemaker/latest/dg/distributed-training.html) on updating learning rate and batch size as a function of the overall accelerator world size

### 3. Large-scale training on SageMaker
- End-to-end notebook for training up to [30B parameter GPT-based model on SageMaker](https://github.com/aws/amazon-sagemaker-examples/blob/main/training/distributed_training/pytorch/model_parallel/gpt2/smp-train-gpt-simple.ipynb)
- 

### 4. Compiling your model
- Example [notebook](https://github.com/aws/amazon-sagemaker-examples/blob/main/sagemaker-training-compiler/huggingface/pytorch_single_gpu_single_node/albert-base-v2/albert-base-v2.ipynb) of changing batch size and learning rate as a function of model compilation

### 5. Measuring and boosting throughput

### 6. Fine-tuning your model
- Fine-tuning BLOOM with LoRA using Hugging Face's parameter-efficient fine-tuning [on SageMaker](https://github.com/huggingface/notebooks/blob/main/sagemaker/24_train_bloom_peft_lora/sagemaker-notebook.ipynb)

### 7. Evaluating your model
