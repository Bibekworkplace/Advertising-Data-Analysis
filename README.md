# Marketing-Analysis
#performancemarketing #excel 

**TASK-1**

**1. Past 5 months' data for Amazon is attached in a subsequent sheet, referring to the database; help us draw analysis for each category to plan spending split for upcoming months**

**2. Analysis should cover the grid for monthly performance at category, subcategory,
campaign type, targeting type and performance metrics**

**3. Create a grid explaining the CPCs, CTRs, ACoS, AOV and CVR for the given data-
summarize the performance for each category- any suggestions to further improve the ACoS**


# Analysis 

## Overview:

### Spend and ROAS for Categories over the month:
![](https://github.com/Bibekworkplace/Advertising-Data-Analysis/blob/main/images/1.png)

Findings:
- The trend line for Amount Sales, ROAS, shows that, overall, there has been an increase in sales and ROAS over time, while the amount spent has decreased a little bit. This is a positive sign.
- Most of the sales over time are from the category Filters and Adapter.

![](https://github.com/Bibekworkplace/Advertising-Data-Analysis/blob/main/images/2.png)
In fact, about 88%of  Total spending and Total Sales come from these 2 categories.

![](https://github.com/Bibekworkplace/Advertising-Data-Analysis/blob/main/images/3.png)


**So, we will shift our focus to these 2 categories and deep dive into the subcategory level.**

#Category Analysis
![](https://github.com/Bibekworkplace/Advertising-Data-Analysis/blob/main/images/4.png)


## Overview
- Analysis for the Subcategory level for the Adapter and Filters Category is done.
- Created a line at 3 ROAS. Any subcategory ROAS over this line indicates profitability
- Keeping sales and spending in mind, I decided to focus on the following subcategory:
      - LOW ROAS
        - uv filter - 2.87
        - cpl - 2.29
        - combo - 2.72
         - canon - 2.62

      - HIGHER ROAS
        - adapter - 7.55
        - leica - 3.83
        - sony - 3.36
        - filters - 3.91
        - variable nd - 3.34
- It seems like shifting the budget from Low Roas to High Roas subcategories can improve performance, esp the adapter and filter campaign. But it's never that easy. We need to analyze secondary metrics to confirm our theory.

# Sub-Category Analysis(Selected Subcategory)
![](https://github.com/Bibekworkplace/Advertising-Data-Analysis/blob/main/images/5.png)

## Overview
- The adapter category has a higher CTR and lower CPC compared to Filters Category.
- Improving the CTR and reducing CPC for Variable ND, UV filter and CPL even a little bit can hugely improve performance.

CTR and CPC are impacted by mainly 2 factors:
1. Creatives
2. Targeting

Since we don't have creative data, we will focus on targeting:
**Targeting**
![](https://github.com/Bibekworkplace/Advertising-Data-Analysis/blob/main/images/6.png)

From the above table, we can see that for Adapters, Automatic is the worst performer and for filters, Manual is the worst performer in terms of ROAS. But this doesn't give us the whole picture.
So, we need to analyze the targeting performance for each sub-category level.

**Filter Targeting**
![](https://github.com/Bibekworkplace/Advertising-Data-Analysis/blob/main/images/7.png)

Here, Manual Targeting has a higher CTR than Automatic Targeting

![](https://github.com/Bibekworkplace/Advertising-Data-Analysis/blob/main/images/8.png)

Manual targeting has a higher CPC

![](https://github.com/Bibekworkplace/Advertising-Data-Analysis/blob/main/images/9.png)

Here we can see the ROAS of subcategories based on targeting. Based on the above figure, I’d recommend the following:

![](https://github.com/Bibekworkplace/Advertising-Data-Analysis/blob/main/images/10.png)

**Adapter Targeting**
![](https://github.com/Bibekworkplace/Advertising-Data-Analysis/blob/main/images/11.png)

Here, Manual Targeting has a higher CTR than Automatic Targeting

![](https://github.com/Bibekworkplace/Advertising-Data-Analysis/blob/main/images/12.png)

Manual targeting has comparatively higher CPC than Automatic targeting

![](https://github.com/Bibekworkplace/Advertising-Data-Analysis/blob/main/images/13.png)

Here we can see the targeting for each sub-category level. Based on the above figure, i’d recommend the following:

![](https://github.com/Bibekworkplace/Advertising-Data-Analysis/blob/main/images/14.png)

**Conversion Rate:**

![](https://github.com/Bibekworkplace/Advertising-Data-Analysis/blob/main/images/15.png)


## Overview
- Filters esp Uv filter and variable ND has a high conversion rate compared to the Adapter category
- Conversion rate is mostly influenced by CTR and Landing Page. In order to increase the conversion rate for the Adapter category, the Same strategy should be used as the top-performing subcategory ie adapter to the rest subcategories. (Same goes for Filter Sub-Category)

## Campaign Type with Category

![](https://github.com/Bibekworkplace/Advertising-Data-Analysis/blob/main/images/16.png)

SD is the best performer, followed by SP. SB is worse and is not even profitable.

![](https://github.com/Bibekworkplace/Advertising-Data-Analysis/blob/main/images/17.png)

Based on the following graph, I’d recommend the following:

![](https://github.com/Bibekworkplace/Advertising-Data-Analysis/blob/main/images/18.png)

## Conclusion:
- Filter and Adapter Category brings in 88% + sales
- Sub Category to Focus on are
    - LOW ROAS
        uv filter - 2.87
        cpl - 2.29
        combo - 2.72
        canon - 2.62
    - HIGHER ROAS
        adapter - 7.55
        leica - 3.83
        sony - 3.36
        filters - 3.91
        variable nd - 3.34
- The adapter Category has a higher CTR and lower CPC compared to the Filters Category. Improving the CTR and reducing CPC for Variable ND, UV filter and CPL even a little bit can hugely improve performance.
- Manual Targeting has higher CTR and CPC compared to automatic targeting
- SD is the best performer, followed by SP. SB is worse and is not even profitable.

Based on these conclusions, an updated budget is provided in the Excel sheet.








