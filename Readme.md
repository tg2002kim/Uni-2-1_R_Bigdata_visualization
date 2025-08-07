# Python Big Data Visualization

This repository contains all assignments and lecture materials from the **"Big Data Visualization with Python"** course. The course focuses on practical applications of Python, **pandas** for data manipulation, and **Matplotlib/Seaborn** for creating insightful visualizations using real-world demographic datasets.

---

## Course Information

- **Course Title**: Python Data Visualization (파이썬 빅데이터 시각화)
- **Institution**: Dankook University (단국대학교)
- **Course**: Mobile System Programming
- **Date**: Spring 2025 Semester (3rd year, 1st semester)

---

## Project Objective

The main goal of this course is to teach students how to effectively manipulate tabular data and generate various types of visualizations using Python, thereby gaining skills in communicating data findings.

### Environment
- **Platform**: Jupyter Notebook, Google Colab
- **Python Version**: 3.10+
- **Key Libraries**: pandas, matplotlib, seaborn

---

## Key Learning Topics

- **DataFrame Basics**: Structure, indexing, and filtering data.
- **Time Series Plotting**: Creating line charts for trend analysis.
- **Bar Charts**: Comparing quantities with vertical and horizontal bars.
- **Pie & Donut Charts**: Visualizing distribution ratios and proportions.
- **Stacked Bar Charts**: Showing accumulated comparisons across categories.
- **Multi-Bar Graphs**: Comparing data across multiple variables, such as gender or age.
- **Demographic Analysis**: Visualizing population data by region and age.
- **Exploratory Analysis**: Analyzing user behavior patterns in a gamified dataset.

---

## File Structure

| File / Folder | Description |
| :--- | :--- |
| `01. 데이터프레임과 데이터시각화.ipynb` | Intro to DataFrame structure and basic plotting. |
| `02. 년도별총인구수(꺾은선그래프).ipynb` | Line chart of national population by year. |
| `03. 년도별행정구역 Top3 총인구수(꺾은선그래프).ipynb` | Line chart of top 3 regions by population. |
| `04. (2023년)연령별총인수구(세로막대그래프).ipynb` | Vertical bar chart for age distribution. |
| `05. (2018년)전국성별연령별인구분포(가로막대그래프).ipynb` | Horizontal bar chart for gender-age distribution. |
| `06. 년도별행정구역 Top3 총인구수(누적막대그래프).ipynb` | Stacked bar chart for top regional populations. |
| `07. 년도별10대총인구수비율(원그래프+도넛그래프).ipynb` | Pie and donut charts for youth population ratio. |
| `08. (서울시)년도별남녀총인구수비교(다중세로막대그래프).ipynb` | Multi bar chart comparing male/female populations in Seoul. |
| `09. (2023년)연령별행정구역별총인구수(다중세로막대그래프).ipynb` | Grouped bar charts by age and region. |
| `10. 유저아이템획득패턴분석과개선전략.ipynb` | Gamification case study on user-item interaction. |

---

## Getting Started

1.  **Clone the repository**:
    ```bash
    git clone [https://github.com/your-id/python-data-visualization-lab.git](https://github.com/your-id/python-data-visualization-lab.git)
    ```
2.  **Install requirements**:
    ```bash
    pip install pandas matplotlib seaborn
    ```
3.  **Launch Jupyter Notebook or Google Colab** to explore the `.ipynb` files.

---

## Korean Font Rendering Issue

Due to recent updates in Matplotlib, Korean text may not display correctly. Add the following code at the top of each notebook to fix it.

### Quick Fix (Colab/Linux)
    !apt-get -y install fonts-nanum
    import matplotlib.pyplot as plt
    plt.rcParams['font.family'] = 'NanumGothic'
    plt.rcParams['axes.unicode_minus'] = False
    Quick Fix (Windows)
    Python
    
    import matplotlib.pyplot as plt
    plt.rcParams['font.family'] = 'Malgun Gothic'
    plt.rcParams['axes.unicode_minus'] = False


## License
This repository is for educational use only as part of a course activity. All rights are reserved by the instructor and institution.
