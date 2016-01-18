# PHP Basic course exercisses

## Hello PHP World

### Task 000 - Prepare php page

Crate page called `task001.php` for your forst task. File should start with opening tag: `<?php`. PHP file should NOT include closing tag `?>`.

Reason why we left out closing tag is it can cause a lot of problems later. If you want to learn more read [this](http://stackoverflow.com/questions/4410704/why-would-one-omit-the-close-tag#4499749)

### task 001 - Echo language construct

In the file from previous task print out text using the language constuct `echo` and single quotes `'`;

I went down to the river,  
I set down on the bank.  
I tried to think but couldn't,  
So I jumped in and sank.  

I came up once and hollered!  
I came up twice and cried!  
If that water hadn't a-been so cold  
I might've sunk and died.

### task 002 - Variables

Create variable with name `firstName` and initialize it with your name. Next, create a variable `$age` and initialize with your ages. Create one more variable with name `height` and assign your height as double (Example `1.78` in meters).

Use `print_r` and `var_dump` to see variable values and type.

You can notice that all variables are `strings`. You should convers `age` into `integer` and `height` into `double`.

After conversion asign a values to new variables `ageInteger` and `heightDouble`. Use `var_dump` or `print_r` to see how new varibles looks like. 


### task 003 - Array - most frequent element

Create the array by reading user inputs on the screen. User will enter array values by separating them with commas.

Than find the most frequent element and output in on the screen.

### task 004 - Array - reverse array

Create the array like in previous task. Reverse the array values and output array on the screen.

### task 005 - Array - largest in array

Create the array on the same way we did so far. This time add validation that array can accept only integer or double.

Find the largest element and output his value on the screen.

### task 006 Array - sort the array

Create the array that accept only integer and double like in previous task. Sort the array values in ascending order.