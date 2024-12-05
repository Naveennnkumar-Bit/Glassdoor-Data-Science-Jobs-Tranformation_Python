# Data Science Job Posting on Glassdoor 📊💼

## **Overview**  
This project focuses on cleaning and preprocessing data science job postings from Glassdoor. The dataset was cleaned to ensure consistency and accuracy, preparing it for further analysis or modeling.

---

![Glassdoor Dataset](https://example.com/path-to-image.jpg)  *(Replace with an appropriate image)*

---

## **Skills Demonstrated**  
- Data cleaning and transformation using Python.  
- Handling missing values, parsing salary data, and processing job descriptions.  
- Feature engineering for job title simplification and state normalization.

---

## **Challenges and Solutions**  

- **Salary Parsing**: Cleaned salary values by removing unwanted text and symbols like "$" and "K".  
  - **Solution**: Utilized regular expressions to extract only numeric salary values and applied conversion to standardize formats.

- **Company Name and State Processing**: Extracted relevant company information and standardized state fields for consistency.  
  - **Solution**: Used string splitting and regex to clean and normalize company names and state values.

- **Job Description Analysis**: Extracted key skills (e.g., Python, AWS) and calculated job description length.  
  - **Solution**: Applied text processing techniques to identify and list skills from job descriptions, also computed job description lengths for analysis.

- **Hourly Wage Conversion**: Converted hourly wages to annual salaries for consistency.  
  - **Solution**: Assumed a 40-hour work week and 52 weeks per year to compute annual salary values from hourly rates.

- **Handling Missing or Null Values**: Identified missing or incomplete data in critical fields like salary and job titles.  
  - **Solution**: Filled missing values with appropriate placeholders or used data imputation techniques where necessary.

- **Inconsistent Data Formats**: Dealt with multiple formats in job titles and salaries (e.g., "per hour", "employer provided salary").  
  - **Solution**: Standardized the formats by creating separate columns for hourly and employer-provided salaries and removing redundant terms from original salary fields.

- **State Normalization**: Los Angeles was listed inconsistently with various states.  
  - **Solution**: Standardized all occurrences of Los Angeles to the state of California (CA) for consistency.

---

## **Tools Used** 🛠️  
- **Python**: For data cleaning, transformation, and feature engineering.  
- **Pandas**: To manipulate and preprocess data.

---

## **Key Takeaways**  
- Cleaned dataset with structured salary and job information.  
- Enhanced dataset with relevant features such as job title categorization and company age.

---

## **Future Improvements**  
- Build predictive models using the cleaned data.  
- Perform exploratory data analysis (EDA) to uncover trends and patterns in job postings.

---

## **Contact** ✉️  
Feel free to reach out with feedback or questions!
