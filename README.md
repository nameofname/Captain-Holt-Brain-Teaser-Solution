# Captain Holt's Brain Teaser Solution: 

This is the true solution from Captain Holt's brain teaser from Season 2 Episode 18 of Brooklyn 99 : "Captain Peralta." Before you read on, I just want to say that this problem drove me absolutely crazy! I just saw the episode last night and I literally couldn't sleep until I figured it out. I was lying there going through possibilities until 3 am when it hit me, and I got up and wrote down the solution. I later went back and refined it a little, so here it is. Hope you all sleep well after reading this. 

![Alt text](http://31.media.tumblr.com/cbacd818b46c49da33d64965591a7419/tumblr_mz2j20XaOA1r64iyzo3_250.gif)

## The problem : 
There are 12 men on an island. All of the men look identical, but one of them is either heavier or lighter than all of the other men. There is also a see-saw on the island. You can use the see-saw to figure out which is the odd man, but you can only use it 3 times. 

Now GO!

## Step 1 : 
* Number the men from 1 to 12. Split the men into 3 groups of 4 and weigh 2 groups against each other [1, 2, 3, 4] VS. [5, 6, 7, 8]. 
	a. IF the 2 scales are equal, then you know the odd man is in the remaining group of 3. Proceed to solution 1a. 
	b. IF the 2 scales are unequal, then you know the odd man is in the set of 1-8. Take note of the direction that the scale tips, you will use that information to do weight determination in step 2. Proceed to step 2. 

## Step 2 : 
* Shift all of the men 3 positions to the right and weigh them again using men from the 3rd group (which you know to all be neutral) to fill in the missing positions on the left scale. [10, 11, 12, 1] VS. [2, 3, 4, 5]. 
	a. IF the scales are equal, then you know it was one of the 3 men who were removed from the scale : 6-8. Use the weight difference from step 1 to determine heavier lighter. Proceed to solution 2a. 
	b. IF the scales are unequal, but the balance of weight changes (ie. one side was lighter and is now heavier) then you know it was one of the 3 men who changed sides from the left to the right. Use the weight info from step 1 to determine lighter / heavier. 
	c. IF the scales are still unequal but remain the same, then you know it was 1 of the 2 men who did not change sides, 1 or 5. You cannot determine lighter, heavier, proceed to solution 2c. 

## Solutions : 
* Solution 1a. The first measurement of 4 vs. 4 was equal. The odd man is in the group is in 9-12. You don't know if he is heavier or lighter, and there is a 2 step solution to this : 
	* Take 3 men from the group and measure against 3 neutral men from 1-8. [9, 10, 11] VS. [1, 2, 3]. 
		* IF the measurement is equal then the odd man is 12. You don't know heavier or lighter, but you still have 1 remaining move. 
			* Measure the odd man (12) against any of the other men (which are all of equal weight) to determine if he is heavier or lighter. 
		* IF the scale is unequal, then you know the odd man is within the group 8-11. Take note of whether it is heavier or lighter. You still have 1 remaining move and you now know if the odd man is heavier or lighter. 
			* {{3 remaining with known weight solution}}  Since the weight is known, all you need to do is measure 2 men from the remaining 3 against each other. There are 2 possible outcomes, either they are equal, or unequal. 
				* If they are equal, it is the remaining man not being measured. 
				* If they are unequal then the odd man is within the last 2 being measured. 

* Solution 2a. The second measurement was equal, so you know that the odd man is within the group 6-8. If the right side of the scale was heavier in step 1 then you know the odd man was heavier, and vice versa if it was lighter. 
	* Use the {{3 remaining with known weight solution}} from solution 1a. 

8 Solution 2b. The second measurement was equal but the first measurement was not. You know therefore that the odd man is within the group 6-8 (the 3 men removed from the scale). You can also use the weight difference from the first step to determine if that man was heavier or lighter. 
	* Use the {{3 remaining with known weight solution}} from solution 1a. 

* Solution 2c. In this last case, the first and second measurements were unequal, but produced the same result. Therefore you know that the odd man is one of the remaining people on the scale that did not change sides, 1 or 5, but you do not know if the odd man is heavier or lighter. 
	* Weigh the lighter of the 2 men against any other neutral man. If they are equal then it is the one not being measured and he is heavier. If he is lighter then it is the one being measured and he is lighter. 




