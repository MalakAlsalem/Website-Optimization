Website Optimization Project
============================
This is a project for Front-End Web Development Nanodegree from [Udacity][1].

**What I did for improvement:**
**On index. html page:**
- Delete web font link to reduce requests for additional resource.
- Add *media="print"* to make it only loads when user wants to print to avoid block rendering.
- Delete the second link of css and make it *embedded style* to avoid block rendering.
- Add *"async attribute"* to load Javascript asynchronously to avoid block rendering.
- Optimize images via [optimizilla.com][2].
- Add different optimized *"pizzeria image"* to the page.

**Result of PageSpeed Analysis:**
- For desktop: 96 / 100
- For mobile: 95 / 100

***
**On main.js & pizza.html :**
- Optimize images via [optimizilla.com][2].
- Replace all querySelector & querySelectorAll with getElementById & getElementsByClassName.
- Make the varibles as a global varibles to avoid creation every time functions runs.
- Convert *"sizeSwitcher and changeSliderLabel functions"* into an objects to reduce using loops & function calls.
- Move *"scrollTop varible"* out of loop to avoid creation every time iside a loop. 
- Set *"document.getElementsByClassName("randomPizzaContainer");" and "document.getElementById("movingPizzas1");"* in a globle varibles.
- Pull *"dx" and "newwidth" varibles* out of loop and function to aviod recreate and recalculate them every time.
- Minify CSS & JS files via [CSS Minifier][3] & [JavaScript Minifier][4].

[1]:https://www.udacity.com/ 
[2]:http://optimizilla.com/
[3]:https://cssminifier.com/
[4]:https://javascript-minifier.com/