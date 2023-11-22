# Debugging assessment

1. Line 3
   // Reading the line
   Syntax error:

   - missing semicolon ';' after search.
   - It was used two different quotes ” and ’.

2. From Line 3 to line 6
   //Checking the console in web I found this "Uncaught TypeError: Cannot read properties of null (reading 'addEventListener')" and I realized that something was wrong and I started to read again step by step.
   Syntac error:

   - missing # to call correctly the ID from Html.

3. Line 4
   // Reading the line
   Syntax error:

   - Query selector is not written correctly, the letter "o" is missing

4. Line 17
   // Making a console.log of data, the promise that came back from JSON format API response fields were a series of objects and arrays.
   Runtime error:

   - Found data.temp undefined because we need to follow the order of the object: data.main.temp

   - It’s better to use Math.round() to avoid decimals in out temperature.

5. Line 19
   // Reading the line
   Syntax error:

   - If we write the name of the function with ${} then we will have to write the Back quotes ``

6. Line 28
   // Reading the conditionals.
   Logical error:

   - If we want print "winter is coming.." we need that conditional of temp should be < 0 and not >.

7. Line 30
   // Reading the conditionals.
   Logical error:

   - Correct the conditional and finish it to make it between 0 and 10.
     (temp >= 0 && temp <= 10)

8. Line 32
   // Reading the conditionals.
   Logical error:

   - Correct the conditional and finish it to make it more than 10 until 20.
     (temp > 10 && temp <= 20)

9. Line 39
   //checking live, the buttons didn't work and reading code, the function argument was missing parentheses ()Syntax error:

   - function e should be function(e)

10. Line 40
    Runtime error:

    - for preventDefault we need to recall the argument. e.preventDefault();
