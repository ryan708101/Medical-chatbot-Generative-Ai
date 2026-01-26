## Medical Chatbot with Langchain and Pinecone

This project builds a medical chatbot that retrieves information from a medical PDF book and utilizes Langchain for processing and Pinecone for efficient information retrieval.


![[Web Page of The Chat App]](https://raw.githubusercontent.com/Azazel0203/Medical_ChatBot/main/static/web_page.jpg)


###  Features

* **Medical Knowledge Base:** Extracts and organizes medical information from a PDF book.
* **Langchain Integration:** Uses Langchain libraries to process user queries and match them with relevant information from the knowledge base. 
    * Specifically, Langchain's text processing capabilities will be leveraged to clean and prepare the medical text for further analysis.
* **Llama2 Embeddings:** Employs the powerful Llama2 model from Hugging Face to generate contextual embeddings for both user queries and medical text snippets. This allows for semantic matching and retrieval of relevant information even when phrased differently.
* **Pinecone Vector Database:** Stores the generated embeddings in a Pinecone vector database for efficient retrieval. This enables fast and scalable search of the medical knowledge base.
* **Chatbot Interface:** Provides a user-friendly interface (text-based or potentially voice-based) for users to interact with the chatbot and ask medical questions.
* **HTML and CSS Design:** The chat interface is designed using HTML and styled using CSS to provide an intuitive and visually appealing user experience.
* **Flask Backend:** The application backend is built using Flask, a lightweight web framework for Python, to handle user requests and interact with the chatbot.
* **Real-time Messaging:** Users can communicate with the chatbot in real-time, receiving instant responses to their queries.

###  Technical Stack

* **Langchain:** A Python library for Natural Language Processing (NLP) workflows, offering modules for text processing, embedding generation, and information retrieval.
* **Hugging Face Transformers:** Provides access to pre-trained NLP models like Llama2 for generating contextual embeddings.
* **Pinecone:** A vector database service enabling efficient storage and retrieval of high-dimensional data like embeddings.
* **Additional Libraries:** Depending on the chosen interface (text-based or voice-based), additional libraries like NLTK or spaCy might be used for further text processing and chatbot functionalities.
* **Flask:** A lightweight web framework for Python used to develop the chatbot's interface and handle user requests.
