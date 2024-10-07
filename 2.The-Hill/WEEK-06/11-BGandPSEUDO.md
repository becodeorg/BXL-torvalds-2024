# CSS Backgrounds and pseudo elements.

In a CSS integration of designs, `backgrounds` and `pseudo elements` are much more important than we think.

Not all images we see in a webpage are given by an img tag. This is because the img tag has its limitations with positionning.

Sometimes, and mostly when it's a matter of pure decoration, we will use backgrounds (in the body or in a div) that can recreate the decoration.

Find a good doc [here](https://developer.mozilla.org/en-US/docs/Web/CSS/background) and a nice usecase [here](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_backgrounds_and_borders/Using_multiple_backgrounds)

Also, when we have small decorations, the pseudo elements `::before` and `::after` can be very handy.

You can find the docs [here](https://developer.mozilla.org/en-US/docs/Web/CSS/::after) and [here](https://developer.mozilla.org/en-US/docs/Web/CSS/::before)

---

I prepared a list of videos that can lead you to complete sucessfully the exercise to come :

For **backgrounds** :

https://www.youtube.com/watch?v=dr1y4m7iEoU&ab_channel=DevDreamer
https://www.youtube.com/watch?v=3T_Jy1CqH9k&ab_channel=KevinPowell

For **Pseudo elements** :

https://www.youtube.com/watch?v=0okY5vUnfu0&ab_channel=ColtSteele

For **position relative/absolute** :

https://www.youtube.com/watch?v=P6UgYq3J3Qs&ab_channel=KevinPowell

---

Remember that `before` and `after` can work as a `div` if you stipulate its content to empty `''` and give it a `width`, a `height` and a `display:block`. Inside of this "div" you can give a backround image as a decoration. Combining it with a `position: absolute`, you can do whatever you want with positioning.

This is just an example. The possibilites are huge !

---
