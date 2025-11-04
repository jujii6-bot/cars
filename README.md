# cars
if (navigator.geolocation) {     navigator.geolocation.getCurrentPosition(function(position) {       console.log("Latitude: " + position.coords.latitude + ", Longitude: " + position.coords.longitude);       // Send to GA or your server for tracking     });   }   
