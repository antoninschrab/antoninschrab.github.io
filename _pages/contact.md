---
layout: archive
title: "Contact"
permalink: /contact/
author_profile: true
---

{% include base_path %}

<address>
  UCL Centre for Artificial Intelligence<br />90 High Holborn<br /> WC1V 6LJ London<br /> United Kingdom
</address>
<br>
<!-- ([see on Google Maps](https://goo.gl/maps/5JmzYNJTt8hZufbZA)) -->

<iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d4965.579778013099!2d-0.12450412319706675!3d51.51707062522409!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x48761b3585a9c137%3A0xffe1d0c346654ca5!2s90%20High%20Holborn%2C%20Holborn%2C%20London%20WC1V%206LJ!5e0!3m2!1sfr!2suk!4v1588107506410!5m2!1sfr!2suk" width="600" height="450" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>

<body>
  <div id="map"></div>
  <script>
    function initMap() {
      // Styles a map in night mode.
      var map = new google.maps.Map(document.getElementById('map'), {
        center: {lat: 40.674, lng: -73.945},
        zoom: 12,
        styles: [
          {elementType: 'geometry', stylers: [{color: '#242f3e'}]},
          {elementType: 'labels.text.stroke', stylers: [{color: '#242f3e'}]},
          {elementType: 'labels.text.fill', stylers: [{color: '#746855'}]},
          {
            featureType: 'administrative.locality',
            elementType: 'labels.text.fill',
            stylers: [{color: '#d59563'}]
          },
          {
            featureType: 'poi',
            elementType: 'labels.text.fill',
            stylers: [{color: '#d59563'}]
          },
          {
            featureType: 'poi.park',
            elementType: 'geometry',
            stylers: [{color: '#263c3f'}]
          },
          {
            featureType: 'poi.park',
            elementType: 'labels.text.fill',
            stylers: [{color: '#6b9a76'}]
          },
          {
            featureType: 'road',
            elementType: 'geometry',
            stylers: [{color: '#38414e'}]
          },
          {
            featureType: 'road',
            elementType: 'geometry.stroke',
            stylers: [{color: '#212a37'}]
          },
          {
            featureType: 'road',
            elementType: 'labels.text.fill',
            stylers: [{color: '#9ca5b3'}]
          },
          {
            featureType: 'road.highway',
            elementType: 'geometry',
            stylers: [{color: '#746855'}]
          },
          {
            featureType: 'road.highway',
            elementType: 'geometry.stroke',
            stylers: [{color: '#1f2835'}]
          },
          {
            featureType: 'road.highway',
            elementType: 'labels.text.fill',
            stylers: [{color: '#f3d19c'}]
          },
          {
            featureType: 'transit',
            elementType: 'geometry',
            stylers: [{color: '#2f3948'}]
          },
          {
            featureType: 'transit.station',
            elementType: 'labels.text.fill',
            stylers: [{color: '#d59563'}]
          },
          {
            featureType: 'water',
            elementType: 'geometry',
            stylers: [{color: '#17263c'}]
          },
          {
            featureType: 'water',
            elementType: 'labels.text.fill',
            stylers: [{color: '#515c6d'}]
          },
          {
            featureType: 'water',
            elementType: 'labels.text.stroke',
            stylers: [{color: '#17263c'}]
          }
        ]
      });
    }
  </script>
  <script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap"
  defer></script>
</body>

<!-- <LinkedIn: [<font color="#52ADC8">mrsandeshbhat</font>](https://in.linkedin.com/in/mrsandeshbhat)> -->

<!-- <embed src="https://www.linkedin.com/in/mrsandeshbhat" width="650" height="1800" type='application/pdf'> -->
