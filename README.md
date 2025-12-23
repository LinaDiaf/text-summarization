# Text Summarization with PEGASUS on SAMSum Dataset

This project demonstrates **text summarization** using the PEGASUS model from Hugging Face Transformers, trained and evaluated on the **SAMSum dataset** of dialogues and summaries.

---

## 📂 Project Structure

- `TextSummarization.ipynb` – Jupyter notebook containing all the steps:
  - Installing required libraries
  - Loading and preprocessing the dataset
  - Training PEGASUS model
  - Evaluating the model with ROUGE scores
  - Generating summaries on sample dialogues
- `pegasus-samsum-model/` – Saved PEGASUS model (not included in repo, download separately)
- `tokenizer/` – Saved tokenizer (not included in repo, download separately)

---

## 🛠 Technologies
- Python
- Hugging Face Transformers (PEGASUS)
- PyTorch
- Datasets & Evaluate libraries

---

## ✨ Example

**Dialogue:**
Hannah: Hey, do you have Betty's number?
Amanda: Lemme check
Hannah: <file_gif>
Amanda: Sorry, can't find it.
Amanda: Ask Larry
Hannah: I don't know him well
Hannah: <file_gif>
Amanda: Don't be shy, he's very nice
Hannah: If you say so..
Hannah: I'd rather you texted him
Amanda: Just text him 🙂
Hannah: Urgh.. Alright
Hannah: Bye
Amanda: Bye bye


**Reference Summary:**
Amanda can't find Betty's number. Larry called her last time they were at the park together. Hannah wants Amanda to text Larry. Amanda will text Larry.
