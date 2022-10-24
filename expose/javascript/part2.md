1. Line 12 outputs 3 as i has function scope, and 3 is its value after the for loop.
2. Line 13 outputs 150 which is discountedPrice value after the for loop is done. This var has function scope.
3. Line 14 outputs 150 which is finalPrice value after the for loop is done. This var has function scope.
4. Function returns array with [50, 100, 150].
5. Line 12 will error as i is out of scope.
6. Line 13 will error as i is out of scope.
7. Line 14 outputs 150 which is finalPrice value after the for loop is done. This var has block scope.
8. Function returns array with [50, 100, 150].
9. Line 11 will error as i is out of scope.
10. Line 12 will output length 3.
11. Function returns array with [50, 100, 150]. This is because const allows pushing to the array as long as the object which it points to isn't changed.
12. Answers:  
    A. student.name  
    B. student['Grad Year']  
    C. student.greeting()  
    D. student['Favorite Teacher'].name  
    E. student.courseLoad[0]  
13. Answers:  
    A. ‘3’ + 2 returns 32 because + means string concat when first arg is string   
    B. ‘3’ - 2 returns 1 because - switches to number  
    C. 3 + null returns 3 because + converts both to numbers and null=0   
    D. ‘3’ + null returns 3null because + with a string as first arg converts both to string and does concatenation  
    E. true + 3 returns 4 because + with bool and a number converts both to numbers and true =1.  
    F. false + null returns 0 because + with bool changes everything to numbers  
    G. '3' + undefined returns 3undefined because first arg is string so + is concatenation.  
    H. '3' - undefined returns NaN because numerical operations with undefined return NaN

14.  Answers:  
    A. ‘2’ > 1 returns true as converts to numbers when one arg is a number.  
    B. ‘2’ < ‘12’ returns false because this is string comparison.  
    C. 2 == ‘2’ returns true because converts to number  
    D. 2 === ‘2’returns false because type is taken into account  
    E. true == 2 returns false because true is 1  
    F. true === Boolean(2) returns true because Boolean(2) returns boolean with value true.  

15.  == converts types and compares, or in other words only looks at the value of the variables, while === checks the types as well.
16.  see code
17.  returns [2, 4, 6] as code calls do something on each array element and stores the result in the returned array. 
18.  see code 
19.  1 4 3 2
