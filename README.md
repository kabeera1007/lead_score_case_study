## Problem Statement

X Education sells online courses to industry professionals. The company markets its courses on several websites and search engines like Google. Once these people land on the website, they might browse the courses, fill up a form for the course, or watch some videos.

When these people fill up a form providing their email address or phone number, they are classified as a lead. Moreover, the company also gets leads through past referrals. Once these leads are acquired, employees from the sales team start making calls, writing emails, etc. 

Through this process, some of the leads get converted while most do not. The typical lead conversion rate at X Education is around 30%.

## Business Goal

X Education needs help in selecting the most promising leads, i.e., the leads that are most likely to convert into paying customers.

The company needs a model wherein a lead score is assigned to each of the leads such that the customers with a higher lead score have a higher conversion chance, and the customers with a lower lead score have a lower conversion chance.

The CEO, in particular, has given a ballpark target lead conversion rate to be around 80%.

## Strategy

The following approach is followed in order to build the project:

- **Load and inspect the data**
- **Clean and prepare the data**
- **Exploratory Data Analysis**
- **Feature Scaling**
- **Splitting the data into Test and Train dataset**
- **Building a logistic regression model and calculate Lead Score**
- **Evaluating the model by using different metrics** (Specificity and Sensitivity or Precision and Recall)
- **Applying the best model in Test data based on the Sensitivity and Specificity Metrics**

## Conclusion

It was found that the variables that mattered the most in identifying potential buyers are (in descending order):

- The total time spent on the website.
- Total number of visits.
- When the lead source was:
  - Google
  - Direct traffic
  - Organic search
  - Welingak website
- When the last activity was:
  - SMS
  - Olark chat conversation
- When the lead origin is Lead add format.
- When their current occupation is a working professional.

Keeping these in mind, X Education can flourish as they have a very high chance of converting most of the potential buyers.
