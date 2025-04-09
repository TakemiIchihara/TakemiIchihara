# Guidance of Creating a File with MarkDown

Editing README file is such an unpleasant experience with its inflexibility in design.<br />
Here is a little note of some of the design techniques that I learned for future references.

[HTML Tags](#your-friends)
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
  <li> ins with <> blanket &nbsp;: underline</li>
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

## Quotes
### Text Quote
You can make a text quote using &nbsp;"**\>**"
> This is a quote

### Code Quote
You can make a code quote wrapping the code with "**\```**"
```
This is a code quote
```
>[!tip]
>You can dpecify the coding language by simply adding the name of the language right after the first &nbsp; ```
>```javascript
>let greeting = "Hello, World!";
>console.log(greeting);
>```

### Annotation
```md
> [!NOTE]  
> Highlights information that users should take into account, even when skimming.

> [!TIP]
> Optional information to help a user be more successful.

> [!IMPORTANT]  
> Crucial information necessary for users to succeed.

> [!WARNING]  
> Critical content demanding immediate user attention due to potential risks.

> [!CAUTION]
> Negative potential consequences of an action.
```

> [!NOTE]  
> Highlights information that users should take into account, even when skimming.

> [!TIP]
> Optional information to help a user be more successful.

> [!IMPORTANT]  
> Crucial information necessary for users to succeed.

> [!WARNING]  
> Critical content demanding immediate user attention due to potential risks.

> [!CAUTION]
> Negative potential consequences of an action.


## Your friends
>**\<br />** is your best friend because you cannot break a line just simply hit the line.

>**\&nbsp;** is your friend when you need a white space

> **\<hr>** is your friend whe you want to divide segments with a border

>**\<!-- -->** is your friend when you wnat to leave a comment invisible to viewer

## Resources for Visual Elements
Adding SVGs is a great way to make your README fiile look fun and inviting✨ Here are some URLs to helpful websites🧑‍💻🦋

>### <a href="https://skillicons.dev">Skill Icons</a>

>### <a href="https://capsule-render.vercel.app">Capsule Render</a>

>### <a href="https://shields.io/badges/endpoint-badge">Endpoint Badge</a>

>### <a href="https://readme-typing-svg.herokuapp.com">Typing Animation</a>



