**Demographic-Driven Advertisement Optimization**  
**Course**: CSI 4142 - Fundamentals of Data Science  
**Group 33 Members**: Dana Shayakhmetova, Tanner Guiddings, Coralie Ostertag

### Project Overview:
The "Demographic-Driven Advertisement Optimization" project aims to provide insights into customer behavior and improve marketing campaign performance through data-driven analysis. Using customer demographic data, spending patterns, web activity, and response to marketing campaigns, the project develops a data mart to facilitate in-depth analysis and model-driven predictions for optimizing advertisements.

### Phase 1: Data Modeling & Design  
- **Objective**: Create a dimensional model that captures the necessary metrics for evaluating customer behavior and ad campaign effectiveness.
- **Key Tasks**:
  - Identified key business processes such as customer purchases, marketing responses, web visits, and customer complaints.
  - Defined a **Data Mart Schema** focusing on fact and dimension tables (e.g., Customer, Campaign, and Transaction tables).
  - Established the **Grain** of each table to ensure data granularity and clarity.
  - Mapped relationships between tables for effective data querying and reporting.

### Phase 2: Data Staging & Data Mart Creation  
- **Objective**: Implement an ETL process to extract, transform, and load customer and marketing data into a data mart.
- **Key Tasks**:
  - Extracted customer data from multiple sources and cleaned it to ensure accuracy.
  - Performed **data transformations** like handling missing values, outlier detection, and feature engineering for demographic segmentation.
  - Loaded the transformed data into a **PostgreSQL database hosted on Supabase**, ensuring the data mart supported efficient querying.
  - Connected Colab to Supabase for data exploration and analysis.

### Phase 3: Data Exploration & Analysis  
- **Objective**: Perform exploratory data analysis (EDA) to extract meaningful insights from the data.
- **Key Tasks**:
  - Conducted **descriptive statistics** and visualized the data using scatter plots, box plots, and histograms to understand customer spending and campaign responses.
  - Identified patterns in customer behavior based on **age, gender, income**, and **campaign interactions**.
  - Used **correlation analysis** to determine the impact of different demographics on campaign success and overall spending behavior.
  - Applied outlier detection methods to clean and enhance data quality further.

### Phase 4: Data Mining & Model Development  
- **Objective**: Use supervised learning techniques to predict ad campaign success and optimize future strategies.
- **Key Tasks**:
  - Applied machine learning models like **Decision Trees, Gradient Boosting, Random Forest, and SVM** to classify campaign responses based on customer demographics and spending habits.
  - Evaluated model performance using metrics like **accuracy, precision, recall, and F1-score**, and performed **hyperparameter tuning** for optimal results.
  - Generated actionable insights to improve future ad targeting, with recommendations for demographic-based advertisement strategies.
  - Documented findings and prepared a one-page summary for easy understanding.
