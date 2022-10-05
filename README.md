# Ex-04-Multivariate-Analysis

AIM:
1. Start
2. Read the data from the file
3. clean the data by 
i. removing outliers
ii. filling the null value or dropping the column
4. perform multivariate analysis by using
i. scatter plot
ii. box plot
iii. heat map


PROGRAM:

![Screenshot 2022-10-05 214131](https://user-images.githubusercontent.com/113016903/194109610-cce472b7-2988-4e02-bc2e-3aa23de9bc53.jpg)


        df.dtypes:


![image](https://user-images.githubusercontent.com/113016903/194111118-c39c6daf-513b-4b46-8643-a185fe3cc753.png)

        kurtosis:
        df.kurtosis()
        
        ![image](https://user-images.githubusercontent.com/113016903/194111535-74f96f30-90ae-4dd8-8838-4b0778a8d085.png)

        scatterplot:
        import pandas as pd
        import seaborn as sns
        sns.boxplot(df['Sales'],df['Postal Code'])
        
