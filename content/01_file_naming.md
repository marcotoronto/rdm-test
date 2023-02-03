---
layout: default
title: File Naming
nav_order: 2
---

# File Naming

## Why is file naming important?

Creating a well-organized hierarchy of files with clear naming conventions is an important part of improving your research process. This is especially important if you are working with large data sets and complex output files or coordinating with multiple people at multiple institutions. There are many ways to structure your folders, and multiple naming conventions you can use. The key is **consistency**. Make your file names descriptive, and include information about dates and versioning. The best practice is to consult with your lab or with your co-workers to develop a naming schema that everyone is willing to follow consistently.
<br>
<br>


<span style="color:grey"> 
What do you think about the following file names?  

  - 10_data 2.txt
  - figure 1.png
  - final revision.docx
  - Lily's schedule&plan 2022Jul9.xlsx 
</span>
<br>

<span style="color:grey"> 
This is what happens when you do not have effective naming conventions:
</span>
<br>
<br>
<img src="figures/comic.gif" alt="comic" width="500"/>

<br>

<span style="color:grey"> 
Are these names better?  

- better-filenames.txt
- 003_raw-data_2022-07-09.txt
- fig01_scatterplot-talk-length-vs-interest.png
- 20220709_interview-script_v01.docx
</span>
<br>
<br>
<br>

## Follow 3 principles to make good file names!
<br>
*1*{: .circle .circle-blue} Machine-Readable

*2*{: .circle .circle-red} Human-Readable  

*3*{: .circle .circle-yellow} Plays Well With Default Ordering 
<br>
<br>

## *1*{: .circle .circle-blue} Machine-Readable 
<p align="center">
<img src="figures/machine-reading.png" alt="machine" width="500"/>
</p>

Goal
{: .label .label-green }
    - The characters in file names should be able to handled by all computer systems.
    - The names should be brief and easily searchable. 

Only use the following:

- Alphanumeric characters (alphabetic characters and Arabic numerials)  
<br>

<p align="center">
<img src="figures/alphanumeric.png" alt="alphanumeric" width="200"/>
</p>

<br>

- Element delimiters: **_(underscore)**  
- Word delimiters (within an element): **-(dash)** and/or **capitalize** the first letter of each word (camel case)
<br>
<br>
**e.g. [element 1]\_[element 2]\_[WordPart-WordPart-WordPart]_[element 3].txt**
<br>
<br>

Avoid spaces and special characters, such as: ~ ! @ # $ % ^ & * ( ) ` ; : < > ? . , [ ] { } ' "  \|   <img src="figures/say-no.png" alt="say-no" width="19">
{: .warn}


- Make file names 32 characters or less

- If you decide to abbreviate the elements with 2- or 3-letter codes (e.g. project 1 = P1, mouse = "MUS"), make sure these are well documented
- Keep case sensitivity in mind - Machine searching for files named "Scan" would not find files named "scan"

<br>

## Exercise
Let's try improve the file names!
    
Pick your favourite file name and make it more machine-readable! 

![](figures/cakes-exmaple.jpeg)

[//]: # (activity link: https://bit.ly/rdmactivity)

<br>
<br>
<br>


## *2*{: .circle .circle-red} Human-Readable

<p align="center">
<img src="figures/human-reading.jpg" alt="human" width="500"/>
</p>

Goal
{: .label .label-green }

    - The file names should provide concise information.  
    - They are easily understandable to anyone who may access them in future.

- Provide *essential information* concisely in the file name
  - Ideally 3 elements, 5 max.
  - Avoid complex hierarchical folder structures.
- Consider putting authors' names in the file name.
  - Put family names first followed by first names or initials.
- Write down your naming convention pattern and **document it** in your README file.
  - e.g. My file naming convention is [SA-MPL-EID]\_[YYYY-MM-DD]\_[###]_[status].[txt]
  - Define acronyms, abbreviations and codes

<br>
<br>

## *3*{: .circle .circle-yellow} Plays Well With Default Ordering 

Goal
{: .label .label-green }

    - The names should start with the element that is used to order the files.
    - Keep versions at the end.

Decide the beginning of the file name according to how you want to sort and search for your files
- When using a sequential numbering system, use **leading zeros** to make sure files sort in sequential order. e.g. 001, 002, 010, 011 ....100,101 ...
- Order elements from general to specific to make searching easier
Versions: should be used as the last element
- Use ISO 8601 standard for dates: **YYYYMMDD** or **YYYY-MM-DD** 
- For version numbers, use at least two digits with a leading zero (e.g. v0)
- Version types (e.g. _raw, _processed, _composite)

## Exercise

Your lab has a spectrometer that is measuring thermal emissions once a day for a year for your experiment. There are three people who take that measurement in the lab. 
    
Please create a file naming convention for these .hdf5 files to reflect what you have learned about file naming in today's session and post your example on Padlet.

<br>

<br>

<p align="center">
<img src="figures/congrats.jpg" width="500"/>
</p>

<br>

## **Congrats!**
### Now you know how to organize files with your own file naming conventions! As long as your names are clear and consistent, you are good to move forward!

<br>
<br>
<br>

## References
- https://datacarpentry.org/rr-organization1/01-file-naming/index.html
- https://authors.library.caltech.edu/103626/1/FileNamingConventionWorksheet_Caltech.pdf
- http://www.exadox.com/en/articles/file-naming-convention-ten-rules-best-practice
- https://datamanagement.hms.harvard.edu/collect/file-naming-conventions