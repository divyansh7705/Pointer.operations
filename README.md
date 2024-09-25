# Pointer.operations

## AIM:-<br>
To perform call by value function<br>

## Software Used :- <br>
VS Code <br>

## Theory :- <br>
### Call by Reference<br>
Definition: Call by Reference means passing the address (reference) of the actual parameters to the function. This allows the function to modify the original values.<br>

Working: The function receives pointers to the variables, and operations performed inside the function affect the original variables directly.<br>

### Call by Value<br>
Definition: Call by Value means passing a copy of the actual parameters to the function. Changes made to the parameters inside the function do not affect the original variables.<br>

Working: The function operates on copies of the values, leaving the original variables unchanged.<br>

## Algorithm for call by value:

1. **Define Swap Function**:
   - Create a function `swap` that takes two integer parameters `x` and `y`.
   - Inside the function, declare a temporary variable `temp`.
   - Swap the values of `x` and `y` using the temporary variable `temp`.

2. **Main Function**:
   - Declare and initialize two integer variables `a` and `b` with values (e.g., `5` and `2`).
   - Call the `swap` function with `a` and `b` as arguments.
   - Print the values of `a` and `b` after calling the `swap` function.

3. **End Program**:
   - Conclude the program after printing the values of `a` and `b`.

## Algorithm for call by refrense :

1. **Define Swap Function**:
   - Create a function `swap` that takes two integer pointers `x` and `y` as parameters.
   - Inside the function:
     - Declare an integer variable `swap` for temporary storage.
     - Assign the value pointed to by `x` to `swap`.
     - Assign the value pointed to by `y` to the location pointed to by `x`.
     - Assign the value of `swap` to the location pointed to by `y`.

2. **Main Function**:
   - Declare and initialize two integer variables `x` and `y` with values (e.g., `500` and `200`).
   - Call the `swap` function, passing the addresses of `x` and `y`.
   - Print the values of `x` and `y` after the swap operation.

3. **End Program**:
   - Conclude the program after printing the values of `x` and `y`.

## Conclusion :- <br> 

In this experiment we learned call by value function <br>

