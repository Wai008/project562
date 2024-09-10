---
title: "Executive Summary"
author: Hnin Thuzar Lwin & Wai Linn
format: gfm
---

# Executive Summary 

## An analysis of contraceptive knowledge, practice and unmet need among currently married women aged 15-49 based on demographic characteristics in Myanmar 

## Background

Myanmar, also known as Burma, is located in Southeast Asia. Administratively, it consists of 7 states, 7 regions, and 1 union territory. The total population is approximately 52 million, comprising a diverse range of 135 ethnic groups1. The different terms “state” and “region” are intentionally used in Myanmar to differentiate the geographical locations between one dominant ethnic population, which is Bamar, accounting for 68% of the total population, with the majority residing in the regions and other ethnic minority populations typically inhabiting the states. Since 1962, certain regions such as Chin, Kachin, Kayin, and Rakhine states have experienced significant armed conflicts between pro-Bamar government military forces and ethnic armed groups. Consequently, these conflict-affected areas lag behind in terms of development, facing disparities in economic opportunities, access to healthcare, and education compared to their non-conflicted counterparts. Specifically focusing on healthcare, significant disparities exist in health service accessibility across different ethnic populations, influenced by various demographic characteristics, including conflict-affected situations. However, there is limited data-driven evidence to quantify the extent of these disparities at the ethnic population level. In order to improve this information gap, we conducted an analysis using a nationally representative dataset to examine the associations between demographic characteristics and family planning service inequities in Myanmar. Our objective is to generate reliable and generalizable data that enhance the accessibility of health information. This data can be utilized by policymakers, NGOs, and international donors, enabling them to deliver targeted interventions on health inequities, particularly for family planning services, to communities most in need.


## Research Question

1. How do demographic characteristics influence contraceptive knowledge, practices and unmet need among currently married women aged 15-49 in Myanmar?
2. Is there any disparities in accessing contraceptive knowledge and practice, and unmet need between regions and states in Myanmar?

## Methodology 

We conducted data analysis based on our research question using the Demographic and Health Surveys (DHS) dataset, which was carried out by the Ministry of Health and Sports (MoHS) in Myanmar in 2016. This survey utilized stratified two-stage cluster sampling and weighted sample size calculation methods to ensure national representativeness and validity. The dataset contains a comprehensive range of demographic and health-related information, including family planning practices among women aged 15-49. From the available datasets, we selected the family planning dataset, which is an individual-level dataset focusing specifically on the family planning knowledge and practices of women aged 15-49, comprising a total of 12,885 participants. Upon reviewing the dataset, we noted that information on contraceptive knowledge was collected for all women, regardless of their marital status, while contraceptive practices were recorded only for currently married women. Therefore, we analyzed only the subgroup of currently married women to ensure comparability of contraceptive outcomes among knowledge, practice, and unmet need


Our Key variables are as below:
- Demographic characteristics: age (5-yr group), location (region/state), residence (urban/rural), education (four levels), wealth index (five levels)
- Outcome: contraceptive knowledge, practice, unmet need (Binary outcome: Yes/No)

To facilitate this analysis, we created the _location_ variable into binary type with two main groups "states and regions" depending on our research interest, which was mentioned elsewhere. In addition, sampling weights were used to generate generalizable information. We applied the methods of sampling weights calculation available on DHS program website. 

We began by analyzing the dataset, initially stratifying specific contraceptive outcomes against each demographic characteristic. These characteristics were presented separately on the project dashboard. Additionally, we created comparison plots to illustrate the disparities in contraceptive outcomes (knowledge, practice, and unmet need) between states and regions, categorized by each demographic characteristic. Furthermore, we utilized a country map to visualize contraceptive inequities across the 7 states and 7 regions. Subsequently, we employed logistic regression models to assess contraceptive outcomes (practice and unmet need) separately, using binary location variables while adjusting for other demographic covariates. We set _state_ as reference for location variable and other covariates, _age group 30-34_ for age, _no education_ for education, _rural_ for residence, and _poorest_ fro wealth index. To note that, we did not fit the model for knowledge outcomes due to the lack of significant differences observed between states and regions in the visual plots. 



## Key Findings

### Contraceptive Knowledge

Women with higher education demonstrate a greater proportion of contraceptive knowledge compared to those with lower or no education. Among age groups, the youngest (15-19 years) exhibit the lowest proportion of contraceptive knowledge  (94%), particularly evident among younger women with no education (86%). Women in regions generally have equal or higher knowledge proportions compared to those in states across all wealth index groups, except for the richer group, where women in states show higher knowledge proportions. Urban residents consistently display higher contraceptive knowledge across all wealth index groups, except for the poorest group, where urban residents in states have lower knowledge proportions than rural residents. These findings underscore the variability in contraceptive knowledge among women, even within regions, influenced by residence and wealth. In combination of location, residence, and wealth index, relatively poor women in rural areas within states tend to have less contraceptive knowledge.  

### Contraceptive Practice

The proportion of contraceptive method usage generally increases with education levels and age until around 40 years, after which it tends to decline. Younger and older women with lower education levels tend to have lower usage of contraceptive methods. Regarding location, residence and wealth index, poorer women from state and rural are less likely to use contraceptive methods. In particular, women living in regions have a higher proportion of contraceptive practice compared to those living in states (53% and 43% respectively). Similarly, women living in urban were more likely to use contraceptive methods than those living in rural (60% and 50% respectively). Furthermore, the proportion of contraceptive usage increases with higher wealth index.

### Unmet Need

The proportion of unmet need decreases with higher education levels. Regarding age groups, women being in the older age group (40-44) and (45-49) have the highest proportion of unmet need (30% and 47% respectively). Within age and education strata, younger and older women with lower education levels are more likely to experience unmet need. Additionally, the proportion of unmet need is lower among women living in regions (23%) compared to those in states (31%), with a similar pattern observed in urban and rural areas (18% and 26% respectively). Moreover, as the wealth index rises, the likelihood of unmet need decreases. When considering the combination of location, residence, and wealth, poorer women from rural areas within states are more likely to experience unmet need. 

### Comparison between Regions and States

In general, women residing in regions exhibit higher levels of knowledge and engagement with contraceptive methods, accompanied by reduced unmet needs compared to their counterparts in states. These disparities in contraceptive outcomes between states and regions were observed across all demographic characteristics, reflecting health inequities and systematic barriers in states compared to regions.

However, upon closer examination, even within regions, specific groups face pronounced challenges in accessing and utilizing contraceptive services effectively. For instance, women lacking formal education, residing in rural areas, belonging to the lowest wealth quintiles, or falling within the youngest (15-19) or oldest (45-49) age brackets demonstrate the lowest rates of contraceptive practice and the highest unmet needs.

This highlights a concerning pattern where communities with these characteristics are often overlooked in terms of receiving quality contraceptive services and support. For example, the proportion of contraceptive utilization among women without formal education residing in regions hovers around 40%, underscoring the urgent need for targeted interventions to address these disparities and ensure equitable access to reproductive healthcare.


### Regression models

Overall, the regression results indicate that residing in regions, urban areas, belonging to the age groups of 20-39, and possessing secondary education, as well as being in the richer and richest wealth index groups, are associated with increased likelihoods of contraceptive use and decreased unmet need. Living in a region, as opposed to a state, is linked to a nearly 60% increase in contraceptive usage and a 34% reduction in unmet need. Similarly, urban populations exhibit approximately a 30% higher contraceptive practice and a 22% decrease in unmet need compared to rural populations. Among age groups, only the 35-39 age group surpasses the reference group (30-34) with a 26% increase in contraceptive practice, while the rest show lower contraceptive practice ranging from 10-20%, except for the oldest age group (45-49), which sees over a 70% reduction. Regarding education, women with secondary education exhibit the highest contraceptive usage (77%), followed by those with higher (59%) and primary education (55%) compared to the reference group. Regarding wealth index, higher quintiles correlate with increased contraception usage, with percentages ranging approximately from 15 to 33% compared to the reference group. The unmet need results directly mirror the contraceptive use, confirming that women across the covariates tend to have lesser unmet need when they use more contraception.



## Limitations 

* The survey of this dataset was conducted in 2016, and it is the only available DHS dataset for Myanmar. Hence, although we assume the situation has not undergone significant changes in the Myanmar context, our findings may not fully reflect the updated situation.
* The analysis specifically focused on contraceptive services; hence, the findings can be linked to the inequities in family planning services in Myanmar but cannot generalize to overall health inequities.
* The analysis included only women who are currently married; therefore, the findings are not generalizable to all types of women who participated in the DHS survey.
* Some key variables, such as religion and specific occupation, which could potentially confound the results, were not available in the dataset. Hence, these variables could not be adjusted for, which may reduce the precision of our regression models.



## Conclusions

The findings underscore disparities in accessing knowledge, practicing contraceptive methods, and experiencing unmet needs across various demographic characteristics, especially between Bamar-dominant regions and ethnic minority states. For example, women residing in rural areas within specific states tend to have lower levels of knowledge and practice regarding contraception, alongside higher rates of unmet needs compared to their counterparts in urban areas within regions. We take into account sampling weights in the analysis, enhancing the generalizability of the findings. However, several limitations exist depending on the context and data analysis method. Nevertheless, our results remain valuable for informing policymakers, implementation partners, and donors, guiding strategic and targeted interventions. Additionally, they can serve as a basis for evaluating the effectiveness of ongoing reproductive health projects and contraceptive provision initiatives. 



## References
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9678470/
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7837347/
