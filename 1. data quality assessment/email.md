Hi there, 

As per voicemail, please find 3 datasets attached from Sprocket Central Pty Ltd:
- New Customer List
- Customer Demographics
- Customer Addresses
- Transcation data in the past three months

I notice some irregular data entries which may affect the future analysis. 
Can you please review the data quality to ensure it is ready for our analysis in phase two.

Here are the problems I found in each dataset, please take a look to ensure these data points are correct.

| Datasets | Problems | 
| -------- | -------- | 
| Transaction | found 0 product id |
| Transaction | unknown data type of product_first_sold_date |
| NewCustomerList | there are four unknown column names after property_valuation and before Rank |
| NewCustomerList | missing values exist from in following attributes: last_name, DOB, job_title, job_industry_category |
| NewCustomerList | rank attribute doesn't contain unique values, need be double checked |
| CustomerDemographics | missing values exist in the following attributes: last_name, DOB, job_title, job_industry_category, default and tenure |
| CustomerDemographics | inconsistent date entry in gender attribute |
| CustomerDemographics | row index 33 has a DOB of 1843-12-21 which is impossible |
| CustomerDemographics | default attribute contains unknown characters |


I've also attached a data quality framework as a guideline. Let me know if you have any questions.

Kind regards
