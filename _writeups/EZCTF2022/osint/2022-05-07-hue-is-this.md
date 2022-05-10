---
layout: post
title: "Hue is this EZCTF2022 Writeup"
date:   2022-05-07 20:59:22 +0100
categories: [writeup,EZCTF2022,osint]
---
This is the description of this task:
```
Solves: 247  Medium, Points 170
I think you need  to do a -180 turn to find her name and the song.

Flag Format: EZ-CTF{Her_Name_And_The_7th_Song_In_The_Album}
```

This is another challenge from the OSINT category.
All we get is a photo of an interesting person.

<style>
    img[src$="centerme"] {
  display:block;
  margin: 0 auto;
}
</style>

![]({{ site.url }}/static/assets/writeups/EZCTF2022/osint/hue_is_this.jpeg?style=centerme)

The first thing that i've done was to use google image search. 

![]({{ site.url }}/static/assets/writeups/EZCTF2022/osint/2022-05-07_13-03.png?style=centerme)

I clicked through first three pages and found the name of the album (cover of
the album was the same as in the photo)

![]({{ site.url }}/static/assets/writeups/EZCTF2022/osint/2022-05-07_13-03_1.png?style=centerme)

On the same page, if you look closely, you can find information about the model from 
our photo.

![]({{ site.url }}/static/assets/writeups/EZCTF2022/osint/2022-05-07_13-03_2.png?style=centerme)



If we combine all the information that we found the flag is:
```EZ-CTF{India_Waters_Rock_Bitch}```