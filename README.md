
# Communicating with Your Computer via the Shell: A Walkthrough

In this lab, I'll walk you through the process of interacting with the Bash shell by inputting text and performing basic mathematical calculations using the `echo` and `expr` commands. I’ll also demonstrate how to clear the shell using the `clear` command. By the end of this lab, you'll understand how to generate output and manipulate data via the shell.

### Prerequisites:
- You are already logged in to the Bash shell as `analyst`.
- You will be using a Linux terminal for all the steps in this lab.

## Task 1: Generate Output with the `echo` Command

The `echo` command outputs text strings to the shell. Let’s begin with a simple command.

### Step 1: Display a String
I start by typing the following command:
```bash
echo hello
```
Once I press `ENTER`, the shell returns:
```
hello
```
<p align="center">
  <img src="https://github.com/user-attachments/assets/ea7f49db-ae4c-48c3-a986-ea1e17054a95" height="70%" width="70%" >
</p>


Here, `hello` is the string I input, and the shell outputs it as expected.

### Step 2: Use Quotation Marks
Now, I’ll add quotation marks around the text to group it. Although the output will be the same, it’s a good habit when dealing with more complex strings.
```bash
echo "hello"
```
The result is:
```
hello
```

<p align="center">
  <img src="https://github.com/user-attachments/assets/b92e172b-36e4-42a6-a42b-5c072ffa4dce" height="70%" width="70%" >
</p>

### Step 3: Output My Name
Next, I’ll replace the string with my name:
```bash
echo "name"
```
The shell returns:
```
name
```
<p align="center">
  <img src="https://github.com/user-attachments/assets/c5c9802b-d3c6-41dd-8756-02d7b5d34724" height="70%" width="70%" >
</p>


The string I input is echoed back as output. It's that simple!

---

## Task 2: Generate Output with the `expr` Command

The `expr` command helps perform basic mathematical calculations. Let's try it out.

### Step 1: Subtracting Alerts
Imagine I have 32 alerts, and 8 require action. To calculate how many are false positives, I subtract 8 from 32 using the `expr` command:
```bash
expr 32 - 8
```
The result is:
```
24
```

<p align="center">
  <img src="https://github.com/user-attachments/assets/e87ecf84-e188-4986-b651-e881c6ab55fc" height="70%" width="70%" >
</p>

### Step 2: Multiplying Monthly Login Attempts
Next, I’ll calculate the total number of login attempts expected in a year. With 3500 login attempts each month, I multiply that by 12:
```bash
expr 3500 \* 12
```
The correct result:
```
42000
```
<p align="center">
  <img src="https://github.com/user-attachments/assets/9bb5e669-e31a-45c1-a350-fc6b1762201c" height="70%" width="70%" >
</p>
---

## Task 3: Clear the Bash Shell

Now, I’ll use the `clear` command to clean up the shell. This will give me a fresh window for further commands.

### Step 1: Clearing the Screen
```bash
clear
```


<p align="center">
  <img src="https://github.com/user-attachments/assets/d32904d3-4c13-4fc5-a648-977647bbe537" height="70%" width="70%" >
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/1b4e8bd2-1b9d-4c2d-838a-e3daa0d2084b" height="70%" width="70%" >
</p>


The screen is now cleared, and I can start fresh from the top of the terminal.

---

## Optional Task: More `echo` and `expr` Practice

I encourage you to try out more commands on your own. Here are a couple of examples I tested:

### Additional `echo` Example
```bash
echo "This is Cybersecurity Analyst Kwe hoping you're enjoying yourself in my Github!"
```
The result:
```
This is Cybersecurity Analyst Kwe hoping you're enjoying yourself in my Github!
```

### Additional `expr` Calculation
To practice, I calculated the sum of 25 and 15:
```bash
expr 9 + 10
```
The result:
```
19
```

<p align="center">
  <img src="https://github.com/user-attachments/assets/91ec8ca0-a9d0-4a98-a40d-b42b83323a7b" height="70%" width="70%" >
</p>

Feel free to explore more calculations with different operators like `+`, `-`, `/`, and `*`!

---

## Conclusion
In this lab, I demonstrated how to interact with the Bash shell using `echo` for text output, `expr` for basic calculations, and `clear` to clean the terminal. These fundamental commands are essential for navigating and manipulating data via the command line. Try experimenting with these commands further to deepen your understanding!
