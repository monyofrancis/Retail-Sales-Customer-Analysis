# Retail-Sales-Customer-Analysis
This is a project to analyse the relationship between customer demographics and the electronics they purchase at a retail store. KPI's were achieved through data cleaning, future engineering and visualization


# 1. Project Overview

* **Retail Dataset** (Transaction ID, Customer ID, Item Quantity, Age, Unit, Total Amount)
    The objective is to create an **interactive Retail Sales & Customer Analysis Dashboard** in **Excel** that answers;
  * Which product Category generate the most revenue?
  * What age group gives the most revenue
  * Which month did sales peak
  * The average age of a customer


# 2. Data Understanding

 **Retail Sales Dataset**

   * Fields; Transaction ID, Date,Customer ID, Gender, Age, Product Category, Quantity, Price Per Unit, Total Amount.



# 3. Methodology

1 **Data Cleaning (Excel)**

   * Removed duplicates, nulls, and inconsistencies.
   * Standardized product and region names.

2. **Feature Engineering (Excel)**

   * Created new column: **Age Group = =IF(AND(F2>=18,F2<=29),"Youth",IF(AND(F2>=30,F2<=49),"Young Adult",IF(AND(F2>=50,F2<=64),"Adult","")))**.

3. **Data Analysis (Excel)**

   * Created Pivot Tables:

     * Sales ↔ Gender
     * Sales ↔ Age Group
   * Sales ↔ Category :

     * Total Sales
     * Average Age
     * Monthly Sales
     * Customer Count
     * Total Quantity sold

4. **Visualization (Excel)**

   * Dashboard 1: **Sales Overview**
   * Dashboard 2: **Sales by Male Gender**
   * Dashboard 3: **Clothing Category and Male Gender Insights**
   * Dashboard 4: **Clothing Category, Male Gender and Young adult group Insights**


# 4. The Dashboards
![October class 1](https://github.com/user-attachments/assets/b0f05452-950b-414f-8bc4-9e1f44461557)


#  Sales Overview

* **Total Sales**: 456K
* **Sales by Categories**: Beauty (143.52k) > Clothing (155.58K) > Electronics (156.91K)
* **Gender Contribution**: Male (49%), Female (51%)
* **Monthly Trends**: Peak in May (53.15K), dip in September (23.62K)

![October class 2](https://github.com/user-attachments/assets/8070e259-e3e6-44c0-8bed-af0a00fb767c)


# Sales By Gender

* **Top Revenue**: (23.8K, 1298 units)
* **Revenue by Category**: Beauty (74.83k) > Clothing (81.28K) > Electronics (76.74K)
* **Average Female Customer Age**: 41
* **Monthly Quantity Trend**: Peak in October (26.6k)


![October class 3](https://github.com/user-attachments/assets/0c53ecab-e273-4724-b3ca-3f1355b63d37)
# Clothing Category and Male Gender Insights

# Clothing Category, Male Gender and Young adult group Insights
![October class 4](https://github.com/user-attachments/assets/3b4918c1-06a3-4ae4-b5d2-e9e2dd0b0afa)

# 5. Key Insights

* **Electronics dominate** sales, (34.41%).
* **Young Adult Customer group** bring the most revenue, churning 189.69K.
* Sales are **seasonal**, peaking in May across both revenue and quantity.


# 6. Recommendations

1. **Expand the electronics category** to sustain revenue growth.
2. **Target female-dominated demographics especially young adults** with tailored marketing campaigns.
3. **Improve customer diversity**—tailor campaigns for male customers to encourage sales.


# 7. Conclusion

This project shows how structured analysis of **Sales, Product, and Customer data** using **Excel can generate clear business insights.

It demonstrates **end-to-end analytics workflow**:


# 8. Tool; Excel & Tech Flow

* *Data Cleaning*
* *Feature Engineering*
* *Pivot tables*
* *Visualization*
