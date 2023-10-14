## Introduction

In this lab, you will open a notebook environment to practice debugging skills in Python. You’ll be presented with a security scenario to explore throughout the lab. You’ll utilize debugging skills to identify errors in code and resolve them so that the code achieves the desired outcome.

## What you’ll do

You have multiple tasks in this lab:

- Apply debugging strategies to ensure code works properly
    
- Adjust code to resolve syntax errors, exceptions, and logic errors


## Scenario

In your work as a security analyst, you need to apply debugging strategies to ensure your code works properly.

Throughout this lab, you'll work with code that is similar to what you've written before, but now it has some errors that need to be fixed. You'll need to read code cells, run them, identify the errors, and adjust the code to resolve the errors.

## Task 1
The following code cell contains a syntax error. In this task, you'll run the code, identify why the error is occuring, and modify the code to resolve it. (To ensure that it has been resolved, run the code again to check if it now functions properly.)

![Pasted image 20231007213442](https://github.com/cosbey/python/assets/32424700/8f6d3f6a-3d8d-4112-bcb6-2f2b04d65ec4)

```
# For loop that iterates over a range of numbers
# and displays a message each iteration

for i in range(10):
    print("Connection cannot be established")

```

```
Missing colon after for loop
```

## Task 2

In the following code cell, you're provided a list of usernames. There is an issue with the syntax. In this task, you'll run the cell, observe what happens, and modify the code to fix the issue.

![Pasted image 20231007213553](https://github.com/cosbey/python/assets/32424700/10913119-00fa-4ab5-9a57-c764bb00009c)

```
# Assign `usernames_list` to a list of usernames

usernames_list = ["djames", "jpark", "tbailey", "zdutchma" "esmith", "srobinso", "dcoleman", "fbautist"]

# Display `usernames_list`

print(usernames_list)
```

```
Missing quote in string.
```

## Task 3

In the following code cell, there is a syntax error. Your task is to run the cell, identify what is causing the error, and fix it.

![Pasted image 20231007213902](https://github.com/cosbey/python/assets/32424700/a6dc8927-d7a4-422f-bbb4-0932314f7692)


```
# Display a message in upper case 

print("update needed".upper())
```

```
Missing right parentheses for print function. 
```

## Task 4

In the following code cell, you're provided a `usernames_list`, a `username`, and code that determines whether the username is approved. There are two syntax errors and one exception. Your task is to find them and fix the code. A helpful debugging strategy is to focus on one error at a time and run the code after fixing each one.
![Pasted image 20231007214242](https://github.com/cosbey/python/assets/32424700/ab372da3-348f-429c-a419-aba752d785bb)

`Missing equals operand.`

![Pasted image 20231007214808](https://github.com/cosbey/python/assets/32424700/ba59ea1a-3975-4e86-8adb-221409bd306b)

![Pasted image 20231007214727](https://github.com/cosbey/python/assets/32424700/62cce005-6e90-4625-9820-1716a1d3ef7f)

`Needed indent for nested print function.`

```
# Assign `usernames_list` to a list of usernames that represent approved users

usernames_list = ["djames", "jpark", "tbailey", "zdutchma", "esmith", "srobinso", "dcoleman", "fbautist"]

# Assign `username` to a specific username 

username = "esmith"

# For loop that iterates over the elements of `usernames_list` and determines whether each element corresponds to an approved user

for name in usernames_list:

    # Check if `name` matches `username` 
    # If it does match, then display a message accordingly 

    if name == username:
        print("The user is an approved user")
```


## Task 5
In this task, you'll examine the following code and identify the type of error that occurs. Then, you'll adjust the code to fix the error.

![Pasted image 20231007215332](https://github.com/cosbey/python/assets/32424700/87602de3-11d6-48f4-8bd0-224eb5c12023)

```
# Assign `usernames_list` to a list of usernames

usernames_list = ["elarson", "bmoreno", "tshah", "sgilmore", "eraab"]

# Assign `username` to a specific username

username = "eraab"

# Determine whether `username` is the final username in `usernames_list` 
# If it is, then display a message accordingly 

if username == usernames_list[4]:
    print("This username is the final one in the list.")

```

Index for `usernames_list` is out of range. to correct issue, I changed it to four.

## Conclusion

**What are your key takeaways from this lab?**
