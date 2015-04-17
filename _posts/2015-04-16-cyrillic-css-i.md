---
layout: post
title: "Cyrillic CSS - Letter И"
description: "I will try to make every cyrillic letter in CSS... Stay tuned..."
category: project
tags: [css] 
imagefeature: css-cyrillic.jpg
modified: 2015-04-16
comments: true
share: true
featured: true
---

# Project Cylilic Letters in CSS

### Letter И

    .i{
        position:relative;
        top:12.5px;
        left:10px;
        width:63px;
        height:125px;
        border-width:0 15px 0 15px;
        border-color:#000000;
        border-style:solid;
    }
    .i:before{
        transform:skew(-30deg,0);
        position:absolute;
        content:'';
        top:0;
        left:24px;
        width:15px;
        height:125px;
        background-color:#000000;
    }
    
### [see example on codepen.io](http://codepen.io/MilosRujevic/pen/LEwWyx){:target="_blank"}