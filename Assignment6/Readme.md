# Prompt Engineering Techniques in Colab

This repository provides a comprehensive guide to various **Prompt Engineering Techniques** using OpenAI's GPT-4 and GPT-3.5 models, with practical implementations in Google Colab. The project includes examples of failure cases and their resolutions through advanced prompting techniques. 

---

## Contents

### a) Illustrating Prompt Engineering Techniques
A detailed Colab notebook demonstrating the following techniques:

1. **In-Context Learning (ICL)**
2. **Chain of Thought (CoT)**
3. **Iterative Chain of Thought (iCOT)**
4. **Tree of Thought (TOT)**
5. **Graph of Thought (GOT)**
6. **Agent of Thought (AOT)**
7. **Reasoning Across Sources with Chain-of-Thought (RASCEF)**
8. **Reason + Act (REACT)** - [More Info](https://til.simonwillison.net/llms/python-react-pattern#:~:text=The%20ReAct%20pattern%20(for%20Reason,results%20back%20into%20the%20LLM.)
9. **Forest of Thoughts (FoT)** using LangChain - [More Info](https://www.linkedin.com/posts/richard-walker-a18528_forest-of-thoughts-boosting-large-language-activity-7073925128778067968-xAHN/)
10. **Tree of Thought UI** - [Repository](https://github.com/mazewoods/tree-of-thought-ui)

The notebook illustrates each technique with:
- **Failure cases**: When a technique fails to provide correct results.
- **Resolutions**: How advanced prompting techniques overcome these failures.

### b) 21 Prompt Templates with Success and Failure Cases
A Colab notebook featuring:
- 21 diverse prompt templates based on practical examples discussed in class.
- Each template includes:
  - **Success Cases**: When the prompt yields the desired output.
  - **Failure Cases**: Instances where the prompt fails and suggestions to improve it.

Templates follow the patterns discussed in the [Prompting Guide](https://www.promptingguide.ai/papers) and the techniques outlined in [this paper](https://arxiv.org/pdf/2302.11382.pdf).

### c) Domain-Specific Prompts
A set of prompts tailored for **10 diverse fields** (e.g., HR, teaching, finance). Each field includes three unique prompts with practical test cases.

Examples:
- **HR**: Crafting job descriptions, conducting mock interviews, analyzing resumes.
- **Teaching**: Designing quizzes, explaining concepts, providing feedback.
- **Finance**: Analyzing financial statements, predicting trends, summarizing reports.

### d) OpenAI Example Implementation for PaLM 2 API
A Colab notebook demonstrating how to replicate OpenAI's example workflows using **PaLM 2 API**. Includes:
- Text completion
- Text summarization
- Sentiment analysis

### e) Function Call API Examples
Implementation of **function calls** with OpenAI API in a Colab notebook:
- Example: Calling a weather API via OpenAI to fetch weather updates.
- Use Case: Dynamic interaction with external APIs through LLMs.

### f) System Prompt Use Case
A Colab notebook showcasing how to use **system prompts** effectively. Includes:
- Defining the assistant's behavior for specific use cases.
- Examples like coding assistants, customer service agents, and creative writing assistants.

---

## Setup Instructions

### Prerequisites
- Python 3.7 or higher
- Google Colab account
- API key for OpenAI and PaLM 2

