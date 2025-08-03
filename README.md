# 🇮🇳 Indian Energy Generation Analysis (2022–23)

Hey there!
This is a small practice project where I explored how different Indian states generated electricity during the year **2022–23**, focusing on **solar, wind, hydro, and thermal** power.

I worked with official data from the **Central Electricity Authority (CEA)** to answer some interesting questions about how India is progressing in energy production — especially in renewable sources 🌱.

---

## What's this project about?

Using state-wise energy generation data, I analyzed:

1. **Total electricity generation** for each state or for all states combined (based on user input).
2. **Which state generated the most renewable energy?**
3. **Which state generated the most thermal energy?**
4. **What % of a state’s energy is from renewables vs thermal?**
5. **Which states are leading in renewable energy by percentage?** (sorted list from highest to lowest)

---

## Data Source

- **Original data**: Taken from CEA’s official PDF report — *General Review*, using:
  - **Table 4.4** – State-wise generation (Hydro, Thermal, Nuclear)
  - **Table 4.7** – Renewable generation (Solar, Wind, etc.)
- **Excel file**: I manually extracted the relevant tables into an Excel sheet for easier analysis.

---

## Tools I Used

- **Python-Google Colab**  – for calculations and analysis  
- You can also use Power BI or Google Sheets for visualization!

---

## Folder Structure
project-folder/
├── README.md ← This file
├── cea_report.pdf ← Official CEA PDF (original source)
├── energy_data.xlsx ← Cleaned data from Tables 4.4 & 4.7
└── Indian_Energy_Generation_2022-23.ipynb ← Colab notebook with all answers

---

## What I Learned

- How to work with **real government data**
- How to use **Pandas/Excel** for meaningful energy insights
- Improved my understanding of India’s **energy mix** and **state-wise differences**
- Practiced cleaning and analyzing data from PDFs and tables

---

## What's Next?

Here are a few ideas to take this further:
- Add **visual charts** (bar plots, pie charts, maps) for better presentation
- Compare trends over **multiple years**
- Include **per capita generation or consumption**

---

## Acknowledgements

- Data by: [Central Electricity Authority, Ministry of Power – Government of India](https://cea.nic.in)
- This project is purely educational and done to **practice real-world data analysis**.
