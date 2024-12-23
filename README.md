# Korean Entertainment Analysis

## Project Overview
This project dives deep into analyzing the longevity and success factors of K-pop idols within the Korean entertainment industry. By leveraging advanced data analysis and visualization techniques, the goal is to uncover key patterns that contribute to the sustained popularity and career spans of K-pop idols.

### Key Highlights:
- **Data-Driven Insights**: Explore correlations between debut years, group dynamics, and individual success.
- **Predictive Analysis**: Identify potential longevity factors using machine learning models.
- **Interactive Visualizations**: Engage with detailed and dynamic visual content for actionable insights.

---

## File Descriptions

### 1. `kpop_idol_longevity_analysis.ipynb`
The core Jupyter Notebook containing:
- Data preprocessing pipelines.
- Exploratory Data Analysis (EDA).
- Advanced visualizations and statistical inferences.
- Predictive modeling techniques applied to K-pop idol data.

### 2. `cleaned_kpop_data.csv`
A cleaned and enriched dataset with comprehensive attributes for K-pop idols. Key columns include:
- **Name**: The name of the idol.
- **Group**: Affiliated group(s) or solo status.
- **Debut Year**: Year of debut in the entertainment industry.
- **Activity Span**: Calculated longevity based on career duration.

### 3. `kpopidolsv3.csv`
A raw dataset containing extensive but unprocessed information about K-pop idols. Use this for experimental preprocessing or as a backup reference.

---

## Dataset Source
The datasets used in this project originate from the Kaggle repository:
[K-pop Idol Dataset by Nicol Salayo Arias](https://www.kaggle.com/datasets/nicolsalayoarias/all-kpop-idols/suggestions?status=pending&yourSuggestions=true). This dataset includes detailed information about idols, their groups, and key metrics relevant to their careers.

---

## Installation

1. Clone the repository:
```bash
$ git clone [REPOSITORY_URL]
```
2. Install the required Python dependencies:
```bash
$ pip install -r requirements.txt
```
3. Ensure Jupyter Notebook is installed:
```bash
$ pip install notebook
```

---

## Usage

### Step 1: Run the Analysis
   Open the `kpop_idol_longevity_analysis.ipynb` file in Jupyter Notebook to perform the following:
   - Preprocess the datasets.
   - Explore trends in idol longevity.
   - Generate predictive models for career success.

   ```bash
   $ jupyter notebook kpop_idol_longevity_analysis.ipynb
   ```

### Step 2: Load Data
   Place `cleaned_kpop_data.csv` and `kpopidolsv3.csv` in the data directory or update the paths in the notebook accordingly.

### Step 3: Visualize Insights
   Interactive charts and plots in the notebook provide an engaging way to explore:
   - Longevity distributions.
   - Key factors influencing career spans.
   - Predictive outcomes.

---

## Results and Insights
Key findings from the analysis include:
- **Longevity Trends**: Insights into the average career span of idols based on debut year and group dynamics.
- **Predictive Modeling**: Identified factors like training duration, debut age, and group size that correlate with longevity.
- **Visual Storytelling**: Custom interactive charts that make the insights easy to understand and presentable.

Detailed outcomes, predictive models, and visualizations are documented in the notebook.

---

## License
This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgments
- The K-pop fandom community for curating invaluable datasets.
- Open-source tools like Pandas, Matplotlib, and Scikit-learn for enabling robust analysis.
- [Kaggle Dataset by Nicol Salayo Arias](https://www.kaggle.com/datasets/nicolsalayoarias/all-kpop-idols/suggestions?status=pending&yourSuggestions=true) for providing detailed idol information.
- Inspiration from the creativity and resilience of K-pop idols :)
