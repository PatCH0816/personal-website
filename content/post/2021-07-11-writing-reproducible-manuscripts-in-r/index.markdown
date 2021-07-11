---
title: Writing reproducible manuscripts in R
author: Shilaan Alzahawi
date: '2021-07-11'
slug: writing-reproducible-manuscripts-in-r
categories: 
  - rmarkdown
tags: []
subtitle: ''
summary: 'A workshop on writing reproducible APA manuscripts using R Markdown and papaja'
authors:
    - admin
lastmod: '2021-07-11T10:34:17-07:00'
featured: no
image:
  placement: 2
  caption: ''
  focal_point: 'Center'
  preview_only: no
projects: []
---

<script src="{{< blogdown/postref >}}index_files/clipboard/clipboard.min.js"></script>
<link href="{{< blogdown/postref >}}index_files/xaringanExtra-clipboard/xaringanExtra-clipboard.css" rel="stylesheet" />
<script src="{{< blogdown/postref >}}index_files/xaringanExtra-clipboard/xaringanExtra-clipboard.js"></script>
<script>window.xaringanExtraClipboard(null, {"button":"<i class=\"fa fa-clipboard\"><\/i> Copy Code","success":"<i class=\"fa fa-check\" style=\"color: #90BE6D\"><\/i> Copied!","error":"Press Ctrl+C to Copy"})</script>
<link href="{{< blogdown/postref >}}index_files/font-awesome/css/all.css" rel="stylesheet" />
<link href="{{< blogdown/postref >}}index_files/font-awesome/css/v4-shims.css" rel="stylesheet" />
<script src="{{< blogdown/postref >}}index_files/fitvids/fitvids.min.js"></script>

{{&lt; toc &gt;}}

## Motivation

I recently gave a talk on writing reproducible manuscripts using R Markdown and the R package [*papaja*](https://github.com/crsh/papaja) (*p*reparing *apa j*ournal *a*rticles). One of my main motivations for using R to write up my manuscripts is contained in this tweet by [Pamela Jacobsen](https://twitter.com/pamelacjacobsen?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1394207042462785539%7Ctwgr%5E%7Ctwcon%5Es1_&ref_url=http%3A%2F%2Flocalhost%3A4321%2Fpost%2Fwriting-reproducible-manuscripts-in-r%2F):

<center>

{{&lt; tweet 1394207042462785539 &gt;}}

</center>

### A reproducible workflow

In the workshop, I go through methods that keep you from manually transcribing and/or copy pasting tables, figures, and statistical output over and over again.

Perhaps my favorite introduction to the idea of a [**reproducible workflow**](https://www.youtube.com/watch?v=s3JldKoA0zw) (and the horrors of a non-reproducible workflow) is given in this short YouTube video:

<center>

{{&lt; youtube s3JldKoA0zw &gt;}}

</center>

#### Benefits

The video hints at some of the benefits of a reproducible workflow. A reproducible workflow is…

⚠️ Less error-prone  
⏳ Less time-consuming  
⇄ More dynamic  
🔎 More transparent

### The result

You can find a list of papers written with papaja [here](https://github.com/crsh/papaja#papers-written-with-papaja). Here’s a sneak peek of what’s happening behind the scenes, and the rendered result:  
![](manuscript.png)
![](cites.png)

## Materials

If you want to learn more, you can [find the slides here {{&lt; icon name=“images” pack=“far” &gt;}}](https://shilaan-apa.netlify.app) or browse them through below.

<div class="shareagain" style="min-width:300px;margin:1em auto;">
<iframe src="https://shilaan-apa.netlify.app" width="400" height="300" style="border:2px solid currentColor;" loading="lazy" allowfullscreen></iframe>
<script>fitvids('.shareagain', {players: 'iframe'});</script>
</div>

### Acknowledgements

❤︎ Slides created with the R package [xaringan](https://github.com/yihui/xaringan)  
❤︎ papaja created by [Frederik Aust](http://frederikaust.com)  
❤︎ GIFs created by [Shannon Pileggi](https://www.pipinghotdata.com/posts/2020-09-07-introducing-the-rstudio-ide-and-r-markdown/)  
❤︎ Artwork created by [Allison Horst](https://github.com/allisonhorst/stats-illustrations)
