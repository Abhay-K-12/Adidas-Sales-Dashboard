# Adidas Interactive Sales Dashboard

A data visualization dashboard built using **Streamlit** and **Plotly** as part of my 5th Semester Data Visualization project.

---

## Features
- Total Sales by Retailer, Bar Chart
- Total Sales Over Time, Line Chart
- Sales and Units Sold by State, Combined Bar and Line Chart
- Total Sales by Region and City, Treemap
- Download any chart data as CSV

---

## Technologies Used

| Tool | Purpose 
| Python | Main programming language 
| Streamlit | Web app framework 
| Pandas | Data manipulation 
| Plotly | Interactive charts 
| OpenPyXL | Reading Excel files 
| Pillow | Loading logo image 

---

## How to Run Locally

**1. Clone the repository**
```bash
git clone https://github.com/Abhay-K-12/Adidas-Sales-Dashboard.git
```

**2. Go to the project folder**
```bash
cd Adidas-Sales-Dashboard
```

**3. Install dependencies**
```bash
pip install -r requirements.txt
```

**4. Run the app**
```bash
python -m streamlit run app.py
```

---

## Project Structure
```
Adidas-Sales-Dashboard/
├── app.py                  → Main Adidas Sales Dashboard
├── Dashboard.py            → Superstore EDA Dashboard
├── Adidas.xlsx             → Adidas Sales Dataset
├── adidas-logo.jpg         → Adidas Logo Image
├── requirements.txt        → Required Python Packages
└── README.md               → Project Documentation
```

---

## Dataset
The dashboard uses the **Adidas Sales Dataset** containing:
- Retailers, Regions, States, and Cities
- Invoice dates and Monthly sales trends
- Units sold and Total sales figures

---

## Dashboard Preview

The dashboard includes interactive charts with filters, expanders to view raw data, and download buttons for every chart.

---


<img width="1365" height="675" alt="Screenshot 2026-04-07 133215" src="https://github.com/user-attachments/assets/b161c403-ed52-42c1-8ed9-d06428bd02b6" />
<img width="1265" height="575" alt="Screenshot 2026-04-07 133138" src="https://github.com/user-attachments/assets/e012a98d-64ac-4000-933e-b9c7854fa598" />
<img width="1365" height="678" alt="Screenshot 2026-04-07 133130" src="https://github.com/user-attachments/assets/0fb6532b-033c-4c78-ad50-263a2f18b688" />


## Note
This project was originally built in 5th Semester as a Data Visualization assignment. It has been version controlled using Git and GitHub in 8th Semester.
