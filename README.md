Healthcare Insurance Cost Analysis Assessment


Healthcare Insurance Cost Analysis Assessment is a comprehensive data analysis tool designed to streamline data exploration, analysis, and visualisation. The tool supports multiple data formats and provides an intuitive interface for both novice and expert data scientists.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Content
* The data set i used was the Healthcare Insurance Dataset by willian oliveira.
(https://www.kaggle.com/datasets/willianoliveiragibin/healthcare-insurance/data)
The dataset contains the following information:
Age: The insured person's age.

Sex: Gender (male or female) of the insured.

BMI (Body Mass Index): A measure of body fat based on height and weight.

Children: The number of dependents covered.

Smoker: Whether the insured is a smoker (yes or no).

Region: The geographic area of coverage.

Charges: The medical insurance costs incurred by the insured person.


## Business Requirements
* I wanted to analyse the factors influencing healthcare insurance costs and identify key trends and patterns. Which will help in making informed decisions regarding pricing strategies and risk assessments for insurance providers and future insights.

## Hypothesis and how to validate?
* The hypothesis is that certain demographic and health-related factors significantly influence healthcare insurance costs. To validate this, I have performed statistical analysis and visualisations to identify correlations between these factors and the insurance charges. 
The analysis revealed that factors such as age, BMI, smoking status, and gender have varying degrees of impact on insurance costs.
As validated in my Data_visualisation notebook, i have come to these conclusions:
-Older policy holders tend to have higher insurance charges.
-Women with higher BMI may face increased insurance costs.
-Women who smoke may also face higher premiums.
-Men who don't smoke may have lower insurance costs.
-Men with lower BMI may have lower insurance costs.
-From our data we can also say that location and number of children provides inconclusive/low evidence regarding its impact on insurance costs.

## Project Plan
* I collected the raw data from the Healthcare Insurance Dataset by William Oliveira.
* I then cleaned the raw data to ensure its quality and suitability for analysis.
* while cleaning the data i found an outlier in the age column, which was significantly higher than the rest of the data. I decided to remove this outlier to prevent it from skewing the analysis. While also checking for duplicates i found initially it seemed to be clear, then after standardising the text data i found some duplicates that were not initially apparent. After making sure all of the data was cleaned and processed without any issues, I proceeded to the visualisation stage.
This process involved creating various plots and charts to illustrate the relationships between the different factors and insurance charges, ultimately leading to my hypothesis.


## Analysis techniques used
* I used data cleaning to remove outliers and duplicates.to ensure the data provided was accurate and reliable. I also used correlation analysis to see the relationship between factors such as: age, BMI, smokers and insurance charges. i also used featyre engineering to creat new vaiables such as age groups and BMI categories.
* I structured the analysis techniques in a logical flow, starting with data cleaning, followed by analysing the cleaned data for patterns and insights. If i found any significant patterns, I would then visualise these findings and focus less on data that showed less significance such as number of children and location.
* I found a few challenges in my project when using AI to help with blocks of code which i left comments in the notebook to visually show why double checking work is nessessary. The AI code used the lowest possible outcomes even though the data wasn't represented in the data set. 
* I used the following libraries for data analysis: pandas, numpy, matplotlib, seaborn, and plotly. These libraries provided the necessary tools for data manipulation, statistical analysis, and visualisation.


## Ethical considerations
* All data was handled in accordance with relevant data protection regulations and ethical guidelines. This included anonymising personal information and ensuring that the data was used solely for the purposes of this analysis with no personal identifiable information being exposed.


## Unfixed Bugs
* As being a beginner in data analysis and this being my first project i did have to resort to using AI tools for some blocks of code, which sometimes produced unexpected results. I plan to revisit these sections and improve my understanding of the underlying concepts to fix any issues. As stated earlier, I left comments in the notebook to visually show why double-checking work is necessary.



## Main Data Analysis Libraries
* Pandas: Used for data manipulation and analysis, particularly for handling data frames.
* NumPy: Used for numerical operations and handling arrays.
* Matplotlib: Used for creating static visualizations and plots.
* Seaborn: Built on top of Matplotlib, used for making statistical graphics and visualizations more attractive and informative.
* Plotly: Used for creating interactive visualizations and dashboards.

## - Best Practices & Notes
* for future projects i will avoid using a direct path for my data files and instead i will use .env files and push them to .gitignore to keep sensitive information secure.


## Credits 

* The project was inspired by the Healthcare Insurance Dataset by William Oliveira, which provided the raw data for analysis.
* The use of AI tools from ChatGPT helped in generating code snippets and providing explanations for complex concepts.
* My mentor/tutor from CodeInstitute provided guidance and support throughout the project. Thank you Vasi!


## Project Review and Conclusion
* From this dataset, I was able to identify that Age, BMI and Smoking will significantly raise the cost of insurance. Number of children nudges costs up. Region and sex have comparatively small effects. Charges in this sample range from very low (around 1–3k) to very high (40–65k), with smokers and high-BMI, older members clustering in the top end.

* In the future i would like to use data that includes more diverse demographics and a wider range of health conditions to gain a more comprehensive understanding of the factors influencing insurance costs such as pre-existing conditions, such as diabetes and heart disease. Another factor when concluding my findings could be that the smokers are self reported so their accuracy may be questionable.

* If i presented this data to stakeholders, i would highlight 4 main groups:
  1. Low Risk - £1,000 - £5,000 - non-smokers, healthy BMI, age range 18-35
  2. Medium Risk - £5,000 - £15,000 - non-smokers, higher BMI, age range 35-55
  3. High Risk - £15,000 - £30,000 - smokers, high BMI, age range 45-65
  4. Very High Risk - £30,000+ - smokers, overweight BMI, age range 35-65


* From my conclusion, This project successfully transformed a raw health insurance dataset into clear, actionable insights by applying a structured ETL process, careful data cleaning, and focused exploratory analysis. The findings highlight smoking status, age, and BMI as the most influential drivers of healthcare charges, while also revealing the limited impact of region and number of children. The visualisations effectively communicate these relationships, making the data accessible and understandable for stakeholders. The project demonstrates the value of data-driven decision-making in healthcare insurance, providing a solid foundation for future analyses and strategic planning.