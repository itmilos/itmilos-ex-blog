---
layout: post
title: "CSS ЋИРИЛИЦА"
description: "Probaću da napravim svako ćirilično slovo srpskog jezika u CSS"
category: projekat
tags: [css] 
imagefeature: css-cyrillic.jpg
modified: 2015-04-14
comments: true
share: true
featured: true
---

# CSS ЋИРИЛИЦА 

### Slovo A

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
    
### [Vidi na codepen.io](http://codepen.io/MilosRujevic/pen/xbeRzv){:target="_blank"}

### Slovo Б    


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

### [Vidi na codepen.io](http://codepen.io/rujke/pen/myoGpN){:target="_blank"}

### Slovo В

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
    
### [Vidi na codepen.io](http://codepen.io/MilosRujevic/pen/WbWoXX){:target="_blank"}

### Slovo Г

    .G{
        position:relative;
        top:12.5px;
        left:10px;
        width:60px;
        height:125px;
        border-left:solid 16px #000000;
        border-top:solid 15px#000000;
    }
    
### [Vidi na codepen.io](http://codepen.io/MilosRujevic/pen/RNOBBQ){:target="_blank"}

### Slovo Д
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
    
### [Vidi na codepen.io](http://codepen.io/MilosRujevic/pen/azrpLO){:target="_blank"}

### Slovo Ђ
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
    
### [Vidi na codepen.io](http://codepen.io/MilosRujevic/pen/myYRYx){:target="_blank"}

### Slovo З
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
    
### [Vidi na codepen.io](http://codepen.io/MilosRujevic/pen/LEwWZR){:target="_blank"}


### Slovo И

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
    
### [Vidi na codepen.io](http://codepen.io/MilosRujevic/pen/LEwWyx){:target="_blank"}

### Slovo Ј


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
      border-radius:0 0 55% 75%;
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
    
    
### [Vidi na codepen.io](http://codepen.io/MilosRujevic/pen/rVBYXo){:target="_blank"}

### Slovo Ж
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
    
### [Vidi na codepen.io](http://codepen.io/MilosRujevic/pen/raXyOX){:target="_blank"}