![Ironhack logo](https://i.imgur.com/1QgrNNw.png)

# Lab | Statistics Foundations
In this lab we are going to put into practice what we learned about the foundations of statistics. You won't need to use Python, just your brain and a little bit of *Markdown*. 

## Your task
Today you'll need to complete the challenges described below.

## Deliverables
You need to submit a markdown file with the solution to the following challenges. You can create a new *.md* file or directly edit the *README.md* to include your solutions.

## Challenges
### Challenge 1
One player rolls two dices. Describe the measurable space and the random variable for:
* A. The values that the player obtains.   ((1,1),(1,2),(2,2),(2,3),(3,3),(3,4),(4,4),(4,5),(5,5),(5,6),(6,6))
* B. The sum of the values obtained.        (2,3,4,5,6,7,8,9,10,11,12)
* C. The maximum value obtained after rolling both dices. (12)

Describe the following events:
* Case A: Both values are greater than 5.           For both to be greater than 5, means both = 6 = 2/36, or 1/18
* Case B: The sum of values is even.                (5,6 ot 6,5) 6/11
* Case C: The maximum is the value of both rolls.   Same as case A i.e. need 6 and 6.

### Challenge 2
One player picks two cards from a poker deck. Describe the measurable space and the random variable for:
* A. The number of figures he picks.            2 to 10 J,Q,K,A (8 figures per suit)        32/52 and X/51
* B. The sum of card values. Consider that the value of figures is 10 and the value of aces is 15.
* C. The number of hearts or spades he picks.   x/26

Describe the following events:
* Case A: The number of figures in the cards the player picked is two. 32/52 * 31/51 = 
* Case B: The sum of card values is 17. (9,8) (4/52* 5*51)
* Case C: The value of both cards is less than 8. (24/52* 23*51 )

### Challenge 3
Two players roll a dice. Describe the measurable space and the random variable for:
* A. The score of player A. 1/6
* B. The greatest score. 6
* C. The earnings of player A if the game rules state that:  
"The player with the greatest score gets a coin from the other player.". one coin
* D. The earnings of player A if the game rules state that:  
"The player with the greatest score gets as many coins as the difference between the score of player A and player B.". ??

Describe the following events:
* Case A: The score of player A is 2.       1/6
* Case B: The greatest score is lower or equal than 2. 1/6 ot 2/6 = 2/36
* Case C: Considering the case where the winner gets as many coins as the difference between scores (D), describe: 
  * Player A wins at least 4 coins. (6,2) (6,1)
  * Player A loses more than 2 coins. 
  * Player A neither wins nor loses coins.

## Bonus challenges
### Bonus Challenge 1
Three players take balls from a box. Inside that box there are red, blue, green and black balls. The players can take three balls at mosts with the following rules:

* If the ball is blue, they can take another ball.
* If the ball is green, they get one point and they can take another ball.
* If the ball is red, they can’t take another ball.
* If the ball is black, they lose one point and they can’t take another ball.

Describe the measurable space and the random variable for:
* A. Player A wins. Do not consider ties as a win.
* B. Player A and B get the same points.
* C. All players get 0 points.

### Bonus Challenge 2
Consider the situation of bonus challenge 1 but now with four players. Does anything change in your solutions? What are the changes in each case?

### Bonus Challenge 3
One player takes three balls from a box. Inside the box there are 5 balls: two of them are black and the other three are white. 

Describe the measurable space and the random variable for:
* A. The number of white balls if every time we take a ball we keep it.
* B. The number of white balls if every time we take a ball we put it back again into the box.
* C. The number of black balls if every time we take a ball we keep it.
* D. The number of black balls if every time we take a ball we put it back into the box.