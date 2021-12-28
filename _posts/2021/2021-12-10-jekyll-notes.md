---
layout: post
title: "jekyll notes"
date: 2021-12-10 
category: Notes
tags: jekyll html
excerpt_separator: <!--more-->
---

## Some notes

Make entire Div Clickable:
```html
<a href="http://example.com">
  <div class="example"> anything </div>
</a>
```
This is perfectly valid HTML.

<!--more-->

In liquid, we can use composite filter. The exection order is from left to right. For example.
```
{% assign var = site.baseurl | append: "/page" | append: 2 | string %}
```
Note that { int | string } convert integer to strings.


Also, we need to find a way to write liquid in code block.