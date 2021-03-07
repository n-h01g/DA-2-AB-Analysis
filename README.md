<p align="center">
  <a href="https://www.udacity.com/">
    <img src='https://course_report_production.s3.amazonaws.com/rich/rich_files/rich_files/5511/s300/udacity-logo.png' alt="Udacity logo" width = 100px>
   </a>
</p>

<h1 align="center"><a href = "https://www.udacity.com/course/data-analyst-nanodegree--nd002"> Udacity Data Analyst Nanodegree </a></h1>
<h2 align="center">Project II: Practical Statistics<br><br>Analysis of A/B Test Results</h2>

### Tools and Skills Used

#### Tools
- Python 3.6.3
  - numpy
  - pandas
  - matplotlib
  - random
- Jupyter Notebook

#### Skills
- Data exploration
- A/B testing
- Bootstrapping
- Statistical analysis

### Project Details

#### Introduction
A/B tests are very commonly performed by data analysts and data scientists. 

For this project, a company developed a new e-commerce web page in order to increase the number of users who "convert", meaning the number of users who decide to pay for the company's product. I worked to understand the results of an A/B test run and understand if the company should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

#### Project Details
The Project was divided into three parts: 
Part I - Probability
> Statistics were computed to find out the probabilities of converting regardless of page. These were used to analyze if one page or the other led to more conversions.

Part II - A/B Test
> Next, hypothesis testing was conducted assuming the old page is better unless the new page proves to be definitely better at a Type I error rate of 5%. The data was bootstrapped and sampling distributions were determined for both pages. Conclusions were drawn on conversions for both pages by calculating p-values.

Part III - Regression
> Logistic regression was then performed to confirm results of the previous steps. Null and alternative hypotheses associated with this regression model were stated and verified using statsmodel.

#### Result
There was not sufficient evidence to suggest that the new page converts better than the old one.
