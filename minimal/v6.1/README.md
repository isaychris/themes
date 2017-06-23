![Image](http://i.imgur.com/zGtapuo.png)

Usage:
```CSS

@import url('https://mal-image.appspot.com/all/isaychris');
@import "https://isaychris.github.io/themes/minimal/v6.1/layout.css";

body {
    background-attachment: fixed !important;
    background-color: #f0f0f0 !important;
    background-image: url("http://i.imgur.com/LvvaNSQ.png") !important;
    background-repeat: repeat-x !important;
}

/* BANNER */
:nth-child(5) .header_title {
    background: rgba(255, 255, 255, 0) url("http://i.imgur.com/lxDniKJ.gif") no-repeat scroll center center / 100% 100%;
}

/* User tag */
:nth-child(5) .header_title::before {
    content: "MyAnimeList";
}
````
