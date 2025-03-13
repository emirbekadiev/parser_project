# 🚗 Car Parser Project

![Python Version](https://img.shields.io/badge/python-3.13%2B-blue)

A project designed to scrape car listings from **m.mashina.kg** and store the data in a structured format.

---

## 📚 Table of Contents

| Section | Description |
|---------|------------|
| [Project Overview](#-project-overview) | Overview of the project's purpose and structure. |
| [Prerequisites](#-prerequisites) | Requirements for running the project. |
| [Setup Instructions](#-setup-instructions) | Step-by-step installation guide. |
| [Running the Project](#-running-the-project) | How to execute the scripts. |
| [Project Structure](#-project-structure) | Directory and file organization. |
| [Contributing](#-contributing) | How to contribute to the project. |
| [License](#-license) | License information. |

---

## 🚀 Project Overview

| Script | Description |
|--------|------------|
| **`get_links.py`** | Fetches car listing URLs from **m.mashina.kg** and saves them in `data/links.json`. |
| **`main.py`** | Scrapes detailed car information and saves it in `data/dataset.jsonl`. |
| **`pars_block.py`** | Contains helper functions to extract relevant car details from HTML content. |
| **`requirements.txt`** | Lists required Python packages for the project. |

---

## 🛠 Prerequisites

| Requirement | Description |
|------------|-------------|
| **Python 3.13+** | The project requires Python 3.13 or later. Download from [python.org](https://www.python.org/). |
| **Virtual Environment** | A virtual environment is recommended for managing dependencies. |

---

## 📦 Setup Instructions

| Step | Command | Description |
|------|---------|-------------|
| **1. Clone the Repository** | `git clone https://github.com/yourusername/car-parser-project.git && cd car-parser-project` | Downloads the project to your local machine. |
| **2. Activate Virtual Environment** | `source my_env/bin/activate` | Activates the provided virtual environment (`my_env`). |
| **3. Install Dependencies** | `pip install -r requirements.txt` | Installs required Python packages. |

---

## 📜 Installed Packages

| Package | Purpose |
|---------|---------|
| `tqdm` | Displays progress bars. |
| `beautifulsoup4` | Parses HTML content. |
| `requests` | Handles HTTP requests. |

---

## ▶️ Running the Project

| Step | Command | Output |
|------|---------|--------|
| **1. Fetch Car Listing URLs** | `python get_links.py` | Saves URLs to `data/links.json`. |
| **2. Scrape Car Details** | `python main.py` | Saves scraped data in `data/dataset.jsonl`. |
| **3. View Data** | Open `data/dataset.jsonl` | Contains structured car listing details. |

---

## 📂 Project Structure

| Path | Description |
|------|-------------|
| `car-parser-project/` | Root directory of the project. |
| `├── data/` | Directory for storing data files. |
| `│   ├── links.json` | Contains URLs of car listings. |
| `│   └── dataset.jsonl` | Contains scraped car data. |
| `├── my_env/` | Virtual environment directory. |
| `├── get_links.py` | Script to fetch car listing URLs. |
| `├── main.py` | Script to scrape car details. |
| `├── pars_block.py` | Helper functions for parsing HTML. |
| `├── requirements.txt` | List of dependencies. |
| `└── pyvenv.cfg` | Virtual environment configuration. |

---

## 🤝 Contributing

| Step | Command | Description |
|------|---------|-------------|
| **1. Fork the repository** | - | Create a copy of the project. |
| **2. Create a feature branch** | `git checkout -b feature/YourFeatureName` | Work on a new feature. |
| **3. Commit changes** | `git commit -m "Add some feature"` | Save your modifications. |
| **4. Push to GitHub** | `git push origin feature/YourFeatureName` | Upload your branch. |
| **5. Open a Pull Request** | - | Submit your changes for review. |

---
