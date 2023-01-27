# Soft Enter: ```\\```
  Like a normal Enter
  
  Input:
  ```
  Hello there!\\
  It's a new paragraph.
  ```
  Output: 
  ```
    Hello there!
  It's a new paragraph.
  ```
  
# Hard Enter: ```Insert a Blank Line```
  Like a new paragraph
  
  Input:
  ```
  Hello there!
 
  It's a new paragraph.
  ```
  Output: 
  ```
    Hello there!
    It's a new paragraph.
  ```
  
  # One-Line Equation
  Put it into curly brackets 
  
  Input:
  ```
  A rectangle has side lengths of $(x+1)$ and $(x+3)$. The equation ${A(x) = x^2+4x+3}$ gives the area of the rectangle.
  ```
  Output:
  ```
  A rectangle has side lengths of (x+1) and (x+3). The equation 
  A(x) = x^2+4x+3 gives the area of the rectangle.
  ```
