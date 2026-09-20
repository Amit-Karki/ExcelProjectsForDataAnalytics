# ✈️ Flight Passenger Satisfaction Dashboard

##  📋 Introduction
This dataset is from Kaggle and covers an airline's passengers — Frequent 
and Rare customers, flying in different classes (Eco, Eco Plus, Business) 
and travel types (Business, Personal) — who reported satisfaction or 
dissatisfaction based on features like inflight service, seat comfort, 
and others, each rated on a scale of 0 to 5.

This project focuses on extracting valuable insights from that data and 
building an interactive dashboard that lets airline staff view total 
customer count, satisfaction %, average customer age, and more — filtered 
live by the criteria they select.

## 🔍  Key Insights
- Frequent customers report higher satisfaction than rare/first-time customers.
- Business class passengers are more satisfied than Eco and Eco Plus passengers.
- Male customers report slightly higher satisfaction than female customers.
- Flight distance and onboard service show the strongest positive correlation 
  with satisfaction, while departure/arrival time convenience shows a 
  negative correlation — inconvenient scheduling appears to hurt satisfaction 
  even when service quality is good.

##  🎥 Dashboard Demo

https://github.com/user-attachments/assets/d856975a-d0cf-486c-b063-47b5478e0f70

This dashboard lets the user filter by **Customer type** (Rare, Frequent, All), 
**Gender** (M, F, All), **Flight type** (Business, Personal, All), and 
**Class** (Eco, Eco Plus, Business, All). Based on these selections, it shows:
- Total Customers
- Average Customer Age
- Customer Satisfaction % and Dissatisfaction %
- A correlation chart ranking which in-flight service factors most affect 
  satisfaction, sorted in descending order

## Graphs used:
<img width="394" height="230" alt="Image" src="https://github.com/user-attachments/assets/86446719-6338-4143-8e69-4effbee8ae29" />

This is a bar chart used to show the top factor driving the Customer Satisfaction in descending order. The used input is given below:
<img width="801" height="160" alt="Image" src="https://github.com/user-attachments/assets/a5d004be-3979-4a8b-acd1-69a11d1780c5" />

The behind the scene formula is: 
<img width="395" height="100" alt="Image" src="https://github.com/user-attachments/assets/ceee1902-05f3-4b18-916a-c54d60ab4385" />

The bar chart shows that for this specific case the customers who gave high score in terms of Inflight entertainment tends to be more satisfied. Also the Ease of online booking and online boarding tends to be negatively coorelated.

Pie Chart:
<img width="366" height="229" alt="Image" src="https://github.com/user-attachments/assets/fa4e933f-d390-4020-916d-c6588dd0e1e5" />
This chart shows the percent of 



##  🛠️ Excel Tools & Skills Used
- **Formulas & Functions**🧮 — AVERAGEIFS and SUMIFS with dynamic wildcard 
  logic (`IF(filter="All","*",filter)`) to calculate Average Age and Total 
  Customers across any combination of filters
- **Charts & Graphs** — 📊 Bar chart visualizing correlation coefficients 
  between satisfaction and individual service factors (inflight service, 
  seat comfort, etc.)
- **Sheet Protection** — 🔒 Protected the sheet while keeping filter/input 
  cells selectable, so users can only interact with intended controls
- **Icons & Sheet View** — 🎨 Used icons to visually represent filters 
  (Gender, Flight type, etc.) and hid gridlines, the formula bar, and 
  headers for a cleaner, dashboard-style look

##  📌 Conclusion
This dashboard can help airline stakeholders analyze which customer 
segments — by type, gender, flight type, and class — report lower 
satisfaction, and use that to guide decisions aimed at improving customer 
experience and retention. The correlation chart adds a layer of insight 
beyond raw satisfaction numbers, showing *which specific service factors* 
are most associated with how satisfied or dissatisfied customers are — 
useful as a starting point for further investigation, not a final answer 
on its own.
