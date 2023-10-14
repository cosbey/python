## Introduction

In this lab, you will open a notebook environment to practice writing iterative statements in Python. You’ll be presented with a security scenario to explore throughout the lab. You’ll practice creating loops to automate repetitive processes and make them more efficient.

## What you’ll do

You have multiple tasks in this lab:

- Create a simple loop related to connecting to a network
    
- Utilize a for loop to investigate login activity by comparing a list of allowed IP addresses with a list of IP addresses from which users have tried to log in
    
- Use a while loop to generate unique employee IDs by iterating through numbers

## Scenario

You're working as a security analyst, and you're writing programs in Python to automate displaying messages regarding network connection attempts, detecting IP addresses that are attempting to access restricted data, and generating employee ID numbers for a Sales department.

## Task 1

In this task, you'll create a loop related to connecting to a network.

Write an iterative statement that displays `Connection could not be established` three times. Use the `for` keyword, the `range()` function, and a loop variable of `i`. Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.

![Pasted image 20230925211855](https://github.com/cosbey/python/assets/32424700/c120869e-34ee-4156-8170-dd8668f609a4)


## Task 2

The `range()` function can also take in a variable. To repeat a specified action a certain number of times, you can first assign an integer value to a variable. Then, you can pass that variable into the `range()` function within a `for` loop.

In your code that displays a network message connection, incorporate a variable called `connection_attempts`. Assign the positive integer of your choice as the value of that variable and fill in the missing variable in the iterative statement. Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell. Test out the code with different values for `connection_attempts` and observe what happens.
![Pasted image 20230925212018](https://github.com/cosbey/python/assets/32424700/db70fb21-938a-4b58-a314-2cd2c1fddcce)

## Task 3
This task can also be achieved with a `while` loop. Complete the `while` loop with the correct code to instruct it to display `"Connection could not be established."` three times.

In this task, a `for` loop and a `while` loop will produce similar results, but each is based on a different approach. (In other words, the underlying logic is different in each.) A `for` loop terminates after a certain number of iterations have completed, whereas a `while` loop terminates once it reaches a certain condition. In situations where you do not know how many times the specified action should be repeated, `while` loops are most appropriate.

Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.

![Pasted image 20230925213000](https://github.com/cosbey/python/assets/32424700/15f74ab6-51ea-41ee-8d41-16405a804ee8)


## Task 4
Now, you'll move onto your next task. You'll automate checking whether IP addresses are part of an allow list. You will start with a list of IP addresses from which users have tried to log in, stored in a variable called `ip_addresses`. Write a `for` loop that displays the elements of this list one at a time. Use `i` as the loop variable in the `for` loop.

Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.

![Pasted image 20230925213201](https://github.com/cosbey/python/assets/32424700/2e9e95fa-a91e-4ef3-b3fd-6f40a8562b47)


## Task 5

You are now given a list of IP addresses that are allowed to log in, stored in a variable called `allow_list`. Write an `if` statement inside of the `for` loop. For each IP address in the list of IP addresses from which users have tried to log in, display `"IP address is allowed"` if it is among the allowed addresses and display `"IP address is not allowed"` otherwise.

Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.

![Pasted image 20230925213815](https://github.com/cosbey/python/assets/32424700/665e4d18-c07b-44e7-b30f-905a47c74888)

## Task 6

Imagine now that the information the users are trying to access is restricted, and if an IP address outside the list of allowed IP addresses attempts access, the loop should terminate because further investigation would be needed to assess whether this activity poses a threat. To achieve this, use the `break` keyword and expand the message that is displayed to the user when their IP address is not in `allow_list` to provide more specifics. Instead of `"IP address is not allowed"`, display `"IP address is not allowed. Further investigation of login activity required"`.

Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.

![Pasted image 20230925223116](https://github.com/cosbey/python/assets/32424700/d1fb330b-6644-409a-8802-c325f34b2103)



## Task 7

You'll now complete another task. This involves automating the creation of new employee IDs.

You have been asked to create employee IDs for a Sales department, with the criteria that the employee IDs should all be numbers that are unique, divisible by 5, and falling between 5000 and 5150. The employee IDs can include both 5000 and 5150.

Write a `while` loop that generates unique employee IDs for the Sales department by iterating through numbers and displays each ID created.

Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.

![Pasted image 20230925221756](https://github.com/cosbey/python/assets/32424700/42229879-327a-479b-8377-e27481528f37)


## Task 8

You would like to incorporate a message that displays `Only 10 valid employee ids remaining` as a helpful alert once the loop variable reaches `5100`.

To do so, include an `if` statement in your code.

Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.


## Conclusion
**What are your key takeaways from this lab?**
