# Blackjack-weighted-random-choices-visualization-with-numpy-and-Python
This is a small project to test and visualize the result of the weighted probability capability of Python's numpy.random.choice().

In any 2-player Blackjack game where the computer's the dealer, we need to consider the computer's decision to hit on the next card provided its current point. The closer the dealer's point to 21, the lesser the probability of it making a hit (drawing another card). The Python code in this repository reduces the probability of the computer to draw another card when its point is close to 21 with simple if-else algorithm and the help of numpy.random.choice()'s weighted probability capability.

In this case, if the point is less than or equal to 17, the probability of the computer to draw another card is 0.99, and decreases respectively to the increasing point. The probability of the computer to draw another card when its point is 21 is 0.

The following bar chart shows the times out of 100 times the computer will draw another card for each of its point:

![image](https://user-images.githubusercontent.com/65524471/153182930-1b6935f9-2756-4a5f-adb0-df877916294e.png)

The visualiztion can differ from what's shown here if the computer is given a different set of probabilities.
