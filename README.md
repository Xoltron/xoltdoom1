#play now
https://vidferris.github.io/FaviconDoom/favicondoom.html

# what
doom, rendered into a browser favicon. also rendered in your main monitor so you can see it

# why
had to be me, someone else might have gotten it wrong ~mordin solus

# how
https://js-dos.com/ renders to a canvas object, https://developer.mozilla.org/en-US/docs/Web/API/HTMLCanvasElement/toDataURL converts canvas objects to a data URL, favicons can be set to a dataURL. it's just chaining it all together. i also do a downscale before turning it into a dataurl and that seemed to make it a bit faster but that could just be confirmation bias on my end

# huh
yeah
