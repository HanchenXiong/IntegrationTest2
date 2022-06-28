# HanchenXiong/IntegrationTest2 

[![Boltzbit Project](https://img.shields.io/badge/Boltzbit-Project-blueviolet?style=for-the-badge)](https://demo.platform.boltzbit.com/demo-user/HanchenXiong/IntegrationTest2)

[![Data Status](http://demo.platform.boltzbit.com/github-service/api/v1/cubes/status/data?repositoryOwnerPlusName=HanchenXiong/IntegrationTest2&token=PUBLIC)](https://demo.platform.boltzbit.com/demo-user/HanchenXiong/IntegrationTest2?tab=Dataset)
[![Training Status](http://demo.platform.boltzbit.com/github-service/api/v1/cubes/status/train?repositoryOwnerPlusName=HanchenXiong/IntegrationTest2&token=PUBLIC)](https://demo.platform.boltzbit.com/demo-user/HanchenXiong/IntegrationTest2?tab=Training)
[![Serving Status](http://demo.platform.boltzbit.com/github-service/api/v1/cubes/status/serving?repositoryOwnerPlusName=HanchenXiong/IntegrationTest2&token=PUBLIC)](https://demo.platform.boltzbit.com/demo-user/HanchenXiong/IntegrationTest2?tab=Deployment)


## Model Details

 **Developed by:** Hugging Face
 **Model type:** Transformer-based Language Model
 **Language:** English
 **License:** Apache 2.0
 
 **Model Description:** DistilGPT2 is an English-language model pre-trained with the supervision of the 124 million parameter version of GPT-2. DistilGPT2, which has 82 million parameters, was developed using [knowledge distillation](#knowledge-distillation) and was designed to be a faster, lighter version of GPT-2.
 
**Resources for more information:** See [this repository](https://github.com/huggingface/transformers/tree/main/examples/research_projects/distillation) for more about Distil\* (a class of compressed models including Distilled-GPT2), [Sanh et al. (2019)](https://arxiv.org/abs/1910.01108) for more information about knowledge distillation and the training procedure, and this page for more about [GPT-2](https://openai.com/blog/better-language-models/).


## Uses, Limitations and Risks

#### Limitations and Risks


**CONTENT WARNING: Readers should be aware this section contains content that is disturbing, offensive, and can propagate historical and current stereotypes.**

As the developers of GPT-2 (OpenAI) note in their [model card](https://github.com/openai/gpt-2/blob/master/model_card.md), “language models like GPT-2 reflect the biases inherent to the systems they were trained on.” Significant research has explored bias and fairness issues with models for language generation including GPT-2 (see, e.g., [Sheng et al. (2021)](https://aclanthology.org/2021.acl-long.330.pdf) and [Bender et al. (2021)](https://dl.acm.org/doi/pdf/10.1145/3442188.3445922)). 

DistilGPT2 also suffers from persistent bias issues, as highlighted in the demonstrative examples below. Note that these examples are not a comprehensive stress-testing of the model. Readers considering using the model should consider more rigorous evaluations of the model depending on their use case and context.
