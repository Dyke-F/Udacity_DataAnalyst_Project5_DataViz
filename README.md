# Data Analyst Project5 Data  Visualisation

### The `PISA 2012` dataset: A brief introduction
---

The PISA survey (Programme for International Student Assessment) is an international survey dedicated to compare the level of educational fitness of school students around the age of 15 years that are about to graduate. Therein, PISA does not aim to assess theoretical knowledge in different domains like biology, chemistry and languages, however asks how well the teenagers can apply what they have learned throughout their school time to real-world situations.  

The dataset we used here contains the full results from 2012. It holds 485489 entries (observations) and  635 features (variables). It is therefore an extraordinarily large dataset and we will therefore reduce it in order to answer some key questions in this dataset.  

While many other Udacity Students followed the most obvious question, wheter the amount of time and effort spend learning correlates to overall good test results, I herein want to ask 2 key questions. 1: wether the financial situation at home has anything to do with the outcome in the test statistics, and 2. if students that regularly skip school perform worse (I almost never skipped lessons and wonder if I should have done this in order to sometimes evade some boring hours without sacrifying my test performance) ... 

The following is a list of variables, that I decided to focus on for my analysis in order to answer the two key questions as described above:
    `1. Is there a potential impact of the financial situation on a students test outcome or vice versa ?`  
    `2. Is beeing late for school and skipping school lessons bad for your test performance ?`  
    `(3. Additional) What countries perform best ? How is Germany performing ? Is it as bad as we think ?`  
    
* Country_Code   
* Student_ID        
* International_Grade   
* Birth_Month  
* Birth_Year  
* Sex  
* Late_For_School  
* Skip_Whole_School_Day  
* Skip_Classes_Within_School  
* Mother_Highest_Schooling  
* Mother_Job_Status  
* Father_Highest_Schooling  
* Father_Job_Status  
* Poss_Desk  
* Poss_Own_Room  
* Poss_Study_Place  
* Poss_Computer  
* Poss_Software  
* Poss_Internet  
* Poss_Literature   
* Poss_Poetry   
* Poss_Art     
* Poss_Textbooks  
* Poss_Technical_Ref_Book         
* Poss_Dict          
* Poss_Dishwasher        
* Poss_DVD      
* Count_Cell_Phone      
* Count_TV     
* Count_Computer     
* Count_Cars      
* Count_Bath_Rooms        
* Count_Books      
* Homework_Time      
* Guided_Homework_Time    
* Personal_Tutor_Time    
* Commercial_Company_Time     
* Study_Time_with_Parent     
* Learn_Time_Test_Language       
* Learn_Time_Test_Math    
* Learn_Time_Test_Science           
* Value_1_Math      
* Value_2_Math     
* Value_3_Math     
* Value_4_Math     
* Value_5_Math    
* Value_1_Read    
* Value_2_Read       
* Value_3_Read     
* Value_4_Read         
* Value_5_Read   
* Value_1_Science      
* Value_2_Science    
* Value_3_Science     
* Value_4_Science     
* Value_5_Science     
* Total_Learning_Time      
* global_score        
* math_score      
* read_score     
* science_score      
* Count_Books_Numeric`  

### Key findings from the analysis:
---
> **In this notebook we investigated the role of possessing items like a lot of cars, books etc at home on the overall score kids achieve in the PISA 2012 survey. We found out that**

1. ... the better the financial situation at home appears, reflected by the number of cars they have in their garage or the number of bathrooms in their houses, the more likely it is that this  correlates with a better performance in the test. This is an important insight, because it might still show that in the year 2012 educational fitness is still a matter of money. Some third world countries performed especially bad in this survey (data not shown), while highly developped countries like Germany and Taiwan perform overall better. Especially modern media like the access to computers and the internet appears to be quite important on the test results (cave: we did not perform any statistics, so we should not conclude a direction of the correlation, but I just do it here intuitively), while number of cars or bath rooms is most likely to some kind of bias (bystander effect) reflecting the overall economical situation at home. Therefore, guaranteeing  access to a computer seems to be important in the future to provide same chances for everyone irrespective of the financial situation at home.

2. ... the more often kids skip school days, skip lessons, the more likely it is that they will perform worse than their classmates that never skip lessons or are late for school. This trend is especially stricking for boys, while girls that skip the same amount of lessons or are as frequently late in the morning perform still a lot better. 

3. ... the smartest students come from the asian region (especially China) but also that we in Germany do not perform so bad at all, as we would always consider.

### Preparation for slide deck:  
---
I used exactly these 3 key questions to select plots from my EDA for the explanatory data analysis. I only improved layout, figure size, relabeld axes accordingly (for instance replaced underscores ( _ ) with spaces and gave the plots appropriate titles.
Unfortunately, the cleaned .csv file still is several hundreds of MB in size so github doesnt allow to upload it, but following the notebook instructions, allows to entirely reproduce it.
