## Week 9 <br>Week of 10/124

### [Unit 2](/apcsp/curriculum/2)

  |       |In Class               |Homework   |
  |-------|---------              |---------  |
  |**Mon**|Command-line Arguments | |
  |**Tue**|Exit Status and Exercises |Finish the `addition.c` program for homework - [details below](https://candib80.github.io/apcsp/weeks/week9/#additionc) |
  |**Wed**|Go over Addition<br>Start on Initials |Work on Initials - [details below](https://candib80.github.io/apcsp/weeks/week9/#initials) |
  |**Thu**|Go over Initials then start on [Lab2](https://cs50.harvard.edu/ap/2023/curriculum/x/labs/2/) |Work on Lab 2 |
  |**Fri**|Continue working on Lab2 | |


<meta http-equiv="refresh" content="300"/>

<img src="https://media.geeksforgeeks.org/wp-content/cdn-uploads/Array-Declaration-In-C.png" alt="arrays in C" height="350">
<img src="https://media.geeksforgeeks.org/wp-content/cdn-uploads/20201209135923/String-in-C.png" alt="Strings in C" height="350">


#### `addition.c`

- Write a program `addition.c` that adds two numbers provided as command-line arguments.
  - The program should accept two integers as command-line arguments.
  - The program should output both original numbers, and their sum. If the program is run as `./additional 2 8`, for example, the output should be `2 + 8 = 10`.
  - If the incorrect number of command-line arguments is provided, the program should display an error and return with exit code 1.
  
  - Sample usage: 

  ```c
    $ ./addition 2 8
    2 + 8 = 10
  ```

  ```c
    $ ./addition 2
    Usage: ./addition x y
  ```

#### Initials

- Write a program `initials.c` that takes a user’s full name as input, and outputs their initials.
  - The program should accept a user’s name using `get_string`
  - Initials should all be printed as uppercase letters, even if the name contains lowercase letters
  - Students can assume that the user’s names will be separated by one space
  - Sample usage:
      ```
      $ ./initials
      Name: David J. Malan
      DJM
      ```

  - Partial sample solution:
    ```c
      #include <cs50.h>
      #include <ctype.h>
      #include <stdio.h>
      #include <string.h>

      int main(void)
      {
        ...
    ```