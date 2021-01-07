<p align="center">
 
[![Jina](https://github.com/jina-ai/jina/blob/master/.github/badges/jina-badge.svg "We fully commit to open-source")](https://jina.ai)
[![Jina](https://github.com/jina-ai/jina/blob/master/.github/badges/jina-hello-world-badge.svg "Run Jina 'Hello, World!' without installing anything")](https://github.com/jina-ai/jina#jina-hello-world-)
[![Jina](https://github.com/jina-ai/jina/blob/master/.github/badges/license-badge.svg "Jina is licensed under Apache-2.0")](#license)
[![Jina Docs](https://github.com/jina-ai/jina/blob/master/.github/badges/docs-badge.svg "Checkout our docs and learn Jina")](https://docs.jina.ai)
[![We are hiring](https://github.com/jina-ai/jina/blob/master/.github/badges/jina-corp-badge-hiring.svg "We are hiring full-time position at Jina")](https://jobs.jina.ai)
<a href="https://twitter.com/intent/tweet?text=%F0%9F%91%8DCheck+out+Jina%3A+the+New+Open-Source+Solution+for+Neural+Information+Retrieval+%F0%9F%94%8D%40JinaAI_&url=https%3A%2F%2Fgithub.com%2Fjina-ai%2Fjina&hashtags=JinaSearch&original_referer=http%3A%2F%2Fgithub.com%2F&tw_p=tweetbutton" target="_blank">
  <img src="https://github.com/jina-ai/jina/blob/master/.github/badges/twitter-badge.svg"
       alt="tweet button" title="👍Share Jina with your friends on Twitter"></img>
</a>
[![Python 3.7 3.8](https://github.com/jina-ai/jina/blob/master/.github/badges/python-badge.svg "Jina supports Python 3.7 and above")](#)
[![Docker](https://github.com/jina-ai/jina/blob/master/.github/badges/docker-badge.svg "Jina is multi-arch ready, can run on differnt architectures")](https://hub.docker.com/r/jinaai/jina/tags)

</p>

# BERT-based Financial Question Answering System

In this example, we use [Jina](https://github.com/jina-ai/jina), PyTorch, and [Hugging Face transformers](https://github.com/huggingface/transformers) to build a production-ready
BERT-based Financial Question Answering System.
We adapt a [passage reranking](https://arxiv.org/pdf/1901.04085.pdf) approach by first retrieving the top-50 candidate answers,
then reranking the candidate answers using [FinBERT-QA](https://github.com/yuanbit/FinBERT-QA), a BERT-based model fine-tuned on
the [FiQA](https://sites.google.com/view/fiqa/home) dataset that achieved the state-of-the-art results.

**🦉 Please refer to this [tutorial](https://jina.ai/2021/01/07/financial-qa-tutorial.html)
for a step-by-step guide and detailed explanations.**

<p align="center">
<img src="img/qa-pipeline-simple.png" width="1000">
</p>

## Motivation
Motivated by the emerging demand in the financial industry for 
the automatic analysis of unstructured and structured data at scale, QA systems can provide lucrative and competitive 
advantages to companies by facilitating the decision making of financial advisers. The goal of our system is to
search for a list of relevant answer passages given a question. Here is an example of a question and a ground
truth answer from the [FiQA](https://sites.google.com/view/fiqa/home) dataset:

<p align="center">
<img src="img/sample-qa.png" alt="performance" width="400px">
</p>

<p align="center">
<img src="img/search-results.png" width="900">
</p>

## Community

- [Slack channel](https://join.slack.com/t/jina-ai/shared_invite/zt-dkl7x8p0-rVCv~3Fdc3~Dpwx7T7XG8w) - a communication platform for developers to discuss Jina
- [Community newsletter](mailto:newsletter+subscribe@jina.ai) - subscribe to the latest update, release and event news of Jina
- [LinkedIn](https://www.linkedin.com/company/jinaai/) - get to know Jina AI as a company and find job opportunities
- [![Twitter Follow](https://img.shields.io/twitter/follow/JinaAI_?label=Follow%20%40JinaAI_&style=social)](https://twitter.com/JinaAI_) - follow us and interact with us using hashtag `#JinaSearch`  
- [Company](https://jina.ai) - know more about our company, we are fully committed to open-source!

## License

Copyright (c) 2021 Jina's friend. All rights reserved.


