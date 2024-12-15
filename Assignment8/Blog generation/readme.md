# Blog Generation Application using Hugging Face and Streamlit

## Overview
This repository contains an end-to-end Generative AI application that generates blogs using a Hugging Face model and a Streamlit app. The application leverages the power of Large Language Models (LLMs) to create well-structured blog posts based on user input.

## Features
- **User-friendly Interface**: Built with Streamlit for a seamless user experience.
- **LLM-Powered**: Utilizes Hugging Face pre-trained models for generating high-quality blogs.
- **Customizable Output**: Allows users to define the blog style, topic, and desired word count.
- **Real-Time Generation**: Generates blogs instantly based on user input.

## Architecture
1. **Frontend**: A Streamlit-based interface for user interaction.
2. **Backend**: A Python application integrating Hugging Face models for blog generation.
3. **LLM Integration**: Hugging Face models are used to generate blog content dynamically.

## Installation

### Prerequisites
- Python 3.9 or later
- Conda or virtual environment tool
- Git

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/blog-generation-app.git
   cd blog-generation-app
   ```

2. Create a virtual environment and activate it:
   ```bash
   conda create -n blog-gen-env python=3.9 -y
   conda activate blog-gen-env
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## Usage
1. Open the app in your browser (Streamlit will provide a local URL).
2. Enter the following details in the app:
   - **Blog Style**: Select the tone/style of the blog.
   - **Input Topic**: Provide the topic for the blog.
   - **Word Count**: Define the desired length of the blog.
3. Click on the **Generate Blog** button.
4. The generated blog will appear in the app interface.

## Technical Details
- **Hugging Face Model**: The application uses a pre-trained model from Hugging Face for text generation. The specific model can be replaced as needed.
- **Streamlit**: Provides a clean and interactive interface for users.
- **Python**: The core logic for integrating the model and processing inputs/outputs.

## File Structure
```plaintext
blog-generation-app/
├── app.py                # Streamlit app code
├── requirements.txt      # List of Python dependencies
├── README.md             # Project documentation
└── ...                   # Additional files and folders
```

## Example Workflow
1. **Input**: The user enters a blog topic, selects a style, and specifies the word count.
2. **Processing**: The Hugging Face model processes the input and generates the blog.
3. **Output**: The blog is displayed in the Streamlit app for the user to review.

## Video Demo
Check out the end-to-end application demo:
[Watch the Video](https://youtu.be/1IRNg0rJQOE)

## References
- [An End-to-End Framework for Production-Ready LLM Systems](https://www.comet.com/site/blog/an-end-to-end-framework-for-production-ready-llm-systems-by-building-your-llm-twin/)
- [LLM Twin Course on GitHub](https://github.com/decodingml/llm-twin-course)
- [SLM Innovator Lab](https://azure.github.io/slm-innovator-lab/3_llmops-aistudio/README.html)
- [Generative AI Projects](https://github.com/GURPREETKAURJETHRA/END-TO-END-GENERATIVE-AI-PROJECTS)
- [GenAI Examples](https://github.com/opea-project/GenAIExamples)


