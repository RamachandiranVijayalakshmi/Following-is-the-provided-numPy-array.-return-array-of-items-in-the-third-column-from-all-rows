## Following-is-the-provided-numPy-array.-return-array-of-items-in-the-third-column-from-all-rows
## Sample code to check the details 
```sh
import numpy

sampleArray = numpy.array([[11 ,22, 33], [44, 55, 66], [77, 88, 99]]) 
print("Printing Input Array")
print(sampleArray)

print("\n Printing array of items in the third column from all rows")
newArray = sampleArray[...,1]
print(newArray)
```
## Example output
Printing Input Array
[[11 22 33]
 [44 55 66]
 [77 88 99]]

 Printing array of items in the third column from all rows
[22 55 88]
