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
                        src: "http://vimeo.com/44633289",
                        in: 13,
                        out: 20
                    },
                    {
                        src: "http://www.youtube.com/watch?v=EHkozMIXZ8w&wmode=opaque&controls=0&disablekb=1&controls=0&modestbranding=1&rel=0&showinfo=0",
                        in: 8,
                        out: 18
                    }
                ]
                [,'http://soundcloud.com/lilleput/popcorn']);
                //audio src is optional. if you set an audio source the videos' audio will be muted.
                
                
Sequences implement the following methods:

//play the sequence

sequence.play();

//pause the sequence

sequence.pause();

//check if sequence is paused

sequence.paused();
```

