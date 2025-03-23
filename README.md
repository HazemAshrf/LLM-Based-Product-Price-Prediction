# LLM-Based Product Price Prediction and Deal Analysis

This repository presents a comprehensive workflow that fine-tunes a Meta-Llama model using QLoRA, employs the Gemini model to generate targeted prompts for product data, and integrates DeepSeek and Gemini (with RAG-enhanced prompts) with the fine-tuned model to predict product prices. The entire pipeline is delivered through an intuitive Gradio interface that allows users to input a product URL and receive a detailed price analysis, including a recommendation on whether the product is a good deal.

## Model Fine-Tuning

The Meta-Llama model is fine-tuned using **QLoRA** to enhance its ability to understand product descriptions and pricing dynamics. Fine-tuning allows the model to better interpret structured and unstructured product data, improving its effectiveness in price prediction tasks.

## Prompt Generation

The **Gemini model** is used to generate structured prompts based on product information. These prompts help improve the accuracy and relevance of the pricing predictions by ensuring that the input provided to the models is contextually rich and well-formatted.

## Price Prediction Pipeline

- **Integrated Predictions:**  
  The price prediction process combines outputs from **DeepSeek** and **Gemini** (enhanced using **RAG**) alongside the fine-tuned **Meta-Llama** model. This multi-source integration helps provide a more reliable and accurate estimation of product prices.

- **Contextual Enhancement with RAG:**  
  Retrieval-Augmented Generation (RAG) ensures that relevant external context is incorporated into the prediction process, improving the model’s ability to assess real-world pricing trends.

## User Interaction via Gradio Interface

A **Gradio-powered interface** provides an interactive way for users to analyze product prices. By entering a product URL, users receive:
- Price predictions based on integrated model outputs.
- A recommendation on whether the product is a good deal.

## Acknowledgments

This project was developed with knowledge gained from the course:  
[LLM Engineering: Master AI, Large Language Models & Agents](https://www.udemy.com/share/10bOXH3@bR_BvzCmyw5QhqER2Ss9EXcKibGmZJS9ooTETW_CpIZGQSHqvvO3KDqAFwTvtEnq9Q==/)  
