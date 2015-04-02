---
layout: post
title: "Cyrillic CSS - Letter Б"
description: "I will try to make every cyrillic letter in CSS... Stay tuned..."
category: project
tags: [css] 
imagefeature: css-cyrillic.jpg
modified: 2015-03-31
comments: true
share: true
featured: true
---

# Project Cylilic Letters in CSS

### Letter Б    


    .B{
        position:relative;
        top:12.5px;
        left:10px;
        width:60px;
        height:125px;
        border-left:solid 16px #000000;
        border-top:solid 15px#000000;
    }
    .B:after{
        position:absolute;
        content:'';
        bottom:0;
        width:58px;
        height:55px;
        border-width: 15px 12px 15px 0;
        border-color:#000000;
        border-style:solid;
        border-radius:0 180% 220% 0 / 0 180% 180% 0;
    }

### [see example on codepen.io](http://codepen.io/rujke/pen/myoGpN){:target="_blank"}

