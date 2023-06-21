# openai-logit-bias-classification-walkthrough
Learn how to use logit bias with OpenAI models to create highly-powerful classifiers in minutes.

This notebook will walk you through using OpenAI's logit bias functionality to force the model to output only the classifiers we want, drastically improving LLM performance on classification tasks. With this approach, we can (in minutes) create classifiers that outperform custom-trained classifiers simply by using off-the-shelf LLM APIs.

This notebook shows a) how to make a standard 'true'/'false' classifier, and b) how to make a custom classifier for more complex tasks.

**Beyond demonstrating how these systems are built, this notebook also provides a benchmarking system to test the performance of multiple LLMs against your target tasks.**

The system will output easy-to-read performance tables, like this:
