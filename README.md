News Insights Analyzer
News Insights Analyzer is an AI-powered tool that extracts, processes, and analyzes content from news articles. This tool allows users to input article URLs, ask questions, and receive AI-driven insights, particularly useful in finance and stock market research. The system leverages LangChain, OpenAI embeddings, and FAISS to provide accurate and meaningful responses.

📌 Features
1️⃣ Extracts news article content from a given URL.
2️⃣ Uses AI embeddings to understand the article’s key insights.
3️⃣ Allows users to ask questions about the article.
4️⃣ Retrieves relevant answers along with references to the source.
5️⃣ Provides a fast, interactive, and user-friendly experience using Streamlit.

🛠️ Technologies Used
Python – Core language for backend processing.

LangChain – Used for structured data extraction and query processing.

OpenAI Embeddings – Converts text into vector representations for efficient search.

FAISS (Facebook AI Similarity Search) – Enables fast and accurate similarity-based retrieval.

Streamlit – Builds an intuitive and interactive web interface for users.

🚀 Installation Guide
Step 1: Clone the Repository

First, open your terminal and clone this repository:
git clone https://github.com/Shyam-45/News-Insights-Analyzer.git
Then, navigate to the project folder:
cd News-Insights-Analyzer

Step 2: Install Dependencies
Ensure you have Python installed, then install the required libraries using:
pip install -r requirements.txt

Step 3: Set Up API Key
This project uses OpenAI’s API for embeddings.
Create a .env file in the project directory.
Open the .env file and add your OpenAI API key:
OPENAI_API_KEY=your_openai_api_key

Step 4: Run the Application
Once everything is set up, launch the tool using Streamlit:
streamlit run main.py

📝 How to Use
1️⃣ Enter a news article URL in the input field.
2️⃣ Ask a question related to the article’s content.
3️⃣ Receive AI-powered insights with reference links.
4️⃣ Explore various articles to analyze trends and financial news.
