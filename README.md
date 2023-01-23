# c_proejct2_GroceryStorePart2

Learn C

Operators

Grocery Store Part 2

We will start you with our solution to the previous project for our apple information for a grocery store. Our version might be slightly different than what you had. You might also notice a few changes that were not part of the previous project but we will be using these as part of this project. We will get to each of the changes in the appropriate tasks.

We will be adding more information, applying sales, modifying the review score and more.

1. We want to offer a sale when we are running out of apples to help move the last few that everyone skipped over. There is an empty if statement setup in the code for you, since you have not learned about these formally yet we provided this part. Inside the parenthesis write your check to see if appleQuantity is less than 10.

2. The calculated review score you were given before was done incorrectly. This time you are going to calculate the review average yourself to make sure it’s correct. The total review score is 823 from 9 reviewers. Calculate the appleReview to be stored before you cast it into the appleReviewDisplay variable.

3. We want to see if certain days of the week impact our sales. Create a new int called dayOfWeek and set it to any value greater than or equal 0 (0 represents the first day of the week).

4. Now that we have a variable to track the day of the week, try adding any number of days you want to the initial value later in the code. For preparation for a future task, make this adjustment before the if code block.

5. The sales records show that the fourth day of the week (identified by 3) has lower sales of apples than any other day. Extend the appleQuantity check inside the if parentheses to see if it is the fourth day of the week. This should offer up the sale if either value is true.

6. Another review came in, so your logic needs to be updated for the average review score. This customer was not a fan and gave your apples a 52. Modify the review score to take this new information into account (don’t forget to increase the number of reviewers in your division as well as the total score).
