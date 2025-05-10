# Exampeer Business Automation - searchKeywordsCategorize 🤖📚

**searchKeywordsCategorize** is a Python-based automation tool designed for **Exampeer**. The script helps categorize a list of URLs and keywords into predefined segments like **JEE**, **Government Exams**, **NEET Exams**, and **Other**. This tool improves efficiency in organizing data for targeted exam preparation resources.

---

## 🧰 Features

- 📂 Categorizes keywords and URLs into categories: **JEE**, **Government Exams**, **NEET Exams**, and **Others**  
- 📊 Generates a detailed report in `report.xlsx`  
- 📝 Easy to use with simple text files (`jee.txt`, `govt.txt`, `others.txt`, etc.) for input  
- 📸 Includes images and error notifications for easy understanding of process flow  
- 🛠️ Handles errors effectively and provides error logs

---

## 📁 Project Structure

searchKeywordsCategorize/  
│  
├── main.py               # Main script for categorizing URLs and keywords  
├── govt.txt              # Input file containing Government exam-related keywords  
├── jee.txt               # Input file containing JEE exam-related keywords  
├── others.txt            # Input file for other miscellaneous keywords  
├── wrong.txt             # Input file for incorrect or unclassified data  
├── report.xlsx           # Output report after categorization  
├── try.xlsx              # Test data for validation  
├── pics/                 # Folder for images (icons and notifications)  
│   ├── error.ico         # Error icon  
│   ├── error.jpg         # Error notification image  
│   └── notification.jpg  # Notification image  
├── icon.ico              # Application icon  
└── README.md             # Project documentation (this file)

---

## 🛠️ Requirements

- Python 3.6+  
- pandas  

Install dependencies:
``` bash
  pip install pandas
```

## 🖥️ How to Use

1. Place your **URLs and Keywords** in the appropriate `.txt` files: `jee.txt`, `govt.txt`, `others.txt`, and `wrong.txt`.  
2. Run the script:
``` bash
python main.py
```

3. The script will read the data from the text files and categorize it into different segments based on the keywords.  
4. The categorized data will be saved in the `report.xlsx` file for easy analysis.  
5. Check the `pics/` folder for any error notifications during the categorization process.

---

## 🔍 How It Works

- **main.py** processes the input data from `.txt` files and matches keywords with predefined categories (JEE, Government Exams, NEET, Others).  
- The script analyzes the URLs and keywords and sorts them accordingly.  
- A report is generated with categorized data in `report.xlsx`.  

---

## ⚠️ Disclaimer

This tool is intended for **internal business automation purposes** and may not be suitable for general public use without modifications.  
Use responsibly and ensure compliance with data usage and privacy policies.

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙋‍♂️ Author

Developed by @princemehta-git  
https://github.com/princemehta-git

