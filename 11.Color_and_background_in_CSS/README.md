<img alt="logo" src="http://coderslab.pl/svg/logo-coderslab.svg" width="400">

# CSS &ndash; color and background

Write CSS styles in the style.css file. Check whether this file is linked to index.html.

1. Create a **div** element with the ```opacityTest``` class, and in it, make two paragraphs filled with text. Set the ```first``` class for the first **p** element, and the ```second``` class to the second one. Set any background for the first **p** element and give it a transparency of 0.4 using RGBa (remember to override the RGBa color earlier - if you do not remember, go back to to "Background transparency" slide in the presentation.

2. Next, also set any background for the second **p** element, and give it a transparency using opacity. Compare the effects. Describe your observations in a comment. How does the div change and how do the elements contained in it change?

3. Using [gradient-generator](http://www.cssmatic.com/gradient-generator) create a gradient for the **div** with ```gradient``` class.
Make sure that the colors are similar to the following:

	![Sample gradient](images/gradient.jpg)

4. Do the following steps:
   * download any image &ndash; e.g. from the website [sitebuilderreport](http://www.sitebuilderreport.com/stock-up), and save it in the **images** folder (located in the main project folder),
   * create a **div** with the **image** class and set the image above as its background.

5. Next, set the width of the **div** from the previous task to 100%, and height to 200px. Also, block image repetition.

6. Set the image from the previous task in the center of the **div** (use **background-position**).

## Attention
The gradient should have prefixes for older browsers. Just use the generator and copy the code.
Look at the link. Two dots indicate moving one level up (to the main folder):
  'background-image: url(../images/mydog1.jpg);'


## Need help or inspiration?
* [documentation, gradient](https://developer.mozilla.org/en-US/docs/Web/CSS/linear-gradient)
* [documentation, background-image](https://developer.mozilla.org/en-US/docs/Web/CSS/background-image)
* [Codecourse video tutorial, background-image](https://www.youtube.com/watch?v=cUF-q50DPPM)
* [gradient generator](http://www.cssmatic.com/gradient-generator)
* [sitebuilderreport, stock photos](http://www.sitebuilderreport.com/stock-up)
* HTML and CSS &ndash; prework
