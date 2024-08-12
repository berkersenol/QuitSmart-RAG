# Smoking Cessation Companion. 

This project represents a cutting-edge approach to natural language processing (NLP) by deploying a Naive Retrieval-Augmented Generation (RAG) system tailored for smoking cessation. Drawing inspiration from the seminal work "The Easy Way to Stop Smoking" by Allen Carr, this initiative aims to transform how individuals engage with the process of quitting smoking. By integrating advanced NLP techniques and deep learning, the project offers a novel application that enhances user interaction through personalized and context-aware responses.

Project utilizes Llama2 (with 13B parameters), Langchain and ChromaDB and FAISS to establish a Retrieval Augmented Generation (RAG) system. This system empowers you to ask questions about your documents, even if the information wasn't included in the training data for the Large Language Model (LLM). Retrieval Augmented Generation works by first performing a retrieval step when presented with a question. This step fetches relevant documents from a special vector database, where the documents have been indexed.

### Definitions

* **LLM:** Large Language Model
* **Llama2:** LLM developed by Meta
* **Langchain:** Framework designed to streamline the creation of applications utilizing LLMs
* **Vector database:** Database that organizes data using high-dimensional vectors
* **ChromaDB** and **FAISS:** Vector databases
* **RAG:** Retrieval Augmented Generation

### Model Details

* **Model:** Llama 2
* **Variation:** 13b-chat-hf (13b: 13 Billion parameters; hf: HuggingFace)

---
**The Sources that have been used for this project:**

1. To grasp general understanding about the Project: (https://js.langchain.com/v0.1/docs/use_cases/question_answering/)
2. To grasp general understanding about the Project: (https://colab.research.google.com/drive/172uMprWwUfEecXQWBrsgDAlkpT_EK39z?usp=sharing#scrollTo=AOzZWPU05WLr)
3. BGE Embedding model implementation guide: (https://python.langchain.com/v0.1/docs/integrations/text_embedding/bge_huggingface/)
4. LLAMA-2 implementation guide:(https://huggingface.co/meta-llama/Llama-2-13b-chat-hf)

## Acknowledgments

- Thanks to Allen Carr for the inspirational book that motivated this project.

