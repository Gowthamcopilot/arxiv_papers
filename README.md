# arxiv_papers
# 🧠 arXiv Dataset Collector (Metadata + PDFs)

This project collects and organizes metadata and full-text PDFs from [arXiv.org](https://arxiv.org), focusing on research publications across fields like Computer Science, Quantitative Finance. It uses the official arXiv API and direct PDF links to build a structured dataset for analysis, ML training, or exploration.

---

## 📁 Contents

- `metadata_collector.ipynb`  
  → Jupyter Notebook to collect metadata from the arXiv API using search queries and save it to a CSV file.

- `pdf_downloader_batch.ipynb`  
  → Notebook that reads the metadata CSV, downloads PDFs in batches, and marks progress in the file.

- `metadata.csv`  
  → CSV file containing structured metadata for arXiv papers (title, abstract, id, categories, date, etc.).

- `pdf_links_scraped.csv`  
  → Same metadata CSV with additional fields like direct PDF links and a boolean `is_scraped` column to track download status.

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

- Author: *[Your Name or GitHub handle]*
- Data source: [arXiv.org](https://arxiv.org)

---

## 💬 Feedback or Contributions

Feel free to open issues, pull requests, or forks. This repo is meant to be freely usable and modifiable by the research and open-source communities.

