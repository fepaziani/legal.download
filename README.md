# legal.download

![Project Banner](https://socialify.git.ci/fepaziani/legal.download/image?description=1&language=1&name=1&owner=1&pattern=Solid&stargazers=1&theme=Dark)

## 📌 Overview
**legal.download** automates the retrieval of legal documents using **Selenium** for authentication and **requests** for API interactions. It dynamically fetches session cookies, retrieves document lists based on process IDs, downloads `.zip` files, and processes them in parallel using `ThreadPoolExecutor`.

## 🚀 Features
- **Automated authentication** using Selenium.
- **Session management** with dynamically fetched cookies.
- **API integration** for retrieving document lists.
- **Multi-threaded downloads** using ThreadPoolExecutor.
- **Automated `.zip` extraction** and processing.

## 🛠 Tech Stack
- **Automation**: Selenium, Requests
- **Parallel Processing**: ThreadPoolExecutor
- **File Handling**: Zipfile, OS
- **Python Version**: 3.x

## 📂 Project Structure
```
legal.download/
│-- code/                 # Source code
│-- README.md             # Project documentation
│-- .gitignore            # Git ignore file
|-- requirements.txt      # Required Modules to Run the Program
```

## 🚀 Getting Started
### 1️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 2️⃣ Run the Script
```bash
python code/main.py
```

## 📌 Example Workflow
### 📝 Input
- List of **process IDs** to retrieve documents for.
- Authentication details handled via Selenium.

### 🔄 Processing
1. **Authenticate** via Selenium.
2. **Fetch session cookies** dynamically.
3. **Retrieve document lists** using API calls.
4. **Download and extract `.zip` files**.
5. **Process files in parallel** for efficiency.

### ✅ Output
- Extracted and processed legal documents from the downloaded `.zip` files.

## 🤝 Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

## 📜 License
This project is licensed under the MIT License.

## 📊 Project Stats
![GitHub Repo stars](https://img.shields.io/github/stars/fepaziani/legal.download?style=social)
![GitHub forks](https://img.shields.io/github/forks/fepaziani/legal.download?style=social)
![GitHub issues](https://img.shields.io/github/issues/fepaziani/legal.download)
![GitHub last commit](https://img.shields.io/github/fepaziani/legal.download)

---

*Developed by fepaziani*

