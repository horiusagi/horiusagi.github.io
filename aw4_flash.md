---
layout: page
title:
permalink: /artwork/flash/
img: /img/portfo4_tengu.jpg
---
<html>
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
                   <li><a class="selected" href="#" data-filter="*">All</a></li>
                   <li><a href="#" data-filter=".category1">Available Designs</a></li>
                   <li><a href="#" data-filter=".category2">Archived Designs</a></li>
                   <li><a href="/artwork/"><i class="fa fa-angle-left" aria-hidden="true"></i></a></li>
                 </ul>
             </div>
             <div id="grid">
         <!-- -------------------------- BOX MARKUP -------------------------- -->
                 <div class="media-box category1" data-columns="2">
                     <div class="media-box-image mb-open-popup" data-src="/img/fl_tengu.jpg">
                         <div data-thumbnail="/img/fl_tengu.jpg" ></div>
                         <div class="thumbnail-overlay">
                             <div class="media-box-title">天狗</div>
                             <div class="media-box-date">tengu</div>
                         </div>
                     </div>
                 </div>
         <!-- -------------------------- BOX MARKUP -------------------------- -->
                 <div class="media-box category1">
                     <div class="media-box-image mb-open-popup" data-src="/img/il_usaginoryuu.jpg">
                         <div data-thumbnail="/img/il_usaginoryuu.jpg" ></div>
                         <div class="thumbnail-overlay">
                             <div class="media-box-title">.</div>
                             <div class="media-box-date"></div>
                         </div>
                     </div>
                 </div>
         <!-- -------------------------- BOX MARKUP -------------------------- -->
                 <div class="media-box category1">
                     <div class="media-box-image mb-open-popup" data-src="/img/.jpg">
                         <div data-thumbnail="/img/.jpg" ></div>
                         <div class="thumbnail-overlay">
                             <div class="media-box-title">.</div>
                             <div class="media-box-date"></div>
                         </div>
                     </div>
                 </div>
         <!--  =============================================================== -->
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
             boxesToLoadStart: 12,
             noMoreEntriesWord: '',
             columns: 3,
         });
     </script>
 </body>
 </html>
