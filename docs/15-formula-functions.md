# Formula functions

The module supports many Excel functions that you can use in your calculations

List of functions:

**SQR**: Return the square of a number 
```xls
SQR(5) → 25
```

**SQRT**: Returns the square root of a number  
````xls
SQRT(25) → 5 
````
**ABS**: Returns the absolute value of a number
````xls
ABS(-10) → 10
````
**SIGN**: Returns the signs of a number
```xls
SIGN(10) → 1
SIGN(-10) → -1
SIGN(0) → 0
```
**TRUNC**: Returns the truncated number  
```xls
TRUNC(4.9) → 4
TRUNC(-3.5) → -3
```
**CEIL**: Rounds a number up
```xls
CEIL(3.2) → 4
CEIL(-3.14) → -3
```
**FLOOR**: Rounds a number down
```xls
CEIL(3.2) → 3
CEIL(-3.14) → -4
```  
**ROUND**: Uses PrestaShop rounding method (configurable in the PrestaShop settings)
```xls
ROUND(number, decimals)
ROUND(5.16, 0) → 5
ROUND(5.16, 1) → 5.2
```
**ROUNDUP**: Rounds a number up using PrestaShop's rounding method
```xls
ROUNDUP(number, decimals)
ROUNDUP(5.16, 0) → 6
ROUNDUP(5.11, 1) → 5.2
```  
**ROUNDDOWN**: Rounds a number down using PrestaShop's rounding method
```xls
ROUNDDOWN(number, decimals)
ROUNDDOWN(5.16, 0) → 5
ROUNDDOWN(5.11, 1) → 5.1
```     
**VAL**: Returns the number value of a string  
```xls
VAL("2") → 2
```
**POW**: Raise a number to a specific power
```xls
POW(5, 3) → 125
```  
**MIN**: Return the smallest value among the passed parameters (accept two parameters or more)  
```xls
MIN(10, 5, 14, 3) → 3
```
**MAX**: Return the biggest value among the passed parameters (accept two parameters or more)
```xls
MAX(10, 5, 14, 3) → 14
```  

**IF**: Test for a specific condition
```xls
IF(condition, value if true, value if false)
IF(100 > 10, 1, 2) → 1
IF(5 > 10, 1, 2) → 2
```

**STRLEN**: Return the number of characters in a string (supports UTF-8)
```xls
STRLEN('Hello') → 6
STRLEN('World') → 5
```
**CHECK**: Checks if a string if not empty, return 0 if string is empty, 1 otherwise
```xls
CHECK("Hello") → 1
CHECK("") → 0
```
**SUBSTR**:   
**REPLACE**:   
**CONCAT**:   
**TRIM**:   
**RTRIM**:   
**LTRIM**:   
**CHR**:   
**NUM**:   
**SUM**:   

**GRID**:   
