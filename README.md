# Sams Teach Yourself C | Storing Information: Variables and Constants

## Files

 - *const.c* is a provided program used to illustrate numeric variables and constants.

## Quiz

1. An **integer** variable stores whole numbers. A **floating-point** variable stores real numbers.
2. A **double-precision floating-point** variable would be used instead of a **single-precision floating-point** variable because
the number requires greater precision and has a value that is greater than that which can be stored in a `float`. 
3. The five rules that are always true when allocating size for variables are
  1. `char` is 1 byte
  2. `short` is less than or eq to the size of an `int`
  3. `int` is less than or equal to the size of a `long`
  4. `unsigned` is equal to the size of an `int`
  5. `float` is less than or eq to the size of a `double`
4. The two advantages of using a **symbolic constant** instead of a **literal constant** are (1) you'll only need to change a constant value in one
place if you need to update the value (2) the code is easier to read.
5. A constant named MAXIMUM that has a value of 100 can be defined with `const int MAXIMUM = 100` or `#define MAXIMUM 100`.
6. The characters allowed in C variable names are letters, numbers, underscores.
7. When creating variable names, they cannot begin with a number or be a C language keyword. In addition, beginning with an underscore is not recommended.
8. The difference between a symbolic and literal constant is that the literal constant is typed directly into the source code whenever it is needed.
9. The minimum value that an `int` can hold is -2,147,483,647.

## Exercises

1. What variable types for these values:
  - person's age to nearest year: `char`
  - number of Facebook friends a person has: `short`
  - radius of a circle: `float`
  - annual salary: `float`
  - cost of an item: `float`
  - highest grade on a test: `char`
  - a person's first initial: `char`
  - temperature: `float`
  - person's net worth: `float`
  - distance to a star in miles: `double`
2. Name variables in 1:
  - `age_in_years`
  - `friend_count`
  - `radius`
  - `salary`
  - `item_cost`
  - `MAX_GRADE`
  - `first_initial`
  - `temp`
  - `net_worth`
  - `distance_in_miles`
3. Write declarations for the variables in 2:
  - `char age_in_years`
  - `short friend_count`
  - `float radius`
  - ` float salary`
  - `float item_cost`
  - `const char MAX_GRAD`
  - `char first_inital`
  - `float temp`
  - `float net_worth`
  - `double distance_in_miles`
4. Valid variable names are b, c, e, f, g, h, i, j (though only first 31 characters will be recognized) 
