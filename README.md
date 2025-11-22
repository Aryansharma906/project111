# 📊 Z-Score Statistical Analysis

**Sampling Distribution & Z-Score Calculation | Educational Data Analysis with Python**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)
![Statistics](https://img.shields.io/badge/Statistics-DC143C?style=flat)

## 📋 Overview

This project demonstrates **statistical analysis techniques** using sampling distributions and Z-score calculations to analyze student reading time data. Built as an educational tool to understand:

- Sampling distribution theory
- Standard deviation and confidence intervals
- Z-score statistical significance testing
- Data visualization with Plotly

Perfect for students learning statistics, data science practitioners, or anyone interested in statistical hypothesis testing!

## ✨ Features

- 📈 **Sampling Distribution**: Generate 1000 sample means from population data
- 📊 **Statistical Metrics**: Calculate mean and standard deviation
- 🎯 **Standard Deviation Bands**: Visualize 1σ, 2σ, and 3σ intervals
- 🔬 **Z-Score Calculation**: Determine statistical significance
- 📉 **Interactive Plots**: Plotly visualizations for data exploration
- 📚 **Multiple Samples**: Compare different student groups

## 🛠️ Tech Stack

- **Python 3.x** - Core programming language
- **Pandas** - Data manipulation and CSV handling
- **Plotly** - Interactive visualization library
- **Statistics** - Built-in statistical functions
- **Random** - Random sampling for distribution

## 📁 Project Structure

```
project111/
│
├── z_score.py           # Main analysis script
├── medium_data.csv      # Population data (student reading times)
├── sample_1.csv         # Sample 1: Students with math labs
├── sample_2.csv         # Sample 2: Students using practice app
└── sample_3.csv         # Sample 3: Students with enforced registers
```

## 🚀 Installation & Usage

### Prerequisites

- Python 3.7 or higher
- pip package manager

### Setup

1. **Clone the repository**
```bash
git clone https://github.com/Aryansharma906/project111.git
cd project111
```

2. **Install dependencies**
```bash
pip install pandas plotly statistics
```

3. **Run the analysis**
```bash
python z_score.py
```

## 📊 How It Works

### 1. Sampling Distribution Generation
```python
# Creates 1000 sample means, each from 100 random data points
for i in range(0, 1000):
    set_of_means = random_set_of_mean(100)
    mean_list.append(set_of_means)
```

### 2. Statistical Calculations
- **Mean of sampling distribution**: Central tendency
- **Standard Deviation**: Measure of spread
- **Confidence Intervals**: 68%, 95%, 99.7% (1σ, 2σ, 3σ)

### 3. Sample Comparisons
- **Sample 1**: Students who had extra math lab time
- **Sample 2**: Students who used math practice app
- **Sample 3**: Students enforced with math registers

### 4. Z-Score Calculation
```python
z_score = (mean - mean_of_sample) / std_deviation
```

## 📈 Output

The script generates:

1. **Console Output**:
   - Mean of sampling distribution
   - Standard deviation
   - Mean of each sample group
   - Z-score value

2. **Interactive Plots** (3 visualizations):
   - Distribution curve with sample 1 mean
   - Distribution curve with sample 2 mean
   - Distribution curve with sample 3 mean
   - Standard deviation markers

## 🎓 Statistical Concepts

### Sampling Distribution
A distribution of sample means representing the population mean

### Z-Score
Measures how many standard deviations a data point is from the mean:
- **|z| < 1**: Within 1 standard deviation (68%)
- **|z| < 2**: Within 2 standard deviations (95%)
- **|z| < 3**: Within 3 standard deviations (99.7%)

### Interpretation
- High |z-score| (>2): Statistically significant difference
- Low |z-score| (<1): Not significantly different from mean

## 📝 Customization

### Using Your Own Data

1. Replace `medium_data.csv` with your population data
2. Ensure CSV has a `reading_time` column
3. Update sample CSV files (`sample_1.csv`, `sample_2.csv`, `sample_3.csv`)
4. Modify column names in the script if needed

```python
# Change the data source
df = pd.read_csv("your_data.csv")
data = df["your_column_name"].tolist()
```

## 🔧 Configuration

- **Sample Size**: Change `random_set_of_mean(100)` - modify the 100
- **Number of Samples**: Change `range(0,1000)` - modify the 1000
- **Plot Style**: Customize Plotly figures in the code

## 📚 Learning Outcomes

- ✅ Understanding sampling distributions
- ✅ Central Limit Theorem application
- ✅ Statistical significance testing
- ✅ Data visualization with Plotly
- ✅ Working with CSV data in Python
- ✅ Practical statistics implementation

## 🎯 Use Cases

- **Education**: Teaching statistics and probability
- **Research**: Analyzing experimental data
- **Quality Control**: Process analysis
- **A/B Testing**: Comparing two groups

## 🐛 Troubleshooting

**Import Errors?**
- Install missing packages: `pip install pandas plotly`

**CSV File Not Found?**
- Ensure CSV files are in the same directory
- Check file names match exactly

**No Plot Displayed?**
- Plotly requires a browser to display interactive plots
- Check if browser opens automatically

## 🤝 Contributing

Contributions welcome! Feel free to:
1. Fork the repository
2. Add new statistical tests
3. Improve visualizations
4. Enhance documentation
5. Submit pull requests

## 📜 License

Open-source for educational and personal use.

## 📬 Connect

**✨ Aryan Sharma ✨**

💻 Where algorithms dream and melodies spark

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aryan-sharma-6a7b85317/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/Aryansharma906)

🎓 Student | 📊 Data Science Enthusiast | 💻 Python Developer

### ⭐ Star this repo if you found it helpful!

**Built with 💜 by Aryan Sharma**

*Making statistics accessible through code* 📊✨
