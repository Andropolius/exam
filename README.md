Only use vanilla js please do not use jquery nor underscore or any other libraries. Do not use es 
functions that browsers do not support without babel or etc. This needs to work out of the box when delivered.

Task 1:
Make this work (repeat 3 times the contents of an array):

repeat([1,2,3]) //[1,2,3,1,2,3,1,2,3]

Your solution:

if we type in our console your function and repeat([1,2,3]) then the result should be [1,2,3,1,2,3,1,2,3]

Task 2:

Make this work (no vowels, lowercase except the first letter):

reformat("BeMEir DeveLoper TEST") //Bmr dvlpr tst

Your solution:

if we type in our console your function and reformat("BeMEir DeveLoper TEST") then the result should be Bmr dvlpr tst

Task 3 (optional, for bonus points):

Make this work (without using any built in functions, only a for loop, return the next binary number in a string or as an array)

next_binary_number([1,0]) // [1,1]

// possible test cases:
// [1,0] => [1,1]
// [1,1] => [1,0,0]
// [1,1,0] => [1,1,1]
// .......
// [1,0,0,0,0,0,0,0,0,1] => [1,0,0,0,0,0,0,0,1,0]

Your solution:

if we type in our console your function and next_binary_number([1,0,0,0,0,0,0,0,0,1]) then the result should look like 1,0,0,0,0,0,0,0,1,0 (or as an array).


Please make a git repo for this which you can then reshare with us
