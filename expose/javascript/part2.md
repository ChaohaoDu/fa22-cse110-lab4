1. student.name
2. student['Grade Year']
3. student.greeting()
4. student['Favorite Teacher'].name
5. student.courseLoad[0]

## Arithmetic

3.
    1. "32". Integers map to their exact string representation
    2. 1; String map to integer
    3. 3; `null` maps to 0
    4. "3null"; `null` maps to string `"null"`
    5. 4; `true` maps to 1
    6. 0; `null` and `false` map to 0
    7. "3undefined"; `unndefined` maps to string `"undefined"`
    8. `NaN`; Both of them are not numbers.

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
6. file `part2-question16.js`
7. `[ 2, 4, 6 ]`. First, we init a new array `newArr`, and then we iter each value of `array`, multiple it by 2, and then append it into the `newArr` 
8. file `part2-question18.js`
9. 1 4 3 2
