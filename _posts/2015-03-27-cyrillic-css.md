---
layout: post
title: "Cyrillic CSS"
description: "I will try to make every cyrillic word in CSS... Stay tuned..."
category: project css
tags: [css] 
imagefeature: css-cyrillic.jpg
modified: 2015-03-27
---

# Project Cylilic Letters in CSS

### Letter A

    .A{
        position:relative;
        left:30px;
        width:60px;
        height:91px;
        border-bottom:solid 14px#000000;
    }
    .A:before{
        transform:skew(-19deg,0);
        position:absolute;
        content:'';
        top:12.5px;
        left:0;
        width:16px;
        height:125px;
        background-color:#000000;
    }
        .A:after{
        transform:skew(19deg,0);
        position:absolute;
        content:'';
        top:12.5px;
        left:45px;
        width:16px;
        height:125px;
        background-color:#000000;
    }
    
### [see example on codepen.io](http://codepen.io/anon/pen/NPJxEp){:target="_blank"}

