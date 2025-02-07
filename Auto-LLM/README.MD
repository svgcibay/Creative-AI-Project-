
<img width="572" alt="Image" src="https://github.com/user-attachments/assets/61919e7c-1b7a-418b-ae98-320378eb0679" />


[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/feed/) | 
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/svgcibay) | 
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white)](https://www.kaggle.com/sevgiyazc)



AutoLLM Project

Overview

AutoLLM is a project that leverages LangChain and Gradio to build an interactive question-answering system powered by large language models (LLMs). This notebook integrates various AI components to enable efficient querying and response generation.

Features

LangChain Integration: Uses LangChain to handle and process natural language queries.

Vector Database Support: Embeds and stores text for efficient retrieval.

Gradio Interface: Provides a user-friendly web-based interface for interaction.

Query Processing: Implements a query engine for extracting relevant information from the knowledge base.

Installation

To run this project, install the required dependencies:

pip install gradio langchain openai lancedb

How to Use

Run the notebook to initialize the query engine.

Enter queries in the Gradio web interface.

The system will process the query and return a relevant response.

Code Highlights

Query Processing:

response = query_engine.query("What do we mean by Chain in Langchain?")

Gradio Interface:

demo = gr.Interface(fn=chat_function, inputs="text", outputs="text")
demo.launch()

Future Enhancements

Improve accuracy using more advanced embedding models.

Expand the knowledge base with additional data sources.

Optimize performance for faster response times.


