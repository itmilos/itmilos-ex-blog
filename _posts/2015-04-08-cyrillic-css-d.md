---
layout: post
title: "Cyrillic CSS - Letter Д"
description: "I will try to make every cyrillic letter in CSS... Stay tuned..."
category: project
tags: [css] 
imagefeature: css-cyrillic.jpg
modified: 2015-04-08
comments: true
share: true
featured: true
---

# Project Cylilic Letters in CSS

### Letter Д
    .D {
          transform: skew(-20deg,0);
          position:absolute;
          content:'';
          top:2px;
          left:50px;
          background-color:#000;
          width:15px;
          height:100px;
    }
    .D:before{
          transform: skew(35deg, 0);
          position:absolute;
          content:'';
          top:0px;
          left:40px;
          width:15px;
          height:100px;
          background-color:#000000;
    }
    .D:after{
        transform: skew(20deg, 0);
        position:absolute;
        content:'';
        top:75px;
        left:-10px;
        width:95px;
        height:15px;
        background-color:#000000;
    }
    
### [see example on codepen.io](http://codepen.io/MilosRujevic/pen/azrpLO){:target="_blank"}