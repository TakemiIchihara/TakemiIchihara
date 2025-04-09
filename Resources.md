# Guidance of Creating a File with MarkDown

Editing README file is such an unpleasant experience with its inflexibility in design.<br />
Here is a little note of some of the design techniques that I learned for future references.

[HTML Tags](#html-tage)
## Headings
```md
  #    == <h1>
  ##   == <h2>
  ###  == <h3>

  ex) ## My Favourite Artists
```
>[!warning]
>\# and \## automatically generate underline and you absolutely CANNOT eliminate those unfortunately.

## Customize Fonts
<ul>
  <li> *&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;: italic</li>
  <li> **&nbsp;&nbsp;&nbsp;&nbsp;: bold</li>
  <li> ***&nbsp;&nbsp;: italic & bold</li>
  <li> <ins>&nbsp;: underline
</ul>

## HTML tags
For the most part, you can find that you can use tags from HTML interchangeably.
However, what MD does not allow you to do is **inline styling**

>Here is what you can do:
>```md
><img align="center" src="#" width="350px" alt="">
>```
<ul>
  <li> align&nbsp;&nbsp;&nbsp;: aligns the content to left, center, or right</li>
  <li> width&nbsp;&nbsp;: Set the width of the content</li>
  <li> height&nbsp;: Set the height of the content</li>
</ul>

>[!warning]
>Somehow the align styling does not apply to images where you have to wrap the image in a **\<div>** first and style the \<div> as you want


## Your friends
>**\<br />** is your best friend because you cannot break a line just simply hit the line.

>**\&nbsp;** is your friend when you need a white space

>**\<!-- -->** is your friend when you wnat to leave a comment invisible to viewer

## Good Resources for Visual Elements
Adding SVGs is a great way to make your README fiile look fun and inviting✨ Here are some URLs to websites that 

>### Capsule Render
```
https://capsule-render.vercel.app
```

>### Endpoint Badge
<a href="https://shields.io/badges/endpoint-badge">### Endpoint Badge</a>

behance


https://readme-typing-svg.herokuapp.com



