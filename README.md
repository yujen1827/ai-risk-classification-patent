# ai-risk-classification-patent
An automated system for classifying AI-related risks in patent documents

# An automated system for classifying AI-related risks in patent documents
# Automated AI Risk Classification for Patent Documents

**Author:** Yu-Jen Tsai

## Project Overview

This project introduces an automated system designed to classify Artificial Intelligence (AI) related risks within patent documents. As global AI regulations, such as the EU AI Act, become more prevalent, technology companies require a scalable method to assess the compliance of their patent portfolios. This system addresses the inefficiencies of manual review by providing an automated solution that understands the contextual nuances of AI risks described in dense, technical patent texts.

## Key Features

* **Machine Learning Model**: Utilizes a fine-tuned sentence-transformer model (`all-MiniLM-L6-v2`) coupled with a Multi-layer Perceptron (MLP) classifier to accurately categorize AI-related risks.
* **Data Processing**: Implements robust text extraction and preprocessing pipelines specifically designed to handle the unique structure of patent claims.
* **Interactive Interface**: A user-friendly web interface, built with Gradio, allows for easy input of patent text and provides real-time classification results and detailed analysis.
* **Scalability**: Offers a scalable alternative to manual, time-consuming patent reviews.


## Project Outcome

This project successfully developed an automated system capable of analyzing and classifying AI-related risks in patent documents. The final model was deployed into a practical, interactive tool, demonstrating its potential for real-world application in helping organizations navigate the complex landscape of AI regulation.
