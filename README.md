🚗 Traffic Penalty Scraper
This project automates the retrieval of governmental traffic penalties for multiple cars using Python and Selenium. The script reads car plate numbers from an Excel sheet, scrapes penalty data from the official government website, and stores the results in a database for further analysis.

📌 Features
✅ Bulk processing: Reads multiple plate numbers from an Excel sheet
✅ Automated web scraping: Uses Selenium to fetch real-time penalty data
✅ Database integration: Saves penalties into a structured database
✅ Error handling: Handles website delays and invalid plate numbers

🛠 Tech Stack
Python 🐍
Selenium 🌐
Pandas (for Excel processing)
SQLite / PostgreSQL (for database storage)
📂 How It Works
The script reads car plate numbers from an input.xlsx file.
It navigates the government website using Selenium.
Extracts penalties and other relevant data.
Appends the results into an SQL database for record-keeping.
🛠 Installation & Setup
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/Traffic-Penalty-Scraper.git
cd Traffic-Penalty-Scraper
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Ensure you have the necessary files:

input.xlsx → Contains plate numbers
scrapping_traffic.ipynb → Main script
Run the script:

Open Jupyter Notebook
Run scrapping_traffic.ipynb
