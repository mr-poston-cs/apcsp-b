## Week 9 <br>Week of 10/124

### [Unit 2](/apcsp/curriculum/2)

  |       |In Class               |Homework   |
  |-------|---------              |---------  |
  |**Mon**|Command-line Arguments | |
  |**Tue**|Exit Status and Exercises |Finish the `addition.c` program for homework - details below |
  |**Wed**| | |
  |**Thu**| | |
  |**Fri**| | |


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