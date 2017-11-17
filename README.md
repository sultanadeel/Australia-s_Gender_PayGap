# Australia-s_Gender_PayGap

Australia's Top 50 jobs pay Men more than Women

# Tableau Workbook Link

https://public.tableau.com/profile/muhammad.adeel3420#!/vizhome/Aus_GenderPayGap/DNA_ChartDashboard?publish=yes

# Project Statement:

This project is aimed at creating two contradictory Tableau Visualizations using a selected dataset on a contentious and debatable topic. Initially, we will develop a visualization that conforms to our main claim and then by incorporating external data in the existing dataset using Python, we will create a rebuttal Tableau visualization that would refute our original claim by providing a legitimate and valid arguments, claims and warrants

# Project Motivation:

Our main objective in this project has been to analyze and discuss a current topic which is contentious in nature. After researching several websites and datasets, we selected a dataset topic from http://www.makeovermonday.co.uk/data/. The topic is based on the Gender pay gap in Australia, which has been a matter of debate and concern in the recent times. Our main claim using the original dataset is that “Australia’s top 50 jobs pay Men more than Women”. We performed data cleaning in Python Jupyter Notebook and created some visualizations using Pandas plotting packages in Python. We analyzed that the top paying jobs such as Neurosurgery, Ophthalmology and the related Internal Medicine professions are paying Men more than Woman, despite the fact that Women are competitively qualified and capable to perform well in the respective professions.

# Dataset Description:

The statistics in the dataset is provided by the Australian government for over 1,000 related occupations and the respective salaries for Men and Women under each occupation. The occupations are ranked from 1, Neurosurgery being the highest paid profession and 1104 being the lowest paid. The dataset has 5 columns namely, Gender Rank; which ranks every profession differently for Men and Women, Occupation name, Gender, Number of Individuals in the related profession, and the Average Taxable Income in accordance with the occupation and gender. 
The dataset required extensive cleaning in terms of extra columns which were removed and also the missing and null values were also filled with zeros using Python data science analysis tool. After performing several data wrangling steps and creating visuals using matplotlib library to support our main claim, we then incorporated data on Australia’s labor statistics over the years from http://www.oecd.org/gender/data/employment/ and then finally concatenated the retrieved data in the original dataset for further data visualization in Tableau.

# Argument Model (Claim):

Based on the available data and our preliminary analysis in Python and Tableau, we want to claim that the top ranked occupations like Neurosurgery, Opthalmology, Cardiology and Judge Law are paying Men significantly more than Women. The several intermediate visualizations and the DNA chart to support this claim are presented and discussed further down in this document. All of these visualizations clearly support our argument that, indeed there is a wide gap and variation between Men and Woman Average Taxable Income in a certain occupation in Australia. However, in our Rebuttal we would present valid arguments and data to contradict our original claim and would show that it's not that Men and Women are paid differently, it is just that Women prefer to work part time post motherhood in Australia due to the local cultural and social factors, which affect their total take home salary in comparison with Men

# Audience Model:

Before creating visualizations, we need to understand the concerned audience and their respective Needs, Wants and Fears in interpreting our visualizations. Our main audience of this dataset analysis is presumably an Australian Labor Force statistician, who after collecting and consolidating the widely dispersed data, wants to analyze the visual characteristics and arguments behind the facts, relationships and patterns in the dataset. Their Need is to better understand the data in terms of disparity between Men and Women salaries for various occupations in Australia. Their Wants include analyzing which occupations are in the top ranking scale and which are ranked in the middle or the lower tier of salary range. The dataset also provides no.of individuals in each occupation so the demographic feature of the data is also one of the wanted findings of our audience. To persuade our audience towards the claim that “Australia’s top 50 jobs pay Men significantly more than Women” is one of our Goals. This topic is of interest to our audience because this is a very volatile and debatable issue in and outside of Australia especially pertaining to Men and Women salary gaps within a similar occupation

# Metrics:

The metrics in this analysis of the Australian Gender pay gap includes the Average Taxable Income for both Men and Women as a separate measure in every respective occupation. Another metric is the no. of individuals in every occupation. Since metrics connect data to the claims and act as a glue in between, Average Taxable Income in the dataset support us in making our claim “Australia’s top 50 jobs pay Men more than Women” more persuasive and qualifying for the intended audience of our visualizations

# Perception:

Changing or correcting a general perceived perception is one of our major goals in this project as we aspire to shed light and bring realistic assumptions towards the claim that “Men are significantly paid more than Women for Australia’s top 50 jobs”. Through our rebuttal and contradictory arguments, we endeavor to prove that there is no gender discrimination or a biased attitude behind the gender pay gap in Australia. It’s because Women participate relatively less than Men in full time labor force in Australia, thereby accounting for the fact that Men are taking home higher salaries. In top professions like Neurosurgery, Judge Law and other medical related professions, being full time in the job is very crucial, therefore, Men being available for full time schedules are commanding higher salaries than Women

# Tableau Visualizations 

<img width="944" alt="ausdata1" src="https://user-images.githubusercontent.com/31932632/32963114-c7ab24b2-cb83-11e7-9364-caf9a43c8e00.png">

                                                          Fig 1.1

# Claim: 

Male salaries in top professions in Australia are highly dispersed

# Warrant:

The above Fig 1.1 shows a Tableau boxplot visualization, which analyzes the variation in the salaries of Men and Women in Australia. We can see that the median of the boxplot for Men is relatively higher than Women and the Men boxplot is skewed to the right and has positive skewness. The outliers for Men boxplot are comparatively greater than for Women boxplot, indicating the fact most of the top occupations are paying Men more than Women in Australia for specific reasons that we would analyze in the rebuttal section of this analysis. We can also see in the boxplot visual that for some high ranked professions like Neurosurgery, there is a wide gap between the Men and Women Average Taxable Income. Men are commanding around $550,000 vs Women only $320,000 for a Neurosurgeon occupation. The boxplot visualization in Fig 1.1 is an ideal snapshot for analyzing the variation and dispersion in the salaries of Men and Women as it clearly shows the range of values and also indicates which occupations are paid more and which are low paid professions for Men and Women in Australia



<img width="899" alt="ausdata2" src="https://user-images.githubusercontent.com/31932632/32963113-c78e7e0c-cb83-11e7-8543-b040ae8e2954.png">

                                                           Fig 1.2
                                                     
# Claim:

Top Ranked Professions pay Men more than Women in Australia

# Warrant:

The tableau bar chart in Fig 1.2 shows the scale of Average Taxable Income for Men and Women in the top ranked professions. The visual shows that as the rank of occupation gets lower, the Average Taxable Income variation between Men and Women gets narrower. Therefore, the top ranked professions such as Neurosurgery, Ophthalmology, Judge Law, Plastic Surgery and Cardiology are some of the professions which pay Men significantly more than Women. The bar chart in Fig 1.2 is a clear, concise and easy to understand for the intended audience, the color comparison is just used to show the salary difference between Men and Women and the X and Y axis are straightforward for the audience to understand the claim.  We can see that a profession like Cricket which is very popular in Australia, has a very considerable difference in Men and Women Average Taxable Income. However, if we analyze the other dimensions and measures in the dataset, we can see that the no. of individuals in the Cricket profession shows that there are more Men 10,000 vs Women only 22, thereby justifying the claim that Men are paid more than women.



<img width="899" alt="ausdata3" src="https://user-images.githubusercontent.com/31932632/32963112-c772bf1e-cb83-11e7-8f4f-efd3d6c5990c.png">

                                                           Fig 1.3
                                                          
# Claim:

The Average Taxable Income of Men is higher than Women in Australia

# Warrant:

The Tableau Donut Pie chart in Fig 1.3 is one of the intermediate visualizations that we created to support our original claim. It shows the proportion of average salary of Men and Women. The pie chart shows that Women Average Taxable Income is $56,000 or 42.7% of the total, whereas Men Average Taxable Income is $75,000 and occupies 57.3% of the pie chart. Therefore, it is a clear indication towards supporting our claim that Men Average salary is higher than Women Average Salary in Australia



# Final Visualization of the Original Claim

<img width="960" alt="dashboard" src="https://user-images.githubusercontent.com/31932632/32968440-11f87d00-cb96-11e7-94d7-805a645c2131.png">

                                                          Fig 1.4
  
# Claim: 

Australia’s Top 50 jobs pay Men significantly more than Women

# Warrant:

Fig 1.4 is a Tableau DNA chart designed to support our claim that the top ranked jobs are paying Men more than Women. The DNA chart is an accurate reflection of this claim, it represents the actual difference or spread between the two quantities which are the Average Taxable Income of Men and Women represented by blue and yellow colors respectively. The line between any two points shows the difference in the salary range for any particular occupation. We can see that the biggest difference is in the top ranked profession of Neurosurgery, Ophthalmology, Orthopedic Surgery and Cardiology. The bigger the difference in the two quantities in the DNA chart, the more persuasive our claim would be that the top ranked jobs are paying Men more than Women. Fig 1.4 DNA chart clearly supports our claim and is a persuasive and easy to understand visualization made using the existing dataset on Australian Gender gap in salaries 



# Rebuttal

After incorporating external data from http://www.oecd.org/gender/data/employment/ on Australia’s total and full time labor force participation by Men and Women, we analyzed that Women’s participation in full time labor force in Australia is significantly less than Men and stands at 53.3% against 81.4% for Men in the year 2016

Therefore, our Rebuttal claim which contradicts and refutes our original claim that “Australia’s Top 50 jobs pay Men significantly more than Women” is that “Since Women’s participation in Australia’s Full time labor force is significantly less than Men, the Average Taxable Income of Women is less than Men”.

Through this rebuttal, our specifically targeted audience who is presumed to be a Labor Force Statistician in our case would be able to understand the main reason behind the discrepancy between Men and Women Taxable Income in Australia. A general perception before analyzing this contradictory argument would be that a perceived or an apparent discrimination exists behind Australia’s gender pay gap. However, through this rebuttal, we intend to change our audience perception using valid and supportive arguments that a significant difference exists in full time labor force participation by Men and Women over the last few years in Australia. There is no discrimination as such in Men and Women earning different salaries within a same occupation, it’s just that Women who have at least one child at home are more inclined towards working part time rather than full time in Australia. Therefore, top ranked occupations like Neurosurgery, Ophthalmology, general surgery and other highly skilled occupations which require full time work schedules affect Women’s total taxable income based on their part time work schedules. Since Men in these highly skilled occupations tend to devote full time work schedules are able to generate higher income than Women based on the total no.of hours worked in a day

# Tableau Visualizations of our Rebuttal to the Original Claim

<img width="900" alt="rebuttal 2" src="https://user-images.githubusercontent.com/31932632/32963122-cdedfc78-cb83-11e7-92af-500cdcf04866.png">

                                                        Fig 1.5
                                                     
# Claim:

Full Time Labor force participation of Women is less than Men in Australia

# Warrant:

The bar chart in Fig 1.5 shows that Women participation rate in full time labor force is just 53% while Men participation rate is 81% much higher than Women. This is an important argument in rebutting our original claim that top professions in Australia pay Men more than Women. Since women are less actively involved in the full time employment, their Average taxable Income is lesser than Men who are able to work full time more often than Women and thus able to command higher income than Women because of greater full time availability. This analogy is focused more on the top 50 occupations including Neurosurgery and Medicine related occupations where full time availability is of utmost importance and of higher demand by the employer considering the risk involved in the occupation



<img width="900" alt="rebuttal 1" src="https://user-images.githubusercontent.com/31932632/32963123-ce037260-cb83-11e7-8481-1599e5ffd66b.png">

                                                         Fig 1.6

# Claim:

Women participation in Australia’s total labor force is less than Men 

# Warrant:

Tableau bar chart in Fig 1.65 shows that the total labor force of Australia is comprised of more Men and Women. We can analyze from fig 1.6 that Women are less involved in the total labor force as their participation rate is 71.6% as compared to Men’s labor force participation rate of 82.3% in the year 2016. Since Women are less actively involved in the labor force than Men, their Average Taxable Income is less than Men in most of the professions thereby refuting our original claim that the top professions pay Men more than Women
   


# Conclusion

<img width="944" alt="rebuttal 3" src="https://user-images.githubusercontent.com/31932632/32963121-cdd30670-cb83-11e7-87bb-2ae5ca841bc3.png">  Image Source: https://www.ussc.edu.au/analysis/women-at-work-australia-and-the-united-states
Data Source:  http://stats.oecd.org/
  
  The above image which is used for explanatory purposes from the source mentioned above, indicates the proportion of Women and Men working full time and part time in Australia, it shows that 61.7% of Women work full time compared to 86% of Men. 
  
A recent research shows that as compared to the U.S., Australian Women are more likely to work part time after motherhood and prefer to devote more time and energy towards household related matters. The concept of day long child care is still not very popular in Australia and is comparatively costlier than in the U.S, in fact many firms are now providing childcare services to their Women employees in order to attract and retain the top Women talent. This is another crucial factor behind the fact that Australian Women are less involved than Men in the full time labor force. The trend of working part time is quite popular in Australia for Women, some major Australian companies like Telstra, ANZ Bank, Westpac, and PWC have offered extended part time shifts to their employees especially targeted towards Women in order to attract skilled and talented applicants. 

All of these factors help us in our rebuttal to contradict the claim that “Australia’s top occupations pay Men more than Women” as it is not that Men are getting paid more than Women in a specific profession, it is because Women in those skilled professions are less likely to work full time after motherhood and therefore their Average Taxable Income gets thinner than that of Men based on the total no.of hours worked per day.
