TEAM MEMBERS:
-----------------------------------
1. Vinayaka SN (211AI040)
2. Vivek Vittal Biragoni (211AI041)
3. Raghavendra (211AI029)


STEPS FOR EXECUTING CODE:
--------------------------------------------------------------------------------------------------------------
1. Warnsdorff's Algorithm:
	--> Run the program once and enter the board size(n).
	--> Then enter the Initial position of the knight(x, y) one by one.

2. Brute Force(Backtracking):
	--> Run the program once and it shows the output of desired board size which already exists in the code.

3. Warnes-Brute(Hybrid):
	--> Run the program once and it shows the output of desired board size which already exists in the code.

4. Game:
	--> Run the index.html file and set the board size in the local host website to play the game.


SAMPLE INPUT AND OUTPUT:
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
1. Warnsdorff's Algorithm:
	INPUT:	Enter N, size of the board (NxN): 6
		Enter initial x position: 0
		Enter initial y position: 0
	OUTPUT: [[ 1. 10. 21. 36.  7. 12.]
 		[22. 33.  8. 11. 20. 27.]
 		[ 9.  2. 35. 26. 13.  6.]
 		[34. 23. 32. 17. 28. 19.]
 		[ 3. 16. 25. 30.  5. 14.]
 		[24. 31.  4. 15. 18. 29.]]

		Knight's positions:  [[0, 0], [2, 1], [4, 0], [5, 2], [4, 4], [2, 5], [0, 4], [1, 2], [2, 0], [0, 1], [1, 3], [0, 5], [2, 4], [4, 5], [5, 3], [4, 1], [3, 3], [5, 4], [3, 				     5], [1, 4], [0, 2], [1, 0], [3, 1], [5, 0], [4, 2], [2, 3], [1, 5], [3, 4], [5, 5], [4, 3], [5, 1], [3, 2], [1, 1], [3, 0], [2, 2], [0, 3]]


2. Brute Force(Backtracking):
		INPUT: Board size: 6
		OUTPUT: 0       15      6       25      10      13
			33      24      11      14      5       26
			16      1       32      7       12      9
			31      34      23      20      27      4
			22      17      2       29      8       19
			35      30      21      18      3       28


3. Warnes-Brute(Hybrid):
	INPUT: Board Size : 8
	OUTPUT: Knight's Tour:
		0       33      2       17      48      31      12      15
		3       18      55      32      13      16      49      30
		56      1       34      47      54      51      14      11
		19      4       59      52      35      46      29      50
		40      57      36      45      60      53      10      25
		5       20      41      58      37      26      63      28
		42      39      22      7       44      61      24      9
		21      6       43      38      23      8       27      62