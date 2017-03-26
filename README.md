# GrubJs
Grub.js - Javascript library(like as jQuery) created for make work with HTML DOM simpless.  


Fast connect to website without downloading:  
```html
<script src="https://raw.githubusercontent.com/SLNETAIGA/Grub/master/Grub.js"></script>
```

# How to use
Grub.js work like as jQuery: select(selector).method(args);  
In Grub.js at this moment: 10 methods, it is:  
.getNodeName() - Returning node name of selected element(in upper case)  
.html(value) - Change or get value from selected element  
.append(value) - Adding text after old text to selected element  
.preappend(value) - Adding text before old text to selected element  
.del() - Remove DOM-object  
.hide() - Hide DOM-object  
.show() - Show not visible DOM-object  
.attr(attr,value) - Set or get attribute of selected element  
.removeAttr(attr) - Removing attribute of selected element  
.isHasAttr(attr) - Returning true if selected element has typed attribute  
.makeEvent(event,flags) - make some event  
.addEvent(function, event) - add some event to element  
.delEvent(function, event) - remove some event to element  


# Code examples
[Basic GrubJs example](https://raw.githubusercontent.com/SLNETAIGA/Grub/master/Grub.js "Basic GrubJs example")  

Other examples:  

1 Example with function html() 
```html
<script src="https://raw.githubusercontent.com/SLNETAIGA/Grub/master/Grub.js"></script>
<div id="text">Text</div>
<script>
select("text").html("Text");
</script>
```  
2 Example with function makeEvent()
```html
<script src="https://raw.githubusercontent.com/SLNETAIGA/Grub/master/Grub.js"></script>
<button id="b" onclick="alert('hello!')">Autoclick button</button>
<script>
select("b").makeEvent("click");
</script>
```  
3 Example with function attr()
```html
<script src="https://raw.githubusercontent.com/SLNETAIGA/Grub/master/Grub.js"></script>
<div onmouseenter="select(this).attr('color','blue')" onmouseleave="select(this).attr('color','white')" id="text">Text</div>
```
