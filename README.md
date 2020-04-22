# HK Anti-extradition Symbol

It starts with a deep red box. Inside, we have three main parts.

## Main shape
This is basically a white semicircle, using the `overflow` property to trim off the right half of a circular white div.

## Cutout
Left of the main shape are three divs, each with a circular `before` pseudoselector. The top and bottom are deep red, and the middle is white. That gives it the illusion of a wave edge and trims the white semicircle nicely.

## Handcuff
The handcuff is made up of three parts as well.
- Cuff: This is a deep red circle. There is also a white div that "breaks" the circle.
- Cufflink: This is a deep red rectanble that is offset andalsigned to fit under the Cuff.
- Chain: This is a round div with the left border set to dashed deep red. The top border is set to transparent so that it will not taper off.

*Note:* While the symbol works nicely across most browsers, the dashed line might render differently across browsers.
