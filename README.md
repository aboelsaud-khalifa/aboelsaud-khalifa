# Re-create the README.md file content after kernel reset

readme_content = """
# Abo El-Saud Khalifa

🎯 Aspiring Data Analyst | Business Intelligence & Analytics Student  
📍 Giza, Egypt | 📧 aboelsaud.khalifa@gmail.com | [LinkedIn](https://www.linkedin.com/in/aboelsaudkhalifa)

---

Hi! I'm a data analytics student passionate about turning raw data into actionable insights.  
I work with tools like **Power BI**, **Excel**, **Python**, and **SQL** to analyze, clean, and visualize data.  
My goal is to help businesses make smarter, data-driven decisions.

---

## 🔧 Tools & Skills

- **Languages:** Python, SQL (basic)  
- **Visualization:** Power BI, Excel, Google Sheets  
- **Data Work:** Data Cleaning, Statistical Analysis  
- **Other Tools:** GitHub, Microsoft Office, Google Workspace  

---

## 📊 Featured Projects

- **Adidas US Sales Dashboard**  
  Built interactive reports in Power BI and Excel to uncover key sales insights.

- **Banking System Simulation**  
  Developed a basic banking system using Python and Flowgorithm to model transaction logic.

- **Stock Market Workshop (One-Day)**  
  Explored portfolio strategies and market behavior through real-world investment discussion.

---

## 📌 What I'm Looking For

I'm looking to grow in environments where data is taken seriously — whether it’s in business, marketing, finance, or tech.  
If you value data, decision-making, and clear insights — let’s connect.
"""

# Save to a file
file_path = "/mnt/data/README_Abo_El-Saud_Khalifa.md"
with open(file_path, "w", encoding="utf-8") as file:
    file.write(readme_content)

file_path
