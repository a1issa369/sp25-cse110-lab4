1. 3 because i is in the range loop and it will end when i equals prices.length, var i is scopred within the function
2. 150 because discountedprice will be updated to the last assignment in the loop, which was 300 times 1/2.
3. 150 as well since it will assign itself for the last time at the very end of the loop and the end of the list
4. [50, 100, 150] because we store the discounted prices into dicounted array and we return that array after looping through each element
5. error because the when i only exists within the loop and we cannot access it outside of it
6. error again since dis2 only exists inside the loop
7. 150 because finalprice exists within the whole function and it will store the last element of the list's discounted value
8. [50, 100, 150] again because we give the function an array and the loop goes through each element to discount and store its value in this new array.
9. error because 'let' i only exists in the loop and cant be accessed elsewhere.
10. 3 b/c we made the length a const, meaning we can't change/reassign its value, and the length of the array is 3
11. [50,100,150] because we made the array a const, meaning we hold the reference point of the array, but we can continue to build within that array by pushing in the changed values of [100,200,300]
12. 1. s.name
    2. s['Grad Year']
    3. s.greeting()
    4. s['Favorite Teacher'].name
    5. s.courseload[0]
13. 1. '32' due to string concatenation
    2. 1; 3 is converted to a number in this case
    3. 3; null is the same as 0 in arthemetic
    4. '3null'; string concatenation
    5. 4; true is the same as the number 1
    6. 0; false =0 and null is the exact same, so 0+0 is 0
    7. '3undefined'; string concatenation
    8. NaN; undefined doesn't have a number and is just equal to NaN(Not a Number), can't do arthemetic with it.
14. 1. true because 2 gets converted to a number 2 and 2 is bigger than 1
    2. false because it compares the strings lexographically and '2' and '1' get compared first and 2 is greater
    3. true; both convert to numbers and both are equivalent
    4. false; both are not the same stype strictly
    5. false; true holds the value of 1 and that is not equal to 2
    6. true because any non-zero number is equal to true when you use the boolean function
15. == means to compare two values after converting them to be the same type whereas === compares by both type and value strictly
16. X
17. returns newarr = [2,4,6] because we go through each element in the loop and we callback the elements with the doSomething function, which is responsible for doubling the array elements given to it one by one. Lastly, we push each new element that is doubled in the new array which is then returned to us
18. X
19. 1. 1 \n 3 \n 2; this is because when we call the func, console prints out 1 first, then setTimeout will delay the output of the second function off of 1000ms and as it waits to do its output, the second settimeout is running with 0ms, which means it will print 3 instantly, so 1 and 3 printed in that order, then 2 after.
