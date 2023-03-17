---
layout: default
title: Folder Organizing
nav_order: 6
---

# Why is a structured directory important?
Now, let’s pretend that you store everything on your computer in one single folder – some of us are probably known to use our desktops for this. Imagine how long it would take you to find data you collected on a specific day a few years ago. 

Instead of keeping every document in a single place, we often organize our files using directory or folder structures. This helps us save precious time and improve our productivity. Organizing folders can also help us collaborate more effectively by ensuring that everyone can find the files they need.

<p style="margin-bottom: 30px"></p>

<img src="figures/folder_organizing.png" width="500" style="margin-left:30px"/>

<p style="margin-bottom: 50px"></p>

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

Question
{: .label .label-green}

<p style="margin-bottom: 10px"></p>

Which ones in this example are root directories? What about subdirectories?

# README Files and Data Dictionaries 
README files and Data Dictionaries - containing a brief description of the major folder contents, naming conventions, and data structure - are critical for transparency and reproducibility because they allow others to easily understand the contents of your directory and data without needing to ask the creator. This is especially helpful when working with a group or sharing directories with others.

Click [here](content/03_create_readme.md) to review how to create a README file!
{: .note}

## We need three files to store all metadata:
1. A ```_README``` file which resides in our **root directory** and elaborates on the contents of our folder structure.
2. A ```_README``` file that resides in our **data directory** and discusses some of the particulars of the how, where, and who did the actual data collection.
3. A ```_DATA-DICTIONARY``` file that also resides in our data directory and elaborates on how our data is stored and organized.

Visually, the stucture looks like this:

```
├── Project-Folder/
|   ├── _DATA-DICTIONARY.txt   <--
|   ├── _README.txt            <--
|   ├── Experiment-Data/
|   |   ├── _README.txt        <--
|   |   ├── File-1
|   |   ├── File-2
|   ├── Experiment-Analysis/
|   |   ├── File-1
|   ├── Experiment-Report/
|   |   ├── File-1
|   |   ├── File-2

```

```_README``` should exist in at least two locations: the root directory and the data directory.
{: .note}




### Naming
```_README``` and ```_DATA-DICTIONARY``` should be the first things you look at when looking at any directory or folder, as this is your guide to its contents. These files should
- Be prepended with an underscore "_". This will push these files to the top of the directory for easy access;
- Be in all caps, so they really stand out.


### Format
```_README``` and ```_DATA-DICTIONARY``` files should be written in plain text, for this will ensure that the files describing your project can be opened on any computer. You will often see readme files called ```_README.txt``` or ```_README.md```.
{: .note}

<br>

---


### Sources
{: .no_toc }
- New York University Libraries. <https://guides.nyu.edu/data_management/file-org>
- <https://pixabay.com>
- <https://www.pexels.com>
