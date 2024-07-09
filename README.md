WEEKLY ALGORITHM - 1 

Find the first ten digits of the sum of the following hundred numbers 50 digit numbers

First, we create a list method and add the numbers given to us to our list.
Then we create a variable that holds all the sums using the BigInteger object.

With the foreach loop, we add each element in our list to the variable we just created. While doing this, we convert the string elements in our list into an integer by using the Parse term.

Now we have the totals, but the total required from us is the first 10 digits of the result. As you know, the first rule of the software is that it starts with 0. First of all, we need a method called Substring to find the first 10 digits of the result we have, but this method only exists in the string. Therefore, we convert the result we have into the string variable we just created and transfer the first 10 digits to our new variable with the Substring method.

Finally, the only thing to do is to print the result on the screen.

For those who don’t know how Substring works, Substring(X, Y) is where x is our starting point and y is the amount it will go to. So, starting from x, including x, move up to y and give us the result we want during this process.
