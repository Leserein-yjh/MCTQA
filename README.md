
# 🧠 MCTQA: Multi-granularity Complex Temporal Question Answering

This repository documents the MCTQA model for multi-granularity temporal knowledge graph question answering.

Due to file size limitations on GitHub, **all source code, data, and environment setup have been packaged and uploaded externally**.

---

## 📦 Download Full Project (Code + Data + Environment)

The full experiment package is available here:

🔗 **[Download MCTQA_Code.zip from Google Drive](https://drive.google.com/file/d/1frrgDt0S0xUlc6coV2SEY3DBs7QaRSaS/view?usp=sharing)**

> Please make sure to **extract** the archive after downloading:
> ```bash
> unzip MCTQA_Code.zip
> cd MCTQA_Code
> ```

The archive contains:

- `MCTQA/` : all `.py` files for training and evaluation  
- `data/` : dataset samples  
- `environment.yml` : Conda environment for reproducibility  
- README instructions  

> ✅ The package is structured for easy reproducibility, especially for reviewers of our [Conference Name] 2025 submission.

---

## ⚙️ Environment Setup

```bash
conda env create -f environment.yml
conda activate yjhQA
```

---

## 🚀 Run the Code

```bash
cd MCTQA
python ./train_qa_model.py --model MCTQA
```

---
