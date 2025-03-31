![image](https://github.com/user-attachments/assets/434cfe75-d085-4529-8308-9c22a43358b4)

# LegalBot – Smart Legal Assistant  

## Introduction  
LegalBot is an intelligent legal assistant designed to help users search and understand legal documents related to various fields such as population, marriage and family, children's rights, gender equality, and domestic violence prevention. The project is built using a Retrieval-Augmented Generation (RAG) architecture, combining natural language processing (NLP) and deep learning models to optimize information retrieval and provide contextually accurate answers.  

## Project Goals  
- **Enhance information retrieval:** Shift from traditional Google search to an RAG-based model, improving search efficiency and answer accuracy.  
- **Provide quick legal reference:** Enable users to efficiently look up current legal regulations and official guidelines.  
- **Contribute to legal awareness:** Help the public better understand their rights and obligations through accessible and comprehensible legal information.  

## Project Components  
### Data Collection & Preprocessing  
- Gather legal documents from official sources such as the Government Portal and relevant ministry websites.  
- Process data (chunking, filtering unnecessary text) and store it in JSONL and CSV formats.  
- Use embedding models to convert text into vectors and store them in a vector database (using Faiss).  

### Text Analysis & Classification  
- Apply the **PhoBERT** model to classify user queries into topics: Children, Marriage & Family, Gender Equality, Population, and Domestic Violence Prevention.  
- Evaluate model performance with Accuracy and F1-score exceeding 96%.  

### Chatbot Deployment  
- Design a chatbot pipeline based on RAG architecture.  
- Fine-tune **Llama 3.2 3B** for question segmentation and **PhoBERT** for query classification.  
- Integrate embeddings with a vector database to retrieve relevant information and generate context-aware responses.  

### Data Analysis, Summarization & Reporting  
- Perform statistical analysis on query distribution, question length, label distribution, and data visualization (histograms, word clouds, cosine similarity).  
- Generate reports, identify limitations, and propose future improvements.  

## System Requirements  
### Hardware  
- A GPU with sufficient power to support deep learning model fine-tuning and inference.  

### Software  
- Python 3.7+  
- Required libraries: Faiss, Sentence Transformer, Hugging Face Transformers, PyTorch, etc.  

### Data  
- Legal documents collected from official sources (PDF, HTML).  
