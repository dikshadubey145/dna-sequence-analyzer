# 🧬 DNA Sequence Analyzer

A beginner-friendly Python tool to analyze DNA sequences. Given a DNA string, this tool computes key biological properties — useful for learning bioinformatics concepts and Python scripting.

---

## 📋 Features

- ✅ Nucleotide frequency count (A, T, G, C)
- ✅ GC content percentage
- ✅ Reverse complement
- ✅ Transcription (DNA → RNA)
- ✅ Input validation (checks for invalid characters)

---

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- No external libraries needed (uses built-in Python only)

### Installation

```bash
# Clone the repository
git clone https://github.com/dikshadubey145/dna-sequence-analyzer.git

# Navigate into the project folder
cd dna-sequence-analyzer
```

### Usage

```bash
python dna_analyzer.py
```

You'll be prompted to enter a DNA sequence:

```
Enter DNA sequence: ATGCGCATTAGC
```

**Example output:**

```
=== DNA Sequence Analysis ===
Sequence Length : 12
Nucleotide Frequencies:
  A : 3
  T : 3
  G : 3
  C : 3
GC Content      : 50.00%
Reverse Complement: GCTAATGCGCAT
mRNA Transcript : AUGCGCAUUAGC
```

---

## 📁 Project Structure

```
dna-sequence-analyzer/
│
├── dna_analyzer.py      # Main script
├── README.md            # Project documentation
└── sample_sequences.txt # Sample DNA sequences to test with
```

---

## 🧠 Concepts Covered

| Concept | Description |
|---|---|
| GC Content | Percentage of G and C bases in a sequence |
| Reverse Complement | The complementary strand read 3'→5' |
| Transcription | Conversion of DNA to mRNA (T → U) |

---

## 📚 What I Learned

- String manipulation in Python
- Biological sequence analysis basics
- Writing clean, readable Python functions
- Using Git for version control

---

## 🔭 Future Improvements

- [ ] Read sequences from FASTA files
- [ ] Add translation (mRNA → protein)
- [ ] Support multiple sequences at once
- [ ] Add basic visualization with matplotlib

---

## 👩‍💻 Author

**Diksha Dubey**  
Biotechnology student | Bioinformatics enthusiast  
[GitHub](https://github.com/dikshadubey145) · [LinkedIn](https://linkedin.com/in/your-linkedin)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
