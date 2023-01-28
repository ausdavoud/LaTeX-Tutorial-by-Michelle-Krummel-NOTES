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
  
  # All-Together Equation ```${(x+1)}$```
  If part of the equation is written in the next line, it'll move it all to the next line
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
  
  # Displayed Math Mode ```$$(x+1)$$``` vs. In-Line Math Mode ```$(x+1)$```
  Displayed-Math Mode writes the equation at the center of a new line (A(x) = ...).
  Whereas, the In-Line Math Mode continues writing the Mathematical text along the previous sentence in the same line (  (x+1) and ...   ). 
  
  ![Displayed-Inline](https://user-images.githubusercontent.com/97347852/215075692-15273773-d293-4c7d-87b5-18099df9c692.png)
