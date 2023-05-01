1. returns the var i loop counter value because it is a var. it is within the function scope. So returns the value of 3, the value of i after running the loop.
2. it will print 150, the last calculation variable of the array. var variables can be access outside of the scope.
3. it will print 150, the last calculation variable from loop. Since var variables can be access outside of the scope, so it prints the data stored in the loop.
4. it will return the array of price after discount, but it will not have any outputs since it is missing console.log.
5. error. let variables needs to be print inside of the scope. where in this case, it is called outside of the for loop, not in the scope for let variables.
6. error. let variables needs to be print inside of the scope. where in this case, it is defined inside of the forloop, called outside, so it is not in the scope.
7. error. the let variable are called outside of the forloop, so it can be accessed.
8. it will return the array of price after discount, but it will not have any outputs since it is missing console.log.
9. error, const are like let variables. it is declare inside of the forloop so cannot be access outside of the loop.
10. outputs 3 because declares the const variable within the same scope, can be access, and the length variable is never changed.
11. it will return the array of price after discount, but it will not have any outputs since it is missing console.log.
12. A: student.name
    B: student['Grad Year']
    C: student.greeting()
    D: student['Favorite Teacher'].name
    E: student.courseLoad[0]
13. A: 32, + between a string and integer becomes a string that combines them together.
    B: 1, - between string and integer becomes a integer and subtract eachother
    C: 3, null treated as 0. so it returns a integer: 3+0 = 3.
    D: 3null, + combines them together and becomes a string.
    E: 4, true is 1, and treat them as addtions with +. true + 3 = 1+3=4.
    F: 0, false is nothing or 0, and + becomes integer, false + null = 0+0 = 0.
    G: 3undefined, string + undefined beomes a string, + combines them together.
    H: NaN, the operation - tries to convert to integers, but undefined cannot be an integer, so NaN(not a number) output.
14. A: true, converts '2' to integer and compare 2 > 1. 
    B: false, since both are string, it converts the integer character-by-character, so it compares '2' < '1' = 2 < 1, so false
    C: true, converts '2' to integer, 2==2 is true.
    D: false, compares 2 to '2', three equals(===) compares the type and value of both sides, so integer is not string. 
    E: false, == operation converts true to 1, and 1 is not equal to 2.
    F: true, Boolean(2) is true true === true is true, and true =1 , both boolean.
15. == is loose equality operation, compares the operand after converting one side to the same type. === is strict equality operation, it checks both sides are the same type or same value, needs both conditions to be true to return true.
16. 
