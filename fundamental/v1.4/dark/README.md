Usage:

```CSS
@import url('https://malcat-gen.appspot.com/series?preset=animetitlebefore');
@import url('https://isaychris.github.io/themes/fundamental/test/dark/layout.css');

/* Header */
BODY::before {
    background-image: linear-gradient(45deg, #155799, #159957);
}

/* Avatar */
#inlineContent {
  background-image: url('https://myanimelist.cdn-dena.com/images/userimages/1117293.jpg');
}

/* User tag */
#inlineContent:after {
  content: "iSayChris";
}

/* Hover mod */
.animetitle:before {
    background-size: cover;
    background-position: 50% 50%;
    position: absolute;
    content: " ";
    pointer-events:none;
    filter: grayscale(20%);
    display: none !important;
}

:hover > .animetitle:before {
    display: inline-block !important;
    height: 320px;
    margin-left: -240px;
    top: 160px;
    position: fixed;
    border-radius: 5px;
    background-position: center;
    width: 190px;
} 
```
