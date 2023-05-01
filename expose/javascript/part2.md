1. Line 12 will print 3 because i is declared using var so it lives inside the function scope, and we input prices to be length of 3 so the for loop will run 3 times so i is incremented to 3.
2. Line 13 will print 150 because discountedPrice is overwritten everytime in the for loop, so the last time discountedPrice is 300 * (1 - 0.5) = 150.
3. Line 14 will print 150 because finalPrice is overwritten everytime in the for loop, so the last time finalPrice is Math.round(150 * 100) / 100 = 150.
4. It will return [50, 100, 150] because finalPrice is added to discounted everytime in the for loop, so it ends up recording all the finalPrice calculated from each item of prices with the discount value. Since 100 has finalPrice 50, 200 has finalPrice 100, and 300 has finalPrice 150, they are all recorded in discounted and returned.
5. It will cause an error because i is decalred by let so it's only visible inside that for loop block.
6. It will cause an error because discountedPrice is decalred by let so it's only visible inside that for loop block.
7. It will print 150 because finalPrice is declared inside function block and its value is updated 3 times in the for loop and the last time it's updated to 150.
8. It will still return [50, 100, 150] because discounted is declared in the function scope so it will return with all finalPrice that pushed to it.
9. It will cause an error because i is declared by let so it's only visible inside that for loop block.
10. It will print 3 because we input prices to be of length 3 and variable length is declared inside the function.
11. It will return [50, 100, 150] because discounted is defined to be a constant reference but we can still change the content inside. The variable discountedPrice is redeclared everytime the loop goes, so it records the correct value for each price element and add it to discounted.
12. A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
13. A. '32' because 2 is converted from int to string '2' and       concatenated with '3'
    B. 1 because '3' is converted to int 3
    C. 3 because null is converted to 0
    D. '3null' because null is converted to 'null'
    E. 4 because true is converted to int 1
    F. 0 because false and null are both converted to 0
    G. '3undefined' because undefined is converted to 'undefined'
    H. NaN because undefined is converted to NaN
14. A. true because '2' is converted to 2
    B. false because comparing strings will compare character by character and '1' comes before '2'
    C. true because '2' is converted to 2 and they are equal
    D. false because === checks without type conversion so int is not equal to string
    E. false because true is converted to 1 so it doesn't equal 2
    F. true because Boolean(2) will turn into true so they are equal
15. == will convert both side to type number and compare them, but === will check not only value but also type, so 2=='2' is true but 2==='2' is false.
17. The result will be [2, 4, 6] because in modifyArray, doSomething is called on every element in [1, 2, 3] and it multiply the value by 2 for every element and add them in sequence to the newArr. Then newArr is returned after all elements in [1, 2, 3] have been processed.
19. The output is 1 4 3 2. There is one second delay before printing the last 2.
