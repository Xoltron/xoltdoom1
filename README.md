# THIS IS NOT MY REPOSITORY, I SIMPLY FORKED IT FOR MY OWN USE ON MY SITE.

[Original Site Here](https://vidferris.github.io/FaviconDoom/favicondoom.html)
(Might not work in all web browsers.)

## the heck is this
Doom, put into a browser favicon. Also rendered in the document itself so you can usefully see it.

## y u do dis
Had to be the dude I forked it from lol. Someone else might have gotten it wrong.
~ [Mordin Solus](https://www.youtube.com/watch?v=1lfJMIwHDEM)

## dos box aint on browser how u do dat
[JS-DOS](https://js-dos.com/) renders to a canvas object, [toDataURL](https://developer.mozilla.org/en-US/docs/Web/API/HTMLCanvasElement/toDataURL) converts canvas objects to a data URL, Favicons can be set to a dataURL. It's just chaining it all together.

### special thanks
Without the existence of [Defender of the Favicon](http://www.p01.org/defender_of_the_favicon/) They probably wouldn't have realised this was possible. Also to [this StackOverflow answer](https://stackoverflow.com/a/62438464), which sent them down the rabbit hole. [This gist](https://gist.github.com/mathiasbynens/428626) from Mathias Bynens also made it all way easier. And of course this wouldn't be possible without [JS-DOS](https://js-dos.com/).

#### disclaimer
Doom is owned by id Software; this repo contains the shareware version of Doom, compressed in .zip format. If you want to play the full version of Doom in your favicon, you can buy it from GOG [here](https://www.gog.com/game/the_ultimate_doom) and then modify the .zip location referred to in the html file. Though that is probably not the best way to experience Doom.
