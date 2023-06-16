# Analysis-of-Chemicals-in-Cosmetics


This project aims to analyze the chemical composition and safety of various consumer products. By examining the reported chemicals and their counts, we aim to gain insights into the presence of potentially harmful substances and identify patterns and trends among different product categories.

**Project Overview**

Consumer product safety is a significant concern for both individuals and regulatory bodies. With the increasing awareness of the potential health risks associated with certain chemicals, it becomes crucial to analyze and understand the composition of consumer products. This project utilizes a dataset containing information about product names, companies, categories, and reported chemicals.

**Dataset Used**

The data is from the [California Safe Cosmetics Program (CSCP)](https://catalog.data.gov/dataset/?sort=score+desc%2C+name+asc&q=Companies&res_format=CSV&_res_format_limit=0&organization=ca-gov&publisher=California+Department+of+Public+Health) in the California Department of Public
Health. The primary purpose of the CSCP is to collect information on hazardous and potentially
hazardous ingredients in cosmetic products sold in California and to make this information available to
the public.

**Objectives**

1. Investigate the chemical composition of different consumer products.

2. Identify products with the highest and lowest chemical counts.

3. Analyze patterns and trends among products based on their chemical counts.

4. Examine the relationship between chemical counts and product categories.

5. Provide insights into potential safety concerns related to specific products or categories.

6. Conduct hypothesis testing to determine if there is a statistically significant difference in the ratio of harmful chemicals to all reported chemicals between two groups of companies (e.g., big vs. small companies, controversial vs. non-controversial companies).

**Technologies Used**

Python: Data analysis, visualization, and statistical calculations.

**Coclusion**

Out of the 122 unique chemicals reported in this dataset, the majority of them have a frequency of occurrence below 1%. However, there is a significant exception in the case of titanium dioxide, which stands out with an occurrence rate of nearly 80% among all the reported chemicals.

But, according to some Google search, Titanium dioxide has received FDA approval and is permitted for use, including in food products. Based on this information, it can be concluded that titanium dioxide is considered to have minimal harm. Moreover, it is worth noting that there are several other chemicals that are significantly more harmful when compared to titanium dioxide.

**Hypothesis Testing**

**Null Hypothesis (H0): Pa = Pp**

The null hypothesis states that there is no significant difference between the proportions of harmful chemicals in the two companies. It assumes that the proportion of harmful chemicals in one company (Pa) is equal to the proportion of harmful chemicals in the other company (Pp).

**Alternative Hypothesis (Ha): Pa ≠ Pp**

The alternative hypothesis suggests that there is a significant difference between the proportions of harmful chemicals in the two companies. It posits that the proportion of harmful chemicals in one company (Pa) is not equal to the proportion of harmful chemicals in the other company (Pp).

One -

The obtained P-value of approximately 0.62 exceeds predetermined rejection threshold.

Hence, we fail to reject the null hypothesis. Consequently, it can be concluded that the observed difference in proportion between** Chanel Inc. and American International Industries** is likely due to random chance. Reliance solely on the ratio difference is insufficient for determining which company has a higher prevalence of very harmful products compared to the other.

Two -

The computed P-value of approximately 0.75 significantly exceeds my predetermined rejection threshold.

Therefore, we fail to reject the null hypothesis once again. Consequently, it can be concluded that the observed difference in proportion between **Benefit Cosmetics and Anastasia Beverly Hills** is likely attributable to random variation. It is not reliable to solely utilize the ratio difference to determine which of the two is more harmful than the other.
