## Introduction

In this lab, you will open a notebook environment to practice assigning values to variables in Python. You’ll be presented with a security scenario to explore throughout the lab. You’ll create variables to keep track of information relevant to the login process for approved users to log in to a specific device.

## What you’ll do

You have multiple tasks in this lab:

- Assign variables of various data types
    
- Use the type() function to return a variable's data type

## Introduction

Variables help security analysts to keep track of a variety of security-related information. For example, analysts may need to create Python variables for the users who are allowed to log in, the number of login attempts that they're permitted, and the current number of attempts that a user has made.

In this lab, you'll practice assigning values to variables and determining their data types.


## Scenario

You are a security analyst who is responsible for writing code that will automate analysis of login attempts made to a specific device. As the first step, you'll need to create variables to keep track of information relevant to the login process. This information includes the device ID, list of approved usernames, maximum login attempts allowed per user, current login attempts made by a user, and login status.

Throughout this lab, you'll assign these variables and check the data types of the variables.

## Task 1.

In your work as an analyst, imagine there is a device only users specified on an allow list can access, and its device ID is `"72e08x0"`.

In the following code cell, assign this value to a variable named `device_id`. Then, display the contents of the variable and observe the output.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

![Pasted image 20230924193335](https://github.com/cosbey/python/assets/32424700/f4c6599e-6859-49e1-8422-dbb56f6fbdf7)
![Pasted image 20230924193912](https://github.com/cosbey/python/assets/32424700/1c90e85d-dd56-42cd-a27f-1a70d1f143f7)

## Task 3.

As you continue your work, you're provided a list of usernames of users who are allowed to access the device. The usernames with this access are `"madebowa"`, `"jnguyen"`, `"tbecker"`, `"nhersh"`, and `"redwards"`.

In this task, create a variable called `username_list`. Assign a list with the approved usernames to this variable. Then, display the value of the `username_list` variable.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

![Pasted image 20230924194405](https://github.com/cosbey/python/assets/32424700/2c691a2f-cf5f-4795-aa9c-f471f75c48bf)

## Task 4.

In this task, find the data type of the `username_list`. Store the type in a variable called `username_list_type`. Then, display `username_list_type` to examine the output.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

![Pasted image 20230924194853](https://github.com/cosbey/python/assets/32424700/64ba6a04-4e31-4112-a607-d3a6a4b6437c)


#### **Question 2**.

**Based on the output above, what do you observe about the data type of `username_list`?**

The type has been identified as a list.

## Task 5.

Now, imagine that you've been informed that the previous list is not up-to-date and that there is another employee that now has access to the device. You're given the updated list of usernames with access, including the new employee, as follows: `"madebowa"`, `"jnguyen"`, `"tbecker"`, `"nhersh"`, `"redwards"`, and `"lpope"`.

In this task, reassign the variable `username_list` to the new list. Run the code to display the list before and after it's been updated to observe the difference.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

![Pasted image 20230924195403](https://github.com/cosbey/python/assets/32424700/a4e0bf45-e832-4e5c-972e-e4789c49e8d7)


#### **Question 3**

**Based on the output above, what do you observe about the contents of `username_list`?**
We've successfully updated the list to include the new usernames with access.

## Task 6.

In this task, define a variable called `max_logins` that represents the maximum number of login attempts allowed per user. Store the value `3` in this variable. Then, store its data type in another variable called `max_logins_type`. Display `max_logins_type` to examine the output.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

![Pasted image 20230924200151](https://github.com/cosbey/python/assets/32424700/b3ccc1e1-a165-407d-8409-585e6283422f)


#### **Question 4**

**Based on the output above, what do you observe about the data type of `max_logins`?**

The maximum amount of logins should be the number three, so we will find that our type should be an integer.

## Task 7

In this task, define a variable called `login_attempts` that represents the current number of login attempts made by a user. Store the value `2` in this variable. Then, store its data type in a variable called `login_attempts_type`. Display `login_attempts_type` to observe the output.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

![Pasted image 20230924201351](https://github.com/cosbey/python/assets/32424700/5311e22b-0ea2-46cd-b26a-cea8751b748d)



#### **Question 5**

**Based on the output above, what do you observe about the data type of `login_attempts`?**

Same as above. This type has been identified as an integer.

## Task 8

In this task, you'll determine the Boolean value that represents whether the current number of login attempts a user has made is less than or equal to the maximum number of login attempts allowed.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

![Pasted image 20230924202246](https://github.com/cosbey/python/assets/32424700/3199e160-50c4-4b8e-81ca-c7ede86044ae)


#### **Question 6**

**What is the output? What does this mean?**
Based off the Boolean operator, login attempts are less or equal to the max logins.


## Task 9.

This code continues to check for the Boolean value of whether `max_logins` is less than or equal to `login_attempts`. In this task, reassign other values to `login_attempts`. For example, you might choose a value that is higher than the maximum number of attempts allowed. Observe how the output changes.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

![Pasted image 20230924202758](https://github.com/cosbey/python/assets/32424700/a5b35d09-c496-40b7-8e87-22150e696763)


## Task 10.

Finally, you can also assign a Boolean value of `True` or `False` to a variable.

In this task, you'll create a variable called `login_status`, which is a Boolean that represents whether a user is logged in. Assign `False` to this variable and store its data type in a variable called `login_status_type` and display it.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

![Pasted image 20230924203238](https://github.com/cosbey/python/assets/32424700/9a939c7f-5cfb-45b5-8b40-384be7599982)

#### **Question 8**

**Based on the output above, what do you observe about the data type of `login_status`?**

This type is of the Boolean type which is represented as either True or False.

## Conclusion

**What are your key takeaways from this lab?**

The examples and tasks in this lab demonstrate how python can be used in simple terms. The decision making process can benefit greatly from these quick tidbits of information.



