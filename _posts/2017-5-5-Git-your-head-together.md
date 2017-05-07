Adding a header image

**Step 1)** get an image (via images.google or any other legal source)<br>
<font size="2">for **taut.tech**, we used Pacifico from [google fonts](https://fonts.google.com/?sort=alpha) to generate "Taut" in varying sizes<br>
the ".tech" was taken from [get.tech](get.tech) ((*thank you*))</font>

**Step 2)** edit image to your liking<br>
<font size="2">we used Gimp and made images *400*(width) *x 150*(height) for Facebook headers and *800 x 300* for Twitter<br>
the header for this page was an arbitrary *328 x 79* only because the resolution looked good</font>

**Step 3)** putting it on the website<br>
<font size="2">a. assuming you want to add an image where your site name is...<br>
b. head to ~/layouts/default.html (assuming you have the *[jekyll-now](https://github.com/barryclark/jekyll-now)* layout)<br>
c. find "<textarea cols="35"><h1 class="site-name"><a href="{{ site.baseurl }}/">{{ site.name }}</a></h1></textarea>"<br>
d. replace <textarea col="35">{{ site.name }}</textarea> with <textarea cols="35"><img src="your-url-here"></textarea><br>
e. repeat Step 2 and make adjustments until perfect</font>
