Supply Chain Analytics: Solving the Late Delivery Crisis 📦
Why I built this?
While looking at this dataset, one number caught my eye: 55.42%. That’s the rate of late deliveries. In any real-world business, this is a disaster. I wanted to build more than just a "pretty dashboard"; I wanted to create a tool that actually tells a manager why this is happening and how much it’s costing the company.
<img width="1293" height="724" alt="Screenshot 2026-04-09 150415" src="https://github.com/user-attachments/assets/f3231ce4-f3b9-4513-a086-48d40ade9e26" />
 
The Problem
The business was struggling with delivery delays, but they didn't know the financial impact. My goal was to link logistics performance (shipping days, risks) directly to the Net Profit.

What I did (The "How"):
Data Cleaning: Spent a good amount of time in Power Query fixing types and handling nulls to make sure the profit calculations are accurate.

Smart Visuals: * Used the Sankey Diagram because it’s the best way to see how orders flow from "Shipping Mode" to "Status". It’s where I spotted the bottleneck in Second Class shipping.

Integrated the Key Influencers AI visual. I didn't want to guess; I wanted the data to tell me exactly what drives a "High Risk" shipment.

Design Pivot: I initially started with a dark/busy theme, but realized it was distracting. I switched to a Clean White Design to make the red "Alert" numbers (like the late delivery rate) pop.

Key Insights Found:
The Profit Killer: High-risk shipping isn't just a delay issue; it’s eating up thousands in potential profit, especially in the USA and France markets.


Shipping Modes: Standard Class might be cheaper, but the correlation with late deliveries makes it a risky choice for high-value orders.

<img width="1288" height="727" alt="Screenshot 2026-04-09 150430" src="https://github.com/user-attachments/assets/bff11adc-a791-491d-ae5e-a603933d2239" />

Tech Stack:
Tool: Power BI Desktop.

Features: DAX measures for Profit & Loss, Power Query, AI Visuals (Key Influencers, Decomposition Tree).
