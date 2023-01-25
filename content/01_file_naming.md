---
layout: default
title: File Naming
nav_order: 2
---

# File Naming

## NO

- 10_data 2.txt
- figure 1.png
- final revision.docx
- Lily's schedule&plan 2022Jul9.xlsx

## Yes

- better-filenames.txt
- 003_raw-data_2022-07-09.txt
- fig01_scatterplot-talk-length-vs-interest.png
- 20220709_interview-script_v01.docx


## Three principles for file names:

1. Machine-readable: the characters can be handled by all computer systems, and the names are brief and easily searchable

2. Human-readable: the names provide concise information and are easily understandable to anyone who may access them in future

3. Plays well with default ordering: start with the element that is used to order the files and keep versions at the end


### Machine-readable

- Only use the following:
  - Alphanumeric characters (examples)
  - Element delimiters: **_(underscore)**
  - Word delimiters (within an element): **- (dash)** and/or **capitalize** the first letter of each word (camel case)
  - e.g. [element 1]_[element 2]_[WordPart-WordPart-WordPart]_[element 3].txt
- Avoid spaces and special characters, such as: ~ ! @ # $ % ^ & * ( ) ` ; : < > ? . , [ ] { } ' " | 
- Make file names 32 characters or less
- If you decide to abbreviate the elements with 2- or 3-letter codes (e.g. project 1 = P1, mouse = "MUS"), make sure these are well documented 
- Keep case sensitivity in mind - machine searching for files named "Scan" would not find files named "scan"

### Human-readable

- Provide **essential information** concisely in the file name
  - Ideally 3 elements, 5 max.
  - Avoid complex hierarchical folder structures.
- Consider putting authors' names in the file name
  - Put family names first followed by first names or initials.
- Write down your naming convention pattern and **document it** in your README file
  - e.g. My file naming convention is [SA-MPL-EID]_[YYYY-MM-DD]_[###]_[status].[txt]
  - Define acronyms, abbreviations, and codes


### Plays well with default ordering 

- Decide the beginning of the file name according to how you want to sort and search for your files
  - When using a sequential numbering system, use **leading zeros** to make sure files sort in sequential order. e.g. 001, 002, 010, 011 ....100,101 ...
- Order elements from general to specific to make searching easier
- Versions: should be used as the last element
  - Use ISO 8601 standard for dates: **YYYYMMDD** or **YYYY-MM-DD** 
  - For version numbers, use at least two digits with a leading zero (e.g. v0)
  - Version types (e.g. _raw, _processed, _composite)



## References

    https://datacarpentry.org/rr-organization1/01-file-naming/index.html

    https://authors.library.caltech.edu/103626/1/FileNamingConventionWorksheet_Caltech.pdf

    http://www.exadox.com/en/articles/file-naming-convention-ten-rules-best-practice

    https://datamanagement.hms.harvard.edu/collect/file-naming-conventions