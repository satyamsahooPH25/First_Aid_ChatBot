https://github.com/user-attachments/assets/efc5d9c7-b42d-41c0-b121-49096345da3b
# First-Aid Chatbot 🤖💡

This project integrates natural language processing and machine learning to deliver quick and reliable first-aid guidance. The chatbot offers real-time responses to inquiries by retrieving relevant information from a first-aid manual, differentiating between emergency and non-critical cases through sentiment analysis.

## 🔑 Core Functionalities:

- **Precise Embeddings Generation**:  
  Utilized the **'all-MiniLM-L6-v2'** model for creating embeddings from the First Aid Manual. These embeddings are stored in **ChromaDB**, enabling fast and contextually relevant information retrieval.

- **Retrieval-Augmented Generation (RAG)**:  
  Implemented the **RAG architecture** to generate responses using **GPT-2**. The chatbot retrieves embeddings and generates nuanced, accurate answers in real-time.

- **Sentiment Analysis**:  
  Incorporated **sentiment analysis** to differentiate between emergency and non-critical inquiries. This enables the chatbot to adapt its responses based on the urgency, ensuring appropriate communication in high-stakes situations.

## 📚 Use Case:
This project represents an innovative use of NLP and AI in the healthcare domain, providing instant access to essential first-aid information. Whether in emergencies or casual inquiries, the chatbot helps users get the right information when they need it most.
