# CoT-Redial

A large‑scale conversational recommendation dataset that augments real‑world product reviews with fine‑grained preference tags, dialogue templates, and Chain‑of‑Thought (CoT) rationales.  
The corpus is designed for training and benchmarking **LLM‑based recommendation agents** and supports academic research.

---

## 1. Key Features
- **Scale:** 151 K multi‑turn dialogues, 13 M tokens—two orders of magnitude larger than prior conversational recommendation corpora.  
- **Diversity:** High lexical diversity (Dist‑4 ≈ 0.997) reduces template artifacts.
- **Rich Annotations:** Includes item metadata, user preference tags, CoT reasoning traces.

---

## 2. Dataset Statistics

| Dataset          | #Dialogues | #Utterances | Domains                         | Dist‑3 | Dist‑4 |
|------------------|-----------:|------------:|---------------------------------|-------:|-------:|
| **CoT-Redial**   | **151 238**  | **807 629**  |  Amazon All-Beauty, Amazon Baby  | 0.9908 | 0.9972 |
| **REDIAL**       | 11 348     | 206 102     |  Movie                           | 0.9806 | 0.9922 |
| **TG‑REDIAL**    | 10 000     | 129 000     |   Movie                           |   —    |   —    |
| **DuRecDial**    | 10 200     | 156 000     |   Movie, music, food, etc.        |   —    |   —    |
| **INSPIRED**     |    999     | 21 124      |  Movie                           | 0.9743 | 0.9922 |
| **OpenDialKG**   | 15 000     | 91 000      |   Movie, book                     |   —    |   —    |
| **LLM‑REDIAL**   | 47 600     | 482 600     |  Movie, book, sport, etc.        |   —    |   —    |


<sup>†</sup> *Dist‑k ≡ (# unique k‑grams) / (# total k‑grams) computed over full dialogues. Higher is more diverse.*

