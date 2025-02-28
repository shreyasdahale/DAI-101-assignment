# DAI-101-assignment

# Exploratory Data Analysis (EDA) of the sleep cycle-productivity dataset

## Project Overview
This project explores the relationships between **sleep patterns**, **lifestyle habits** (such as caffeine intake and exercise), and **productivity**. Using a dataset containing daily logs of these factors, we conducted a thorough EDA to uncover trends and insights.

## Key Findings

### **Caffeine Intake and Sleep**
- **High variance** in caffeine consumption, with a mean of ~147 mg and peaks at 299 mg.
- **No strong correlation** between caffeine intake and sleep quality or duration, suggesting diverse individual responses to caffeine.

### **Exercise and Sleep**
- Exercise showed a **slight positive correlation** with sleep quality.
- The impact on sleep hours was less clear, indicating exercise might improve sleep efficiency rather than duration.

### **Sleep and Productivity**
- **Productivity scores** remained **fairly stable** across varying sleep quality levels.
- Extreme sleep deprivation slightly lowered productivity, but moderate fluctuations had minimal effect.

### **Sleep Hours vs. Sleep Quality**
- Sleep hours mainly ranged between **4 to 9 hours**.
- A **weak positive trend** was observed: longer sleep hours were somewhat associated with higher sleep quality, but the relationship wasn't strong.

## Visualizations
The project includes various visualizations, such as:
- **Scatter plots** for caffeine intake vs. sleep quality.
- **Bar charts** showing average productivity by sleep quality.
- **Line plots** with trend lines highlighting relationships between sleep hours and quality.

## Technologies Used
- **Python** (pandas, numpy)
- **Data Visualization:** seaborn, matplotlib
- **Jupyter Notebook** for analysis

## Project Structure
```
|-- sleep_cycle_productivity.csv                 # CSV file of the data
|-- README.md                                    # Project overview (this file)
|-- EDA.ipynb                                    # Main exploratory data analysis
```

## Conclusion
This analysis suggests that **exercise has a more noticeable impact on sleep quality** than caffeine, while **sleep quality and productivity show a non-linear relationship**. The insights highlight the complexity of sleep’s influence on daily life and stress the importance of personalized approaches to wellness.
