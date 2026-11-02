# Lab 7: Prime Checker
Due: Monday, November 2nd 2026

### Code a program that checks whether or not a given number is prime.  Your program should...

* Prompt the user to input a natural number greater than 2, and
* Display `Prime` if the number is prime or `Not Prime` if the number is not prime.

**What is a Prime Number?**

A prime number is a natural number with no divisors other than 1 and itself.

Example/

|Primes|Non-Primes|
|---|---|
|2 (The only divisors of 2 are 1 and 2)<br>3 (The only divisors of 3 are 1 and 3)<br>5 (The only divisors of 5 are 1 and 5)<br>7 (The only divisors of 7 are 1 and 7)|4 (The divisors of 4 are 1, 2, and 4)<br>6 (The divisors of 6 are 1, 2, 3, and 6)<br>8 (The divisors of 8 are 1, 2, 4, and 8)<br>9 (The divisors of 9 are 1, 3, and 9)|

**Hints:** 
* Define a boolean variable, `is_prime`, to determine whether or not the user's number is prime.  Initially, assign it the value, `True`.
* Within your loop, if the user's number has any divisors other than 1 and itself, change the value of `is_prime` from `True` to `False`.
* Following your loop, use a conditional to display `Prime` if the value of `is_prime` is `True` or `Not Prime` if the value of `is_prime` is `False`.

**Required File Name:** `LastNameFirstInitial_Lab_07_Prime_Checker.py`

**Note:** Your program must have a robust, well-documented, version history.  Programs submitted without a robust, well-documented, version history will not be accepted.

|Assessment Criteria|Mastery| 
|---|---|
|**Design Thinking** |My version history demonstrates genuine engagement in the design thinking process by including several versions of my program developed iteratively over time. |
|**Control Flow**|My code demonstrates mastery of conditionals and for loops, and it is both logically and syntactically correct.|
|**Communication**|My code contains appropriate comments and the commit notes in my version history document my program's development.|
