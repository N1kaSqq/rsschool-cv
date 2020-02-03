# Nikita Bogdanov
## Contact info:  
+375(29)8408010</br>
NBogdanov17@yandex.by  
VK [link](https://vk.com/n1kasvk) </br>
@N1kaSqq

## Summary:
My goal is to become a good IT specialist.  
I chose to start with front-end development

## Skills:
  * HTML5/CSS3  
  * JavaScript/jQuery
  * C++  
## Code examples:
jQuery function example
```
function drawGraph(Class, Array , Color){
    let height = $(`.${Class}`).height();
if(height==0){height=150;}
let m;
m= Array[0];
for(let i =0;i<Array.length-1;i++){
    if(Array[i]>m){
    m=Array[i];
    }
}
$(`.${Class}`).css({'overflow-x': 'scroll'});
$(`.${Class}`).append(`<div style='height: ${height}px; width: ${Array.length*20}px; margin: 0 auto; display: flex; justify-content: center; align-items: flex-end; ' class='box' "></div>`);
for(let i =0;i<Array.length;i++){
    $(".box").append(`<div style='height: ${(Array[i]*90)/m}%; width: 10px; background-color: ${Color}; border-radius: 2px; margin: 5px;' class='column'"></div>`);
}
}
```
## Education:
[Belarusian State University of Informatics and Radioelectronics](https://www.bsuir.by/)  
## English:
Intermediate+
