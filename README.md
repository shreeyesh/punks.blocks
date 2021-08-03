# Punk Building Block Series



## Original CryptoPunks Series (24×24)

Humans (Male/Female)
![](original/human-male_lighter.png)
![](original/human-male_light.png)
![](original/human-male_dark.png)
![](original/human-male_darker.png)
![](original/human-female_lighter.png)
![](original/human-female_light.png)
![](original/human-female_dark.png)
![](original/human-female_darker.png),
Aliens (Male)
![](original/alien-male.png),
Apes (Male),
![](original/ape-male.png),
Zombies (Male)
![](original/zombie-male.png).


Attributes - Cap ![](original/cap.png),
Cap Forward ![](original/capforward.png),
Small Shades ![](original/smallshades.png),
Pipe ![](original/pipe.png),
Smile ![](original/smile.png)


<!-- note:
       double check/todo: some attribute need a variant for females (width less by one or such)
       e.g. shades and others!!!!
-->



## Alien Invasion Series (24x24)

Aliens (Male) in red (0°), orange (30°),  yellow (60°),
, chartreuse (90°), green (120°), magenta (°300), fuchsia (°330), and more.

![](alien-invasion/alien-male_0.png)
![](alien-invasion/alien-male_30.png)
![](alien-invasion/alien-male_60.png)
![](alien-invasion/alien-male_90.png)
![](alien-invasion/alien-male_120.png)
![](alien-invasion/alien-male_150.png)
![](alien-invasion/alien-male_180.png)
![](alien-invasion/alien-male_300.png)
![](alien-invasion/alien-male_330.png)







##  DIY (Do-It-Yourself) - Yes, You Can! Design Your Own Punks Using the Punk (Building) Blocks

Use the [free ImageMagick tools](https://imagemagick.org)
to make your own punks.


### Alien with Cap Forward, Small Shades & Pipe

Let's make punk #7804 - a super rare alien
![](original/alien-male.png)
with a capforward
![](original/capforward.png),
smallshades
![](original/smallshades.png)
and a pipe
![](original/pipe.png)
from scratch:

```
$ magick convert alien-male.png \
                 capforward.png \
                 smallshades.png \
                 pipe.png \
         -background none -flatten punk7804.png
```

<!--
$ magick convert alien-male.png capforward.png smallshades.png pipe.png -background none -flatten punk7804.png
-->

Now open up the new `punk7804.png`. Enjoy your million-dollar punk look-a-alike. Yes, it's
a 100% true authentic pixel ~~copy~~ original.

![](i/punk7804.png)



Zooming In - 2x, 4x


Scale up the image by doubling the pixels (that is, use the `-filter point` option).
Let's try 2x (that is, 200%):

```
$ magick convert punk7804.png \
         -filter point -resize 200% punk7804x2.png
```

<!--
$ magick convert punk7804.png -filter point -resize 200% punk7804x2.png
 -->

![](i/punk7804x2.png)

And 4x (that is, 400%):

```
$ magick convert punk7804.png \
         -filter point -resize 400% punk7804x4.png
```

![](i/punk7804x4.png)

<!--
$ magick convert punk7804.png -filter point -resize 400% punk7804x4.png
 -->


Why stop? Let's add a smile!

```
$ magick convert punk7804.png \
                 smile.png \
         -background none -flatten punk7804_smile.png
```

<!--
$ magick convert punk7804.png smile.png  -background none -flatten punk7804_smile.png
-->

![](i/punk7804_smile.png)   2x, 4x:
![](i/punk7804_smilex2.png)
![](i/punk7804_smilex4.png)





#### Alien Invasion

Let's try the green (120°) variant.
Let's make - a super rare alien
![](alien-invasion/alien-male_120.png)
with a capforward
![](original/capforward.png),
smallshades
![](original/smallshades.png)
and a pipe
![](original/pipe.png)
from scratch:

```
$ magick convert alien-male_120.png \
                 capforward.png \
                 smallshades.png \
                 pipe.png \
         -background none -flatten punk7804_120.png
```

<!--
$ magick convert alien-male_120.png capforward.png smallshades.png pipe.png -background none -flatten punk7804_120.png

$ magick convert punk7804_120.png -filter point -resize 200% punk7804_120x2.png

$ magick convert punk7804_120.png -filter point -resize 400% punk7804_120x4.png
-->

![](i/punk7804_120.png)   2x, 4x:
![](i/punk7804_120x2.png)
![](i/punk7804_120x4.png)

Or try the 90° ![](alien-invasion/alien-male_90.png) variant - `alien-male_90.png`:

![](i/punk7804_90.png)   2x, 4x:
![](i/punk7804_90x2.png)
![](i/punk7804_90x4.png)

Or 150° ![](alien-invasion/alien-male_150.png) - `alien-male_150.png`:

![](i/punk7804_150.png)   2x, 4x:
![](i/punk7804_150x2.png)
![](i/punk7804_150x4.png)




### Alien with Cap

Let's make punk #2890 - another super rare alien
![](original/alien-male.png)
with a cap
![](original/cap.png)
from scratch:

```
$ magick convert alien-male.png \
                 cap.png \
         -background none -flatten punk2890.png
```

<!--
$ magick convert alien-male.png cap.png -background none -flatten punk2890.png
-->


![](i/punk2890.png)   2x, 4x:
![](i/punk2890x2.png)
![](i/punk2890x4.png)




That's it.



## Questions? Comments?

Post them on the [CryptoPunksDev reddit](https://old.reddit.com/r/CryptoPunksDev). Thanks.
