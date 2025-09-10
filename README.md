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

## Installation

To get this project up and running on your local machine, please follow these steps.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    cd your-repository-name
    ```

2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install the required dependencies:**
    A `requirements.txt` file is provided to ensure a correct setup. Run the following command:
    ```bash
    pip install -r requirements.txt
    ```

## How to Use

1.  **Prepare Your Data**:
    * Place your patent data CSV files inside the `/data` directory.
    * The primary script expects files with specific columns for processing. Please refer to the notebook for details on the data structure.

2.  **Run the Jupyter Notebook**:
    * Launch Jupyter Notebook or JupyterLab:
        ```bash
        jupyter notebook
        ```
    * Open `project_code.ipynb`.
    * Run the cells sequentially to process the data, train the model (optional), and launch the interactive tool.

3.  **Use the Interactive Risk Analysis Tool**:
    * The final cell in the notebook will start a Gradio web service.
    * Open the provided local URL (usually `http://127.0.0.1:7860`) in your web browser.
    * Paste the patent text into the input box to receive a detailed risk classification report.

## Project Outcome

This project successfully developed an automated system capable of analyzing and classifying AI-related risks in patent documents. The final model was deployed into a practical, interactive tool, demonstrating its potential for real-world application in helping organizations navigate the complex landscape of AI regulation.

## Thesis

For a comprehensive
