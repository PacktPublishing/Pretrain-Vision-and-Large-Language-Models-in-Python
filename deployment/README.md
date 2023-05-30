# Deploying foundation models on AWS

### 1. Detecting and mitigating bias
- Amazon's ***BOLD: Bias in Open-ended Language Generation Dataset*** Github project is [here](https://github.com/amazon-science/bold).
- Princeton's ***REVISE: REvealing VIsual biaSEs*** GitHub project is [here](https://github.com/princetonvisualai/revise-tool).
- Detecting bias in vision and language with SageMaker Clarify, [noteooks are here](https://github.com/aws/amazon-sagemaker-examples/tree/2e60fb1522d1b228a77d4979a0c4ae269a4afe9c/sagemaker-clarify).
- Monitoring model drift and bias for hosted models with SageMaker [documentation is here](https://docs.aws.amazon.com/sagemaker/latest/dg/clarify-model-monitor-bias-drift.html).

### 2. Hosting foundation models on SageMaker
- Notebook for [hosting distributed models](https://github.com/aws/amazon-sagemaker-examples/blob/main/inference/generativeai/deepspeed/GPT-J-6B_DJLServing_with_PySDK.ipynb) on SageMaker with `deepspeed` is right here. This example uses GPT-J 6B.
- Using SageMaker JumpStart for hosting (and training) foundation models. This [repository has 7+ example notebooks](https://github.com/aws/amazon-sagemaker-examples/tree/main/introduction_to_amazon_algorithms/jumpstart-foundation-models), you can use these images  and models directly.
- Source code [link](https://github.com/aws/amazon-sagemaker-examples/tree/main/introduction_to_amazon_algorithms/jumpstart-foundation-models) for large model serving container with SageMaker

### 3. Prompt engineering
- Repository with a [self-managed UI](https://github.com/aws-samples/prompt-engineering-playground-with-sagemaker) to run on Jupyter for prompting prebuilt foundation models with SageMaker JumpStart.
- AWS [documentation](https://docs.aws.amazon.com/sagemaker/latest/dg/jumpstart-foundation-models-customize-prompt-engineering.html) on prompt engineering for foundation models.

### 4. MLOps for foundation models with SageMaker
