# Calculating Pi 🌐

Using a “**[Monte Carlo](https://en.wikipedia.org/wiki/Monte_Carlo_method)**” method – that is, a randomized simulation – we can compute a
good approximation of π.

![circle circumscribed by a square](https://cloud-rdyo1m0p1.vercel.app/1screenshot_2021-02-04_200812.png)

Consider a circle of radius 1, centered on the origin and circumscribed by a square, like so:

Imagine that this is a dartboard and that you are tossing darts at it randomly. With
enough darts, the ratio of darts in the circle to total darts thrown should be the ratio between
total darts 4 the area of the circle (call it a) and the area of the square (4): = . We can use darts in circle a
this ratio to calculate a, from which we can then find π = a<sup>2</sup>/.

![area approximation](https://cloud-rdyo1m0p1.vercel.app/0330px-montecarlointegrationcircle.svg.png)

[learn more](https://en.wikipedia.org/wiki/Monte_Carlo_method) about Monte Carlo Method