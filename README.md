# arxiv_papers
# 🧠 arXiv Dataset Collector (Metadata + PDFs)

This project collects and organizes metadata and full-text PDF links from [arXiv.org](https://arxiv.org), focusing on research publications across fields like Computer Science, Quantitative Finance. It uses the official arXiv API and direct PDF links to build a structured dataset for analysis, ML training, or exploration.

---

## 📁 Contents

- `pdf_collection_ code.ipynb`  
  → Jupyter Notebook to collect metadata from the arXiv API using search queries and save it to a CSV file.

- `paper_metadata_ collection.ipynb`  
  → Notebook that reads the metadata CSV, downloads PDFs in batches, and marks progress in the file.

- `q_fin_arxiv.csv`  
  → CSV file containing structured metadata for arXiv papers (title, abstract, id, categories, date, etc.) in feild of quantitative finance.

- `axive_cs_metadata.csv`  
  → file containing structured metadata for arXiv papers (title, abstract, id, categories, date, etc.) in feild of computer science.

    Link: [huggingface](https://huggingface.co/datasets/gowthamgoli/arxive_papers)

---

## 🚀 Features

- 🔎 Fetches paper metadata via the [arXiv API](https://info.arxiv.org/help/api/index.html)
- 📄 Builds PDF links and downloads papers in organized batches
- ✅ Tracks which files have been successfully downloaded
- 🐼 Built with `pandas`, `requests`, `tqdm` for smooth progress handling

---

## 🧪 Example Use Cases

- Pretraining datasets for LLMs and language models
- Research analysis or citation tracking
- Offline paper archives
- Dataset curation for academic ML projects

---

## 📜 License

This project is released under the **[CC0 1.0 Universal (Public Domain Dedication)](https://creativecommons.org/publicdomain/zero/1.0/)**.

> You are free to copy, modify, distribute, and use the data and code for any purpose, without asking permission.

---

## 🙋‍♂️ Credits

- Author: *G Gowtham*
- Data source: [arXiv.org](https://arxiv.org)

---

## 💬 Feedback or Contributions

Feel free to open issues, pull requests, or forks. This repo is meant to be freely usable and modifiable by the research and open-source communities.

