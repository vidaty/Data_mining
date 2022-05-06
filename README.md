Report Data Science and Stem Salaries
 


Introduction:

In this project I am exploring the Data Science and Stem Salaries Data set which includes 62642 observations of employees with 29 different variables.
The data set is published on Kaggle:https://www.kaggle.com/datasets/jackogozaly/data-science-and-stem-salaries.My goal is to suggest different possible paths that can be taken in the field of data science and computer science in the US. What motivated me to work on this specific data set is because we all heard of opportunities that exists at companies like Google, Facebook, IBM or banks like Goldman Saks. However, to start exploring these opportunities, my first question is whether these opportunities are the same or not?



Target audience of the project:

This project is targeted toward college students like myself. As a college student majoring in data science, who is an immigrant in the US. I have very limited understanding of different paths that can be taken in the field of data science and software. 


Main Idea:

Looking at the ordered list of companies, I decided to divide these companies to 4 main groups of Faang, Unicorn, Legacy and banks to offer 4 different paths by exploring the difference between features like salary, stock value, level of education and years of experience and etc. 
pattern. However, I ended up using un supervised learning models to predict different clusters of people more accurately. 


Modeling method:

1-I divided the data set to 4 main groups as 4 different paths:
The list of the initial 4 groups in details are below:
1-Faang: Amazon, Google, Facebook, Apple, Netflix, Microsoft
2-Unicorn: Uber, Twitter, Nvidia, Lyft, Dropbox, Shopify, Airbnb, Snap, Indeed, Yelp, Square, Tesla, Stripe, Splink

3-Legacy_software: Oracle, Salesforce, Intel, Sisco, IBM, Qualcomm, Adobe, Sap, Del, Atlassian, ServicNow, Bloomberg 
4-Banks: CapitalOne, Jpmorgan chase, Goldman sachs, Pay pal, Intuit, Deloitte,Visa

I used K-means and PCA to find clusters to compare different clustering in these 4 main groups.

•	Difference between stock value vs Base salaries at these companies that are two main factors of total compensation
•	Base salary vs years of experience
•	Base salary vs different levels of education

 



 

 



Assuming there are 4 different paths based on 4 groups of Faang, unicorn, legacy and banks. I learned that on average base salary in Faang companies are higher whereas total compensation on average for Unicorn are higher. In addition, it seems, that the rate of acceptance for BA degrees are higher in Bank and Unicorn, on the other hand the rate of P.H.D acceptance at Fanng companies are much higher. In another word, it means that out of 20 people working in Bank group, only one has a P.H.D while out of 20 people working at Faang, 3 to 4 people have a P.H.D. In terms of level of education: Can we say that the first job out of college  with a BA degree could be at bank's with a lower salary. But if the person is looking for more of a prestigious job at Faang companies, perhaps they need a Master's or P.H.D degree.

I used a K-NN model which predict 62 % right for which companies people work for. This model does an ok job. Because if we predict ourselves, we can predict only for 43%.


2- I used k-means to find the best clusters to see if it suggests me another way to group the possible paths.

 

This suggests to have at least 6 groups instead of 4 groups.

 





Looking at 6 different group summaries below, we can observe that perhaps it is more accurate to use these k-means clustering for different paths that people can take. 

  yearsofexperience yearsatcompany basesalary stockgrantvalue
1         11.053030       3.134470  488677.54       12079.072
2          9.387704       3.308369  174840.79       95911.984
3         12.177331       3.759871  203738.04      228728.457
4          5.795078       2.396755   34818.06        7704.666
5          5.719028       2.348223  135331.52       24761.455
6         15.052539       4.435902  235599.11      517238.179




conclusion:

My goal was to shed light on different opportunities at various companies in the US. for those who are interested in the field of data science and software. Although this can be varying from person to person, I hope that people with different level of education, experience and interest can find their path by looking at this data.

There could be 6 different paths:

1-In group one we can see people with a lot of years of experience and high base salary and lower stock value.
2 Group two is also similar to one, but with more in stock value, perhaps this group are in their mid-late career and are highly compensated
3- Group three are more experienced than group one but with less base salary and higher stock value compared to group one. 
4- Group four are those in their early career with lower base salary and low stock value.
5- Group 5 is very similar to group 4, however the base salary in this group compared to group four is much higher, this can be an average person at Facebook or Google
6- last group: This is people level 8 who makes a very high salary and high stock value.




