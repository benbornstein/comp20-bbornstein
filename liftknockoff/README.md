# Benjamin Bornstein - COMP20 Assignment 2: The Private Car Service

## Description
I successfully built a webpage that displays map (using Google Maps API) of the user's current location (represented by a unique marker), passengers or vehicles, and weinermobiles. I also successfully implemented an on-click info window that displays distance from nearest weinermobile AND distance from nearest passenger or vehicle relative to the user's position (in miles), as well as on-click info windows for the weinermobile and passenger/vehicle markers which display username and distance from user's position. Within index.html, I successfully utilized navigator.geolocation to obtain current location within a getLocation function. My other functions include: a function to initialize the map, a function that utilizes XML to send my current location and username to the server using ride request API and parses response data, a function that populates the map with markers, and a function that locates relative distances of markers and feeds them into info window content. In addition to including a basic HTML body, I also included basic styling in a separate style.css file. More nuanced implementations (i.e. alert messages and info window content for cases where there are no weinermobiles) were also implemented successfully.

## Collaboration/Discussion
This was a solo assignment; I did not collaborate on it with any peers. However, I did receive guidance from TA Kingsley Udoyi during office hours.

## Duration
I spent approximately 16 hours completing this assignment.

