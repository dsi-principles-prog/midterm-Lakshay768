# About the data
 
 Link to data: https://www.kaggle.com/farukbuldur/fifa-2020-exploration-1st-version/data
 
This dataset is collected from Kaggle which was scraped from https://sofifa.com/. 

The dataset is FIFA 20 complete player dataset. This dataset has all the information about the football players which are gonna be a part of the game FIFA 20.

FIFA 20 players data consisting of over 18K players information and about 70 attributes including name, age, overall, value, position, etc.


# Defining the problem

Problem: Predicting the release clause value of a player. 

This will help football clubs set the value of release clauses on their players.

Release clause is the money which another club would have to pay if they want a player from your club even before his contract has expired.


Predicting this might involve factors such as 

1. Player age

2. Player Overall

3. Value of the Player determined by their clubs in terms of money, how valuable that player is 

4. What are his wages.

5. The time player has spent at the club.

6. Player growth potential - This is another column which is in ratings, this column shows the potential rating of the player , even if the overall(present rating) maybe be bad but in the future the player might develop into a really good player and hence would have high potential. Clubs want to keep such players, so you will have to pay alot to get such players.

7. The position the player plays at - In the real scenario one of the most highest paid football players right now are the players who play at the front(Attacking players), which is not fair because all positions are equally important but this is how it is. Clubs tend to pay more money to attacking players, so position matters.    



# Import dataset

Reading and checking in data 

Check conditions:

1. Checking if Name of the player,The country and club they play for, the position,The date they joined their current club they play in and their wages and Release Clause are all character type or not.

2. Checking whether age is in bounds from 10 to 50 years

3. Checking for null values of ID and name

4. Checking whether Age, Overall score of a player(out of 100), Hits(Goals scored by them), Potential score are all numeric.
