# IBM-HR-Analytics-Project

![](Images_.png)

**Introduction** : 

I decided to play around with an HR Dataset called **IBM Data Science Datasets** the insights gotten from these datasets are not real. It was intended to practice my skills using Power Query, Power BI and DAX. What interests me most about these Report is the part where i wrote different DAX to gain meaningful insights from the Data, and the familiarity with some HR terms commonly used. I ma going to be taking us along every process that was done,even the littlest of it :cowboy_hat_face: that became meaningful Insights and in turn made me come up with a fascinating Report!

**_Disclaimer_**

This project is not in any way a real life project. _The dataset is a dummy Dataset that is intended to practice the capabilities of PowerBI and DAX_. Now lets jump right in :collision:

**Problems Statement**

1. The dataset contained more of numerical values that needed to be adjusted in order to gain meaningful insights.
2. There was an Attrition column that contained a Yes/No value. In order to gain meaningful insights from it, i needed to apply a measure that will help in deriving the total percentage of employees that have left the organization. 
3. The Age column in the dataset was grouped into Age ranges of 4 categories in order to derive meaningful insights from it.

However, this documentation will cover every step that i carried out to ensure that i derive and gain meaningful Insights from the Dataset, not only to have a beautiful Report but for better understanding of the Data.

**Skills Demostrated**
- DAX
- Page Navigation
- Filters
- Buttons
- New Measures

**Modelling**: The Dataset is only a table, so there was no need for Data Modeling because there is no table that i was going to model it against.

**Visualization**

The report comprises of 3 pages which includes:
- Overview Page
- Action Page
- Attrition Page

**Data Manipulation/Transformation Process**

**Education Column, Environmental satisfaction, Job involvement, Job satisafaction, Performance rating, Relationship satisfaction, Work life balance**. 

These contained Data enteries that were recorded in numerical form, and i needed to change it to a text form in order to gain meaningful insights from it when visualizing. A conditional column statement was applied here. I am going to attach images of the Before Columns and the Conditional statement that i wrote to change the numerical information to text values.

Below is an image of what the columns looked like before Transformation :point_down:

**Column 1**                                   | **Column 2**
:----------------------------------------------|:--------------------------------
![](1-.png)                                    |              ![](2-.png)


The Conditional statements that was written is as follows;

**1**                                       |                   **2**             
:-------------------------------------------|:--------------------------------------
![](3_.png)                                 |![](4-.png)



**3**                                       |                   **4**             
:-------------------------------------------|:--------------------------------------
![](5-.png)                                 |![](6-.png)

