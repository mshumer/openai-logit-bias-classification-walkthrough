# openai-logit-bias-classification-walkthrough
Learn how to use logit bias with OpenAI models to create highly-powerful classifiers in minutes.

[This notebook](https://colab.research.google.com/drive/1fx0NeWHE7S97gdvadR-WC0z36R2Z_mu9?usp=sharing) will walk you through using OpenAI's logit bias functionality to force the model to output only the classifiers we want, drastically improving LLM performance on classification tasks. With this approach, we can (in minutes) create classifiers that outperform custom-trained classifiers simply by using off-the-shelf LLM APIs.

This notebook shows a) how to make a standard 'true'/'false' classifier, and b) how to make a custom classifier for more complex tasks.

## Getting Started
[Use it in Google Colab with this link,](https://colab.research.google.com/drive/1fx0NeWHE7S97gdvadR-WC0z36R2Z_mu9?usp=sharing) or download the .ipynb file in the repo.

## Benchmarking
**Beyond demonstrating how these systems are built, this notebook also provides a benchmarking system to test the performance of multiple LLMs against your target tasks.**

The system will output easy-to-read performance tables, like this:
<img width="923" alt="Screen Shot 2023-06-20 at 9 21 03 PM" src="https://github.com/mshumer/openai-logit-bias-classification-walkthrough/assets/41550495/64eed7d5-8389-47bc-a844-41f6571de469">

Below these tables, you'll be able to see the latency of each model. With both of these, you should be able to choose the best model for your use-case.

## Productionizing Classifiers
After you've created a classifier you're happy with, you can use the templates in the bottom two cells to get your classifiers ready for production use.

## License
This project is MIT licensed.

## Contact
Matt Shumer - @mattshumer_
Project Link: https://github.com/mshumer/openai-logit-bias-classification-walkthrough
