---
layout: default
title: Directory Structures
nav_order: 7
---

# Why are structured directories important?
{: .no_toc }

Now, let’s pretend that you store everything on your computer in one single folder – some of us are probably known to use our desktops for this. Imagine how long it would take you to find data you collected on a specific day a few years ago. 

<p style="margin-top:25px">
<img src="figures/folders.png" width="300"/>
</p>

<p style="margin-bottom:25px">

Instead of keeping every document in a single place, we often organize our files using directory or folder structures. This helps us save precious time and improve our productivity. Organizing folders can also help us collaborate more effectively by ensuring that everyone can find the files they need.

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
 - TOC
{:toc}
</details>


<p style="margin-bottom: 30px"></p>

<img src="figures/folder_organizing.png" width="500" style="margin-left:30px"/>

<p style="margin-bottom: 50px"></p>

---

# Directory Hierarchies
  
A typical directory structure is composed of a **root directory** (i.e. top-level folder), **subdirectories** (i.e. subfolders), and relevant **files**.

The structure looks like this:   

```
├── Project-Folder/
|   ├── Experiment-Data/
|   |   ├── File-1
|   |   ├── File-2
|   ├── Experiment-Analysis/
|   |   ├── File-1
|   ├── Experiment-Report/
|   |   ├── File-1
|   |   ├── File-2
```

Directory names are frequently followed by a slash- / -to differentiate them from files. 
{: .note}

Question
{: .label .label-green}
<p style="margin-bottom: 10px"></p>
Which ones in this example are root directories? What about subdirectories?

# README Files and Data Dictionaries 
README files and Data Dictionaries - containing a brief description of the major folder contents, naming conventions, and data structure - are critical for transparency and reproducibility because they allow others to easily understand the contents of your directory and data without needing to ask the creator. This is especially helpful when working with a group or sharing directories with others.