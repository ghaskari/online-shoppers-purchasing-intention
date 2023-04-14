# Online Shoppers Purchasing Intention

## Introduction
This dataset contains information on online shoppers' behavior and purchasing intentions. The data set includes feature vectors for 12,330 user sessions over a period of one year, with the aim of avoiding bias towards specific campaigns, special days, user profiles, or periods.

## Attribute Information
The dataset consists of 18 attributes, with 10 numerical and 8 categorical features. The "Revenue" attribute serves as the class label, indicating whether the user made a purchase during the session.

The numerical attributes are:

- Administrative
- Administrative Duration
- Informational
- Informational Duration
- Product Related
- Product Related Duration
- Bounce Rate
- Exit Rate
- Page Value
- Special Day


The categorical attributes include:

- Operating system
- Browser
- Region
- Traffic type
- Visitor type (returning or new)
- Weekend (a Boolean value indicating whether the visit occurred on a weekend)
- Month of the year


The numerical attributes represent the number of pages visited by the user, as well as the time spent on each page category. These features are derived from the URL information of the pages visited by the user and are updated in real time when a user takes an action, such as moving from one page to another.

The "Bounce Rate," "Exit Rate," and "Page Value" features represent metrics measured by "Google Analytics" for each page on the e-commerce site. The "Bounce Rate" measures the percentage of visitors who enter the site from a page and then leave without triggering any other requests to the analytics server during that session. The "Exit Rate" calculates the percentage of pageviews to the page that were the last in the session. The "Page Value" represents the average value for a web page that a user visited before completing an e-commerce transaction.

The "Special Day" feature indicates the closeness of the site visiting time to a specific special day, such as Mother’s Day or Valentine's Day, during which the sessions are more likely to be finalized with a transaction. The value of this attribute is determined by considering the dynamics of e-commerce, such as the duration between the order date and delivery date.

## Conclusion
This dataset provides valuable insights into online shoppers' behavior and purchasing intentions, which can be used to optimize e-commerce sites and marketing campaigns. The combination of numerical and categorical features offers a comprehensive view of user behavior, enabling businesses to tailor their strategies to specific user segments.
