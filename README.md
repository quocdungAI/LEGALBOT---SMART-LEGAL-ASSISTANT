# LegalBot – Smart Legal Assistant  
## Project Objectives:

- Develop a chatbot that supports Q&A on legal documents related to five topics: Children, Gender Equality, Marriage and Family, Domestic Violence Prevention, and Population.
- Help people access legal information easily, quickly, and accurately.

## Approach:

- Utilize Retrieval-Augmented Generation (RAG) for information retrieval and response generation.
- Apply the Vietnamese-document-embedding model and FAISS for efficient information search in the database.
- Fine-tune the Llama 3.2B model to decompose complex questions into smaller sub-questions.
- Fine-tune the Pho BERT base v2 135M model to classify each sub-question into predefined categories.

## Chatbot Deployment:

- The chatbot is hosted on Cloud to ensure performance and scalability.
- Gradio is used to enhance the user interface for better interaction. Ollama serves as the API endpoint for Gemma3.
- Legal documents are stored in JSONL, FAISS Index, and Chunk CSV formats to enable fast and efficient retrieval.
![image](https://github.com/user-attachments/assets/434cfe75-d085-4529-8308-9c22a43358b4)
## Results Achieved:

- The chatbot can accurately respond to legal inquiries within the five specified topics.
- Chatbot accuracy: Multiple choice: 83%, Open-ended: 42%

## Roles:

- Data classification
- Model evaluation

## Team Size: 4
