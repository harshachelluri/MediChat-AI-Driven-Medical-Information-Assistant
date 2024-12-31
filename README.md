# MediChat: AI-Driven Medical Information Assistant

[DATASET](https://github.com/harshachelluri/MediChat-AI-Driven-Medical-Information-Assistant/blob/main/Patient%20Information.pdf)

**MediChat** is an AI-powered chatbot designed to assist healthcare professionals by providing instant, personalized patient information. The chatbot integrates **Google Gemini** for generative AI responses and **Retrieval-Augmented Generation (RAG)** for context-aware, real-time information retrieval from medical records.

## Key Features:
- **Patient Data Retrieval**: Uses **FAISS** for quick search and retrieval of patient data from large medical documents.
- **AI-Enhanced Responses**: Combines data retrieval with **Google Generative AI** to generate meaningful, context-aware responses.
- **Flask Web Application**: A user-friendly web interface for healthcare professionals and patients to query medical data.

## Technologies Used:
- **Google Gemini**: For generative AI responses to patient queries.
- **FAISS**: Efficient similarity search and fast retrieval of patient data.
- **LangChain**: Framework for processing documents and chaining multiple AI tasks.
- **HuggingFace**: Used for converting documents into embeddings for vector-based search.
- **Flask**: A lightweight web framework for deploying the application.
  
## Skills Required:
- **Machine Learning & AI**: Knowledge of **NLP**, **Google Gemini**, and **Generative AI**.
- **Data Retrieval & Vector Databases**: Experience with **FAISS** and **RAG** architecture.
- **Programming**: Proficiency in **Python**, **Flask**, and web technologies (**HTML**, **CSS**, **JavaScript**).
- **Machine Learning Frameworks**: Familiarity with **HuggingFace** and **LangChain**.
- **Cloud & API Integration**: Experience with cloud platforms and API integration.
- **Version Control**: Familiarity with **Git** for code management.

## How It Works:
1. **Document Processing**: Patient records are loaded and split into chunks using **LangChain**.
2. **Data Embedding**: Chunks are embedded using **HuggingFace** and stored in a **FAISS** database.
3. **Querying**: When a query is made, **FAISS** retrieves the most relevant chunks, which are then processed by **Google Generative AI** to create a response.
4. **Web Interface**: A **Flask** web app enables easy interaction with the chatbot, allowing healthcare professionals to query patient data quickly.

## Example Use Case:
Healthcare professionals can query the system for detailed patient information:

**Query**: "Tell me about the details of the patient with ID 1001, including their medical history, current condition, and treatment plan."

**Response**: "Patient Rajesh Kumar (ID 1001), admitted on January 5, 2024, is currently experiencing shortness of breath and chest discomfort, likely due to an asthma exacerbation. His medical history includes hypertension and asthma, and he is currently on Atenolol and Salbutamol. The treatment plan involves nebulized bronchodilators, steroid therapy, and blood pressure monitoring."


 
**MediChat** is an innovative solution aimed at improving healthcare delivery by making patient data easily accessible through AI-powered, real-time responses. The integration of generative AI, machine learning, and document retrieval ensures high accuracy and efficiency in managing medical information.
