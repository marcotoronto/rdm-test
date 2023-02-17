---
layout: default
title: File Formats
nav_order: 4
---

# File Formats for Data Curation
{: .no_toc }

<p style="margin-bottom: 20px"></p>

A file format encodes information within a computer file so that it can be recognized by an application and accessed. It is indicated by the file name extension. Each file type (such as text, images, or sound) has many file formats available.

<p style="margin-bottom: 25px"></p>

<img src="figures/formats.png" width="300" style="margin-left:30px"/>

<p style="margin-bottom: 25px"></p>

Looking for a cheat sheet? Check out our <a href="https://osf.io/ena5p" target="_blank">one-pager</a>!
{: .note}
  

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
  TOC
{:toc}
</details>

---

Which formats do you use the most?
- .xls (Microsoft Excel) 
- .mp3 (for digital audio)
- .docx (Microsoft Document) 
- .gdoc (Google Document)

<p style="margin-bottom: 25px"></p>

<p style="margin-bottom:20px"> 
These are all commonly used file formats, but what if we tell you that these formats are <b>not recommended</b> to be used for data curation? These formats are unsustainable because they are proprietary.
</p>

<p style="margin-bottom: 30px"></p>

<img src="figures/shock.png" width="150" style="margin-left:30px"/>

<p style="margin-bottom: 50px"></p>

## Warm-up exercise
{: .no_toc}

Let's try to open the Lotus 1-2-3 version 3 file <https://github.com/openpreserve/format-corpus/tree/master/office/spreadsheet/wk3> (this is from 1990) and try to see the variable used.  
Share your experience in Padlet

[//]: # (activity link: https://bit.ly/rdmactivity)


<p style="margin-bottom: 50px"></p>

# What are proprietary formats?

- The file you were trying to open in the warm-up exercise was an older proprietary file that can no longer be opened. This inaccessibility can happen to other proprietary formats like Microsoft 
- They are limited by software patents, lack of format specification details, or built-in encryption to prevent open usage by the public.
- This results in requiring specific software provided by one vendor to use the proprietary format.
- In some cases, an industry may treat specific file formats as a de facto standard even if the formats are proprietary and rely on expensive software.

<p style="margin-bottom: 30px"></p>

We recommend <B>open formats</b> because they are more sustainable and easier to preserve in the long term.
{: .note}

<p style="margin-bottom: 30px"></p>

# What are open formats?

- They are non-proprietary.
- They are freely available for everyone to use.
- Because the specifications are released, open-source developers can write software to utilize the file format in case a particular vendor no longer supports the format.
- They may decrease the risk of technical obsolescence by removing the dependency on the underlying technology.

<p style="margin-bottom: 50px"></p>

# We recommend these common file formats:

<p style="margin-bottom: 20px"></p>

| File Type | Recommended File Formats |
| -- | --|
| Text | XML, ASCII, TXT, PDF|
| Images | TIFF, JPEG2000, PNG, JPEG/JFIF | 
| Video | MOV, MPEG-2 | 
| Audio | PCM, WAVE, DSD |
| Dataset | CSV, TSV, .db, .sqlite, Shapefile |
| Web Data | JSON, XML, HTML |



<br>

# Congrats!
{: .no_toc }

<p style="margin-top:25px">
<img src="figures/congrats.jpg" width="300" style="margin-left:30px"/>
</p>

Now you know which file formarts are proper for data curation and you can preserve the data for a longer term!

<br>

---


### Sources
{: .no_toc }
- <https://lib.guides.umbc.edu/c.php?g=728911&p=5872066>
- <https://guides.nyu.edu/data_management/file-formats>
- <https://www.library.northwestern.edu/about/administration/policies/file-format-recommendations.html>
- <https://www.loc.gov/preservation/resources/rfs>