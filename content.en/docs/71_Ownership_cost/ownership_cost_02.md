---
weight: 02
title: Edmunds.com | Ownership Cost 
authors: Lenny
categories: null
tags: 
description: 
draft: false
date: "2023-07-10"
lastmod: "2023-07-10"
series:
toc: true
---

Reference: Edmunds.com

Basic information:

Near ZIP: 58067

*Based on a 5-year estimate with 15,000 miles driven per year.

<figure>
  <img width = "540" src = "/docs/images/Screenshot 2023-07-10 224520.png"/>
  <figcaption class = "bottom">2023 Mazda CX-5 2.5L AWD</figcaption>
</figure>

<figure>
  <img width = "540" src = "/docs/images/Screenshot 2023-07-10 225945.png"/>
  <figcaption class = "bottom">2023 Lexus ES 350 F Sport Handling</figcaption>
</figure>

<figure>
  <img width = "540" src = "/docs/images/Screenshot 2023-07-11 124050.png"/>
  <figcaption class = "bottom">2023 Kia Carnival LX+</figcaption>
</figure>

<!--more-->
---

<div id="carlist">
  <ul>
    <li>
      <input type="checkbox" checked>
      <i></i>
      <h2>Mazda CX-5 2.5 AWD</h2>
      <p>True cost to own: US$39,722
      <br>Total cash price: US$29,833
      <br><br><img src = "/docs/images/Screenshot 2023-07-10 224158.png"/>
      </p>
    </li>
    <li>
      <input type="checkbox" checked>
      <i></i>
      <h2>Lexus ES 350 F Sport Handling</h2>
      <p>
True cost to own: US$59,569  
<br>Total cash price: US$54,305
<br><br><img src = "/docs/images/Screenshot 2023-07-10 230215.png"/>
      </p>
    </li>
    <li>
      <input type="checkbox" checked>
      <i></i>
      <h2>2023 Kia Carnival LX+</h2>
      <p>
      <p>True cost to own: US$49,951
      <br>Total cash price: US$38,994
      <br><br><img src = "/docs/images/Screenshot 2023-07-11 124153.png"/>
      </p>
    </li>
    <li>
      <input type="checkbox" checked>
      <i></i>
      <h2></h2>
      <p>
      <p>True cost to own: US$
      <br>Total cash price: US$
      <br><br><img src = "/docs/images/"/>
      </p>
    </li>
    <li>
      <input type="checkbox" checked>
      <i></i>
      <h2></h2>
      <p>
      <p>True cost to own: US$
      <br>Total cash price: US$
      <br><br><img src = "/docs/images/"/>
      </p>
    </li>
  </ul>
</div>


<style>

#carlist {
  max-width: auto; /*700px*/
  margin: auto;
  padding: 0 15px;
  text-align: center;
}

section.carlist {
  padding-top: 2em;
  padding-bottom: 3em;/*3*/
}

#carlist ul {
  text-align: left;
}

.transition, p, ul li i:before, ul li i:after {
  transition: all 0.3s;
}

#carlist .no-select, #carlist h2 {
  -webkit-tap-highlight-color: transparent;
  -webkit-touch-callout: none;
  user-select: none;
}

#carlist h2 {
  color: #cc071e;
  font-size: 17px; /*20*/
  line-height: 34px;/*34*/
  text-align: left;
  padding: 15px 15px 0; /*15px 15px 0*/
  text-transform: none;
  font-weight: 300;
  display: block;
  margin: 0;
  cursor: pointer;
  transition: .2s;
}

#carlist p {
  color: #333;
  text-align: left;
  font-size: 14px;
  line-height: 1.45;
  position: relative;
  overflow: hidden;
  max-height: 500px; /*the image size is determined by this setting*/
  will-change: max-height;
  contain: layout;
  display: inline-block;
  opacity: 1;
  transform: translate(0, 0);
  margin-top: 5px;
  margin-bottom: 15px;
  padding: 0 50px 0 15px;
  transition: .3s opacity, .6s max-height;
  hyphens: auto;
  z-index: 2;
}

#carlist ul {
  list-style: none;
  perspective: 900;
  padding: 0;
  margin: 0;
}
#carlist ul li {
  position: relative;
  overflow: hidden;
  padding: 0;
  margin: 0;
  /*padding-bottom: 4px;*/
  /*padding-top: 18px;*/
  background: #fff;
  box-shadow: 0 3px 10px -2px rgba(0,0,0,0.1);
  -webkit-tap-highlight-color: transparent;
}
#carlist ul li + li {
  margin-top: 15px;/*gap between two h2*/
}
#carlist ul li:last-of-type {
  padding-bottom: 0;
}
#carlist ul li i {
  position: absolute;
  transform: translate(-6px, 0);
  margin-top: 28px; /*location of the arrow*/
  right: 15px;
}
#carlist ul li i:before, ul li i:after {
  content: "";
  position: absolute;
  background-color: #cc071e;
  width: 3px;
  height: 9px;
}
#carlist ul li i:before {
  transform: translate(-2px, 0) rotate(45deg);
}
#carlist ul li i:after {
  transform: translate(2px, 0) rotate(-45deg);
}
#carlist ul li input[type=checkbox] {
  position: absolute;
  cursor: pointer;
  width: 100%;
  height: 100%;
  z-index: 1;
  opacity: 0;
  touch-action: manipulation;
}
#carlist ul li input[type=checkbox]:checked ~ h2 {
  color: #000;
}
#carlist ul li input[type=checkbox]:checked ~ p {
  /*margin-top: 0;*/
  max-height: 0;
  transition: .3s;
  opacity: 0;
  /*transform: translate(0, 50%);*/
}
#carlist ul li input[type=checkbox]:checked ~ i:before {
  transform: translate(2px, 0) rotate(45deg);
}
#carlist ul li input[type=checkbox]:checked ~ i:after {
  transform: translate(-2px, 0) rotate(-45deg);
}

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

html, body {
  /*height: 100%;*/
}

a,
a:visited,
a:focus,
a:active,
a:link {
  text-decoration: none;
  outline: 0;
}

a {
  color: currentColor;
  transition: .2s ease-in-out;
}

h1, h2, h3, h4 {
  margin: .3em 0;
}

ul {
  padding: 0;
  list-style: none;
}

img {
  vertical-align: middle;
  height: auto;
  width: 100%;
}


</style>