# Pandas-CSS3-Hamburger

# Pandas CSS3 Hamburger
#### Description 


##### To use this hamburger, you just have to include the following link in the Head Tag. Link the Author!

Example:

`<!-- Copyright (c) 2019 Benedikt Wolf https://github.com/Panda279TV -->`

`<link rel="stylesheet" href="pandas-hamburger.css">`

`<link rel="stylesheet" href="YOUR.CSS.FILE">`

---

## Demo

![](pandas-hamburger-demo.gif)

The [DEMO](https://github.com/Panda279TV/Pandas-CSS3-Hamburger/pandas-hamburgers-demo.gif) shows the [HTML FILE](https://github.com/Panda279TV/Pandas-CSS3-Hamburger/pandas-hamburgers-test.html). You can download this and the CSS and have a look at it again.

---

## Statistics
- Minimalistic and Small
- Simple, Easy and Fast to learn
- No CSS `!Important`
- Only about 900 bytes (pandas-hamburgers.min.css)
- Works with older browsers (-webkit, -moz, -o, -ms)

---

## First Step


    <div class="hamburger">
      <span></span>
    </div>

---

## Introduction



    var hamburger = document.querySelector('.hamburger');

    hamburger.addEventListener('click', function(){
      hamburger.classList.toggle("is-active");
    })

---

