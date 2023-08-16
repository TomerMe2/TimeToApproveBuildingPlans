# Factors Influencing Forecasting of Approval Time for Building Plans in Israel: Unveiling Insights for Urban Development

## Abstract
The approval process for building plans exerts a profound impact on our society. Understanding the factors that contribute to accurately forecasting the approval time for building plans in Israel is pivotal for enabling informed decision-making and gaining foresight into the future urban landscape. This work delves into the exploration of key elements that aid in predicting the time it takes to approve building plans in Israel, shedding light on the underlying dynamics that influence the process. By leveraging machine learning models and analyzing relevant factors, we uncover valuable insights into the determinants that shape approval timelines. Our study pioneers this investigation, focusing on uncovering the factors that play a crucial role in forecasting the approval time for building plans in Israel. The findings from this research offer essential knowledge to stakeholders, policymakers, and urban development professionals, facilitating informed decision-making and enabling a better understanding of the approval process for building plans in Israel.

## Data Sources Used
### From [Meirim's Database](https://github.com/meirim-org/meirim)
1. Plan committee (local or regional)
2. Plan geographic data (location, area, city)
3. Plan submitter (from table 1.8.1 of the plan's instructions)
4. Allowed usages (from table 4 of the plan's instructions)

### From [the Israeli Central Bureau of Statistics (Lamas)](https://www.cbs.gov.il/he/publications/Pages/2023/%D7%90%D7%A4%D7%99%D7%95%D7%9F-%D7%99%D7%97%D7%99%D7%93%D7%95%D7%AA-%D7%92%D7%90%D7%95%D7%92%D7%A8%D7%A4%D7%99%D7%95%D7%AA-%D7%95%D7%A1%D7%99%D7%95%D7%95%D7%92%D7%9F-%D7%9C%D7%A4%D7%99-%D7%94%D7%A8%D7%9E%D7%94-%D7%94%D7%97%D7%91%D7%A8%D7%AA%D7%99%D7%AA-%D7%9B%D7%9C%D7%9B%D7%9C%D7%99%D7%AA-%D7%A9%D7%9C-%D7%94%D7%90%D7%95%D7%9B%D7%9C%D7%95%D7%A1%D7%99%D7%99%D7%94-%D7%91%D7%A9%D7%A0%D7%AA-2019.aspx)
1. Statistical Areas within Municipalities and Local Councils
2. Settlements within Regional Councils
Both used for socio-economic features.

## Results
### Time to Approve Plans In the Most Common Cities\Settlements
TODO PLOT HERE

### Accuracy
We split our target range into 5 equal parts.
We trained a classifier on these categories and our classifier acheives an accuracy of 37.65% compared to a base-rate of 19.61%
The confusion matrix is:
TODO CONF MAT

### Most Important Features
We extracted the important features from the feature importance that is reported by the classifier that we trained.
