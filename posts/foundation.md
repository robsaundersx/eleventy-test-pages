---
title: Creative Programming - Foundation
description: Foundation is the first topic in the Creative Programmin course.
date: 2022-06-18
tags:
  - creative programming
layout: layouts/post.njk
---
# Foundation

## This is an example sketch

<div id="blue_canvas"></div>
<div id="pink_canvas"></div>

<script>
const pink_sketch = p => {
  p.setup = function() {
    p.createCanvas(200, 200);
    p.background(255, 0, 200);
  };
};

const blue_sketch = p => {
  p.setup = function() {
    p.createCanvas(200, 200);
    p.background(0, 200, 255);
  };
};

let s1 = new p5(pink_sketch, pink_canvas);
let s2 = new p5(blue_sketch, blue_canvas);
</script>
