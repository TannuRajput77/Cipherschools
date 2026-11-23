# CipherSchools: Python, Data Science & Machine Learning

My notes, practice notebooks and final project from the CipherSchools **Python, Data Science & Machine Learning
Integrated** training (July 2024). The completion certificate is included as `TANNU_KUMARI.pdf`.

The course goes from spreadsheets to machine learning in 38 lectures. Each `Lecture N - ...` file holds my notes
for that lecture: definitions, key points and examples.

## Course map

| Module | Lectures | Topics |
|---|---|---|
| Foundations | 0-6 | What data science is, key skills and tools, Anaconda, Google Colab, Git version control |
| Excel | 7-12 | Advanced formulas, data cleaning, date and time functions, Pivot Tables and Pivot Charts, Power Query, macros and VBA |
| Python | 13-16 | Variables, data types, loops, functions, lambdas, error handling, NumPy, pandas |
| Visualisation and BI | 17-22 | Design principles, Matplotlib, Seaborn, interactive Plotly, Power BI dashboards, data modelling and DAX |
| Statistics | 23-25 | Distributions, correlation, hypothesis testing and inference |
| Data preparation | 26-28 | Cleaning and normalisation, outliers, feature engineering and selection |
| Machine learning | 29-32 | Supervised learning (linear and logistic regression, decision trees), unsupervised learning, neural networks |
| Applied projects | 33-38 | NLP and chatbots, Dash and Plotly web apps, image processing and a simple image classifier |

## Practice notebooks

| Notebook | What it covers |
|---|---|
| `Python_Fundamentals_2.ipynb` | Core Python practice |
| `Data_Manipulation_and_Analysis_with_NumPy_(1).ipynb` | NumPy arrays, indexing, maths and statistics |
| `Working_with_Data_using_Pandas_(1).ipynb` | Loading, filtering, grouping and cleaning data with pandas |
| `Introduction_to_Matplotlib_and_Seaborn.ipynb` | Static charts |
| `Using_Plotly_for_Data_Visualization.ipynb` | Interactive charts |
| `Main/Lecture 36 - .../chatbot_app.ipy`, `chatbot_dataset.csv` | Chatbot integrated into a Python web app |

## Final project: mall customer analysis

`course_project.ipynb` analyses the Mall Customers dataset (gender, age, annual income, spending score) to
understand spending behaviour for targeted marketing:

1. Load the data and inspect it (`info`, `head`, `describe`)
2. Fix column names, check missing values, encode gender
3. Compare total spending and income by gender
4. Visualise the distributions of age, income and spending score
5. Plot age vs spending and income vs spending to find customer patterns

The clustering follow-up is in
[CipherSchools-Image_Classification_project](https://github.com/TannuRajput77/CipherSchools-Image_Classification_project),
and the chatbot project is in
[CipherSchools-chatbot_project](https://github.com/TannuRajput77/CipherSchools-chatbot_project).

## Tools used

Excel · Power Query · VBA · Python · NumPy · pandas · Matplotlib · Seaborn · Plotly · Dash · Power BI ·
scikit-learn · NLTK · Google Colab · Git

## Run the notebooks

```bash
pip install numpy pandas matplotlib seaborn plotly jupyter
jupyter notebook
```

The notebooks were written in Google Colab, so data paths start with `/content/`; change them to the local file
name when running on your own machine.

## Author

Tannu Kumari · [GitHub](https://github.com/TannuRajput77) · [LinkedIn](https://linkedin.com/in/tannu-singh1)
