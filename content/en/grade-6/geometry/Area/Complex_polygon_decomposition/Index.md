---
title: "06 Decomposition Of Complex Polygon"
description: "We decompose a complex polygon multiple times to calculate the area"
lead: ""
date: 2020-11-12T13:26:54+01:00
lastmod: 2020-11-12T13:26:54+01:00
draft: false
images: []
weight: 660
toc: true
---
## Finding area using decomposition (complex shapes)


We can use decomposition to find the area of different shapes. It's really helpful when we don't know the shape well. For example, let's say we have a shape we don't know how to find the area of. We can break it down into smaller shapes we do know how to find the area of.

Sometimes, we have to break down and rearrange the shape more than once to find the area, like given below.

<img src="1_69_complex_quadrilateral.png" width="300" style="display: block; margin: 0 auto;">


Our goal is to get as many complete squares in the shape as we can. To do this, we can add more lines to the shape to make it easier to work with. 
To start, we draw a vertical line in the shape. Then, we use decomposition and rearrangement to turn it into a pentagon shape.

<img src="1_70_complex_quadrilateral_to_pentagon.gif" width="300" style="display: block; margin: 0 auto;">
 
We get a figure somewhat like the one shown below.
<img src="1_71_pentagon_from_quadrilateral.png" width="300" style="display: block; margin: 0 auto;">

The shape we're looking at is made up of two trapeziums. We can use a formula to find the area of each trapezium and add them together to get the area of the whole shape. 

<img src="1_72_pentagon_into_two_trapeziums.png" width="300" style="display: block; margin: 0 auto;">

Another way to find the area of the shape is to break it down into smaller parts. We can turn the half triangle at the bottom of one of the trapeziums into a whole square.

<img src="1_73_pentagon_to_heptagon.gif" width="300" style="display: block; margin: 0 auto;">

Now, we have a new shape that's made up of a triangle (half a unit square), 3 rectangles (half of a unit square), and 2 squares (one unit square). 

<img src="1_74_countingsquares_in_heptagon.png" width="300" style="display: block; margin: 0 auto;">

When we add the areas of all the individual pieces we get:
Total area= 0.5 +1 + 1 + 0.5 + 0.5 + 0.5 = 4 square units.
It is always a matter if an incomplete square can be combined with another incomplete square to make a complete square! It's like a puzzle! Sometimes you need more than two pieces to make a complete square, but you can figure it out by trying different combinations. You can even rotate the pieces to make them fit. This idea of breaking shapes into smaller pieces can be used for any polygon.

