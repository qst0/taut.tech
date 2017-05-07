<table><tr><td>Adding a header image<tr><img src="https://github.com/qst0/taut.tech/blob/master/images/tact_tech.png?raw=true">

**Step 1)** get an image (via images.google or any other legal source)<br>
<font size="2">for **taut.tech**, we used Pacifico from <a href="https://fonts.google.com/?sort=alpha">google fonts</a> to generate "Taut" in varying sizes<br>
the ".tech" was taken from <a href="get.tech">get.tech</a> ((*thank you*))</font>

**Step 2)** edit image to your liking<br>
<font size="2">we used Gimp and made images *400*(width) *x 150*(height) for Facebook headers and *800 x 300* for Twitter<br>
the header for this page was an arbitrary *328 x 79* only because the resolution looked good</font>

**Step 3)** putting it on the website<br>
<font size="2">a. assuming you want to add an image where your site name is...<br>
b. head to ~/layouts/default.html (assuming you have the <a href="https://github.com/barryclark/jekyll-now">jekyll-now</a><br>
c. find "<textarea rows="1" cols="60"><h1 class="site-name"><a href="{ { site.baseurl }}">{{ site.name }}</a></h1></textarea>"<br>
d. replace <textarea rows="1" col="1">{ { site.name }}</textarea> with <textarea rows="1" cols="25"><img src="your-url-here"></textarea><br>
e. repeat Step 2 and make adjustments until perfect</font><p>
