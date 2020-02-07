<meta http-equiv="refresh" content="300"/>

## Week 22  
Week of 2/3/2020 

  |       |In Class               |Homework   |
  |-------|---------              |---------  |
  |**Mon**|[Chapter 6](/ap/curriculum/6/) Intro to Python |Make corrections to your quiz and turn in first thing tomorrow in class.<br>Make sure to finish [Homepage PSET](https://docs.cs50.net/2019/ap/problems/homepage/homepage.html) and submit, via Submit50, by 11:59 tonight<br>Also make sure your bring your PSET rubric with you in class tomorrow so I can grade it |
  |**Tue**|Continue with Python |See [tonight's homework](/ap/weeks/week22/#tuesday-homework) below|
  |**Wed**|Functions in Python<br>`argv` in Python |See [homework](/ap/weeks/week22/#wednesday-homework) below |
  |**Thu**|Swapping variables & Lists in Python | |
  |**Fri**|Data structures & objects | |

<div style="text-align:center">
<img src="https://cdn.lynda.com/course/661773/661773-637122005058334771-16x9.jpg" alt="python" width="40%">
</div>

### Tuesday Homework
* Create a folder in your `chapter6` folder called `homework`
* Inside the `homework` folder, create a file called `hw1.py`
* In `hw1.py` write a program that does the following:
  * Ask the user for a number. Depending on whether the number is even or odd, print out an appropriate message to the user. *Hint: how does an even / odd number react differently when divided by 2?*
* For extra credit on your HW grade:
  1. If the number is a multiple of 4, print out a different message.
  2. Ask the user for two numbers: one number to check (call it `num`) and one number to divide by (`check`). If `check` divides evenly into `num`, tell that to the user. If not, print a different appropriate message.
* Make sure to check your program by running it before you turn it in.
  * To run your program execute the below in the terminal window
```
cd chapter6/homework
python hw1.py
```
* To submit `hw1.py`, execute the below in the terminal window, logging in with your GitHub username and password when prompted. For security, you'll see asterisks (`*`) instead of the actual characters in your password.
```
submit50 candib80/cs50labs/python/hw1
```
### Wednesday Homework
* Create a file in your `chapter6/homework` folder named `hw2.py`
* In `hw2.py`, write a program that takes in a simple math problem (you need only worry about adding & subtracting)
* Your problem should be able to differentiate between addition and subtraction and depending on the operation, **call a function** to print the appropriate answer to the screen. **If you have no functions, then you will only receive 1/2 credit for this HW assignment**
* Make sure you convert the appropriate arguments to numbers
* For extra credit on your HW:
  * Add the ability to multiply and divide to your program (the user should type a lower case `x` for multiplication not `*`)
* Make sure to check your program by running it before you turn it in.
  * To run your program execute the below in the terminal window, *where `x` & `y` are numbers and `+` can be any operation you programmed*
```
cd chapter6/homework
python hw2.py x + y
```
* To submit `hw2.py`, execute the below in the terminal window, logging in with your GitHub username and password when prompted. For security, you'll see asterisks (`*`) instead of the actual characters in your password.
```
submit50 candib80/cs50labs/python/hw2
```