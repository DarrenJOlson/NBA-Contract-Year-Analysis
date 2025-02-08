# 🏀 Using "Total Value Added" to Analyze the Contract Year Phenomenon in the NBA

**Darren Olson (University of Mississippi, Oxford, MS 38677)**  
**Yong Chae Rhee (Washington State University, Pullman, WA 99164)**  

## 📖 Project Overview
There is a widely held belief among basketball fans that players perform better in the final year of their contract. This capstone project analyzes whether there is a **statistically significant difference** in performance between players in a contract year and those who are not.  

Using a custom formula, **Total Value Added (TVA)**, I conducted a statistical analysis on **NBA player performance** during the **2021-2022 season**, categorizing contract statuses and comparing player efficiency metrics.

📄 **[Read the Full Capstone Report (PDF)](./CapstoneFinal_DarrenOlson.pdf)**  
🎥 **[Download the Presentation (MP4)](./DarrenOlson_Capstone.mp4)**  

---

## 📊 Methodology
1. **Data Collection**  
   - Downloaded **2021-2022 NBA player stats** from [Basketball-Reference](https://www.basketball-reference.com/).
   - Obtained **contract status** from [Spotrac](https://www.spotrac.com/nba/free-agents/2022/).

2. **Total Value Added (TVA) Calculation**  
   - Formula:  
     ```math
     TVA = Points + Defensive Rebounds + 2*(Offensive Rebounds + Assists + Steals + Blocks) - 2*(Turnovers)
     ```
   - Standardized by **TVA per minute**.

3. **Statistical Analysis**  
   - **One-Way ANOVA** to compare TVA/min across contract types (Unrestricted Free Agents, Restricted Free Agents, Club Options, Player Options, Non-Free Agents).  
   - **Tukey’s HSD Test** for multiple comparisons.  
   - **One-Sample t-test** to compare contract year players against the population mean.

---

## 📌 Key Findings
- **Statistically significant differences exist** in TVA/min between at least two groups (**F(4, 600) = 2.691, p = 0.0303**).  
- **Restricted Free Agents (RFAs) underperform** compared to the general NBA population (**p = 0.0419**).  
- **No evidence supports the idea that contract-year players perform better overall**.

### 🔎 **Conclusion**
These findings **challenge the common belief** that NBA players elevate their performance in contract years. **Further research** is needed to understand external factors influencing performance during contract years.

---

## 📚 References
- Basketball-Reference.com ([Link](https://www.basketball-reference.com/))
- Spotrac.com ([Link](https://www.spotrac.com/nba/free-agents/2022/))
- Lyons, R., Jackson, E., & Livingston, A. (2015). Determinants of NBA Player Salaries. *The Sport Journal*.
- Stiroh, K. (2007). Playing for Keeps: Pay and Performance in the NBA. *Economic Inquiry*.
- White, M. H., & Sheldon, K. M. (2014). The contract year syndrome in the NBA and MLB: A classic undermining pattern. *Motivation and Emotion*.

---

## 📫 Contact
💼 **[LinkedIn](https://www.linkedin.com/in/darrenjolson/)**  

---
📝 *This repository serves as a portfolio showcase of my Capstone findings. The original R code used for analysis is unavailable.*  
