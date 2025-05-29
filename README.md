# 🧠 Awarded Minds: Mapping the Literary Web

Explore the hidden connections between some of the world’s most celebrated writers. This project uses **network science**, **natural language processing**, and **Wikipedia data mining** to build a network of authors linked by shared **literary awards**, revealing genre patterns, influential figures, and thematic clusters.

---

## 📁 Project Structure

```
.
├── Authors/                   # Raw Wikipedia text files of authors
├── cleanFiles/               # Cleaned text files (tokenized, lemmatized)
├── Authors_Details.csv       # Metadata of authors (original version)
├── Authors_DetailsNew.csv    # Updated metadata with award links etc.
├── countries.csv             # Country reference data
├── Data_Set_S1.txt           # Supplementary dataset (raw or results)
├── Init.ipynb                # Initial setup notebook
├── notebook.ipynb            # Main analysis notebook
├── requirements.txt          # Python dependencies
```

---

## 🎯 Project Goals

1. **Construct a network of writers** based on shared awards
2. **Analyze genre-specific text** with TF, TF-IDF word clouds
3. **Detect communities** using Louvain modularity
4. **Perform sentiment analysis** (VADER + LabMT) at writer and group levels
5. **Visualize the network** by genre and community
6. Compare to a **random network** to interpret network structure

---

## 📊 Key Insights

- **Nodes**: 1,075 authors
- **Edges**: 41,816 award-based connections
- **Genres**: Playwrights, Poets, Fantasy authors, Historical Novelists
- **Top Authors**: Ursula K. Le Guin, Neil Gaiman, Stephen King, Louise Erdrich
- **Most Frequent Awards**: Pulitzer Prize, National Book Award, Nobel Prize in Literature
- **Communities Detected**: 10 with modularity score ≈ **0.55**

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/awarded-minds.git
cd awarded-minds
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the notebook

Start with `notebook.ipynb` to follow the entire analysis pipeline.

---

## 🧰 Requirements

Key libraries include:

- `networkx`
- `powerlaw`
- `vaderSentiment`
- `wordcloud`
- `nltk`
- `python-louvain`
- `fa2`
- `pandas`, `numpy`, `matplotlib`

Full list in `requirements.txt`.

---

## 📎 Credits

Project created by Pranjal Garg and Fotios Kots as a deep dive into literary networks, using open data from Wikipedia and open-source tools.

---

## 📖 License

This project is licensed under the MIT License. See `LICENSE` for more details.

---

## 🌐 Inspiration

Inspired by the idea that **literature reflects the evolution of human consciousness**, this project treats writers as nodes in a universal mind—connected by recognition, genre, and time.
