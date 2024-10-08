# WiFi Whispers
*A sonified internet connection speed test.*

**A running instance of this project can be found at the following URL: [https://listen.2nd.systems/](https://listen.2nd.systems/)**

![a screenshot of a webpage that reads "number" secrects per second" on a dark blue background with small white dots scattered about](https://raw.githubusercontent.com/ratemypraxis/ratemypraxis.github.io/main/images/ww.gif).

## What is going on?
- An image is hosted on a secure server in NYC.
- Your browser downloads this image every second, with the speed of that download being measured to estimate network strength. (*distance from NYC (the server location) has an affect on speed here*)
- The playback of a generative melody is manipulated by the real-time changes in connection stength.

## What's it made of and what's it on?
- p5.js
  - p5.sound
- node.js
  - Express
- CertBot
- Digital Ocean
- Your connection

## Who is to thank?
- [School for Poetic Computation](https://sfpc.study/)
  - [Tommy Martinez](https://thomasjohnmartinez.com/)
  - [Maxine De Las Pozas](https://gnarl.online/)
- Wikipedia
  - Contributers to [Sombrero Galaxy](https://en.wikipedia.org/wiki/Sombrero_Galaxy) article
- geeksforgeeks.com
  - romy421kumari (author of ["How to Detect Network Speed using JavaScript?"](https://www.geeksforgeeks.org/how-to-detect-network-speed-using-javascript/))
