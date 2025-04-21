[![GitHub stars](https://img.shields.io/github/stars/build-on-aws?color=blue&style=flat-square)](https://github.com/build-on-aws/llm-rag-vectordb-python/stargazers) [![GitHub license](https://img.shields.io/github/license/build-on-aws/llm-rag-vectordb-python?color=green&style=flat-square)](https://github.com/build-on-aws/llm-rag-vectordb-python/blob/main/LICENSE)

<h1 align="center">☁️🐍 Getting started with Amazon Bedrock, RAG, and Vector database in Python</h1>

### 🔍 Introduction
In this repository, you'll find sample applications and tutorials that showcase the power of **Amazon Bedrock with Python**. These resources are designed to help Python developers understand how to harness **Amazon Bedrock** in building generative AI-enabled applications. You'll also discover how to integrate Bedrock with vector databases using `RAG (Retrieval-augmented generation)`, and services like Amazon Aurora, RDS, and OpenSearch. Additionally, get insights into using `langchain` and `streamlit` to create applications that demonstrate your experiments effectively.

### 📑 Table of Contents
- [Unified AI Q&A](#unified-ai-qa)
- [Stable Diffusion AI Application](image-generation-node-js-app)
- [Resume Screening Application](resume-screening-app)
- [Building Bonds Application](data-analysis-tool)
- [Data Analysis Tool](data-analysis-tool)
- [Instant Recipe Generator](ingredient-to-recipe)
- [Getting Started](#getting-started)

### 📚🦜 **Unified AI Q&A: Harnessing `pgvector`, Amazon Aurora & Amazon Bedrock**
Craft sophisticated Q&A bots for specialized tasks, and experience the union of `pgvector` with Amazon Aurora PostgreSQL and the prowess of Titan LLMs under the RAG paradigm.
- 📖 [Guide & Setup](searching-from-my-data/README.md)
- 🌠 Key Features:
    - Seamless integration with Streamlit.
    - Efficient backend with Amazon Bedrock and Aurora.

![Preview](searching-from-my-data/data_search.gif)

### 🚀 Integrated Fullstack Showcase
Harness the power of Stable Diffusion AI using Amazon Bedrock.
- 🖥 [Live Demo](https://main.d1zbstr6nltjhw.amplifyapp.com/)
- 📖 [Guide & Setup](image-generation-node-js-app/README.md)
- 🌠 Key Features:
    - Seamless integration: Lambda, API Gateway, Bedrock, Amplify
    - Deployment via Serverless stack.

![Showcase](image-generation-node-js-app/img/img-gen.gif)

### 📄 Resume Screening App
Streamline resume screening based on specific job descriptions.
- 📖 [Guide & Setup](resume-screening-app/README.md)
- 🌠 Key Features:
    - Seamless integration with Streamlit.
    - Efficient backend with Amazon Bedrock and Aurora.

![Screening](resume-screening-app/Resume-Screener.gif)

### 🤝 Building Bonds
Revolutionize introductions by fetching LinkedIn profiles and generating engaging summaries.
- 📖 [Guide & Setup](building-bonds/README.md)
- 🌠 Key Features:
    - Instant LinkedIn profile retrieval.
    - Automated summaries & ice-breakers via Amazon Bedrock and LangChain.

![Bonds](building-bonds/boundbuilding.gif)

### 📊 Data Analysis Tool
Analyze CSV data with a streamlined Streamlit application.
- 📖 [Guide & Setup](data-analysis-tool/README.md)
- 🌠 Key Features:
    - Smooth UI with Streamlit.
    - Advanced functions via Langchain.

![Analysis](data-analysis-tool/da.gif)

### 🥘 Instant Recipe Generator
Build a streamlined Streamlit application to generate recipes given an image of all the ingredients.
- 📖 [Guide & Setup](/llm-rag-vectordb-python/ingredient-to-recipe/README.md)
- 🌠 Key Features:
    - Smooth web application interface via Streamlit.
    - Advanced functionalities through Langchain.
    - Integration with Hugging Face.
    - Generative AI applications with Amazon Bedrock.

![Recipe](ingredient-to-recipe/rec.gif)

### 💼 **Getting Started**

1. 📥 Clone this repository.
2. 🗂 Navigate to the desired project directory:
    - **Resume Screening App**: [README guide](resume-screening-app/README.md).
    - **Building Bonds**: [README guide](building-bonds/README.md).
    - **Stable Diffusion AI App**: [README guide](image-generation-node-js-app/README.md).
    - **Instant Recipe Generator**: [README guide](ingredient-to-recipe/README.md).
    - **Data Analysis Tool**: [README guide](data-analysis-tool/README.md).
3. 🔧 Set up a virtual environment, `.env` files, and install dependencies as outlined in each README.
4. 🚀 Launch the desired Streamlit app and delve in!


### 🔒 **Security**
[See more on security](CONTRIBUTING.md#security-issue-notifications).

### 📜 **License**
Licensed under the MIT-0 License. [View License](LICENSE).