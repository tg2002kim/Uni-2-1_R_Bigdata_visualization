Python Big Data Visualization

This repository contains Jupyter Notebook assignments and lectures from the Big Data Visualization with Python course. The course focuses on using Python and pandas for data manipulation and Matplotlib/Seaborn for creating insightful visualizations using real-world demographic datasets.


Course Overview
Course Title: Python Data Visualization (파이썬 빅데이터 시각화)


Course Information
This project was conducted as part of a short-term course titled “Global Business Strategy for Technology Companies”, offered by Dankook University during the first semester of 2024 (Spring 2024, 2-1), in May 2024.

Subject: 글로벌기업의 기술비즈니스전략
Format: Intensive short-term program
Institution: Dankook University (단국대학교)


Objective: Learn how to manipulate tabular data and create various types of visualizations using Python

Environment:
* Jupyter Notebook
* Google Colab compatible
* Python 3.10+
* pandas, matplotlib, seaborn


Key Learning Topics
  Topic	Description
  DataFrame Basics	Understanding structure, indexing, filtering
  Time Series Plotting	Trend analysis using line charts
  Bar Charts	Vertical and horizontal bar charts to compare groups
  Pie Charts	Distribution ratio and proportions
  Stacked Bar Charts	Accumulated comparisons across categories
  Donut Charts	Enhanced pie charts with central labels
  Multi-Bar Graphs	Gender or age-based multi-dimensional comparison
  Regional Demographic Analysis	Grouped bar charts by regions and ages
  Exploratory User Behavior Analysis	Real-world case of user-item patterns in gamified datasets


File Structure
  Folder / File	Description
  01. 데이터프레임과 데이터시각화.ipynb	Introduction to DataFrame structure and basic plotting
  02. 년도별총인구수(꺾은선그래프).ipynb	Line chart showing national population by year
  03. 년도별행정구역 Top3 총인구수(꺾은선그래프).ipynb	Line chart showing top 3 regions by population
  04. (2023년)연령별총인수구(세로막대그래프).ipynb	Vertical bar chart for age distribution
  05. (2018년)전국성별연령별인구분포(가로막대그래프).ipynb	Horizontal bar chart for gender-age nationwide
  06. 년도별행정구역 Top3 총인구수(누적막대그래프).ipynb	Stacked bar chart for top regional populations over time
  07. 년도별10대총인구수비율(원그래프+도넛그래프).ipynb	Pie and donut charts showing youth population ratio
  08. (서울시)년도별남녀총인구수비교(다중세로막대그래프).ipynb	Multi bar chart comparing male/female in Seoul by year
  09. (2023년)연령별행정구역별총인구수(다중세로막대그래프).ipynb	Grouped bar charts by age and region
  10. 유저아이템획득패턴분석과개선전략.ipynb	Gamification case study: user-item interaction analysis


Visualization Techniques Used
Line Plot: For chronological changes and trend detection
Bar Plot: To compare quantities across discrete categories
Stacked Bar Plot: To visualize component contributions
Pie / Donut Chart: To display ratios
Multi-Bar Plot: For comparisons across multiple variables
Heatmap (if added later): For matrix-style density or correlation


Data Source
  * KOSIS (Korean Statistical Information Service)
    * 전국 시군구별 연령/성별/년도별 총인구 데이터
  * Simulated User Behavior Dataset (for pattern analysis project)


Getting Started
To run the notebooks:
1. Clone this repository:
    git clone https://github.com/your-id/python-data-visualization-lab.git

2. Install requirements:
  pip install pandas matplotlib seaborn
  
3. Launch Jupyter Notebook or Google Colab to explore each .ipynb file.


Learning Outcome
*  By completing this course, you will:
*  Understand how to structure and filter real-world tabular data
*  Generate insightful visualizations to reveal patterns and trends
*  Communicate data findings effectively using visual tools
*  Gain fluency in using pandas, matplotlib, and seaborn for analysis


⚠ Korean Font Rendering Issue
Due to recent updates in Matplotlib, Korean text may not display correctly in plots (e.g., shown as □ or missing).

Quick Fix (Colab/Linux)
  !apt-get -y install fonts-nanum
  import matplotlib.pyplot as plt
  plt.rcParams['font.family'] = 'NanumGothic'
  plt.rcParams['axes.unicode_minus'] = False

Quick Fix (Windows)
  import matplotlib.pyplot as plt
  plt.rcParams['font.family'] = 'Malgun Gothic'
  plt.rcParams['axes.unicode_minus'] = False
  Add this at the top of each notebook if Korean labels are broken.


License
  This repository is part of a course activity. Educational use only. All rights reserved by the instructor and institution.

