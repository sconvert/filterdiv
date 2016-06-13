# filterdiv
An easy method for filtering div in jquery.

###Necessary files :
js/filterdiv.js

###Usage :
  
1- First add script filterdiv.js in your html file. 
```javascript
<script src="js/filterdiv.js"></script> 
```

2-You must have somewhere in your CSS the following style :
```javascript
.hidden {  
  display: none !important;  
}  
```

3- Add class "gallery-chapter" to the links to be listed.
```javascript
<h2 class="gallery-chapter"> Journal télévisé</h2>
```

4- Anywhere in your html file, add the div webiansGalleryLinks. This div will receive the list of all the chapters. This means anything that have the gallery-chapter class.

```javascript
<div id="webiansGalleryLinks"></div>
```

5- Note
This example was build with "ul" as chapter blocks. If you want to use "div", go to line 38 of file filterdiv.js and change "ul" for "div".
```javascript
$(this).next("ul").addClass("hidden");
```
```javascript
$(this).next("div").addClass("hidden");
```

[Project page](http://sconvert.github.io/filterdiv)

[Isotop project](http://isotope.metafizzy.co/)
