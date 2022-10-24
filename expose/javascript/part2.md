1. it will print 3 to the console because i shows how many iterations the for loop goes through in the function
2. it will print 150 to the console because discountedPrice is the price after the discount is applied at line 7 and this happens for every price in the list [100,200,300] and after the for loop runs the very last value discountedPrice was assigned to was the discounted price for 300 which is 300 * 0.5 = 150 
3. it will also print 150 to the console which is the value of finalPrice which is the discounted price after it has been rounded and the last value it was assigned to was the finalPrice for the last price in the prices array, 300
4. it will return a list [50,100,150] which are the discounted prices given the input prices [100,200,300] with a discount of 50% or 0.5
5. there will be an error because console.log(i) is trying to access i when it is only accessible in the for loop
6. an error will occur for the same reason discountedPrice was declared as a let variable and is only acessible in the for loop and console.log(discountedPrice) is referencing it outside of the for loop
7. This will print 150 to the console because it is the finalPrice for the last item in the prices list and although finalPrice is a let variable it was declared in the function block so it is accessbile from anywhere in the discountPrices function
8. similar to number 4 it will return a list [50,100,150] which are the discounted prices given the input prices [100,200,300] at a 0.5 discount 
9. there will be an error because console.log(i) is trying to access i when it is only accessible in the for loop
10. it will print 3 to the console which is the length of the prices array input calculated at line 4
11. it will return a list of discounted prices discounted [50,100,150] which is the calculated discount prices for [100,200,300] at a 0.5 discount
12. A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
13. A. '32', 2 was mapped to string representation '2' and added to '3'
    B. 1, '3' was converted to integer and subtraction was performed
    C. 3, null was converted to integer as 0
    D. '3null', null was mapped to string representation
    E. 4, true is converted to an integer as 1
    F. 0, both are converted to integer false and null are 0 
    G. '3undefined', undefined is mapped to string representation
    H. NaN, both are converted to integer '3' is 3 and undefined is NaN and causes error resulting in NaN
14. A. true, '2' becomes 2 which is greater than 1
    B. false, in string comparison the first character is compared first '2' is greater than '1'
    C. true, '2' becomes 2 which is equal to 2
    D. false, '2' is not equal to 2 without type conversion
    E. false, true becomes 1 which is not equal to 2 
    F. true, the result of Boolean(2) is true which is equal to true without type conversion
15. == is a regular equality operator and will perform type conversion to evaluate the comparison, while === is for strict equality and checks equality and only returns true if they are equal without any type conversion
16. see part2-question16.js file
17. the result is the array [2,4,6] in the modifyArray function we create a newArr that will be returned in the for loop it adds a new element to the array by iterating through the input array [1,2,3] and using the parameter function we passed in doSomething it multiplies the array[i] by 2 and adds it to newArr so the resulting newArr is the input array with the each element multiplied by 2
18. see part2-question18.js file
19. output: 1 4 3 2 
