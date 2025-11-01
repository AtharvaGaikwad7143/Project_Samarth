By: Atharva Gaikwad

This project analyzes rainfall trends and crop yield patterns in India using open datasets from data.gov.in
.
It uses real government data and visualizes rainfall comparison between two states along with the top crop yields for 2019–20.

📊 Datasets Used

Daily District-wise Rainfall Data

Resource ID: 6c05cd1b-ed59-40c2-bc31-e314f39c6971

URL: https://www.data.gov.in/resource/daily-district-wise-rainfall-data

Contains daily rainfall for all Indian districts (updated till Oct 2025).

All India Crop Yield Estimates (2019–20)

Resource ID: 936bddf5-d1a7-4127-a031-b07f5dcad2da

URL: https://www.data.gov.in/resource/all-india-level-estimates-yield-major-crops-during-2019-20-ministry-agriculture-and

Contains yield (kg/hectare) for major crops in 2019–20.

🧠 What the Project Does

Compare average annual rainfall

Compares rainfall between two states (e.g., Maharashtra and Assam)

Uses the last 5 years of rainfall data

Shows both numeric and visual comparison using matplotlib

Analyze crop yields

Displays top 10 crops by yield for 2019–20

Presents data in a simple table and a bar chart visualization

🧩 Technologies Used

Python 3

Pandas → data cleaning & analysis

Matplotlib → data visualization

JSON & urllib → fetching data via API

Jupyter Notebook (recommended for running interactively)

⚙️ How to Run This Project
1️⃣ Clone or Download

Download the project folder and open it in VS Code or Jupyter Notebook.

2️⃣ Install Required Libraries
pip install pandas matplotlib

3️⃣ Get Your API Key

Go to data.gov.in
, register/login →
My Account → My API Key, then copy your key.

4️⃣ Paste Your API Key

In the notebook, find:

api_key = "YOUR_API_KEY_HERE"


and replace it with your actual key.

5️⃣ Run the Script

Run all cells in order.

📈 Example Outputs
🌧️ Rainfall Comparison

Compares average annual rainfall between Maharashtra and Assam for the last 5 years.

Console Output Example:

Average rainfall (last 5 years): Maharashtra = 1256.32 mm, Assam = 2385.67 mm


Visualization:
📊 Line chart showing rainfall trends year-wise for both states.

🌾 Crop Yield (2019–20)

Lists top 10 crops by yield.

Example Output:

Crop	Yield (kg/hectare)
Sugarcane	77893
Wheat	3421
Maize	2945
Rice	2705
...	...

Visualization:
📊 Bar chart showing the top 10 crop yields.

📚 Sources

data.gov.in

Indian Meteorological Department (IMD)

Ministry of Agriculture and Farmers Welfare

💡 Future Enhancements

Add more years of crop yield data

Include seasonal rainfall breakdown

Create a small web dashboard (e.g., using Streamlit)
