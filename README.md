# Setup
- Option 1: Embedded jQuery from Google Libraries (recommend for production) 
[[URL](https://developers.google.com/speed/libraries)]
- Option 2: Download jQuery script to use locally (prefer compressed/minified version)  

# Main
### Object Manipulation 
- ```$("<seletor>")```: select element(s) of the selector 
- ```$(this)```: select element(s) invoking function 
- Basic manipulation for element 
[[basic-manipulation.html]()]
  - ```click(<function>)``` =  ```onclick```
  - ```hover(<function>)``` = ```onmouseover```
  - ```html()```: get content
  - ```html("<content>")```: set content
  - ```attr("<attribute>", "<value>")```: set value for attribute
  - ```css("<property>", "<value>")```: set value for style property
  - ```css("<property>")```: get value of the style property
- Fading 
[[fading.html]()]
  - ```fadeOut()``` and ```fadeIn()```  
  [[advanced.html]()]
    - ```fadeOut("slow")```
    - ```fadeOut("<callback_function>)```: execute function right after fading out
  - ```toggle()```

