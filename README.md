![image](https://github.com/Tashu014/FAQ-Chatbot/assets/87379455/07b34372-7436-4502-8232-5c27d95969fb)


# ChatGPT FAQ Bot:
Answers about application deadlines, required documents, tuition fees, scholarship opportunities, etc.

## Requirements
Language: Python  
Frameworks/Tools: OpenAI's ChatGPT, Pinecone or Weaviate.  
Skills: Basic Python, REST APIs, JSON, introductory NLP.

## Approach
1. Gathered data from json formatted.
2. Authentication, openai and weaviate.
3. Loaded the data
4. Embedded the extracted data.
5. Stored the embeddings into weaviate vector database.
6. chatgpt will retrieve the relevant chunks given predefined system prompt.
7. It will give answer to user's query as response.
