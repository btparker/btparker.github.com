---
layout: page
title: Fleischer Setback Camera - Digital Reconstruction
---

Hello! I am a research engineer and traditional animation enthusiast, working on virtually resurrecting the Fleischer Studios "Stereoptical Process" using modern 3D scanning and computer graphics techniques to digitally reconstruct the rotating sets used in the Fleischer animated shorts. My aim is to enable novel ways to interact with and explore this piece of animation history.

My first rough proof of concept is [from a segment in "Popeye the Sailor Meets Sindbad the Sailor (1936)"](https://www.instagram.com/reel/Cwf-QfNs09N/), where Popeye enters and walks through a cave. Even though I used a small crop of a relatively low resolution video, I was able to obtain a rudimentary point cloud (estimated 3D points in space) and a "NeRF" (neural radiance field, a sort of AI dream of a 3D scene):

{% include youtubePlayer.html id='JeCzfTd7Vqw' %}

{% include youtubePlayer.html id='xZ3zOZRk3h8' %}

Certainly room for improvement, but a promising start!

To obtain higher quality reconstructions, I could:
- use a higher quality version of the video, the greater the detail the better
- mask out the cel painted characters (such as Popeye and the lions) to get more of the background per frame instead of just a rough crop where they don't appear
- mask out the foreground elements, which are not part of the 3D set and confuse the 3D reconstruction

What would enable extremely high quality reconstructions of the background sets (and would be incredibly exciting!) is to virtually reconstruct the Setback Camera / Stereoptical Process entirely. By having a digital replica of the camera and all the dimensions of the elements used in the setup one can reduce a lot of the "computational guesswork", and as a side effect we'd have a virtual recreation of this historic tool for animation.

I've started to break down the device from pictures and from the patents, largely extrapolating dimensions based on what (little) I know about the pegboard and cels used:

![](/assets/media/pages/fleischer-setback-camera-digital-reconstruction/fSpy-setback-camera.png)

However, this is a difficult process to do "from principles". Any additional data, such as dimensions of parts or arrangement of the setup, or exactly what type of camera, etc, would immensely help in this Setback Camera reconstruction which, in turn, would immensely help with the 3D set reconstructions.

My hope is that not only we can obtain 3D models of these wonderful sets and of the Stereoptical Process apparatus as a form of digital archivization, but create an interactive VR exhibit (I am a VR artist/engineer as well). How amazing would it be to see the process play out in real-time, the cels of the characters playing out in front of a rotating set, yet the camera viewport shows the final illusion? Or, if you're really so inclined, virtually go through the process of placing a new cel, cranking the rotation of the stage, adjusting a foreground element, view the shot and ::click:: take a photo and repeat (repeat, repeat).

Again, any resources to help this project, such as high quality video of these rotating sets, dimensions and details of the Setback camera and its setup, anything at all would be immensely appreciated. I am based in NYC, so if there are local resources or people I can see in person, that would be great to know!

Thanks for reading, and hopefully more to come!

P.S. Here is a VR painting of Betty Boop, from "The Old Man of the Mountain (1933)" short:
<div class="sketchfab-embed-wrapper"> <iframe title="Betty Boop" frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" allow="autoplay; fullscreen; xr-spatial-tracking" xr-spatial-tracking execution-while-out-of-viewport execution-while-not-rendered web-share src="https://sketchfab.com/models/2c959b2e8455458f9d9aa33ebab9f747/embed"> </iframe> </div>

P.P.S. Here is a rather terrible Fleischer-esque 2D animation I did of Sir Roderic from Gilbert and Sullivan's 'Ruddigore', as a teaser for a show I was in:
{% include youtubePlayer.html id='bVPhIn1LiZo' %}