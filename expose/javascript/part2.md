1. line 12 will print the final value of i, which will be the size of the prices array. since the prices array has size 3, line 12 will print 3.
2. print the last item of the discounted array's discounted price (unrounded), which will be 150.
3. print the last item of the discounted array's discounted price (rounded), which will be 150.
4. it will return the discounted array containing the rounded and discounted prices of the original prices array. it will return an array [50,100,150].
5. it will return an error because i is defined within the for loop block, and line 12 is outside of the block that i was defined in.
6. it will return an error because discountedPrice is defined within the for loop block, and line 13 is outside of the block that discountedPrice was defined in.
7. it will return 150 because that is the discounted and rounded price (also known as the finalPrice) of the last item in the discounted array. this doesn't return an error because the finalPrice is defined in the same block as line 14 print statement.
8. it will return an array [50,100,150] because discounted array was defined using let and within the same block as line 16.
9. error because i is not defined in the same block as line 11. i was defined in the for loop using let, so i is not accessible by line 11.
10. it will return 3 because length is defined in line 4 being equal to prices.length which equals to 3.
11. function returns [50,100,150] because the for loop is iterating through every element of the prices array and computing the discounted price, and then pushing the discounted price into the discounted array. after the for loop ends, the discounted array is returned.
12. 
    a. student.name
    b. student["Grad Year"]
    c. student.greeting
    d. student["Favorite Teacher"].name
    e. student.courseLord[0]
13. 
    a. '32' because integers map to their exact string represeentation.
    b. 1 because js converts "3" to a number and subtracts by 2.
    c. 3 because null is equal to 0.
    d. "3null" because null maps to the string "null"
    e. 4 because true map to 1.
    f. 0 because false maps to 0 and null maps to 0.
    g. "3undefined" because undefined maps to "undefined" and concatentates with the string "3"
    h. NaN because "3" maps to 3, and we try to subtract undefined from 3, but undefined doesnt have an equivalent number representation.
14. 
    a. true because "2" maps to 2 and 2>1 is true.
    b. false because the string "12" is less than "2" in string ordering (lexicographic)
    c. true because "2" maps to the int 2.
    d. false because "2" is not the same data type as 2 (string vs int)
    e. faluse because true maps to 1, and 1 != 2.
    f. true because Boolean(2) returns true, and true is strictly equal to true.
15. === is strictly equivalent and requires that the two items be equal and be the same type. while == allows the data types to convert into the equivalent forms before comparing. ex: 1 == "1" is true, while 1 === "1" is false because 1 and "1" are not the same type.
16. returns 12 45 5 2. wrote for loop in other file.
17. the modifyArray function will return a array [2,4,6] because the function calls doSomething on every element of the parameter array, and doSomething just doubles a number, so every element of the parameter array gets doubled and a new array of doubled numbers gets returned.
18. program written in part2-question18.js file.
19. 1 4 3 2 on new lines. This is because 1 and 4 are immediately printed and consolelog(3) is run after 0 seconds, andn then console.log(2) is run after 1 second.