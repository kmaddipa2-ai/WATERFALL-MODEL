# 🌦️ Weather Modeling using Quadratic Equation  
**Development Process: Waterfall Model**

This project demonstrates **Weather Modeling** using a **quadratic function**:  

\[
f(t) = a  t^2 + b t + c
\]

The software is developed following the **Waterfall Model** phases:  
1. Requirement Analysis  
2. System & Software Design  
3. Implementation & Unit Testing  
4. Integration & Testing  
5. Deployment  
6. Maintenance  

---

## 📌 Features
- Reads multiple sets of coefficients `(a, b, c)` from a CSV file  
- Simulates temperature variation across a given number of days  
- Generates **plots** for each model (shown inline in Colab / saved as images locally)  
- Includes **unit test** for model correctness  

---

## 📂 Project Structure
weather_model_waterfall/
│── weather_waterfall.py # Main script
│── abc_values.csv # Example coefficients
│── README.md # Documentation

yaml
Copy
Edit

---

## ⚙️ Installation

1. Clone this repo or copy files to your system  
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib
📊 Input Data Format
CSV file abc_values.csv should contain the coefficients for the quadratic model:

csv
Copy
Edit
a,b,c
0.1,2,10
0.05,1.5,15
-0.02,3,5
Each row = one model

Columns = a, b, c

▶️ Running the Project
Option 1: Run Locally
bash
Copy
Edit
python weather_waterfall.py
Outputs plots (inline if run in Jupyter/Colab, or PNGs if saving enabled)

Option 2: Run in Google Colab
Upload abc_values.csv

Run weather_waterfall.py cell

Plots will be displayed inline

✅ Sample Output
Graph: Temperature variation for each (a, b, c) set

Unit Test: Confirms quadratic model is correct

Example graph (for one model):

scss
Copy
Edit
Time (days) → X-axis  
Temperature (°C) → Y-axis  
🔮 Future Improvements (Maintenance Phase)
Add seasonal trends (sine/cosine functions)

Provide comparison plots (multiple models on one chart)

Build a simple GUI/Streamlit app for uploading CSV and visualizing results

👨‍💻 Author
Developed as part of a Software Engineering project following the Waterfall Development Model.
