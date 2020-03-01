## The problem of dealing with 2 separate contour of a truncated objects.  
In the following example, the algorithm could only detect one leg of a person.      
![-](m-25.png)
  
  
In the prior images of this sequence, when there is only one contour, there is no problem.  
  
![](m-24.png)

  
### The problem of minus coordiantes are happend in both cases:  
m-25:  
370 239  
279 0  
351 -27  
442 212  
  
m-24:  
360 395  
206 4  
396 -70  
550 320  
  
  
  
#### An "amodal" box is needed to bound the complete object even if part of the object is occluded or truncated.
