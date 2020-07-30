# Setup
- Option 1: Embedded jQuery from Google Libraries (recommend for production) 
[[URL](https://developers.google.com/speed/libraries)]
- Option 2: Download jQuery script to use locally (prefer compressed/minified version)  

# Basic
- ```$("<seletor>")```: select element(s) of the selector (use ```this``` to reference to the element invoking function)
- Method for element(s): 
  - ```click(<function>)``` =  ```onclick```
  - ```hover(<function>)``` = ```onmouseover```
  - ```html()```: get content
  - ```html("<content>")```: set content
  - ```attr("<attribute>", "<value>")```: set value for attribute
  - ```css("<property>", "<value>")```: set value for style property
  - ```css("<property>")```: get value of the style property
