# Brown-Corpus-Exploration
Exploration of the Brown Corpus using NLTK for category analysis and text extraction to understand structured NLP datasets.
# 📚 Brown Corpus Exploration using NLTK

## 📌 Overview

This project explores the **Brown Corpus**, a widely used dataset in Natural Language Processing (NLP), using Python and NLTK.
It demonstrates how to access categorized text data, analyze categories, and extract sample words for understanding structured linguistic datasets.

---

## ⚙️ Technologies Used

* Python
* NLTK (Natural Language Toolkit)

---

## 🚀 Features

* Download and use Brown Corpus dataset
* Retrieve all available text categories
* Count total categories
* Extract sample words from specific categories (e.g., news)

---

## 📊 Dataset

The **Brown Corpus** is a collection of text documents categorized into different genres such as:

* News
* Fiction
* Government
* Editorial
* Romance
* Adventure

---

## 🧠 Workflow

1. Install and import NLTK
2. Download Brown Corpus
3. Retrieve available categories
4. Count number of categories
5. Extract sample words from a selected category

---

## ▶️ How to Run

1. Install NLTK:

```id="bc1"
pip install nltk
```

2. Run the following code:

```id="bc2"
import nltk
from nltk.corpus import brown

nltk.download('brown')

categories = brown.categories()
print(categories)

print("Total categories:", len(categories))

print(brown.words(categories='news')[:20])
```

---

## 📈 Output

* List of categories in the dataset
* Total number of categories
* Sample words from selected category

---

## 💡 Applications

* Text analysis
* NLP dataset exploration
* Language modeling basics
* Category-based text classification

---

## 🙋‍♀️ Author

**Anshika Raikwar**
B.Tech ECE Student | 
Passionate about learning and building Real world problem solving projects
---

## ⭐ Future Improvements

* Perform word frequency analysis
* Compare different categories
* Visualize data using graphs
* Apply machine learning for text classification

