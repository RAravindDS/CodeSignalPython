
### Question 
Given an array of integers, replace all the occurrences of elemToReplace with substitutionElem.

Example

For inputArray = `[1, 2, 1]`, elemToReplace = 1, and substitutionElem = 3, the output should be
solution(inputArray, elemToReplace, substitutionElem) = `[3, 2, 3]`.
##

### Answer
```python
def solution(a, elemToReplace, substitutionElem):
    
    return [ i if i != elemToReplace else substitutionElem for i in a]

```

##

**give a star✨**
