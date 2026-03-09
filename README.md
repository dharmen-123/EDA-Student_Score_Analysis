# Student Score Analysis – EDA Project
📌 Overview
This project performs Exploratory Data Analysis (EDA) on a dataset of student performance. The goal is to uncover insights into how demographic, parental, and lifestyle factors influence student scores in Math, Reading, and Writing.
The analysis uses Python (Pandas, NumPy, Matplotlib, Seaborn) to clean, explore, and visualize the dataset.

🛠️ Steps in the Project
* Import Libraries    
    - NumPy, Pandas, Matplotlib, Seaborn    
* Load Dataset    
    - student_scores.csv containing 30,641 student records    
    - Columns include: Gender, EthnicGroup, ParentEduc, LunchType, TestPrep, ParentMaritalStatus, PracticeSport, IsFirstChild, NrSiblings, TransportMeans,             - WklyStudyHours, and scores in Math, Reading, Writing    
* Data Cleaning    
    - Dropped unnecessary Unnamed: 0 column    
    - Checked for missing values across categorical and numerical features    
    - Exploratory Analysis & Visualizations    
    - Gender Distribution: Countplot showing more female students than male    
    - Parent Education vs Scores: Heatmap showing higher parental education correlates with better student scores    
    - Outlier Detection: Boxplots for Math, Reading, and Writing scores    
    - Ethnic Group Distribution: Pie chart and countplot showing percentage breakdown across groups    

📈 Key Insights
- Gender: Female students slightly outnumber male students.
- Parental Education: Students with parents holding a master’s or bachelor’s degree tend to score higher across all subjects.
- Outliers: Boxplots reveal extreme values in test scores, useful for further statistical treatment.
- Ethnic Groups: Group C has the largest representation (~32%), followed by Group D and Group B.

📂 Project Structure

Students_Result_Analysis-Project/    
│── Student_Score_Analysis.ipynb   
│── student_scores.csv            
│── README.md                  


🚀 Technologies Used
- Python 3.12
- Pandas – data manipulation
- NumPy – numerical operations
- Matplotlib & Seaborn – visualizations
- Jupyter Notebook – interactive analysis

🎯 Purpose
This project demonstrates how EDA techniques can be applied to educational datasets to:
- Identify performance trends
- Highlight disparities across demographic groups
- Provide a foundation for predictive modeling or machine learning

📌 Future Work
- Apply statistical tests to validate observed trends
- Build predictive models (e.g., regression, classification)
- Explore feature importance for student performance
