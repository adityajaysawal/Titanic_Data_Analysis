# Titanic_Data_Analysis

**Exploratory Data Analysis (EDA) on Titanic Dataset**

The Titanic dataset contains information about passengers, including demographics, ticket details, and whether they survived the disaster. The goal of the EDA was to investigate patterns and relationships between various features to understand what factors may have contributed to passenger survival.

1. **Data Cleaning**:  
   - **Missing Values**: Identified missing values in columns such as `Age`, `Cabin`, and `Embarked`. Imputed missing values for `Age` using the median, while rows with missing `Cabin` data were either removed or categorized as “Unknown.” Missing values in `Embarked` were filled with the most frequent port.
   - **Data Types and Duplicates**: Verified the data types of each column and checked for duplicates, ensuring data consistency.

2. **Univariate Analysis**:  
   - **Survival Rate**: Analyzed the overall survival rate; approximately 38% of passengers survived.
   - **Passenger Class (Pclass)**: Observed that passengers in higher classes had higher survival rates. First-class passengers had the highest survival rate, followed by second and third class.
   - **Gender**: Noted a strong gender-based survival disparity, where females had a significantly higher survival rate than males.
   - **Age Distribution**: Visualized the age distribution, identifying that children had a higher chance of survival. The dataset included a wide range of ages, with a significant number of passengers in their 20s and 30s.

3. **Bivariate Analysis**:  
   - **Survival vs. Pclass**: A positive correlation between passenger class and survival, where those in first-class cabins had a better chance of survival.
   - **Survival vs. Gender**: Explored the relationship between gender and survival. Female passengers had a survival rate close to 75%, while male passengers had a survival rate below 20%.
   - **Survival vs. Age**: Investigated the survival rates across different age groups. Children (age <16) had higher survival rates compared to adults.
   - **Fare**: Higher fares were associated with better survival rates, likely linked to passenger class.

4. **Multivariate Analysis**:  
   - Combined features like `Pclass`, `Sex`, and `Fare` to analyze survival trends. For example, females in first class had the highest survival rate, while males in third class had the lowest.
   - Explored interactions between age, class, and gender to uncover more complex survival patterns.

5. **Visualization Techniques**:  
   Used bar plots, histograms, box plots, and heatmaps to visualize relationships between variables. For instance:
   - Bar plots were used to display survival rates across different classes and genders.
   - Box plots highlighted the distribution of fare prices by class and survival.
   - Heatmaps helped in identifying correlations between numerical variables like `Age`, `Fare`, and `Pclass`.

6. **Key Insights**:  
   - Gender played a crucial role in survival, with women having a far higher survival rate than men.
   - First-class passengers had significantly better chances of survival than those in second or third class.
   - Age was also a determining factor, with younger passengers, especially children, being more likely to survive.
   - Higher fares were positively correlated with survival, indicating wealthier passengers had better access to lifeboats.
     
This analysis provided valuable insights into the factors that influenced survival on the Titanic, offering a deeper understanding of the impact of socio-economic status, gender, and age.
