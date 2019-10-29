# Pandas CSS3 Hamburger
#### There are many good hamburgers or also hamburgers with 10 different animations. I only wanted one to keep it as small as possible! I used an extra div and span because I find it easier, more comfortable and better. Everyone understands it right away and it is as little as possible. There are hamburgers with 3-5 nested elements.


##### To use this hamburger, you just have to include the following link in the Head Tag. Link the Author!

Example:

`<!-- Copyright (c) 2019 Benedikt Wolf https://github.com/Panda279TV -->`

`<link rel="stylesheet" href="pandas-hamburger.css">`

`<link rel="stylesheet" href="YOUR.CSS.FILE">`

---

## Demo
![](pandas-hamburger-demo.gif)

The [DEMO](https://github.com/Panda279TV/Pandas-CSS3-Hamburger/blob/master/pandas-hamburger-demo.gif) shows the [HTML FILE](https://github.com/Panda279TV/Pandas-CSS3-Hamburger/blob/master/pandas-hamburger-test.html). You can download this and the CSS and have a look at it again.

---

## Statistics
- Minimalistic and Small
- Simple, Easy and Fast to learn
- No CSS `!Important`
- Only about 1.300 kilobytes (pandas-hamburgers.min.css)
- Works with older browsers (-webkit, -moz, -o, -ms)

---

## First Step

###### Just insert the code below where you want the hamburger to be!

    <div class="hamburger">
      <span></span>
    </div>
    
    OR
    
    <div class="hamburger"><span></span></div>

---

## Introduction

###### The hamburger needs a little bit of Javascript. The only thing you have to do is toggle the class "is-active"! So when you click, the class is added and when you click again it is removed! Just insert the code below into your Javascript file.

    var hamburger = document.querySelector('.hamburger');

    hamburger.addEventListener('click', function(){
      hamburger.classList.toggle("is-active");
    })

    OR
    
    $hamburger = $('.hamburger');
    
    $hamburger.on('click', function () {
        $hamburger.toggleClass("is-active");
    });
---
