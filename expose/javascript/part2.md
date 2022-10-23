## A Little More of a Challenge...

1. 3; Since `i` is declared as a global variable, it's value is 3 after the loop at line 6-10
2. 150; Since `discountedPriice` is declared as a global variable at line 7, it will store the last value of the
   discounted value, which is $300*(1-0.5)=150$
3. 150; Since `finalPrice` is declared at line 4 as a global variable, it will record the last value of the final price,
   which is `Math.round(150*100)/100 = 150`
4. It will return an array `[ 50, 100, 150 ]`, since the array `discounted` is appended 3 values at line 6-10
5. It will cause an error, since `let` is scope declaration. `i` is declared at line 6, and `i` is called at line 12,
   where is our of the scope.
6. It will cause an error, since `let` is scope declaration. `discountedPrice` is declared at line 7, and it is called
   at line 13, where is our of the scope.
7. 150; `finalPrice` is declared at line 4, and it can be called throughout the whole function (line 4-17). The value
   will store the last round of the `for` loop at line 6-10. Hence `final price = Math.round(300*(1-0.5)*100)/100 =150`.
8. `[ 50, 100, 150 ]`. The function will calculate each discounted price, and append it into the array `discounted`
9. It will cause an error, since `const` is a scope declaration. `i` is declared at line 6, and is called at line 11,
   where is out of the scope.
10. `3`. It will print the length of the array `prices`, which has 3 values.
11. `[ 50, 100, 150 ]`. The function will return an array of discounted price.

## Data Type

1. student.name
2. student['Grade Year']
3. student.greeting()
4. student['Favorite Teacher'].name
5. student.courseLoad[0]

## Basic Operators & Type Conversion

### Arithmetic

3.
    1. "32". Integers map to their exact string representation
    2. 1; String map to integer
    3. 3; `null` maps to 0
    4. "3null"; `null` maps to string `"null"`
    5. 4; `true` maps to 1
    6. 0; `null` and `false` map to 0
    7. "3undefined"; `unndefined` maps to string `"undefined"`
    8. `NaN`; Both of them are not numbers.

### Comparison

4.
    1. true; "2" maps to integer and $2>1$
    2. false; dictionary comparison, first char '2' is greater than the first char '1'
    3. true; week equal unless 'value' is the same
    4. false; strong equal. Not only the 'value' should be the same, but also the type.
    5. false; `true` maps to 1 and $1\neq 2$
    6. true; `Boolean(2)` is `true` and `true===true`

5. `==` is week equation. Sometimes once the values are the same, it will return true. (i.e. the type does not matter).
   For example, `2 =='2'` returns `true`. On the other hand, `===` is strong equation. It requires the value and type be
   the same at the same time. For example, `2==='2'` returns `false`, and `2===2` returns `true`

### Loops

6. file `part2-question16.js`

### Functions

7. `[ 2, 4, 6 ]`. First, we init a new array `newArr`, and then we iter each value of `array`, multiple it by 2, and
   then append it into the `newArr`

### setInterval(), setTimeout(), clearTimeout()

8. file `part2-question18.js`
9. 1 4 3 2
