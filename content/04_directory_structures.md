---
layout: default
title: Directory Structures
nav_order: 7
---

# Why are structured directories important?
{: .no_toc }

<p style="margin-top:15px"></p>

Now, let’s pretend that you store everything on your computer in one single folder – some of us are probably known to use our desktops for this. Imagine how long it would take you to find data you collected on a specific day a few years ago. 

<p style="margin-top:25px;margin-left:30px">
<img src="figures/folders.png" width="300"/>
</p>

<p style="margin-bottom:25px"></p>

Instead of keeping every document in a single place, we often organize our files using directory or folder structures. This helps us save precious time and improve our productivity. Organizing folders can also help us collaborate more effectively by ensuring that everyone can find the files they need.

<p style="margin-bottom: 20px"></p>

Looking for a cheat sheet? Check out our <a href="https://osf.io/5br6a" target="_blank">one-pager</a>!
{: .note}

<br>


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

Usually, we separate data, analysis, and reports into stand-alone subdirectories under the project's root directory. The structure looks like this:   

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


Directory names are frequently followed by a slash ```/``` to differentiate them from files. 
{: .note}

Question
{: .label .label-green}
<p style="margin-bottom: 10px"></p>
Which ones in this example are root directories? What about subdirectories?

<br>

# Organizing your directory structure

There are several things to consider when you are deciding on the organization (structure) of your project directory. 

* Consider organizing your directory such that you clearly delineate segments of your projects to improve searchability. 

* You need to strike a balance between your folders being too deep or too shallow.
    
    * Too deep: this will lead to many clicks before your get to the file you need. Further, a file path that has too many folders can max out the character limit.

      * The length of the OneDrive root folder (e.g. C:\users\meganb\OneDrive - Contoso) + the relative path of the file (up to 400 chars) cannot be more than 520 characters [(Microsoft 2023)](https://support.microsoft.com/en-us/office/restrictions-and-limitations-in-onedrive-and-sharepoint-64883a5d-228e-48f5-b3d2-eb39e07630fa)
      * In the Windows API, the maximum length for a path is 260 characters [(Microsoft 2024)](https://learn.microsoft.com/en-us/windows/win32/fileio/maximum-file-path-limitation?tabs=registry)
      * Would you like to click through all these folders for a csv file? `Z:\1232\New_Projects_shared\2000\2000_0889\site_a_name of the site payment\payment\year_4\payment_year4.csv` (by the way, is this good folder/file naming?)

    * Too shallow: this will lead to too many different subdirectories under your root directory. Again, this can lead to many clicks (and subsequent back clicks) before finding the correct file. 
* When working with a team, consider implementing limitations to sensitive files.

  * Consider making some files "read only"

  ```
  -rwxr-xr-x    1 andrewli  staff   7113 22 Jul 11:56 01_file_naming.md
  -rwxr-xr-x    1 andrewli  staff   6390 22 Jul 11:57 02_file_formats.md
  -rwxr-xr-x    1 andrewli  staff   6664 11 Jul 09:46 03_create_readme.md
  -r--r-xr-x    1 andrewli  staff   6664 11 Jul 09:46 VERY_IMPORTANT_DO_NOT_EDIT.md
  ```

* Be consistent with how you organize your folders and files! It becomes confusing if you mix this organization. Choose what makes sense for your project or stick to what the team/lab has already implemented. Noting your decisions in a README file or a Data Manual makes a big difference!

```
This example folder is organized such that the different experiments are the top folders

example_project 
├─ experiment_1
│  ├─ data.csv
│  ├─ data_cleaning.R
│  └─ model.R
├─ experiment_2
│  └─ ...
└─ experiment_3 
   └─ ...
```


```
This example folder is organized such that the different components are the top folders 

another_example
├─ data
│  ├─ data_exp_1.csv
│  └─ data_exp_2.csv
├─ cleaning
│  ├─ clean_exp1.R
│  └─ clean_exp2.R
└─ visualization
   └─ ...
```

* Folder naming should follow good naming practices:
  * Machine readable
  * Human readable
  * Check out our workshop on [file naming](https://ubc-library-rc.github.io/rdm/content/01_file_naming.html) for more information. 

<br>

# README Files and Data Dictionaries 

README files and Data Dictionaries - containing a brief description of the major folder contents, naming conventions, and data structure - are critical for <b>transparency and reproducibility</b> because they allow others to easily understand the contents of your directory and data without needing to ask the creator. This is especially helpful when working with a group or sharing directories with others.

Click <a href="https://ubc-library-rc.github.io/rdm/content/03_create_readme.html#how-do-i-create-a-readme" target="_blank">here</a> to review how to create a README file!
{: .note}

## Two types of files needed to store all metadata

1. ```README``` file which resides in our **root directory** and elaborates on the contents of our folder structure, discusses how, where, and who did the data collection.
2. ```DATA-DICTIONARY``` file that resides in our **data directory** and elaborates on how our data variables are defined and described.

The structure looks like this:

```
├── Project-Folder/
|   ├── README.md                  <--
|   ├── Experiment-Data/
|   |   ├── DATA-DICTIONARY.md     <--
|   |   ├── File-1
|   |   ├── File-2
|   ├── Experiment-Analysis/
|   |   ├── File-1
|   ├── Experiment-Report/
|   |   ├── File-1
|   |   ├── File-2
```


<br>

### Naming
{: .no_toc}
```Readme files``` and ```data dictionaries``` should be the first things you look at when looking at any directory or folder, as this is your guide to its contents. Therefore, these files should be in all caps, so they really stand out.


### Format
{: .no_toc}
```Readme files``` and ```data dictionaries``` should be written in <b>plain text</b>, for this will ensure that the files describing your project can be opened on any computer. You will often see readme files called ```README.txt``` or ```README.md```.

<p style="margin-bottom: 30px"></p>

<br>

## Exercise
{: .no_toc}

<p style="margin-bottom: 30px"></p>

<img src="figures/folders2.png" width="200" style="margin-left:30px"/>

<p style="margin-bottom: 30px"></p>

Say you’re in BIOL 116 and you’re working on your research project. You have files that looked like the following before submitting our final assignment:

```
Pither_20210921_BIOL116RProject_ph-data.csv
Pither_20210922_BIOL116RProject_ph-data.csv
Pither_20210923_BIOL116RProject_ph-data.csv
Pither_20210924_BIOL116RProject_ph-data.csv
Pither_BIOL116RProject_Analysis_V0.xlsx
Pither_BIOL116RProject_Figure-freq-plot_V0.png
Pither_BIOL116RProject_Figure-linear-reg_V0.png
Pither_BIOL116RProject_Figure-linear-reg_V1.png
Pither_BIOL116RProject_Lab-report_V0.docx
Pither_BIOL116RProject_Lab-report_V1.docx
Pither_BIOL116RProject_Lab-report_V2.docx
Pither_BIOL116RProject_Lab-report_V3.docx
```



Let's put them into structured folders! Please copy the template and use it for your exercise:

```
├── example/
|   ├── example/           
|   |   ├── example

```

Feel free to refer to the example that we saw earlier:

```
├── Project-Folder/
|   ├── _README.md                  
|   ├── Experiment-Data/
|   |   ├── _DATA-DICTIONARY.md            
|   |   ├── File-1
|   |   ├── File-2
|   ├── Experiment-Analysis/
|   |   ├── File-1
|   ├── Experiment-Report/
|   |   ├── File-1
|   |   ├── File-2
```

[//]: # (activity link: https://bit.ly/rdmactivity)

## Tools 
{: .no_toc}

There are some useful tools to help you design your folder structures:

* You paste a link to your GitHub repo URL to generate a project tree or create it from scratch: [https://woochanleee.github.io/project-tree-generator/](https://woochanleee.github.io/project-tree-generator/)

* Design a diagram for potential file tree with more options: [https://t.co/AQzht2i703](https://t.co/AQzht2i703)

* In your terminal you can use `tree` to generate a tree like structure. Windows and Linux have this function, but you will need to install for Mac.

<br>

# Congrats!
{: .no_toc }

You know how to create structured directories for files now! Go ahead and organize your important personal or team files! 


<br>

---


### Sources
{: .no_toc }
- New York University Libraries. <https://guides.nyu.edu/data_management/file-org>
- Copeland, C., Pither, J., Vis-Dunbar, M. (2021). Procedures and Guidelines. <https://ubco-biology.github.io/Procedures-and-Guidelines/>
- <https://pixabay.com>
- <https://www.pexels.com>

---

Need help?
{: .label .label-blue }
  Please reach out to `research.data@ubc.ca` for assistance with any of your research data questions.
