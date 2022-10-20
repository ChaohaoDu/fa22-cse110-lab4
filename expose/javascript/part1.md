## Part 1
1. values added: 20 
2. final result: 20
3. values added: 20
4. It returns an error, since `let` is a block declaration, and line 9 is out of the scope of the declaration.
5. It returns an error, since `const` make `result` unchangeable, but it get changed at line 7
6. It returns an error, since `const` is a block declaration as `let`, and line 9 is out of the scope of the declaration.
## Part 2
1. 3
2. 150
3. 150
4. It will return an array `[ 50, 100, 150 ]`, since the array `discounted` is appended 3 values at line 6-10
5. It will cause an error, since `let` is scope declaration. `i` is declared at line 6, and `i` is called at line 12,
   where is our of the scope.
6. It will cause an error, since `let` is scope declaration. `discountedPrice` is declared at line 7, and it is called
   at line 13, where is our of the scope.
7. 150; `finalPrice` is declared at line 4, and it can be called throughout the whole function (line 4-17). The value
   will store the last round of the `for` loop at line 6-10. Hence `final price = Math.round(300*(1-0.5)*100)/100 =150`.
8. `[ 50, 100, 150 ]`. The function will calculate each discounted price, and append it into the array `discounted`
9. It will cause an error, since `const` is a scope declaration. `i` is declared at line 6, and is called at line 11, where is out of the scope.
10. `3`. It will print the length of the array `prices`, which has 3 values.
11. `[ 50, 100, 150 ]`. The function will return an array of discounted price. 



