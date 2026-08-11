# ⚡ Selenium Web Automation & Data Extraction Suite

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB.svg?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![Selenium](https://img.shields.io/badge/Selenium-WebDriver-43B02A.svg?style=flat&logo=selenium&logoColor=white)](https://www.selenium.dev/)
[![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-4-00599C.svg?style=flat)](https://www.crummy.com/software/BeautifulSoup/)

An automated web automation and scraping tool developed using **Python** and **Selenium WebDriver**. This project automates browser operations, handles search queries, navigates dynamic web pages, and extracts structured data for analysis.

---

## 🌟 Key Features

- **Automated Browser Interaction**: Programmatically opens browsers, submits search queries, and navigates pagination.
- **Dynamic Waiting Strategy**: Implements `WebDriverWait` and `expected_conditions` to reliably handle AJAX/JavaScript-rendered content.
- **Structured Data Extraction**: Parses HTML elements using CSS Selectors and XPath to extract clean text, links, and tables.
- **Data Export**: Saves extracted information into structured CSV and JSON formats.
- **Error & Exception Handling**: Includes fallback handling for missing elements, timeouts, and stale element reference exceptions.

---

## 🛠️ Tech Stack

- **Core Language**: Python 3.10+
- **Automation Framework**: Selenium WebDriver (`selenium`)
- **HTML Parsing**: BeautifulSoup4 (`bs4`)
- **Data Processing**: Pandas (`pandas`)

---

## 🚀 Quickstart & Installation

```bash
# 1. Clone the repository
git clone https://github.com/JaiswalKritika/selenium-web-automation.git
cd selenium-web-automation

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the automation script
python automation_script.py
```

---

## 📂 Project Structure

```
selenium-web-automation/
├── automation_script.py # Main web automation logic
├── utils/               # Scraper helpers and driver initializers
│   └── driver_setup.py
├── output/              # Extracted datasets (CSV/JSON)
├── requirements.txt     # Dependencies
└── README.md            # Documentation
```

---

## 👤 Author

**Kritika Jaiswal**  
- GitHub: [@JaiswalKritika](https://github.com/JaiswalKritika)  
- LinkedIn: [Kritika Jaiswal](https://www.linkedin.com/in/kritika-jaiswal205)
