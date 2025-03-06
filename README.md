
# **AI-Powered Financial Insights and Advisory System Using LLMs & RAG**  

## **📌 Project Overview**  
This project leverages **Large Language Models (LLMs)** and **Retrieval-Augmented Generation (RAG)** to build an AI-driven financial insights system. It integrates real-time stock market data, economic indicators, financial news sentiment analysis, investment advisory, and an AI chatbot for company-specific queries. The system is built using **Python, LangChain, Hugging Face embeddings, Falcon 7B, and Zephyr 7B**, with a **vector database** for efficient retrieval.  

## **🚀 Features**  

1️⃣ **Financial Report Generator**  
   - Fetches company financials and market economic indicators using **Financial Modeling Prep API**.  
   - Pre-processes data and stores it in a CSV file.  
   - Loads data into a **vector database** using **Hugging Face embeddings**.  
   - Uses **Falcon 7B** in a **RAG-based QA Chain** to generate company reports.  

2️⃣ **Market Sentiment Analyzer**  
   - Fetches real-time **financial news** using **NewsAPI**.  
   - Performs sentiment analysis on stock market trends.  
   - Uses **Falcon 7B** in a **RAG-based QA Chain** to generate market insights.  

3️⃣ **Financial Investment Advisor**  
   - Loads financial advisory datasets (stocks, mutual funds, bonds) from **Kaggle**.  
   - Stores processed data in a **vector database** using **Hugging Face embeddings**.  
   - Uses **Falcon 7B** in a **RAG-based QA Chain** to provide AI-driven investment advice.  

4️⃣ **Financial GenAI Chatbot**  
   - Trained on company-specific **product FAQs and support data**.  
   - Uses **Zephyr 7B** in a **RAG-based architecture** for intelligent responses.  
   - Helps customers with **product recommendations** and **financial queries**.  

## **🛠️ Tech Stack**  
- **Programming Language**: Python  
- **Frameworks & Libraries**: LangChain, Hugging Face Transformers, Pandas, NumPy  
- **APIs Used**: Financial Modeling Prep API, NewsAPI  
- **LLMs**: Falcon 7B, Zephyr 7B (Open Source)  
- **Vector Database**: FAISS / ChromaDB  

## **🔧 Installation & Setup**  

1️⃣ **Clone the Repository**  
```bash
git clone https://github.com/yourusername/financial-insights-rag.git  
cd financial-insights-rag  
```  

2️⃣ **Install Dependencies**  
```bash
pip install -r requirements.txt  
```  

3️⃣ **Set Up API Keys**  
- Get API keys for **Financial Modeling Prep** and **NewsAPI**.  
- Store them in a `.env` file:  
  ```plaintext
  FINANCIAL_API_KEY=your_api_key_here  
  NEWS_API_KEY=your_api_key_here  
  ```  

4️⃣ **Run the Financial Report Generator**  
```bash
python financial_report.py  
```  

5️⃣ **Run Market Sentiment Analysis**  
```bash
python sentiment_analysis.py  
```  

6️⃣ **Run Investment Advisor**  
```bash
python investment_advisor.py  
```  

7️⃣ **Run Financial Chatbot**  
```bash
python chatbot.py  
```  

## **📊 Expected Outcomes**  
✔️ **Real-time financial reports** for stocks and market trends.  
✔️ **Sentiment analysis** based on the latest financial news.  
✔️ **Personalized investment advice** using AI.  
✔️ **AI-powered chatbot** for company product recommendations.  

## **📌 Future Improvements**  
- Integrate **Meta LLaMA** or **OpenAI GPT** for higher accuracy.  
- Implement **real-time data pipelines** for stock market trends.  
- Expand chatbot functionality for **multilingual financial queries**.  

## **📜 License**  
This project is **open-source** under the MIT License.  

---
