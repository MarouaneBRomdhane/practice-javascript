# Part II: Foundations of Programming

*Note: Before getting started on these exercises, please be certain that you've read through the root [README.md](../README.md) file in this repository.*

## Exercises

### Basic Requirements

#### Numbers

1. Enter the following expressions into your console.

   ```js
   1 + 2
   3 * 5
   5 / 4 - 13
   5000 * 234
   1073 / 57 + 200
   ```

2. Why are the values produced by the following two expressions different? What
   are they?

   ```js
   3 + 2 * 4 - 1
   (3 + 2) * (4 - 1)

   Answer: its simple math, what's between "()" gets calculated first
   ```

3. Calculate 50 years in minutes using the console.
```
console.log("how to find the number of minutes in 50 years" )

console.log("let's break it down, each hour a day has 60 minutes")
minute_per_hour_day=60
numer_of_hours_per_day=24
number_of_minutes_per_day=minute_per_hour_day*numer_of_hours_per_day
console.log("so the number of minutes a day is",number_of_minutes_per_day)
console.log("the number days in a year is 365")
number_of_days_per_year=365
number_of_minutes_per_year=number_of_minutes_per_day*number_of_days_per_year
console.log("the number of minutes per year is",number_of_minutes_per_year)
number_of_miutes_per_50_years= number_of_minutes_per_year*50
console.log("the number of minutes in 50 years is", number_of_miutes_per_50_years)
```

4. What is the percentage of letters in the english alphabet that are vowels (including y)? Use the
   console to find out.
   ```
number_of_vowels_including_y=6
number_of_english_alphabet=26
percentage_vowels_in_the_english_alphabet= (6 * 100)/26
console.log("the percentage of letters in the english alphabet that are vowels (including y)", percentage_vowels_in_the_english_alphabet)```

5. Try the following expressions in the console:

   ```js
   6 % 2
   42 % 10
   5 % 2
   6 % 3
   7 % 4
   100 % 12
   ```

   What is the significance of the result? How does the `%` (modulus) operator
   work?
``` It give the Mod of numbers```
6. Try the following:

   ```js
   3 % 2
   4 % 2
   5 % 2
   6 % 2
   ```

   What do the results tell you about the first operand to the modulus operator?
   ```pair and umpaired numbers```

#### Strings

1. Write a string that represents your full name.
```"marwen ben romdhane"```
2. Write a string that represents your favorite food.
```"Mlokhia"```
3. Use the `+` operator to combine (known as *concatenation*) two or more
   strings, *e.g.*:

   ```js
   // Your first and last names
   "John" + " " + "Doe"
   ```

   + Your first and last names (as shown above)
   + Your best friend's full name
   + Your home town, state and country

```"marwen"+" "+"ben"+" "+"romdhane"+" "+"john"+" "+"Cena"+" "+"sousse"+" "+"tunis"+" "+"tunisia"```
4. Fix the errors in the following strings:

   ```js
   Where are all the quotes?
   'hmm something is not right"
   'Do other ' * 'operators work with string concatenation?



   solution

   "Where are all the quotes?"
   "hmm something is not right"
   'Do other ' + 'operators work with string concatenation?'
   ```
"