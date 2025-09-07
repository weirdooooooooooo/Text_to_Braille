**Mapping Rules:**
_lower case letter a~z_: 1~26
_number 0~9_: 27~36
_special characters {,;:.?!'-"(}_: 37~46
_space_: 47
_upper case indicator_: 48
_number indicator_: 49

**Upper case letter**
output indicator (48) + corresponding lower case code
(if only 2 output space is left, output -, leave this letter as not visited)
**Number**
output indicator (49) + number code
**When encounter space**
fill the rest output (up to 7) with space
**When output less than 7**
fill the rest output with space
**When next character to process is not space**
replace last output with - 
