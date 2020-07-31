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

### Animation
- [Fading]() 
  - ```fadeOut()``` and ```fadeIn()```  
    - ```fadeOut("slow")```
    - ```fadeOut("<callback>)```: execute callback function right after fading out
  - ```toggle()```
- [Animation]() 
  - ```animate({<property1:"value1",...}, <duration>)```
  - Support callback function
- [AJAX]() 
  - ```$.get("<url>", <callback>)```: get data from url file the execute function (with parameter is the retrieved data)
  - ```$.ajax("<url>").done(<function1>).fail(<function2>)```
- [Regular expression]()
  - ```<variable>.match(<expression>)```: return content(s)/null
  - ```<expression>.test(<variable>)```: return true/false
  - ```/<content>/```: return first matched content (sensitive)
  - ```/<content>/i```: return first matched content (insensitive)
  - ```/<content>/ig```: return all matched contents (insensitive)

### jQuery UI 
- Setup
  - ```<script src="jquery-ui\jquery-ui.js"></script>```
  - ```<script src="jquery-ui\external\jquery\jquery.js"></script>```
  - ```<link rel="stylesheet" href="jquery-ui\jquery-ui.css">```
- [API documentation](https://api.jqueryui.com/)

# Notes - Tips
- AJAX does not work on local files