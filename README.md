<!-- ░░░░░░░░░░░░░░░░░░░░░░ HEADER ░░░░░░░░░░░░░░░░░░░░░░ -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b132b,50:1c4e80,100:00a8cc&height=230&section=header&text=Shahriar%20Emon&fontSize=62&fontColor=ffffff&fontAlignY=38&desc=Turning%20messy%20data%20into%20clear%20decisions&descSize=19&descAlignY=60&animation=fadeIn" width="100%" alt="header"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3200&pause=900&color=00D9FF&center=true&vCenter=true&width=700&lines=Data+Analyst+%7C+SQL+%E2%80%A2+Python+%E2%80%A2+Power+BI+%F0%9F%93%8A;CS+Graduate+%40+BRAC+University+%F0%9F%8E%93;3+end-to-end+analytics+projects+shipped+%F0%9F%9A%80;Learning+Data+Science+%26+Machine+Learning+%F0%9F%A4%96" alt="Typing SVG" />
</a>

<br/>

![Followers](https://img.shields.io/github/followers/noob-shahriar?label=FOLLOWERS&style=for-the-badge&color=00d9ff&labelColor=0b132b)
![Stars](https://img.shields.io/github/stars/noob-shahriar?label=STARS&style=for-the-badge&color=00d9ff&labelColor=0b132b)
![Open to Work](https://img.shields.io/badge/OPEN_TO-DATA_ANALYST_ROLES-22c55e?style=for-the-badge&labelColor=0b132b)

</div>

<br/>

<!-- ░░░░░░░░░░░░░░░░░░░░░░ ABOUT ░░░░░░░░░░░░░░░░░░░░░░ -->

## 👋 &nbsp;Hello, World!

```python
class Me:
    name        = "Shahriar Emon"
    education   = "B.Sc. in Computer Science, BRAC University 🇧🇩"
    location    = "Bangladesh"
    role        = "Aspiring Data Analyst"
    strengths   = ["SQL", "Python", "EDA", "Data Storytelling"]
    exploring   = ["Data Science", "Machine Learning"]
    mindset     = "Curious. Consistent. Always shipping."

    def goal(self):
        return "Use data to solve real problems that matter."

    def fun_fact(self):
        return "I document every cleaning decision, and I'm honest about data limits 😄"
```

> 💡 *"Without data you're just another person with an opinion."* — W. Edwards Deming

<br/>

<!-- ░░░░░░░░░░░░░░░░░░░░░░ PROJECTS ░░░░░░░░░░░░░░░░░░░░░░ -->

## 🚀 &nbsp;Featured Projects

*Three end-to-end analytics projects on real public datasets, each with a documented pipeline, a SQL layer and business recommendations.*

<br/>

### 💳 &nbsp;CreditLens: Loan Default & Credit Risk Analytics

> Which borrowers default, how risky is each segment, and what approval policy cuts defaults without turning away too many good customers?

| 📦 Data | 🧮 Analysis | 🎯 Outcome |
|:--|:--|:--|
| **2.26M** LendingClub records, **786,820** finished loans analysed | **18** SQL queries (CTEs, window functions) on a PostgreSQL star schema | Default rate of **18.64%** profiled by grade, term, purpose, DTI, FICO and vintage |

- 🛡️ **Leakage-safe modelling:** removed every post-origination field so models only use application-time information
- ⏱️ **Time-based validation:** trained on 2012-2014 loans and tested on 2015 instead of a random split
- 📐 **Models:** logistic regression and gradient boosting, judged by ROC-AUC, Gini, KS and calibration
- ⚖️ **Policy simulation:** rejected the riskiest 5% to 50% of applicants to measure defaults avoided vs. good loans lost
- ✅ Modular pipeline with one run command, auto-generated executive summary and `pytest` tests

`Python` `pandas` `scikit-learn` `PostgreSQL` `SQL` `Matplotlib` `pytest`

[![View Project](https://img.shields.io/badge/VIEW_PROJECT-00d9ff?style=for-the-badge&logo=github&logoColor=black&labelColor=0b132b)](https://github.com/noob-shahriar/Creditlense---Loan-Default-Credit-Risk-Analytics)

<br/>

### 🛒 &nbsp;CartPulse: E-Commerce Growth & Profitability Intelligence

> Where does an online marketplace make its money, and what is quietly holding growth back?

| 📦 Data | 🧮 Analysis | 🎯 Outcome |
|:--|:--|:--|
| **99,441** Olist orders across **9** relational tables | **8** SQL files cross-checked by **6** pandas notebooks | **5** evidence-backed business recommendations |

- 🚚 **Late deliveries hurt:** an **8.1%** late rate came with a **1.7-star** review gap (2.57 vs 4.29)
- 📊 **Pareto effect:** **18 of 74** categories drive 80% of revenue, and the top 10% of sellers drive **67.5%**
- 🔁 **Retention is the weak spot:** only **3.04%** of customers repeat, which shaped an acquisition and AOV-first recommendation
- 🌎 **Freight burden:** rises from **15.2%** (Southeast) to **22.7%** (North) of item price, limiting expansion
- 🧩 Custom RFM segmentation built on the real distribution, since ~97% of customers buy once
- 🧾 Every cleaning decision logged, with the cost proxy clearly labelled as an estimate

`Python` `SQL` `PostgreSQL` `Jupyter` `Seaborn` `Power BI`

[![View Project](https://img.shields.io/badge/VIEW_PROJECT-00d9ff?style=for-the-badge&logo=github&logoColor=black&labelColor=0b132b)](https://github.com/noob-shahriar/cartpulse-ecommerce-analytics)

<br/>

### 🌍 &nbsp;Silk Route: Global Health Supply Chain Risk & Cost Intelligence

> Where is a global health supply chain exposed on suppliers, freight cost and delivery reliability?

| 📦 Data | 🧮 Analysis | 🎯 Outcome |
|:--|:--|:--|
| **$1.63B** USAID shipments, ~**10,300** orders, **43** countries | Vendor risk (**HHI**), freight efficiency, lead-time variance | Interactive **Streamlit** dashboard with 3 modules |

- 🏭 **Supplier concentration:** **6 of 69** suppliers hold ~80% of spend, with single-supplier risk up to **89.8%** share in one category
- ✈️ **Air freight premium:** about **7.7x** more per kg than ground, while taking **77%** of freight spend
- ⏳ **Lead times:** separated *chronically slow* routes from *unpredictable* ones, which call for different fixes
- 🧼 Cleaned messy real-world fields, and stated data gaps openly (only 44% of rows had a computable lead time)

`Python` `pandas` `Plotly` `Streamlit` `Matplotlib` `NumPy`

[![View Project](https://img.shields.io/badge/VIEW_PROJECT-00d9ff?style=for-the-badge&logo=github&logoColor=black&labelColor=0b132b)](https://github.com/noob-shahriar/Silk-Route---Global-Health-Supply-Chain-Risk-Cost-Intelligence)

<br/>

#### 🧪 More experiments
[🌋 Earthquake Aftershock Risk Forecast](https://github.com/noob-shahriar/Earthquake-Aftershock-Risk-Forecast) &nbsp;•&nbsp; [🤖 Machine Learning Project](https://github.com/noob-shahriar/Machine-Learning-Project) &nbsp;•&nbsp; [🚗 Cholo Ride-Sharing (Dart)](https://github.com/noob-shahriar/cholo-slot-based-ride-sharing-platform)

<br/>

<!-- ░░░░░░░░░░░░░░░░░░░░░░ SKILLS ░░░░░░░░░░░░░░░░░░░░░░ -->

## 🧠 &nbsp;What I Bring

<table>
<tr>
<td width="33%" valign="top">

### 📊 Data Analysis
- Data cleaning with decision logs
- SQL: CTEs, window functions, star schemas
- EDA, KPIs, cohort & RFM analysis
- Dashboards & storytelling

</td>
<td width="33%" valign="top">

### 🧪 Data Science
- Statistics & risk metrics (HHI, KS, Gini)
- Feature engineering
- Time-based validation
- Honest handling of data limits

</td>
<td width="33%" valign="top">

### 🤖 Learning Next
- Deeper ML & model tuning
- Hypothesis testing
- Intro to deep learning
- Deployment & MLOps basics

</td>
</tr>
</table>

<br/>

<!-- ░░░░░░░░░░░░░░░░░░░░░░ TECH STACK ░░░░░░░░░░░░░░░░░░░░░░ -->

## 🛠️ &nbsp;Tech Stack & Tools

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=python,postgres,cpp,dart,js&theme=dark" alt="languages"/>

**Data & Analytics**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4c8cbf?style=for-the-badge&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)

**Databases, BI & Tools**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

</div>

<br/>

<!-- ░░░░░░░░░░░░░░░░░░░░░░ ROADMAP ░░░░░░░░░░░░░░░░░░░░░░ -->

## 🗺️ &nbsp;My Learning Roadmap

<div align="center">

<img src="https://img.shields.io/badge/Python_%26_Programming-90%25-00d9ff?style=for-the-badge&labelColor=0b132b" alt="Python"/>
<br/>
<img src="https://img.shields.io/badge/SQL_%26_Databases-85%25-00d9ff?style=for-the-badge&labelColor=0b132b" alt="SQL"/>
<br/>
<img src="https://img.shields.io/badge/Data_Analysis_%26_EDA-85%25-00d9ff?style=for-the-badge&labelColor=0b132b" alt="EDA"/>
<br/>
<img src="https://img.shields.io/badge/Data_Visualization-75%25-00d9ff?style=for-the-badge&labelColor=0b132b" alt="Visualization"/>
<br/>
<img src="https://img.shields.io/badge/Statistics_%26_Probability-55%25-00d9ff?style=for-the-badge&labelColor=0b132b" alt="Statistics"/>
<br/>
<img src="https://img.shields.io/badge/Machine_Learning-45%25-00d9ff?style=for-the-badge&labelColor=0b132b" alt="ML"/>
<br/>
<img src="https://img.shields.io/badge/Deep_Learning-20%25-00d9ff?style=for-the-badge&labelColor=0b132b" alt="DL"/>
<br/>
<img src="https://img.shields.io/badge/MLOps_%26_Deployment-10%25-00d9ff?style=for-the-badge&labelColor=0b132b" alt="MLOps"/>

<sub>*Honest estimates, updated as I grow.*</sub>

</div>

<br/>

<!-- ░░░░░░░░░░░░░░░░░░░░░░ STATS ░░░░░░░░░░░░░░░░░░░░░░ -->

## 📊 &nbsp;GitHub Stats

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=noob-shahriar&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0b132b&title_color=00d9ff&icon_color=00d9ff&text_color=ffffff" alt="stats"/>
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=noob-shahriar&layout=compact&theme=tokyonight&hide_border=true&bg_color=0b132b&title_color=00d9ff&text_color=ffffff" alt="top languages"/>

<img src="https://streak-stats.demolab.com?user=noob-shahriar&theme=tokyonight&hide_border=true&background=0b132b&ring=00d9ff&fire=ff6b35&currStreakLabel=00d9ff" alt="streak"/>

</div>

<br/>

<!-- ░░░░░░░░░░░░░░░░░░░░░░ GOALS ░░░░░░░░░░░░░░░░░░░░░░ -->

## 🎯 &nbsp;Goals

- [x] Graduate with a CS degree from BRAC University 🎓
- [x] Build 3 end-to-end analytics projects on real data
- [x] Learn SQL window functions, CTEs and star-schema design
- [ ] Build the CartPulse Power BI dashboard from my spec
- [ ] Deploy my first ML model
- [ ] Land a role as a Data Analyst 💼

<br/>

<!-- ░░░░░░░░░░░░░░░░░░░░░░ CONNECT ░░░░░░░░░░░░░░░░░░░░░░ -->

## 🤝 &nbsp;Let's Connect

I'm open to **Data Analyst roles, internships, and collaborations**. Say hi!

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/shahriar-emon-094639229)
[![Gmail](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:emonshahriar41@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/noob-shahriar)

<br/>

⭐ *If you like what you see, drop a star on my repos!* ⭐

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00a8cc,50:1c4e80,100:0b132b&height=120&section=footer" width="100%" alt="footer"/>

</div>
