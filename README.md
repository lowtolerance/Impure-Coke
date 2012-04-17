This is JavaScript-powered remake of Roman Cortes' [Pure CSS Coke Can](http://www.romancortes.com/ficheros/css-coke.html). A friend bet me that I couldn't make an "impure" CSS version of this in less than 1kB of Javasript code. 

My first attempt ended up clocking in at around 800 bytes of JS. This version used precalculated values extrapolated from Cortes' CSS, but Cortes was kind enough to provide me with the formula he used, which shaved quite a bit off the total filesize. With some hacky minification, I was able to get the end result under 600 *including* CSS and HTML. 

It won't validate, of course, but at the time of its creation(around January of 2010), it worked in all major browsers, I suspect it still will.

You can see it action [here](http://lowtolerance.github.com/Impure-Coke).