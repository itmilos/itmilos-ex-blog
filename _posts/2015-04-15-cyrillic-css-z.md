---
layout: post
title: "Cyrillic CSS - Letter З"
description: "I will try to make every cyrillic letter in CSS... Stay tuned..."
category: project
tags: [css] 
imagefeature: css-cyrillic.jpg
modified: 2015-04-15
comments: true
share: true
featured: true
---

# Project Cylilic Letters in CSS

### Letter З
    .z{
        transform:rotate(180deg);
        position:relative;
        width:105px;
        height:150px;
        top:10px;
        left:10px;
    }
    .z:before{
        transform:rotate(1deg);
        position:absolute;
        content:'';
        left:21px;
        width:52px;
        height:44px;
        border-width:15px 0 15px 15px;
        border-color:#000000;
        border-style:solid;
        border-radius:140% 0 0 105% / 100% 0 0 120% ;
    }
    .z:after{
        transform:rotate(-1deg);
        position:absolute;
        content:'';
        top:65px;
        left:21px;
        width:52px;
        height:44px;
        border-width:15px 0 15px 15px;
        border-color:#000000;
        border-style:solid;
        border-radius:100% 0 0 140% /120% 0 0 105%;
    } 
    
### [see example on codepen.io](http://codepen.io/MilosRujevic/pen/LEwWZR){:target="_blank"}