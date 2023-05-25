---
layout: default
title: Advanced Deposit
parent: Deposit in UBC Dataverse Collection
nav_order: 2
---

<p style="margin-top:25px">
<img src="figures/work-in-progress.png" width="600"/>
</p>

<details open markdown="block">
  <summary>
    Table of Content
  </summary>
  {: .text-delta }
 - TOC
{:toc}
</details>

Looking for a cheat sheet? Check out our <a href="https://osf.io/5u4f3" target="_blank">one-pager</a>!
{: .note }


---

# Recommended File formats 

*Any kind of file* can be uploaded to Dataverse, but extra functionality is supported for some filetypes:

## Tabular data
{: .no_toc}

Tabular data (Stata, SPSS, Excel, R, & CS) is <b>normalized to .tab</b> format on upload--a non-proprietary archival format that a variety of programs can read. See bit.ly/2VmKTGF for more about this process. 

<b>Normalization</b> is important for long-term preservation of digital data. The deposited files can be downloaded in multiple formats, always including the original. 
You will choose the format from a list when you click Download. 
(Picture)
{: .note}

In Dataverse, tabular normalization also allows you to perform statistical data exploration and visualization *right in your browser*. Click the Explore button in the Files tab to see what it can do! 
(Picture)

Learn more about the TwoRavens Data Explorer application at https://bit.ly/3uo2iSL.
{: .note}


## Compressed Files (.zip, tar)
{: .no_toc}

Compressed files are the preferred method for uploading large datasets or many files to Dataverse.

Zip files are automatically extracted on upload, and the contents will appear as a list under the Files tab. Folder structure and file hierarchy within the zip file are maintained on extraction (as of DV version 4.11).

**Geospatial shapefiles and Astronomy data (FITS)** also have special functionality (such as previews) in Dataverse. You can learn more about data licensing in the [Geomatics Deposit Workshop](05-4_Geomatics_Deposit.md)
{: .note}

<br>

# File Size

Dataverse is not intended to handle Big Data. Current file size limits are:
- For upload: 3 Gb per file (unlimited number of files in a dataset)
- For tabular normalization: 500 Mb per file (tabular files over this size will remain in their original format, e.g. Excel)

While there is no cap on the overall number of files that you can upload. If your data exceeds 10 Gb, please contact research.data@ubc.ca to discuss the best repository options, as we have other solutions.
{: .note}

<br>

# Access Control

Sensitive files can be <b>Restricted</b> or <b>Embargoed</b> so they are not freely available to download. Files can either be fully restricted, or set up so users can send access requests to the contact email for review.

### To restrict, unrestrict, or embargo a file:
{: .no_toc}

<p style="margin-top:25px;margin-left:30px">
<img src="figures/borealis-restrict-files.png" width="500"/> </p> 

In the popup window, you may *describe the conditions of use* or *license for this file* in the Terms of Access box. 

<p style="margin-top:25px;margin-left:30px">
<img src="figures/borealis-restrict-access.png" width="500"/> </p> 

Check the `Enable access request` box to allow users to send the contact person an email asking for permission to download a restricted file. Click `Save Changes` to finish.

Files can also be unrestricted if the terms change--for example, once an embargo period has passed. 

<br>

# Version control

Every change made to a dataset—adding files, editing metadata, etc—is saved as a new version of the dataset. This allows you to track the change history of the project, which can be viewed under the Versions tab. This is useful if you need to roll back to a previous version, or find out who made what changes and when.

<p style="margin-top:25px;margin-left:30px">
<img src="figures/borealis-version-control.png" width="500"/> </p> 

<br>

# Where can UBC Dataverse datasets be discovered?
Data deposited in UBC Dataverse Collection is indexed by, and integrated with, many services on the Web, including:

- <a href="http://datacite.org" target="_blank">**DataCite**</a>: This major global non-profit organization provides DOls, indexes the metadata for every object assigned a DOl, and offers a search interface for those objects at <https://search.datacite.org>.
- <a href="https://orcid.org/" target="_blank">**ORCID**</a>: Adding your ORCID to your dataset metadata links it to your body of work, ensuring researchers can easily find all vour publications.
- <a href="https://www.frdr.ca/docs/en/searching/" target="_blank">**FRDR**</a>: Canada's Federated Research Data. Repository. FRDR provides a centralized platform for searching the contents of dozens of Canadian data repositories.
- **Google/Google Scholar/Google Data**: Though data in Dataverse is not automatically searchable by Google Scholar, the UBC Dataverse has been customized so its deposited datasets are findable using this popular search tool.
- <a href="https://www.openaire.eu" target="_blank">**OpenAIRE**</a>
- **Any APIs**


<br>

# Licenses and Terms

You have control over how your data can be used. Dataverse allows for a variety of licenses and terms of use:

- Built-in License Templates—can be selected at da-taset creation, and changed at any time. These auto-matically apply the right information about the li-cense to the dataset’s metadata.Apply a template to your dataset by selecting one from the drop-down menu under Dataset Template, at the top of the New Dataset creation form.
- Custom: One-size-fits-all licenses don’t suit every dataset, you can create customized terms and con-ditions of use.To customize terms:Any dataset saved in Draft or Published form will have a Terms tab on the dataset page. Click Edit Terms Require-mentsand fill in the form with your Terms of Use and/or Terms of Access for Restricted files. If you need help creating a custom license, contact research.data@ubc.ca




