# Propensity-Uplift-Modeling

### In this exercise, we are going to evaluate CausalLift package for building an Uplift Model to help a Digital Marketer on the below two fronts:
- Increase Revenue by Improving Conversion Rates
- Reduce Costs by Reducing Cost Per Click

### Most of the Digital Marketers usually use decriptive analytics in order to identify actionable insights but almost all of them end up either in a fad of improvement or no improvement at all.

### A few of those Digital Marketers evolve from experience and start using predictive analytics to predict click through rates and build a list of campaign success metrics. They get success too but due to constant evolution of customer behavior and technology innovations, they lose out in the long run

### One of the most underused and underappreciated model to get ahead in this domain is Uplift Modeling. It is an extenion of Response Modeling where the marketers can not just get the customers who are likely to respond but they can also identify the set of customers who can get annoyed if treated. We can also identify the customers who will not do anything if treated or not.

### Uplift Model

![Image - Uplift Model](https://raw.github.com/rahul-adwani/Propensity-Uplift-Modeling/main/images/uplift.jpg)

# What do we need to do?

### We need to identify the customers who are Persuadables and approach them with Digital Marketing Campaigns
- This will help us in running campaign operations in a much more efficient way with a very high conversion rate
### We need to avoid all the other 3 types of customers - Sure Things, Do Not Disturb and Lost Causes
- This will help us save unnecessary costs and hence improving the Cost Per Click

### There are a lot of research papers available on the internet, however, there are very few libraries which are available in both Python and R.

### With this exercise, I would like to explore CausalLift package in Python to build an Uplift Model.

### Please note that the data used in this exercise is generated arbitrarily. There are some publicly available datasets and documentation of CausalLift also has a generate_data() method.

### CausalLift package and any other available package uses the below two types of methods:

![Image - Methods](https://raw.github.com/rahul-adwani/Propensity-Uplift-Modeling/main/images/methods.JPG)

### In both these methods, Propensity/Probability of Conversion is calculated and then a difference is taken between propensities of conversion if a customer is treated and if the customer is not treated.

### This difference is called CATE - Conditional Average Treatment Effects

- CATE ranges between -1 and +1. Higher the value, higher the incremental propensity of conversionn

#### Hope this was helpful

#### You can check out my other repositories here: [Github](https://github.com/rahul-adwani?tab=repositories)

#### You can contact me here: [LinkedIn](https://www.linkedin.com/in/rahuladwani/)

#### If you liked the content, please give it a star


Thanks for reading,
Rahul Adwani
