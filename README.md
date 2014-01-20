popcorn.sequence.smart
======================

create a sequence of any kind of media files that are supported by popcorn.js
(see http://popcornjs.org/popcorn-docs/players/)

Usage:
```javascript
var sequence = Popcorn.sequence.smart(
                "container-id",
                [
                    {
                        src: "http://www.youtube.com/watch?v=hHUbLv4ThOo",
                        in: 0,
                        out: 5
                    },
                    {
                        src: "http://www.youtube.com/watch?v=hT_nvWreIhg",
                        in: 13,
                        out: 20
                    },
                    {
                        src: "http://www.youtube.com/watch?v=EHkozMIXZ8w",
                        in: 8,
                        out: 18
                    }
                ]
                [, audio_src]);
                
                
Sequences implement the following methods:

//play the sequence

sequence.play();

//pause the sequence

sequence.pause();

//check if sequence is paused

sequence.paused();
```

