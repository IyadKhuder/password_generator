# password_generator

Notes:
-	I included comments within the code, so there’s no need to explain it here, I believe.
-	The user is free to use upper- or lowercase letters, or to include digits/special characters in the input words.
-	However, I adopted 2 assumptions which are reasonable and intuitive:
1.	The maximum allowed number of user-input words is 9 (to prevent the case when a user hits by mistake a digit twice, resulting in entering 99 instead of 9, for instance. Nine words is pretty enough, anyway). Choosing a number of words that is greater than 9 would return a validation error (See Error 1 in Fig. 1 below). Numerical input, namely the number of words and the password length are validated. Entering a non-numerical value returns a validation error (See Error 2 in Fig. 1 below).
2.	A word, by definition, must contain at least one letter; entering a string that has no letters would return a validation error (See Error 3 in Fig. 1 below).
-	I made sure to make the program ready for any scenario. For example, the user might decide to use just a single word that is formed of just one letter yet wanting a 12-letteer long password. 

