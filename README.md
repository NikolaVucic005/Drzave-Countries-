🌍 Country Info Search App
This is a Python desktop application built with Tkinter, designed to display, search, and analyze country data. It allows users to view all countries, search by capital city or population (including within a range), find the country with the highest or lowest population, and save selected data to a text file.

📌 Features
✅ View All Countries
Display all countries with relevant data (name, capital, population, and area).

🔍 Search Functionality

Search by capital city

Search by population

Search by population range
Example: Find countries with population between 5,000,000 and 20,000,000

📊 Population Analysis

Show country with the highest population

Show country with the lowest population

💾 Save Data to Text File
Export searched results or selected country info to a text file.

🖥️ Clean and Intuitive GUI

🧠 Technologies Used
Python 3

Tkinter – for building the graphical interface

📂 File Format
The application reads from a file named drzave.txt, which should have the following format:

mathematica
Copy
Edit
Country Name | Capital | Population | Area
🔹 Example:

nginx
Copy
Edit
Serbia | Belgrade | 6900000 | 88361
Each field must be separated by the | character.

▶️ How to Run
Make sure you have Python 3 installed.

Place drzave.txt in the same directory as ZAVRSNI RAD NIKOLA.py.

Run the script:

bash
Copy
Edit
python ZAVRSNI RAD NIKOLA.py
📌 Project Structure
bash
Copy
Edit
.
├── ZAVRSNI RAD NIKOLA.py   # Main application file
└── drzave.txt              # Data file containing country info
🚀 Future Improvements
Add sorting by area or alphabetically

Display country flags or map preview

Export data in CSV or JSON format

Filter by continent or region

