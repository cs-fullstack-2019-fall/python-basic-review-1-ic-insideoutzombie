# Basic review questions for Python practice

### Create a ```main``` function and a function for each exercise. Call each exercise from ```main```

1. Variables:
- Define a variable called 'season' and assign it your favorite season as a String. Print 'May favorite season is Fall' (use your favorite season value)

2. Loop:
- Write a loop that prints backwards from 10 - 1, then prints 'LIFTOFF!'

3. Conditionals:
- Create 3 Strings containing movie names of your choice. List the 3 choices and prompt the user to select their favorite movie by entering the corresponding number. Once the User makes a selection, print ```You selected WHATEVER_MOVIE_they_selected```

4. Functions:
- Write a function that accepts a numeric grade as a parameter. The function should return the appropriate letter grade based on the value passed in (10 point scale). If an invalid grade passed in (e.g. > 100 or < 0) return ```invalid grade```. Prompt the User for a grade value. Call your function and print the returned grade or error message in the console.

5. Arrays:

```game_wish_list = ['CyberPunk', 'Borderlands 3', 'Break the Game']```

- Write a loop that iterates through the list and prints each game
- Prompt the User for a game to add
- Add the game entered to the list, and print out the updated list

6. Classes:

- Create an empty list called ```game_collection```
- Create a Game class that has the properties, ```name```, ```release_year```, and ```rating```
- Add a method to update the rating (1 - 5)
- Add a 'str' method that pretty-prints the information about the game

ex.
```
Game Title: Ion Fury
Release: 	2019
Rating: 	5
```
- Create 3 different instances of ```Game``` with data of your choosing and add the objects to your list
- Use a loop to print the list of objects
- Prompt the User to enter the index value of the game to change
- Prompt the User to enter a ```new rating``` for the game
- If the rating is valid (1 - 5) update the Game instance, then re-print the full list of Games
- If invalid, print ```Invalid Rating```


==================================================================
