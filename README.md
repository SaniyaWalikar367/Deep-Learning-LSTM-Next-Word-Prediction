# LSTM Next Word Prediction using PyTorch

## 📌 Project Overview

This project implements **Next Word Prediction using LSTM (Long Short-Term Memory)** in **PyTorch**.
The model learns sentence patterns and predicts the **next word** based on previous words.

Example:

Input:

```
the dog
```

Output:

```
runs fast today
```

---

## 🧠 What is LSTM?

LSTM (Long Short-Term Memory) is a type of **Recurrent Neural Network (RNN)** used for **sequence learning**.
It maintains two memories:

* **Hidden State** → Short-term memory (current context)
* **Cell State** → Long-term memory (important past information)

This helps the model understand sentence meaning and predict next words.

---

## 🏗️ Model Architecture

Input Words → Embedding Layer → LSTM Layer → Linear Layer → Output

### Layers Used

* **Embedding Layer** — Converts words into vectors
* **LSTM Layer** — Learns sequence relationships
* **Linear Layer** — Predicts next word

---

## ⚙️ Technologies Used

* Python
* PyTorch
* LSTM
* NLP
* spaCy Embeddings

---

## 📂 Project Workflow

### Step 1: Data Preparation

Sentences converted into input-target pairs:

```
I → love  
I love → machine  
I love machine → learning  
```

---

### Step 2: Model Training

Model learns:

* Word relationships
* Sentence structure
* Next word prediction

---

### Step 3: Prediction

Input:

```
the dog
```

Predicted Output:

```
runs
fast
today
```

Final Sentence:

```
the dog runs fast today
```

---

## 🔑 Key Features

* LSTM based next word prediction
* spaCy pretrained embeddings
* Padding for variable sequences
* DataLoader for batch training
* Professional NLP pipeline

---

## 📊 Input Shape

```
(batch_size , sequence_length)
```

Example:

```
[[the , dog , runs]]
```

---

## 📈 Output Shape

```
(batch_size , vocab_size)
```

Model predicts probability of next word.

---

## 🚀 Applications

* Text Generation
* Chatbots
* Auto-completion
* NLP Applications
* Language Modeling

---

## 📎 Future Improvements

* Add larger dataset
* Compare GRU model
* Add Transformer model
* Use pretrained models

---

## Author

Saniya Walikar
Deep Learning | NLP | PyTorch
