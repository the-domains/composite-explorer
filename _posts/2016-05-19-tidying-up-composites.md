---
datePublished: '2016-06-01T06:21:54.859Z'
sourcePath: _posts/2016-05-19-tidying-up-composites.md
isBasedOnUrl: 'https://www.youtube.com/watch?v=EbLI7EB88j8'
keywords: []
related: []
author:
  - name: Anna Madra
dateModified: '2016-06-01T06:21:42.237Z'
title: Tidying up composites
app_links: []
publisher:
  url: 'https://www.youtube.com/'
  name: YouTube
  favicon: 'https://www.youtube.com/favicon.ico'
  domain: www.youtube.com
description: '"What a mess!" This was the first reaction of one renowned researcher to the X-ray µ-tomography reconstruction of a composite reinforced with short natural fibers. He followed with "It should be put in order" and then wandered in the distance. It was indeed quite difficult to make out anything out of the picture as you can see here'
starred: false
inFeed: true
hasPage: false
inNav: false
_context: 'http://schema.org'
_type: VideoObject

---
![From X-ray µ-tomography to macroscale model](https://s3-us-west-2.amazonaws.com/the-grid-img/p/de21ca1a3108c26f64c6149af82757e4488612c3.png)

"What a mess!" This was the first reaction of one renowned researcher to the X-ray µ-tomography reconstruction of a composite reinforced with short natural fibers. He followed with "It should be put in order" and then wandered in the distance. It was indeed quite difficult to make out anything out of the picture as you can see here
![Only the surface of the material phases is visualized, with the top part of the EDOLAN UH phase removed to show the fibers inside](https://s3-us-west-2.amazonaws.com/the-grid-img/p/d3a653f2c03fc5a6abd9afec843b0f6bf051c9c5.png)

As I'm an avid fan of art, a proper classification of this figure followed: organic 3D Jackson Pollock. Can be a pleasure to the eye, but is not necessarily easy to comprehend and analyze. What can we do? The TED talk by Ursus Wehrli provides a clue: https://www.ted.com/talks/ursus\_wehrli\_tidies\_up\_art?language=en

His solution for Jackson Pollock-like paintings in our case would be equivalent to summing up the volume fractions of each phase in the material giving
![Composite material decomposed: polymer matrix accounts for 97% of the volume, short natural fibers are the remaining 3%.](https://the-grid-user-content.s3-us-west-2.amazonaws.com/3e508ba3-6eb6-4337-b271-85d120d64ff4.png)

This seems much easier to understand, and the fibers are also color-coded and separated: starting with the small ones and finishing on those with more complex geometry. Not bad, we've discovered that a mass of fibers is not just a homogeneous mess of similar entities, but a mess composed of objects with distinct morphology. What happens within one of such phases? Let's take fibers, for the sake of simplicity and the fact that they usually account for most of the composite's mechanical properties.

This is what it looks like when all of the fibers are arranged according to their volume, from the smallest to the largest
![](https://s3-us-west-2.amazonaws.com/the-grid-img/p/0f07be048a9f8886f776a48ec8ae0f47bac57bf6.png)

And this when their real, curved length is used to sort them out
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/67f24e54-7734-468e-b6ea-f364d9255e6a.png)

Are you thinking what I am thinking? Well, if you have the probability distribution of a given property for each class, then you can generate a similar structure by using stochastic approach. What else can you do? What about creating a custom domain and spreading fibers inside it? After all, sorting out a mess is only half the fun of making one.
![Generating a microstructure based on a stochastic model](https://the-grid-user-content.s3-us-west-2.amazonaws.com/adc0092e-bfa6-4e50-b57f-5af52e33c4f5.png)

For the moving pictures version of this story, please have a look at our video

https://www.youtube.com/watch?v=EbLI7EB88j8