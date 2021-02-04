# Calculating Pi `π`🌐

Using a “**[Monte Carlo](https://en.wikipedia.org/wiki/Monte_Carlo_method)**” method – that is, a randomized simulation – we can compute a
good approximation of `π`.

Consider a circle of radius `1`, centered on the origin and circumscribed by a square, like so:

![circle circumscribed by a square](https://cloud-rdyo1m0p1.vercel.app/1screenshot_2021-02-04_200812.png)

Imagine that this is a dartboard and that you are tossing darts at it randomly. With
enough darts, the ratio of darts in the circle to total darts thrown should be the ratio between
total darts `4` the area of the circle (call it `a`) and the area of the square (`4`): = `(total darts)/(darts in the circle)` = `4/a`. We can use this ratio to calculate `a`, from which we can then find `π` = a/r<sup>2</sup>.

![area approximation](https://cloud-rdyo1m0p1.vercel.app/0330px-montecarlointegrationcircle.svg.png)

We can simplify the math by only considering the first quadrant, calculating the ratio of
the top right square’s area to the area of the single quadrant. Thus, we will actually find `a/4`, and then compute `π` = 4 × (a/4)/r<sup>2</sup>.

learn more about Monte Carlo Method [here](https://en.wikipedia.org/wiki/Monte_Carlo_method).