# Data Science Job Posting on Glassdoor 📊💼

## **Overview**  
This project focuses on cleaning and preprocessing data science job postings from Glassdoor. The dataset was cleaned to ensure consistency and accuracy, preparing it for further analysis or modeling. The final cleaned dataset can be used to identify trends in job titles, salaries, skills required, and other factors across the data science job market.

---

![Glassdoor Dataset](https://github.com/Naveennnkumar-Bit/Glassdoor-Data-Science-Jobs-Tranformation_Python/blob/main/GD.jpg)

---

## **Skills Demonstrated**  
- Data cleaning and transformation using Python.  
- Handling missing values, parsing salary data, and processing job descriptions.  
- Feature engineering for job title simplification and state normalization.

---

## **Challenges and Solutions**  

- **Salary Parsing**: Cleaned salary values by removing unwanted text and symbols like "$" and "K".  
  - **Solution**: Utilized regular expressions to extract only numeric salary values and applied conversion to standardize formats, ensuring uniformity for analysis.

- **Company Name and State Processing**: Extracted relevant company information and standardized state fields for consistency.  
  - **Solution**: Used string splitting and regex to clean and normalize company names and state values, which ensures consistency in future analysis.

- **Job Description Analysis**: Extracted key skills (e.g., Python, AWS) and calculated job description length.  
  - **Solution**: Applied text processing techniques to identify and list skills from job descriptions, which helps in identifying skill requirements across companies.

- **Hourly Wage Conversion**: Converted hourly wages to annual salaries for consistency.  
  - **Solution**: Assumed a 40-hour work week and 52 weeks per year to compute annual salary values from hourly rates, ensuring all salary data is comparable.

- **Handling Missing or Null Values**: Identified missing or incomplete data in critical fields like salary and job titles.  
  - **Solution**: Filled missing values with appropriate placeholders or used data imputation techniques where necessary, ensuring no valuable data is lost.

- **Inconsistent Data Formats**: Dealt with multiple formats in job titles and salaries (e.g., "per hour", "employer provided salary").  
  - **Solution**: Standardized the formats by creating separate columns for hourly and employer-provided salaries and removing redundant terms from original salary fields.

- **State Normalization**: Los Angeles was listed inconsistently with various states.  
  - **Solution**: Standardized all occurrences of Los Angeles to the state of California (CA) for consistency, which made the location data more reliable.

---

## **Tools Used** 🛠️  
- **Python**: For data cleaning, transformation, and feature engineering.  
- **Pandas**: To manipulate and preprocess data.

---

## **Key Takeaways**  
- Cleaned dataset with structured salary and job information, making it ready for deeper analysis.  
- Enhanced dataset with relevant features such as job title categorization and company age, which could be used for various data-driven insights.

---

## **Future Improvements**  
- Build predictive models using the cleaned data, for example, predicting salary based on job title, location, and experience.  
- Perform exploratory data analysis (EDA) to uncover trends and patterns in job postings, such as salary disparities or the most common skills required for data science roles.

---

## **Contact** ✉️  
Feel free to reach out with feedback or questions!
