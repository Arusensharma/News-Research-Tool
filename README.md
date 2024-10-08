# News-Research-Tool
## Context Aware Bot: News Research Tool
This is a user-friendly news research tool designed for effortless information retrieval. Users can input article URLs and ask questions to receive relevant insights from the stock market and financial domain.

### Features
- Load URLs or upload text files containing URLs to fetch article content.
- Process article content through LangChain's UnstructuredURL Loader
- Construct an embedding vector using OpenAI's embeddings and leverage FAISS, a powerful similarity search library, to enable swift and effective retrieval of relevant information
- Interact with the LLM's (Chatgpt) by inputting queries and receiving answers along with source URLs.

### How To Use This Project
1. Run "pip install -r requirements.txt"
2. Get an API key from OpenAI and paste it in the .env file between the ''.
3. Open terminal and change directory to the News-Research-tool folder.
4. Run the command - streamlit run main.py. The application will open in a new tab in the browser.
5. Enter the URLs and press Enter for each URL.
6. Enter the question you want to ask to the Chatbot related to the articles.
7. Click on Process URLs and wait for the answers.
