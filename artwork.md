---
layout: page
title: artwork
permalink: /artwork/
---
<html>
<script>$(window).on(“scroll touchmove”, function () {});</script>
<body>
     <!-- Media Boxes CSS files -->
     <link rel="stylesheet" href="{{ site.baseurl }}/plugin/components/Font Awesome/css/font-awesome.min.css">
     <link rel="stylesheet" href="{{ site.baseurl }}/plugin/components/Magnific Popup/magnific-popup.css">
     <link rel="stylesheet" href="{{ site.baseurl }}/plugin/components/Fancybox/jquery.fancybox.min.css">
     <link rel="stylesheet" type="text/css" href="{{ site.baseurl }}/plugin/css/mediaBoxes.css">
         <div class="content grid-container">
          <!--  ================== MEDIA BOXES ================== -->
          <div class="filters-container">
              <ul class="media-boxes-filter" id="filter">
                <li><a href="/artwork/prints_and_illustrations/">Prints</a></li>
                <li><a href="/artwork/paintings/">Paintings</a></li>
                <li><a href="/artwork/sketchbook/">Sketches</a></li>
                <li><a href="/artwork/flash/">Flash Designs</a></li>
                <li><a href="/artwork/tattoos">Tattoos</a></li>
                <li><a href="https://www.instagram.com/horiusagi_/" target="_blank">Instagram</a></li>
             </ul> 
          </div>
         <div id="grid">
         <!-- -------------------------- BOX MARKUP -------------------------- -->
                 <div class="media-box category1">
                     <a href="/artwork/prints_and_illustrations/">
                     <div class="media-box-image" data-src="gallery/img-8.jpg">
                         <div data-width="240" data-height="151" data-thumbnail="/img/portfo4_tengu.jpg" ></div>
                          <div class="thumbnail-overlay overlay-always-visible">
                             <div class="media-box-title">Prints and Illustrations</div>
                             <div class="media-box-date"></div>
                         </div>
                       </div>
                     </a>
                 </div>
         <!-- -------------------------- BOX MARKUP -------------------------- -->
                 <div class="media-box category2">
                     <a href="/artwork/paintings/">
                     <div class="media-box-image" data-src="gallery/img-8.jpg">
                         <div data-width="240" data-height="151" data-thumbnail="/img/portfo4_tengu.jpg" ></div>
                         <div class="thumbnail-overlay overlay-always-visible">
                             <div class="media-box-title">Paintings</div>
                             <div class="media-box-date"></div>
                         </div>
                     </div>
                     </a>
                 </div>
          <!-- -------------------------- BOX MARKUP -------------------------- -->
                 <div class="media-box category3">
                     <a href="/artwork/sketchbook/">
                     <div class="media-box-image" data-src="gallery/img-8.jpg">
                         <div data-width="240" data-height="151" data-thumbnail="/img/portfo4_tengu.jpg" ></div>
                         <div class="thumbnail-overlay overlay-always-visible">
                             <div class="media-box-title">Sketches</div>
                             <div class="media-box-date"></div>
                         </div>
                     </div>
                     </a>
                 </div>
         <!-- -------------------------- BOX MARKUP -------------------------- -->
                 <div class="media-box category4">
                     <a href="/artwork/flash/">
                     <div class="media-box-image" data-src="gallery/img-8.jpg">
                         <div data-width="240" data-height="151" data-thumbnail="/img/portfo4_tengu.jpg" ></div>
                         <div class="thumbnail-overlay overlay-always-visible">
                             <div class="media-box-title">Tattoo Flash</div>
                             <div class="media-box-date"></div>
                         </div>
                     </div>
                     </a>
                 </div>
          <!-- -------------------------- BOX MARKUP -------------------------- -->
                 <div class="media-box category5">
                     <a href="/artwork/tattoos/">
                     <div class="media-box-image" data-src="gallery/img-8.jpg">
                         <div data-width="240" data-height="151" data-thumbnail="/img/portfo4_tengu.jpg" ></div>
                         <div class="thumbnail-overlay overlay-always-visible">
                             <div class="media-box-title">Tattoos</div>
                             <div class="media-box-date"></div>
                         </div>
                     </div>
                     </a>
                 </div>
         <!-- -------------------------- BOX MARKUP -------------------------- -->
                 <div class="media-box category6">
                     <a href="https://www.instagram.com/horiusagi_/" target="_blank">
                     <div class="media-box-image">
                         <div data-width="240" data-height="151" data-thumbnail="/img/portfo4_tengu.jpg" ></div>
                         <div class="thumbnail-overlay overlay-always-visible">
                             <div class="media-box-title">Instagram</div>
                             <div class="media-box-date"></div>
                         </div>
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
