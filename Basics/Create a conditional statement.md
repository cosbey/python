## Introduction

In this lab, you will open a notebook environment to practice writing conditional statements in Python. You’ll be presented with a security scenario to explore throughout the lab. You’ll practice applying conditional statements to automate processes across an organization.

## What you’ll do

You have multiple tasks in this lab:

- Write code that determines if a user’s operating system requires an update
    
- Write code that determines if login attempts were made by approved users and if login attempts occurred during organization hours

## Scenario

You're working as a security analyst. First, you are responsible for checking whether a user's operating system requires an update. Then, you need to investigate login attempts to a specific device. You must determine if login attempts were made by users approved to access this device and if the login attempts occurred during organization hours.

## Task 1.

You are asked to help automate the process of checking whether a user's operating system requires an update. Imagine that a user's device can be running one of the following operating systems: OS 1, OS 2, or OS 3. While OS 2 is up-to-date, OS 1 and OS 3 are not. Your task is to check whether the user's system is up-to-date, and if it is, display a message accordingly. To do this, complete the conditional statement using the keyword `if`. Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.

![Pasted image 20230924215111](https://github.com/cosbey/python/assets/32424700/b98b3193-1da9-416d-a2c8-36714d91a745)


## Task 2

Now try assigning the `system` variable to different values (`"OS 1"`, `"OS 2"`, and `"OS 3"`), run the cell, and observe what happens. Keep the conditional statement as is. Be sure to replace the `### YOUR CODE HERE ###` with your own code.

![Pasted image 20230924215521](https://github.com/cosbey/python/assets/32424700/99244850-6341-4bfe-a771-495205fee5a6)


## Task 3

Nothing is displayed when the `system` is not equal to `"OS 2"`. This is because the condition didn't evaluate to `True`.

It would be beneficial if an alternative message is provided to them when updates are needed.

In the following cell, add the appropriate keyword after the first conditional so that it will display a message that conveys that an update is needed when the `system` is not running OS 2. Be sure to replace each `### YOUR CODE HERE ###` with your own code.

Then, set the value of the `system` variable to indicate that OS 2 is running and run the cell. After observing what happens, set the value of `system` to indicate either that OS 1 is running or that OS 3 is running and run the cell.

![Pasted image 20230924215912](https://github.com/cosbey/python/assets/32424700/9fee62dc-ab22-4456-ab35-e210fb0fcf81)


## Task 4

This setup is still not ideal. If the variable `system` contains a random string or integer, the conditional above would still display `update needed`.

To improve the conditional, you will need to add the `elif` keyword. In the following cell, you will add two `elif` statements after the `if` statement, to create the final code. The first `elif` statement will display `update needed` if `system` is `"OS 1"`. The second `elif` statement will display the same message, if `system` is `"OS 3"`. Complete the second `elif` statement, and then run the cell with the variable `system` set to a different string each time. Observe what happens when each operating system is running. Also try assigning the `system` variable to some strings other than `"OS 1"`, `"OS 2"`, and `"OS 3"` (for example `"OS 4"`).

Be sure to replace each `### YOUR CODE HERE ###` with your own code.

![Pasted image 20230924221751](https://github.com/cosbey/python/assets/32424700/d58538fd-320b-4307-8d0e-c5905f88e58a)

#### **Question 3**

**Under this setup what happens when OS 2 is running? What happens when OS 1 is running? What happens when OS 3 is running? What happens when neither of those three operating systems are running?**

When this particular code is executed under the current conditions, OS 1 and OS 2 is noted as "no update needed." However, when we change the conditions for the system we'll continue to generate a zero value. This indicates that we'll need additional code to finish our project. 

## Task 5

Writing code that is readable and concise is a best practice in programming.

The conditional above can be written more concisely.

In the following cell, use a logical operator to combine the two `elif` statements from the previous setup into one `elif` statement. Be sure to replace each `### YOUR CODE HERE ###`. Then, assign the `system` variable to a value and run the cell. Like you did in the previous task, use `"OS 1"`, `"OS 2"`, `"OS 3"`, and other strings.

![Pasted image 20230924223026](https://github.com/cosbey/python/assets/32424700/c122f740-692f-450e-8393-599160ed0302)

#### **Question 4**

**What do you observe about this conditional?**
This is another example of how to execute a similar expression that's more concise.

## Task 6

Now you'll move on to the next part of your work. You've been asked to investigate login attempts to a specific device. Only approved users should log on to this device.

You'll start with two authorized users, stored in the variables `approved_user1` and `approved_user2`. You'll need to write a conditional statement that compares those variables to a third variable, `username`. This will be the username of a specific user trying to log in. Be sure to replace each `### YOUR CODE HERE ###` with your own code.

![Pasted image 20230924223755](https://github.com/cosbey/python/assets/32424700/7931eec4-2ed1-474d-9234-58cd4c73a5bf)


## Task 7

The number of approved users has now expanded to five. Rather than storing each of the approved users' usernames individually, it would be more concise to store them in an allow list called `approved_list`.

The `in` operator in Python can be used to determine whether a given value is an element of a sequence. Using the `in` operator in a condition can help you check whether a specific username is part of a list of approved usernames. For example, in the code below, `username in approved_list` evaluates to `True` if the value of the `username` variable is included in `approved_list`.

Complete the code in the following cell to display the same messages that you used in the previous step. When the condition evaluates to `True`, the following message will be displayed: `"This user has access to this device."` When it evaluates to `False`, the following message will be displayed: `"This user does not have access to this device."` Then, run the cell to observe its behavior. Be sure to replace each `### YOUR CODE HERE ###` with your own code. Afterwards, reassign the `username` variable to a username that is not approved and run the cell to observe what happens.

![Pasted image 20230924224321](https://github.com/cosbey/python/assets/32424700/be834ef7-93a2-4392-b8da-a618ed459154)

## Task 8

Now you'll write another conditional statement. This one will use a `organization_hours` variable to check if the user logged in during specific organization hours. When that condition is met, the code should display the string `"Login attempt made during organization hours."`. When that condition isn't met, the code should display the string `"Login attempt made outside of organization hours."`.

The `organization_hours` variable will have a Boolean data type. If `organization_hours` has a Boolean value of `True`, that means the user is logged in during the specified organization hours. If `organization_hours` has a Boolean value of `False`, that means the user is not logged in during those hours.

Complete the conditional in the following cell. Be sure to replace each `### YOUR CODE HERE ###` with your own code before running the following cell.

![Pasted image 20230924224910](https://github.com/cosbey/python/assets/32424700/28a21490-a2d6-4a81-bec6-b051acff8414)

## Task 9

The following cell assembles the code from the previous tasks. It includes the conditional statement that checks if a user is on the allow list and the conditional statement that checks if the user logged in during organization hours.

Run the cell below a few times. Each time, enter a different combination of values for `username` and `organization_hours` to observe how that affects the output.

![Pasted image 20230924225323](https://github.com/cosbey/python/assets/32424700/241b9cb5-dee1-4a1c-bbc6-7ef4dc32fbec)


## Task 10

You can also provide a single message about the login attempt. To do this, you can join both conditions into a single conditional statement using a logical operator. This will make the code more concise.

Examine the code in the following cell and add the missing operator that would allow for a single message. Be sure to replace each `### YOUR CODE HERE ###` with your own code before running the following cell. Then run the cell, entering different combinations of information, and observe what happens.


![Pasted image 20230924225557](https://github.com/cosbey/python/assets/32424700/2701127f-5fc7-4dc7-b62c-bedd22d88b76)

## Conclusion

**What are your key takeaways from this lab?**
This lab builds on the previous by providing examples of how Python can be used to not only audit users but manage assets as well in an organization. 
