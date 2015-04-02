﻿
particle background inspired by [jnicol/particleground](https://github.com/jnicol/particleground)

**Demo** [zodiac.js.org](http://zodiac.js.org/)


``` js
new Zodiac(
            'zodiac',                          // HTMLCanvasElement or id
            {
               directionX: 0,                      // -1:left;0:random;1:right
               directionY: -1,                     // -1:up;0:random;1:down
               velocityX: [.1, .2],                // [minX,maxX]
               velocityY: [.5, 1],                 // [minY,maxY]
               bounceX: true,                      // bounce at left and right edge
               bounceY: false,                     // bounce at top and bottom edge
               parallax: .2,                       // float [0-1...]; 0: no paralax
               density: 6000,                      // px^2 per node
               dotRadius: [1, 5],                  // px value or [minR,maxR]
               backgroundColor: 'rgba(9,9,9,1)',   // default transparent; use alpha value for motion blur and ghosting
               dotColor: 'rgba(99,99,99,.5)',
               linkColor: 'rgba(99,99,99,.8)',
               linkDistance: 50,
               linkWidth: 2
            });
```