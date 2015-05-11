---
layout: post
title: "Cyrillic CSS - Letter В"
description: "I will try to make every cyrillic letter in CSS... Stay tuned..."
category: project
tags: [css] 
imagefeature: css-cyrillic.jpg
modified: 2015-03-27
comments: true
share: true
featured: true
---

# Project Cylilic Letters in CSS

### Letter В

    .V{
        position:relative;
        top:12.5px;
        left:10px;
        width:60px;
        height:125px;
        border-left:solid 16px #000000;
    }
    .V:before{
        position:absolute;
        content:'';
        width:52px;
        height:39px;
        border-width:15px 15px 10px 0;
        border-color:#000000;
        border-style:solid;
        border-radius:0 240% 180% 0 /0 180% 180% 0;
    }
    .V:after{
        position:absolute;
        content:'';
        bottom:0;
        width:58px;
        height:43px;
        border-width:10px 15px 15px 0;
        border-color:#000000;
        border-style:solid;
        border-radius:0 180% 220% 0 /0 180% 180% 0;
    }
    
### [see example on codepen.io](http://codepen.io/MilosRujevic/pen/WbWoXX){:target="_blank"}

