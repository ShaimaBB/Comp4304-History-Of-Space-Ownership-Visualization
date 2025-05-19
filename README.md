# Comp4304-History-Of-Space-Ownership-Visualization

##  Overview

This project explores the shifting power dynamics in space exploration—how satellite ownership evolved from government and military monopolies during the Cold War to a decentralized, commercialized space economy dominated by private corporations.

Using real satellite data from the GCAT catalog, we investigate:
- What historic events triggered spikes in satellite launches?
- How did ownership patterns change from 1960 to the present?
- What role did private companies begin to play in the 21st century?

*NOTE: Due to it being an academic project we aren't allowed to post the codes.*

*This is a group project. Created by Shaima Bashar and Nurul Islam*

---

##  Tech Stack

### Programming & Visualization
- **Pandas**  &  **Numpy** – Data processing
- **Plotly** – Interactive charts & dashboard
- **Matplotlib** – Static visualizations for infographic
- **Seaborn** – Thematic styling for plots
- **Dash** – Web-based interactive dashboard
- **Jupyter Notebook** 

---

###  Key Insights
- 1960–1980s: Space dominated by superpower governments (USA, USSR)
- Post-9/11: Surge in government surveillance & defense satellites
- Post-2019: Rapid commercial expansion (e.g., SpaceX, OneWeb)
- Private Sector: More efficient, innovative, and cost-effective than traditional government launches
  
---
### Visualizations
We deliver our findings via **infographic**, an **interactive dashboard**, and a **video presentation**

### Infographic - credit Nurul Islam
It contains of three visualizations like
- **Tree Graph** showing Major Launch Contributors through 1960s-Present
- **Line-Dot Graph** showing Satellite Launch Trends by Ownership Type
- **Sunburst Chart** showing Purpose of Satellite Launches
![WhatsApp Image 2025-04-10 at 9 10 33 PM (1)](https://github.com/user-attachments/assets/fb5adbad-f936-48c0-a0dc-c5373fb22daf)

### Interactive Dashboard - credit Shaima Bashar
It contains of three visualizations with interactive dashboards like:

1. **GeoMap Chart and Line Graph** showing Satellite Launches by Country and their Count trend over time

This interactive dashboard visualizes satellite launches across countries over time, segmented by sector (Government, Private, Military, Academic). It allows users to Select a sector and see which countries launched the most satellites in that category. Also, Hovering over any country to shows a line chart that showcases that country’s launch count trend over time in the selected sector. It reveals the first-time entries of emerging nations into the space scene, countries like Brazil, Argentina, Israel, and South Korea appear with their first-ever satellite launches, signaling a broader democratization of space.

This dashboard reveals how global space activity has evolved, highlighting the geopolitical and technological shifts that shaped spacefaring nations. It gives a visual trace of the rise and fall of space powers, the shift from government to private dominance, and how satellite launch capacity has expanded globally over time.

### Simple Demo

https://github.com/user-attachments/assets/b8af1561-85b8-440d-b05a-b040372479b7

*A Detailed Video explanation using an example of how to use this interactive dashboard can be found here*

---

2. **Scatter Plot and Bar Chart** showing the Reasons of the Rise of Private Sector Dominance in Space

This interactive dashboard explores how satellite **success rates** and **lifespan trends** have varied across four major sectors and how these differences have shaped the broader trajectory of space leadership.

It shows clearly that government-launched satellites experienced more failures, especially in earlier decades. These failures may be attributed to the ambitious nature of their missions, complex systems, or bureaucratic constraints. In contrast, private sector satellites tend to last longer and show higher success rates, due to innovation in reusable technology, and a focus on cost-effective, low-Earth orbit designs.

As failure rates declined and launch reliability improved, the private sector gained credibility among governments and investors. This led to the commercialization boom of the 2010s and 2020s leaded now by mega-constellations like Starlink. While the government and military sectors still play a role, they now show slower growth compared to the rapidly expanding commercial space race.

The dashboard includes two visualization modes that offer unique perspectives. The **Scatter plot** *("Lifespan by Result")* lets users explore the **lifespan of each satellite**, with dot color showing the sector and shape indicating launch outcome: circle for success and '×' for failure. The **Bar chart** *("Count by Result Per Year")* highlights how many satellites were launched per sector annually, and how many succeeded or failed, helping users compare **efficiency and growth** across time.

A range slider below both charts enables users to focus on specific eras—whether it's the Cold War space race of the 1960s or the post-2010 rise of private space companies. Together, these visual tools tell a clear story of how the balance of power in space shifted from government-led exploration to market-driven expansion

### Screenshort

![Screenshot 2025-05-18 175059](https://github.com/user-attachments/assets/5411664a-a6bf-414b-953f-7c3a3ebf377b)
![Screenshot 2025-05-18 175133](https://github.com/user-attachments/assets/37885820-92eb-4ea4-a088-052c654d62b3)

*A Detailed Video Demo with explanation using an example of how to use this interactive dashboard can be found here*

---

3. **Sunburst Chart** showing Satellite Launch Surge: 1999–2000 and 2020–2023
   
This interactive sunburst visualization reveals which countries and manufacturing companies launched the most satellites—and for what purposes—during two key eras: 1999–2000 and 2020–2023. These launches reflect shifting priorities beyond traditional military and defense uses.

In 1999–2000, the dot-com boom, rising demand for GPS, and post–Cold War space transitions led to major public and private sector investments in satellites, especially for communications, Earth observation, and science.

In contrast, the 2020s era reflects a new space race driven by commercial broadband mega-constellations like Starlink, rapid privatization, and the growing role of private tech companies in orbital infrastructure.

### Simple Demo

https://github.com/user-attachments/assets/a64bc706-39ec-458d-9a6a-4bf05d2447e6

*A Detailed Video Demo with explanation using an example of how to use this interactive dashboard can be found here*

---

### 🛰️ Data Source
All the datasets used in the project are from:
GCAT: General Catalog of Artificial Space Objects
By Jonathan McDowell
https://planet4589.org/space/gcat/web/cat/index.html



