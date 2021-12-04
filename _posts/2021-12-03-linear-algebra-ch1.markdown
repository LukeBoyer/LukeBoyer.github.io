---
layout: post
title:  "LinAlg and Optimization for Machine Learning Ch1"
date:   2021-12-03 13:40:30 -0700
---

I've become pretty enthralled with neural nets lately. In addition to the meme-worthy Andrew Ng coursera thing, I've decided to work through the book mentioned in the title. 

The first chapter was more or less a review of the most basic concepts in linear algebra. It honed in on a lot of geometric interpretations of transformations which were a struggle (like SVD is the product of a rotation, a scaling, and another rotation... crazy). I tend to be better at algebra. 

I thought the results around decomposability into elementry matrices were particularly interesting and new to me. Never occured to me that gaussian elimination is actually just a bunch of elementary matrix multiplications. Since their inverses are pretty trivial its a simple way to decompose. I wonder if there is some generaliztion of elementary matrices that imply a unique decomposition. Also, which ones commute? Probably just row swaps.

Also, having some notion of easy ways to compute inverses for certains sums was not something I have seen. I guess from a general theoretic standpoint those results don't get you very far hence, not covered in undergraduate cirriculum. From the perspective of an ML practioner who cares about computation cost they are obviously much more relevant.

<iframe src="/assets/pdf/lin_alg_ch1.pdf" width="100%" height="1000px"></iframe>
