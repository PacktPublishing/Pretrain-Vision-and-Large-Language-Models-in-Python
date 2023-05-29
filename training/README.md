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
- Basic example of model parallel trainnig on SageMaker with [Hugging Face `Trainer` API](https://github.com/huggingface/notebooks/blob/main/sagemaker/04_distributed_training_model_parallelism/sagemaker-notebook.ipynb)
- Noteook for fine-tuning or pretraining [Stable Diffusion on SageMaker](https://github.com/aws-samples/sagemaker-distributed-training-workshop/blob/main/1_data_parallel/Lab1_stable_diffusion/fine_tune_stable_diffusion.ipynb)
- Using [SageMaker warm pools](https://docs.aws.amazon.com/sagemaker/latest/dg/train-warm-pools.html) to enhance your development cycles for the Training API
- Notebook for using [PyTorch FSDP with SageMaker and Hugging Face](https://github.com/huggingface/notebooks/blob/main/sagemaker/25_pytorch_fsdp_model_parallelism/sagemaker-notebook.ipynb) for 20B+ parameter models

### 4. Compiling your model
- Detailed [walk-through from Chaim Rand](https://towardsdatascience.com/tips-and-tricks-for-upgrading-to-pytorch-2-3127db1d1f3d) on upgrading to PyTorch 2.0 on AWS and SageMaker.
- Example [notebook](https://github.com/aws/amazon-sagemaker-examples/blob/main/sagemaker-training-compiler/huggingface/pytorch_single_gpu_single_node/albert-base-v2/albert-base-v2.ipynb) of changing batch size and learning rate as a function of model compilation, uses SageMaker Training Compiler
- Guidance [from the Neuron SDK](https://awsdocs-neuron.readthedocs-hosted.com/en/latest/general/arch/model-architecture-fit.html) on supported models and compiling your model for AWS custom machine learning accelerators, optimized for training, `Trainium`.

### 5. Measuring throughput
- I'll add an example here of computing TFLOPS per accelerator
- Some [guidance](https://docs.aws.amazon.com/sagemaker/latest/dg/training-metrics.html) on working with CloudWatch and SageMaker
- Using [SageMaker Debugger](https://docs.aws.amazon.com/sagemaker/latest/dg/debugger-configure-framework-profiling.html)

### 6. Fine-tuning your model
- Fine-tuning BLOOM with LoRA using Hugging Face's parameter-efficient fine-tuning [on SageMaker](https://github.com/huggingface/notebooks/blob/main/sagemaker/24_train_bloom_peft_lora/sagemaker-notebook.ipynb)
- Fine-tuning `Donut` for [SOTA document parsing](https://github.com/huggingface/notebooks/blob/main/sagemaker/26_document_ai_donut/sagemaker-notebook.ipynb) with Hugging Face on SageMaker.

### 7. Evaluating your model
- This is too broad to have a single example for everything - that would be like trying to compute the wave angles of every ocean continuously :). However, for some concrete examples in language, take a look at Hugging Face's repository from their book **Natural Language Processing with Transformers** right [here](https://github.com/nlp-with-transformers/notebooks).
