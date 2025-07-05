# Smart-AI-Chatbot-with-Contextual-Responses-and-Web-Search-Integration

This is an intelligent chatbot project named **Sam** that uses deep learning, sentence embeddings, and external web sources to respond contextually and informatively to user queries. The bot can handle casual conversations, answer fact-based questions using **Wikipedia** or **Google search scraping**, and improve its replies based on intent classification.

---

 **Features**

- Intent-based conversational chatbot using custom patterns and responses
- Built on PyTorch with a feedforward neural network trained on sentence embeddings
- Integrates Wikipedia to provide detailed summaries of real-world questions
- Uses `googlesearch-python` and BeautifulSoup to scrape top search result content
- Responds dynamically to unknown queries with intelligent fallback logic
- Embeddings generated using `sentence-transformers` for high-quality language understanding

---

**Technologies Used**
- Python
- PyTorch
- SentenceTransformers (`all-MiniLM-L6-v2`)
- BeautifulSoup
- Wikipedia API
- Google Search API (`googlesearch-python`)
- Requests

1. **Install dependencies**
pip install torch torchvision torchaudio
pip install sentence-transformers
pip install wikipedia
pip install googlesearch-python
pip install beautifulsoup4
pip install requests

**Note**
1) The bot first tries to classify your intent using trained neural network.
2) If confidence is low, it uses Wikipedia and Google to find answers.
3) The bot even responds to love, praise, jokes, and boredom with witty replies.
