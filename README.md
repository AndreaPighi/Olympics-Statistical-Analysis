# Olympics Statistical Analysis (1896 - 2024) 🏅

This project analyzes historical data of Olympic athletes from the first editions of **Athens 1896** to **Paris 2024**. The goal is to explore the relationships between physical characteristics (age, height, weight, BMI) and competitive success, using **Statistical Learning** techniques and inferential analysis.

## 📊 The Dataset

The dataset consists of **8,500 observations** and **30 variables**, covering 128 years of history and 33 sports disciplines.

### Dataset Source 📍
The dataset was retrieved from **Kaggle**:
👉 [**Olympics Athletes (1896 - 2024)**](https://www.kaggle.com/datasets/ashyou09/olympics-athletes-dataset-18962024) by *Ashyou09*.

> [!NOTE]
> The dataset is semi-synthetic/processed (as indicated by the athlete names and the impeccable data cleaning), making it ideal for educational purposes and testing statistical inference models.

## 🔬 Research Questions

The analysis focused on three fundamental questions:

1.  **Physical-Performance Correlation**: Is there a significant relationship between an athlete's age, height, and weight and their probability of winning?
2.  **Age Trend**: How has the average age of gold medalists changed over a century (1896–2024)?
3.  **Seasonal Comparison**: Does the age of champions differ significantly between the Summer and Winter Games?

## 🛠️ Technologies Used

The project is entirely developed in **Jupyter Notebook** using the main libraries in the Python Data Science landscape:

-   **Pandas & Numpy**: Data manipulation and pre-processing.
-   **Matplotlib & Seaborn**: Advanced graphical visualization.
-   **Scipy (stats)**: Execution of inferential tests (Mann-Whitney, Welch's t-test, Chi-square).

## 📈 Main Results

The analyses conducted led to several interesting conclusions:

*   **Biological Stability**: The average age of gold medalists has remained incredibly stable over time, oscillating between **28 and 29 years** (95% CI: [28.01, 29.22]), suggesting a universal biological limit for peak performance.
*   **Gender Independence**: The Chi-square test detected no significant differences in success rates between men (23.1%) and women (24.1%).
*   **Sport Variability**: No strong linear correlation was found between BMI and medals at a global level. This demonstrates that Olympic success depends more on technical and psychological factors than on a single "optimal" physical profile valid for all sports.

## 🚀 Installation and Usage

To reproduce the analysis on your computer, follow these steps:

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/Olympics.git
    cd Olympics
    ```

2.  **Install dependencies**:
    Ensure you have `pip` updated and install the necessary libraries:
    ```bash
    pip install pandas numpy matplotlib seaborn scipy notebook
    ```

3.  **Launch Jupyter Notebook**:
    ```bash
    jupyter notebook
    ```
    Open the `Olimpiadi.ipynb` file and select "Run All Cells" to view the entire analysis.

> [!IMPORTANT]
> Ensure that the file `olympics_dataset.csv` is present in the main project folder before starting the notebook.

---

*Project created for the Statistical Learning exam.*
