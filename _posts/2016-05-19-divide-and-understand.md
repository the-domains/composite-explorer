---
datePublished: '2016-05-23T07:29:15.323Z'
sourcePath: _posts/2016-05-19-divide-and-understand.md
author:
  - name: Anna Madra
dateModified: '2016-05-23T07:29:09.944Z'
title: Divide and understand
description: "So, you’ve managed to open your n-GB data file with attenuation coefficients of your material. And what you see are shades of gray, and far more than fifty. I would risk saying there are 255 of them or even 65,535, with the latter case more probable with 16-bit capture on CCD cameras. Is this where you are? If not, please do relate to the X-ray µ-tomo primer soon available on Composite Explorer.  If you are working at the micro-scale and in material science, a probable image you'll obtain is"
starred: false
inFeed: true
hasPage: true
inNav: false
url: divide-and-understand/index.html
_context: 'http://schema.org'
_type: Article

---
![How segmentation influences X-ray tomography analyses](https://s3-us-west-2.amazonaws.com/the-grid-img/p/43d0432c659eee4b76b31b689d83f397ec69f104.jpg)

So, you've managed to open your n-GB data file with attenuation coefficients of your material. And what you see are shades of gray, and far more than fifty. I would risk saying there are 255 of them or even 65,535, with the latter case more probable with 16-bit capture on CCD cameras. Is this where you are? If not, please do relate to the X-ray µ-tomo primer soon available on Composite Explorer.   
If you are working at the micro-scale and in material science, a probable image you'll obtain is
![The 65,535 shades of gray of a short natural fiber composite](https://the-grid-user-content.s3-us-west-2.amazonaws.com/f2122a4f-dc35-491a-bb2f-d235495fb352.jpg)

The applicability of such picture is quite limited, though. You can do some preliminary examination - look at the shape, have some ideas about the phase distribution and that's about all. No more than some qualitative ideas, like in optical microscopy before the dawn of image processing. And yes, the images we're dealing with are similar to the optical micrographs with a subtle difference: what you see under the microscope are the photons in the visible light spectrum, more precisely:

* photons transmitted through the specimen and shadows where they were blocked by the material (the microscope setup with illumination from the bottom);
* photons reflected from the specimen surface and the shadows where the were absorbed (microscope setup with illumination from the top).

What you see in a tomogram is something different: the attenuation coefficient µ.
![3 key phases in a tomogram of a composite material: black - air, grey - matrix, white - natural fibers](https://s3-us-west-2.amazonaws.com/the-grid-img/p/156d5df4d8b920aa1d74eb5ee23f0efd15919acf.jpg)

This is after segmentation. Nice.