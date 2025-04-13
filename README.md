# 🎮 CineFinder

A semantic search engine to help users discover movies and TV shows using natural language queries. CineFinder uses vector embeddings and FAISS indexing to provide fast, intelligent, and context-aware recommendations.

---

## 📌 Features
- 🔎 **Semantic Search** with vector similarity using FAISS
- 🧠 Embeddings generated from movie titles and descriptions
- ⚡ Fast retrieval from a dataset of 6K+ movie entries
- 📊 Interactive Jupyter Notebook for exploration and testing

---

## 🧱 Project Structure

```
CineFinder/
├── Movie_Wiki_Dataset.ipynb    # Notebook to clean data, embed, and search
├── movie_data.pkl              # Pickled movie metadata
├── movie_faiss.index           # FAISS vector index for fast search
├── requirements.txt            # Python dependencies
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/ShouryaAswal/CineFinder.git
cd CineFinder
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Notebook

```bash
jupyter notebook Movie_Wiki_Dataset.ipynb
```

> 💡 Use the notebook to embed text, build the FAISS index, and run semantic queries like:

```python
search("time travel thriller with a twist ending")
```

---

## 🔧 Tech Stack

- **Python** & **Jupyter Notebook**  
- **FAISS** for vector similarity search  
- **Pickle** for data serialization  
- **Scikit-learn / Transformers** (optional for embeddings)

---

## 📬 Contact

For questions or collaborations:

- 📧 [shouryaaswal@hotmail.com](mailto:shouryaaswal@hotmail.com)
- 🌐 [github.com/ShouryaAswal](https://github.com/ShouryaAswal)

---

> 🎥 CineFinder is an experimental semantic search engine — perfect for exploring how AI can enhance content discovery in entertainment platforms.

