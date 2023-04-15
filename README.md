# ScalableGPT

###  Introduction

Excitement surrounding ChatGPT and its capabilities has been felt across a wide range of industries and fields, and academia is no exception. Researchers are exploring ways to utilize ChatGPT as a consultant, proofreader, or a "CPU" to coordinate various APIs and perform more complex tasks (e.g. <a href="https://python.langchain.com/en/latest/index.html">LangChain</a>). Social scientists, in particular, are beginning to recognize the power of AI in extracting information and making automatic annotations.

One of the most impressive features of ChatGPT is its ability to function as a zero-shot or few-shot learner, meaning that it can achieve a high level of performance even in situations where training samples are limited. Some social scientists are touting ChatGPT and its friends as valuable assistants in their research, with recent studies demonstrating their efficacy in tasks such as sentiment analysis and automatic labeling.

<a href="https://arxiv.org/abs/2303.15056">Gilardi et al. (2023)</a> found that ChatGPT's zero-shot accuracy outperformed crowdsourcing in four out of five tasks, indicating a promising future for automatic labeling by ChatGPT instead of hiring research assistants or MTurk labeling. Similarly, <a href="https://arxiv.org/abs/2304.04339">Wang et al. (2023)</a> demonstrated ChatGPT's impressive zero-shot learning abilities in sentiment analysis, comparable to state-of-the-art models. <a href="https://joeornstein.github.io/publications/ornstein-blasingame-truscott.pdf">Ornstein et al. (2023)</a> also showcased how language models can be applied to various text-as-data tasks in social science research.

Despite some concerns about robustness, it is heartening to see such a powerful tool being applied across numerous fields, enabling less technical researchers to tackle complex tasks. In this project, we have developed a framework to assist social scientists and other practitioners in scaling up their work with ChatGPT.

### Motivation

I encountered a task to identify whether a social media user is an individual user, self-media or an organization according to the user profile. Although this task can be tackled by fine-tuning a pre-trained LM such as BERT, I did not do that but instead asked ChatGPT to help me. Given the large number of users, it was impossible to input the profiles by hands. Therefore, I used OpenAI's API to do this job. Considering the budget and the limit of request per hour, I needed to find a more efficient way to do it. The frame work is the fruit.
