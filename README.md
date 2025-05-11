# 📝 Spelling Correction Using Closest Match

A simple and efficient Python-based spelling correction tool developed during **BhashaTHON**. The system compares misspelled sentences against a list of correct sentences using string similarity and suggests the closest match. Ideal for learning basic Natural Language Processing (NLP) and string matching concepts.

---

## 📂 Project Structure

```
Spelling_Correction/
├── main.py                    # Core logic to compute closest match for each misspelled sentence
├── Problems.txt               # Input file with misspelled sentences
├── artificial.train.tgt       # Reference file with correct sentences
├── english_eval.corrected.txt # Output file with the final corrected sentences
├── requirements.txt           # Required Python packages
└── README.md                  # Project documentation
```

---

## 🔧 How It Works

1. Reads misspelled sentences from `Problems.txt`.
2. Reads correct reference sentences from `artificial.train.tgt`.
3. Uses **Levenshtein-based similarity** (via `difflib` or `rapidfuzz`) to find the closest correct sentence for each misspelled one.
4. Writes all the corrected outputs to `english_eval.corrected.txt`.

---

## 🚀 Getting Started

### 📦 Prerequisites

Make sure the following are installed:

- Python 3.x
- pip (Python package manager)

### 🔧 Installation

```bash
# Clone the repository
git clone https://github.com/Ladanividhi/Misspelling-Correction.git
cd Misspelling-Correction

# Install required packages
pip install -r requirements.txt
```

If you're not using `requirements.txt`, you can install manually:

```bash
pip install rapidfuzz
```

---

### ▶ Run the Project

Run the following command to execute the program:

```bash
python main.py
```

The output will be saved to:

```
english_eval.corrected.txt
```

---

## 🖥 Environment

- **OS**: Windows / Linux / macOS  
- **Python Version**: 3.x  
- **Libraries**:
  - [`rapidfuzz`](https://github.com/maxbachmann/RapidFuzz) (for efficient string similarity)
  - or Python’s built-in `difflib` if not using `rapidfuzz`

---

## 🎥 Demo

A video demonstration of the project is included in the repository:

```
Video.mp4
```

---

## 👨‍💻 Team: Code Crafters

- Ladani Vidhi  
- Dhyey Shah  
- Palak Kanjiya  
- Parth Chandegara  

---

## ✅ Key Takeaways

- Leverages simple yet powerful techniques to correct full sentences based on similarity.
- Lightweight and easy to understand—perfect for beginners in Python and NLP.
- Can be expanded further with grammar correction, language models, or context-aware suggestions.

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙏 Thank You

Thank you for taking the time to explore our project.  
Your interest and support mean a lot to us!

— **Team Code Crafters**
