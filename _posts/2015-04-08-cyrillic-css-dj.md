---
layout: post
title: "Cyrillic CSS - Letter Ђ"
description: "I will try to make every cyrillic letter in CSS... Stay tuned..."
category: project
tags: [css] 
imagefeature: css-cyrillic.jpg
modified: 2015-04-02
comments: true
share: true
featured: true
---

# Project Cylilic Letters in CSS

### Letter Ђ
    .Dj{
          position: relative;
          top: 12.5px;
          left: 25px;
          width: 60px;
          height: 125px;
          border-left: solid 16px #000000;
    }
    .Dj:before{
          position: absolute;
          content: '';
          left: -35px;
          width: 75px;
          height: 44px;
          border-top: solid 15px #000;
    }
    .Dj:after{
        position:absolute;
        content:'';
        top:55px;
        width:52px;
        height:65px;
        border-width:13px 15px 0px 0;
        border-color:#000000;
        border-style:solid;
        border-radius:0 220% 220% 0 /0 180% 180% 0;
    }
### [see example on codepen.io](http://codepen.io/MilosRujevic/pen/myYRYx){:target="_blank"}