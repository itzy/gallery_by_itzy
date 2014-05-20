gallery_by_itzy
===============

Version 1.1

A lightbox gallery, created by Julia Sivartsson, webdeveloper-student att Blekinge Tekniska Högskola.
This module is complete with javascript, css and a test-page that is easy to use.

Within the lightbox you can browse between the pictures in the gallery and close it both by clicking outside the picture or with the esc-button on your keyboard.
There is also room for a image-title.

 License
=====

This software is free software and carries a MIT license.

Screenshots
=====

![screenshot](http://i57.tinypic.com/2vun1au.jpg)
![screenshot](http://i60.tinypic.com/f38j9g.jpg)


How to install
=====
 
To get started, clone gallery_by_itzy or download it manually to your device.
    
 Secondly, put gallery.css in your css folder and add the following to your header to get the stylesheet:

          <link rel="stylesheet" type="text/css" href="css/gallery.css">

To get the javascript to work, put gallery.js in your javascript folder and add the following to the footer of you page: (the first link will make jQuery work for you by an external link, it is important that you load it before gallery.js)

         <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js"></script>
         <script src="js/gallery.js"></script>

Now you're ready to create the gallery!
Open the page you want to have your gallery in and write the following code:

        <div id="lightbox">
        <ul>
        <li>
         <img src="img/picture1_small.jpg" data-large="img/picture1.jpg"/>
         <div class="image_title">
         <h5 class="title">Picture 1</h5>
         </div>
         </li>

        <li>
        <img src="img/picture2_small.jpg" data-large="img/picture2.jpg"/>
        <div class="image_title">
        <h5 class="title">Picture 2</h5>
        </div>
        </li>
        </ul>
        
Note:
I use two sets of my pictures to get the right proportions, but you can ofcourse just set the width and height on the thumbnail picture.

        <img src="img/picture2.jpg" width="100" height="100" data-large="img/picture2.jpg"/>
        
That's it! Hope you'll enjoy it.

© Julia Sivartsson
