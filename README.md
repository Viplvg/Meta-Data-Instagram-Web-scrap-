# Meta-Data-Instagram-Web-scrap-
Web Scrap script

Instagram Research Data Scraper (Selenium)
For Windows & macOS
This notebook scrapes publicly available Instagram post metadata (captions, hashtags, post URLs, etc.) using Selenium and Google Chrome for research and academic purposes. It relies on Selenium to automate Chrome and therefore requires a few prerequisites before running. The notebook imports Selenium, ChromeDriver Manager, and standard Python libraries.

**1. System Requirements**

Requirement	Version
Python	3.10 or newer (Recommended: 3.11 or 3.12)
Google Chrome	Latest Stable Version
Jupyter Notebook	Latest
Internet Connection	Required
Operating System	Windows 10/11 or macOS


**2. Install Python**

Download and install Python:
https://www.python.org/downloads/
During installation on Windows:
✅ Check "Add Python to PATH"

python --version
python3 --version


**3. Install Google Chrome** 

Download: https://www.google.com/chrome/
Always keep Chrome updated.


**4. Install Git (Recommended)**

Git is useful for cloning repositories and version control.
Windows & macOS:
https://git-scm.com/downloads
Verify: git --version


**5. Install Jupyter Notebook**

Open Terminal (macOS) or Command Prompt / PowerShell (Windows)
Install: pip install notebook
Launch : jupyter notebook


**6. Create Virtual Environment (Recommended)**

Windows: python -m venv venv
venv\Scripts\activate

macOS :python3 -m venv venv
source venv/bin/activate


**7. Install Required Python Packages**

Run:
pip install selenium webdriver-manager
The notebook only depends on:
1. selenium
2. webdriver-manager
The remaining modules are part of Python's standard library:
1. csv
2. os
3. re
4. time
These are already included with Python.


**8. Verify Installation**

Run:
pip list
  You should see:
1. selenium
2. webdriver-manager
3. notebook


**9. ChromeDriver**

No manual installation is required.
This project uses:
webdriver-manager


**10. Running the Notebook**

Start Jupyter:

- jupyter notebook

Open:

- Test3.4.ipynb











