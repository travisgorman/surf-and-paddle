# Surf & Paddle Project

Before I write any code, I want to go over the design and map out the structure and style by answering two questions as best I can. 

* Content Sectioning: 
  - What are the main sections of the page?
* Style: 
  - What styles are shared across different elements/sections?

## Content Sectioning
I see 4 sections here.

___

* Header 
* Main 
* Section 

___

 Broken down further into the elements within those sections, I see:

___

* Header (background image with gradient overlay)
  + a (href="index.html")
    + img (logo.png)
  - span 
  - nav 
    + About
    + Search
  - h1 (surf & paddle)
  - h5 (An Ironyard Academy Project Est. Fall 2013)
  
* Main 
  - Article
    + h2
    + Section.author-info
      * author-thumb-sm.png
      * a (href="author.html")
      * span (on)
      * span
        - a (href="date")
    + p
    + p
      * a (href="mixtape")
    + Blockquote
    + p
      * a (href="aliqua")
    + p
    + Section.widgets
      * Button.readComments
      * Button.readLater
      * Button.share
    
  - Aside
    + div.author-social
    + div.ad
      * img (src="ad.png")
      * a (href="#")
    + div.sidebar
      * H4
      * p
        - a (href="mixtape.html")

* Section.popular-posts
  - h2 
  - ul
    + div.post-1
      * a (href="post-1.html")
        - h3
        - post-image-1
    + div.post-2
      * a (href="post-2.html")
        - h3
        - post-image-2
    + div.post-3
      * a (href="post-3.html")
        - h3
        - post-image-3
    + div.post-4
      * a (href="post-4.html")
        - h3
        - post-image-4

* Footer
  - img (tiy-logo.png)
  - p 
  - ul
    + li 
      * a (href="nav-1")
        - Nav Item 1
    + li 
      * a (href="nav-2")
        - Nav Item 2
    + li
      * a (href="nav-3")
        - Nav Item 3
    + li
      * a (href="nav-5")
        - Nav Item 5

___

I don't know if this is the best way to outline structure for a page, but I did this quickly. It gives me idea of how elements are grouped and will help me lay out the scaffolding HTML.

___

## `<head>`
I know I'm going to need two Google fonts, "Open San" for the body copy, and "Oswald" for the headers. I'll also need Font Awesome for the widget button icons. I'll grab the CDN links for those and put them in the head with the `<link>` tag. 



## CSS

When writing my CSS, I want to target elements in the simplest way possible - avoid over-classification and turning this into a muddy mess. 

## Styles shared across multiple sections?

The only ones I see are the h2 headers in the main article as well as the popular-posts section. 

## What elements are there only one of?


