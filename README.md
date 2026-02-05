# 📊 WhatsApp Chat Analysis & Visualization

This project analyzes raw WhatsApp chat exports and transforms unstructured text data into meaningful insights using Python.  
It focuses on understanding **user behavior, activity patterns, and communication trends** within a WhatsApp group through data preprocessing and visual analytics.

---

## 🚀 Key Features

- 📂 Reads WhatsApp `.txt` chat exports
- 🧹 Cleans and structures raw chat data
- 👤 Separates users and group notifications
- ⏰ Extracts detailed date & time features
- 📊 Generates multiple insightful visualizations
- 😄 Analyzes emoji usage
- 🔍 Allows user-specific (chatter-wise) analysis

---

## 🛠️ Tech Stack

- **Python**
- **Pandas** – data manipulation and analysis
- **Regular Expressions (re)** – text preprocessing
- **Matplotlib & Seaborn** – data visualization
- **Emoji** – emoji extraction (installed at runtime in Google Colab)

---

## 📌 How the Project Works

1. The WhatsApp chat export (`.txt`) is read as raw text
2. Regular Expressions are used to:
   - Identify timestamps
   - Split messages correctly
3. User names and message content are separated
4. Data is stored in a Pandas DataFrame
5. Date-time components are extracted for analysis
6. Visualizations are generated to reveal insights

---

## 📊 Visualizations Included

- Top active users (bar chart)
- Messages per month
- Hour-wise activity analysis
- Day vs hour activity heatmap
- User contribution pie chart
- Message length distribution
- Emoji usage visualization
- User-specific activity analysis

---

## 😄 Emoji Analysis (Google Colab Compatible)

Since Google Colab does not include the emoji library by default, it is installed at runtime:

```python
!pip install emoji
