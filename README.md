# Jackpot-Machine
Question

Write a C# program for "Jackpot Machine" that prints the coins he gets.
Don’t take any input from the user, just print the output. 

There are three reels which has numbers between 1 and 6 in the different 3 colors (red, blue and green).

+- If the reels show the same number in the same colors, he gets $30 points. 
   i.e. (4 4 4)  or  (3 3 3) or  (6 6 6)  or ...

-+ If the reels show the same number in the different colors, he gets $28 points. 
   i.e. (1 1 1)  or  (5 5 5) or  (3 3 3)  or ...

- +If the reels show the same number, but they are not all the same color and not all the different colors, he gets $26 points. 
   i.e. (1 1 1)  or  (5 5 5) or  (3 3 3)  or ...

+- If the reels show the consecutive numbers in the same color, he gets $20 points. 
   i.e. (2 3 4)  or  (3 2 1) or  (5 3 4)  or ...

-+ If the reels show the consecutive numbers in the different colors, he gets $18 points. 
   i.e. (2 3 4)  or  (3 2 1) or  (5 3 4)  or ...

- +If the reels show the consecutive numbers, but they are not all the same color and not all the different colors, he gets $16 points. 
   i.e. (2 3 4)  or  (3 2 1) or  (5 3 4)  or ...

-+ If the reels show the different numbers (not consecutive numbers, not any equality) in the same color, he gets $10 points.
   i.e. (1 4 2)  or  (2 5 1) or  (4 6 2)  or ...

-+ If the reels show the different numbers (not consecutive numbers, not any equality) in the different colors, he gets $8 points. 
   i.e. (1 5 6)  or  (3 5 2) or  (4 1 6)  or ...

- If the reels show the same color, but they are not all equal, not all the consecutive numbers and not all the different numbers, he gets $6 points.
   i.e. (1 4 4)  or  (2 5 5) or  (6 6 2)  or ...

- Otherwise, he gets $0 points. 
   i.e. (1 1 4)  or  (2 2 6)  or ...

BONUS: In addition to above conditions, if all numbers are even or odd in any color(s), he gets extra bonus $3.  
   i.e. (2 4 6)  or  (3 5 5) or  (6 4 6) or (5 1 3)  or (2 2 2) or (2 2 2) or ...

Sample Output:
5 5 5
Congratulations!  
You win $28.
You win $3 bonus.	Sample Output:
1 1 2
You lost   
	Sample Output:
1 1 3
You lost   
You win $3 bonus.


