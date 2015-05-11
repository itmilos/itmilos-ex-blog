---
layout: post
title: "Cyrillic CSS - Letter Ж"
description: "I will try to make every cyrillic letter in CSS... Stay tuned..."
category: project
tags: [css] 
imagefeature: css-cyrillic.jpg
modified: 2015-04-14
comments: true
share: true
featured: true
---

# Project Cylilic Letters in CSS

### Letter Ж
    .zz{
        position:relative;
        top:15px;
        left:50px;
        width:16px;
        height:125px;
        background-color:#000000;
    }
    .zz:before{
        transform:skew(32deg,0);
        position:absolute;
        content:'';
        top:0;
        left:1;
        width:16px;
        height:125px;
        background-color:#000000;
    }
    .zz:after{
        transform:skew(-32deg,0);
        position:absolute;
        content:'';
        top:0;
        right:0;
        width:16px;
        height:125px;
        background-color:#000000;
    } 
    
### [see example on codepen.io](http://codepen.io/MilosRujevic/pen/raXyOX){:target="_blank"}