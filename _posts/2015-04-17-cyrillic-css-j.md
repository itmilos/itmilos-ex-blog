---
layout: post
title: "Cyrillic CSS - Letter Ј"
description: "I will try to make every cyrillic letter in CSS... Stay tuned..."
category: project
tags: [css] 
imagefeature: css-cyrillic.jpg
modified: 2015-04-17
comments: true
share: true
featured: true
---

# Project Cylilic Letters in CSS

### Letter Ј


    .j{
      position:relative;
      top:12.5px;
      left:-5px;
      width:75px;
      height:66px;
      border-right:solid 16px #000000;
    }
    .j:before{
      position:absolute;
      content:'';
      bottom:-60px;
      right:-16px;
      width:50px;
      height:60px;
      border-width:0 16px 15px 14px;
      border-color:#000000;
      border-style:solid;
      border-radius:0 0 75% 75%;
    }
    .j:after{
      transform:rotate(-45deg);
      position:absolute;
      content:'';
      top:40px;
      left:-20px;
      width:80px;
      height:60px;
      background-color:#ffffff;
    }        
    
    
### [see example on codepen.io](http://codepen.io/MilosRujevic/pen/rVBYXo){:target="_blank"}