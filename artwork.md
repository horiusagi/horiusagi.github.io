---
layout: page
title: artwork
permalink: /artwork/
---
<html>
<script>$(window).on(“scroll touchmove”, function () {});</script>
<style>
.media-box-image h7{
font-size: 24px;
color: rgba(0,0,0,0,0);
position:absolute;
top:50%;
left:50%;
line-height: 1.5em;
background-color: rgba(0,0,0,0.2);
width: 100%;
height: 100%;
text-allign:center;
margin:0;
transform: translate(-50%, -50%);
}
.media-box-image h1{
font-size: 18px;
font-weight: 600;
position:absolute;
top: 50%;
left: 50%;
transform: translate(-50%, -50%);
color:#eee;
line-height: 1.5em;
background-color: rgba(0,0,0,0.0);
width:100%;
text-align:center;
  /* transform:translateY(-50%);  doesn't work in IE9 and older I'm affraid */
margin:0;
}

.media-box-image .normal {
 transition: .5s ease;
}
.media-box-image:hover .normal {
 opacity: 0;
}
.media-box-image .hover {
 background-color: rgba(0,0,0,0.5);
}


</style>

<body>
 <!-- Media Boxes CSS files -->
     <link rel="stylesheet" href="{{ site.baseurl }}/plugin/components/Font Awesome/css/font-awesome.min.css">
     <link rel="stylesheet" href="{{ site.baseurl }}/plugin/components/Magnific Popup/magnific-popup.css">
     <link rel="stylesheet" href="{{ site.baseurl }}/plugin/components/Fancybox/jquery.fancybox.min.css">
     <link rel="stylesheet" type="text/css" href="{{ site.baseurl }}/plugin/css/mediaBoxes.css">
         <div class="content grid-container">
         <!--  ================== MEDIA BOXES ================== -->
         <div id="grid">
         <!-- -------------------------- BOX MARKUP -------------------------- -->
                 <div class="media-box category2">
                     <a href="/artwork/prints_and_illustrations/">
                     <div class="media-box-image" data-src="gallery/img-8.jpg">
                         <div data-width="240" data-height="151" data-thumbnail="/img/portfo4_tengu.jpg" ></div>
                          <h7></h7>
                          <h1>Prints</h1>
                          <div class="hover"></div>
                       </div>
                     </a>
                 </div>
         <!-- -------------------------- BOX MARKUP -------------------------- -->
                 <div class="media-box category2">
                     <a href="/artwork/paintings/">
                     <div class="media-box-image" data-src="gallery/img-8.jpg">
                         <div data-width="240" data-height="151" data-thumbnail="/img/portfo4_tengu.jpg" ></div>
                          <h7></h7>
                          <h1 allign="center">Paintings</h1>
                     </div>
                     </a>
                 </div>
          <!-- -------------------------- BOX MARKUP -------------------------- -->
                 <div class="media-box category2">
                     <a href="/artwork/sketchbook/">
                     <div class="media-box-image" data-src="gallery/img-8.jpg">
                         <div data-width="240" data-height="151" data-thumbnail="/img/portfo4_tengu.jpg" ></div>
                          <h7></h7>
                          <h1 allign="center">Sketches</h1>
                     </div>
                     </a>
                 </div>
         <!-- -------------------------- BOX MARKUP -------------------------- -->
                 <div class="media-box category2">
                     <a href="/artwork/flash/">
                     <div class="media-box-image" data-src="gallery/img-8.jpg">
                         <div data-width="240" data-height="151" data-thumbnail="/img/portfo4_tengu.jpg" ></div>
                          <h7></h7>
                          <h1>Flash Designs</h1>
                     </div>
                     </a>
                 </div>
          <!-- -------------------------- BOX MARKUP -------------------------- -->
                 <div class="media-box category2">
                     <a href="/artwork/tattoos/">
                     <div class="media-box-image" data-src="gallery/img-8.jpg">
                         <div data-width="240" data-height="151" data-thumbnail="/img/portfo4_tengu.jpg" ></div>
                          <h7></h7>
                          <h1>Tattoos</h1>
                     </div>
                     </a>
                 </div>
         <!-- -------------------------- BOX MARKUP -------------------------- -->
                 <div class="media-box category2">
                     <a href="/artwork/paintings/">
                     <div class="media-box-image">
                         <div data-width="240" data-height="151" data-thumbnail="/img/portfo4_tengu.jpg" ></div>
                          <h7></h7>
                          <h1>Instagram</h1>
                     </div>
                     </a>
                 </div>
         <!-- ================================================================ -->
         <!-- ================================================================ -->
         </div> <!-- #grid -->
         <!--  ================== END MEDIA BOXES ================== -->
         </div> <!-- #grid-container --> 
     <!-- jQuery 1.8+ -->
     <script src="{{ site.baseurl }}/plugin/components/jQuery/jquery-1.11.3.min.js"></script>
     <!-- Media Boxes JS files -->
     <script src="{{ site.baseurl }}/plugin/components/Isotope/jquery.isotope.min.js"></script>
     <script src="{{ site.baseurl }}/plugin/components/imagesLoaded/jquery.imagesLoaded.min.js"></script>
     <script src="{{ site.baseurl }}/plugin/components/Transit/jquery.transit.min.js"></script>
     <script src="{{ site.baseurl }}/plugin/components/jQuery Easing/jquery.easing.js"></script>
     <script src="{{ site.baseurl }}/plugin/components/Waypoints/waypoints.min.js"></script>
     <script src="{{ site.baseurl }}/plugin/components/Modernizr/modernizr.custom.min.js"></script>
     <script src="{{ site.baseurl }}/plugin/components/Magnific Popup/jquery.magnific-popup.min.js"></script>
     <script src="{{ site.baseurl }}/plugin/components/Fancybox/jquery.fancybox.min.js"></script>
     <script src="{{ site.baseurl }}/plugin/js/jquery.mediaBoxes.dropdown.js"></script>
     <script src="{{ site.baseurl }}/plugin/js/jquery.mediaBoxes.js"></script>
     <script>
         $('#grid').mediaBoxes({
             filterContainer: '#filter',
             overlayEffect: 'direction-aware',
             boxesToLoadStart: 16,
             noMoreEntriesWord: '',
             columns: 3,
         });
     </script>
 </body>
 </html>
