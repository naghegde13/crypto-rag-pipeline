# 🧠 Crypto RAG Pipeline

A Retrieval-Augmented Generation (RAG) system for answering questions based on the latest cryptocurrency news from CoinTelegraph.

---

## 📁 Files Included

- `crypto_advisor_with_news.py` – Main script with scraping, embedding, and querying logic
- `data/snews.newsmetadata.csv` – Example news data with metadata
- `.gitignore` – Standard cleanup file

---

## 🔧 Setup Instructions

1. **Install dependencies**

Create a virtual environment (optional) and run:

```bash
pip install -r requirements.txt
```


## 2. **Prepare your API key**

You will need an OpenAI or HuggingFace API key.
Set it like this in your script or using an environment variable:

```
os.environ["OPENAI_API_KEY"] = "your-key-here"
```

## 3. **Set your data path**

In the script, update the data file location if needed:
```
df = pd.read_csv("data/sample_articles.csv")
```

## 4. **Run the script**
```
python crypto_advisor_with_news.py
```
You’ll be prompted to enter a question like:

🔎 Ask a question about recent crypto news: What’s the latest on Bitcoin ETFs?
