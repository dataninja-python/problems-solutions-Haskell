# GIST

Find the two numbers beside each other that have the highest product.

# PROBLEM

Given an array of integers, find the pair of adjacent elements that has the
largest product and return that product.

# GIVENS

    - input = an array
    - input array = contains only integers
    - looking for pair of adjacent numbers = two right beside each other
    - largest product = largest number created by multiplying two together
    - return the product = function will return an integer

# -----------------------------------------------------------------------------------------------------------------------------------

# SOLUTION

Return the result of multiplying two numbers right beside each other together.

## BRAINSTORMED IDEAS

    - brute force: loop through every two numbers in the array, multiply each together, discard any number smaller than the largest, and return the largest product
    - transformation: add up two numbers at a time, throw out all numbers smaller than the current largest sum, if get the same sum more than once, multiple both together and select the largest to return
    - binary search: split array in half, run calculation on both to come up with largest, compare to the result of where the two arrays should connect, select largest and return
    - double loop: select first and next, multiply them on each cycle through loop, compare to previous if exists, select largest when reach end of list
    - combination: ?
    - other: ?

## SELECTION METHODOLOGY

    1. What can I do as quickly as possible to get an answer?
    2. What can I do to improve the time complexity?
    3. What can I do to improve the space complexity?

## SOLUTION APPROACH

I chose to attempt multiple approaches to solve this problem. Here are each of
them, what I did, what I expected, what occured, what I learned, and next steps:

### Fast As Possible

    - beg: write a function that iterates over a list
    - add: iterate over the list in twos, print result
    - add: multiply two items (f x s) together to get a product, print result
    - add: compare product of each pair to say higher or lower, print result
    - add: return the product of each in an array
    - end: return only the highest product

## SOLUTION DETAIL

## METRICS

- Time Complexity
- Space Complexity
- Development Time
- Debugging Time
- Testing Time
- Attempts
- Total Time
- Challenge Difficulty
