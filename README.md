# Day-103-Tokenization

###  Overview

**Tokenization** is a fundamental step in **Natural Language Processing (NLP)** where text is broken down into **smaller units called tokens**.

Tokens can be:

* Words
* Sentences
* Characters

---

##  What is Tokenization?

Tokenization converts raw text into a format that machines can understand.

Example:

```text id="t2k8p1"
Text: "I love AI"
Tokens: ["I", "love", "AI"]
```

---

##  Types of Tokenization

### 1️ Word Tokenization

Splits text into words.

```python id="w9k3p2"
from nltk.tokenize import word_tokenize

text = "I love AI"
tokens = word_tokenize(text)
print(tokens)
```

---

### 2️ Sentence Tokenization

Splits text into sentences.

```python id="s7m2k4"
from nltk.tokenize import sent_tokenize

text = "AI is amazing. It is powerful."
sentences = sent_tokenize(text)
print(sentences)
```

---

### 3️ Character Tokenization

Splits text into characters.

```python id="c3k9p6"
list("AI")
```

---

##  Why Tokenization is Important?

* Converts text into machine-readable format
* First step in NLP pipeline
* Helps in feature extraction

---

##  Use Cases

* Chatbots
* Sentiment analysis
* Text classification
* Machine translation

---

##  Key Takeaways

- Breaks text into smaller units
- Essential for NLP tasks
- Types: word, sentence, character

---

