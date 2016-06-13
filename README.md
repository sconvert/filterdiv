# filterdiv
An easy method for filtering div in jquery.

Usage :
  
1- First add script filterdiv.js in your html file. 
<script src="js/filterdiv.js"></script> 
  
2-You must have somewhere in your CSS the following style :
.hidden {  
  display: none !important;  
}  

3- Add class "gallery-chapter" to the links to be listed.
<h2 class="gallery-chapter"> Journal télévisé</h2>

4- Anywhere in your html file, add the div webiansGalleryLinks. This div will receive the list of all the chapters. This means anything that have the gallery-chapter class.

<div id="webiansGalleryLinks"></div>