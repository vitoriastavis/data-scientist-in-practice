# Data Scientist in Practice
[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
[![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Naereen/badges)

Welcome to my first data science project. It is part of the Data Scientist in Practice Marathon 3.0, from the YouTube portuguese channel https://www.youtube.com/channel/UCd3ThZLzVDDnKSZMsbK0icg.
The marathon happened on 22th, 24th, 26th and 29th of March 2021. The teacher, Eduardo, shared the data and the code with comments, as well as video classes teaching how the code works. 

The goal was to build a machine to predict if a loan is approved or not to be used by employees in credit loaning companies. The data provided by the teacher consists in 614 clients and their information, e.g. marital status, income, number of children, how much they wanted to loan and if that loan was approved or not.

Check below for the statistics and my analysis!

## My experience during the project

At the time of the marathon, I was enrolled in TechLabs' Data Science course, so I already had basic knowledge of data science; the marathon helped me put all I learned into practice. I also learned a lot about machine learning, which I found easier than expected! I was able to use the base code, which was very good, and edit it as I pleased. The data and comments was originally in portuguese, I changed the NaN removal algorithms, improved the graphics. 

## Technologies used

The code was written in Python using Google Colabs.
The graphics were built using seaborn and matplotlib. 
The machine learning was built using sklearn and RandomForestClassifier.
The WEB system used HTML to set the font and colors.

The URL is an ngrok.io type. As it expires in some time, here is some screenshots to show the system works.

# Data analysis

**Variables and their meaning**:
*   client_code: client code in the conglomerate
*   sex: sex
*   marital status: single/married
*   dependents: if the person has children and how many
*   education: schooling
*   employed: if the person is working or not
*   income: monthly income
*   spouses_income: income of the person's spouse
*   loan_value: value of the requested loan (in thousands)
*   installment: value of the monthly installment 
*   credit_history: if the person has delayed a payment or is in breach
*   realty: if the person owns a place
*   loan_approval: if there was approval of the requested loan (variable to be predicted)

There were 614 entries and 13 columns. Some of the information was incomplete. 
<br>
![Screenshot_20](https://user-images.githubusercontent.com/72163805/112728580-c6a1cb80-8f06-11eb-8867-eb16241dddf8.png)

75% of the income and loan_value equal to 5795 and 168000, respectively. Considering that the maximum value for those variables is 81000 and 700000, this means that there are less people who receive a lot of money and want to loan a lot of money.
<br>
![Screenshot_19](https://user-images.githubusercontent.com/72163805/112728712-50ea2f80-8f07-11eb-8d8f-d647100263bf.png)

The characteristics with higher frequency were: male, married, graduated, with 0 children, with debts and own a semi urban property:

![Screenshot_11](https://user-images.githubusercontent.com/72163805/112728931-6ad84200-8f08-11eb-9a2c-a5941e57457d.png)
![Screenshot_12](https://user-images.githubusercontent.com/72163805/112728932-6b70d880-8f08-11eb-8f31-3291b453476d.png)
![Screenshot_13](https://user-images.githubusercontent.com/72163805/112728933-6b70d880-8f08-11eb-8630-78266c5ee909.png)
![Screenshot_14](https://user-images.githubusercontent.com/72163805/112728934-6b70d880-8f08-11eb-9a9b-f29651172c64.png)
![Screenshot_15](https://user-images.githubusercontent.com/72163805/112728935-6c096f00-8f08-11eb-926b-1431acdeea6f.png)
![Screenshot_10](https://user-images.githubusercontent.com/72163805/112728941-6d3a9c00-8f08-11eb-8568-4ad21bac6d78.png)
![Screenshot_7](https://user-images.githubusercontent.com/72163805/112728942-6d3a9c00-8f08-11eb-9f7a-cfe642539846.png)
![Screenshot_5](https://user-images.githubusercontent.com/72163805/112728944-6dd33280-8f08-11eb-9dcc-be5f79c76f44.png)
![Screenshot_8](https://user-images.githubusercontent.com/72163805/112728939-6ca20580-8f08-11eb-96ee-15b37c98d5e4.png)
![Screenshot_9](https://user-images.githubusercontent.com/72163805/112728940-6ca20580-8f08-11eb-9de4-0e92dc885bcf.png)
![Screenshot_6](https://user-images.githubusercontent.com/72163805/112728945-6dd33280-8f08-11eb-8592-28c3bd262bec.png)
<br>
After creating the predictive machine, we can analyse the variables that influenced the most.
<br>
![Screenshot_4](https://user-images.githubusercontent.com/72163805/112884981-8da05d00-90a6-11eb-84a5-2e6d5892581f.png)

Since I ended up changing the random_state parameter of the train_test_split function from sklearn, my result was different from the teacher's, which is a good thing to notice and explore. The variables' influence ended up different, and the accuracy score was higher. 


# Conclusion

Learning how the random forest algorithm and its parameters work was incredible, it surely increased my interest in machine learning. 
It was great to notice how small changes change the outcome, and how there are many ways to do the same thing in data science.
[march 2021] I will be applying those concepts to an analysis of the data in my Netflix account. It will soon be on my GitHub profile.

# Contributing
Pull requests are welcome! For major changes and suggestions, please open an issue to discuss what you would like to change. I would love to learn more.
