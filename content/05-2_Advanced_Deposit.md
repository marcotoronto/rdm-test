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

Tabular data (Stata, SPSS, Excel, R, & CS) is <b>normalized to .tab</b> format on upload--a non-proprietary archival format that a variety of programs can read. 

Normalization is important for long-term preservation of digital data. 
The deposited files can be downloaded in multiple formats, but always including the original. 
{: .note}

In Dataverse, tabular normalization also allows you to perform statistical data exploration and visualization *right in your browser*. Click the `Data Explore` button to see what it can do. 

<p style="margin-top:25px;margin-left:30px">
<img src="figures/borealis-download.png" width="500"/> </p> 



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

Every change made to a dataset—adding files, editing metadata, etc—is saved as a new version of the dataset. This allows you to track the change history of the project, which can be viewed under the `Versions` tab. This is useful if you need to roll back to a previous version, or find out who made what changes and when.

<p style="margin-top:25px;margin-left:30px">
<img src="figures/borealis-version-control.png" width="500"/> </p> 



<br>

# Sharing Data

## Where can UBC Dataverse datasets be discovered?

Data deposited in UBC Dataverse Collection is indexed by, and integrated with, many services on the Web, including:

- <a href="http://datacite.org" target="_blank">**DataCite**</a>: This major global non-profit organization provides DOls, indexes the metadata for every object assigned a DOl, and offers a search interface for those objects at <https://search.datacite.org>.
- <a href="https://orcid.org/" target="_blank">**ORCID**</a>: Adding your ORCID to your dataset metadata links it to your body of work, ensuring researchers can easily find all vour publications.
- <a href="https://www.frdr.ca/docs/en/searching/" target="_blank">**FRDR**</a>: Canada's Federated Research Data. Repository. FRDR provides a centralized platform for searching the contents of dozens of Canadian data repositories.
- **Google/Google Scholar/Google Data**: Though data in Dataverse is not automatically searchable by Google Scholar, the UBC Dataverse has been customized so its deposited datasets are findable using this popular search tool.
- <a href="https://www.openaire.eu" target="_blank">**OpenAIRE**</a>
- **Any APIs**


## Social Media
Spread the word about your research and improve your altmetrics by sharing your linked data on social media!

Dataverse provides a `Share` button for
1. each dataverse
2. each dataset

<p style="margin-top:25px;margin-left:30px">
<img src="figures/borealis-social-media.png" width="500"/> </p> 

This button gives you the option to create a post with a link to your data on Facebook, Twitter, Linkedin.

## Linking to your dataset

There are 2 main ways to direct people to your dataset:

### *1*{: .circle .circle-blue} &nbsp;DOI 
{: .no_toc}

A **permanent DOI (Digital Object Identifier)** is assigned to the dataset by Borealis when the first Draft is created. Once the dataset is **Published**, anyone can use the DOI link to find it. While the dataset is still **unpublished**, the DOI can only be used by Dataverse *account holders* with permission to view that Dataverse.

Use DOIs in citations, on your personal or research group website, in publications, and anywhere else you want to be sure the link to your
data wireman stable over time

Click <a href="bit.ly/2VJtHdM" target="_blank">here</a> for more information about UBC DOIs.

### *2*{: .circle .circle-red} &nbsp;Private URL
{: .no_toc}

A **temporary link** for use with **unpublished** data. The dataset can only be seen by those who have the link, and users *do not need a Dataverse account*. Great for giving pre-publication access to journals, reviewers, and collaborators.

To create a Private URL, click `Private URL`. The generated URL can be access from this location until the dataset is published, so you can copy it again and again as needed.

<p style="margin-top:25px;margin-left:30px">
<img src="figures/borealis-private-url.png" width="500"/> </p>


<br>

## Licenses and Terms

You have control over how your data can be used. Dataverse allows for a variety of licenses and terms of use.

### **Built-in License Templates** 
{: .no_toc}

Templates can be selected at dataset creation, and changed at any time. These automatically apply the right information about the license to the dataset’s metadata.

<p style="margin-top:25px;margin-left:30px">
<img src="figures/borealis-templates.png" width="500"/> </p>

### **Custom license**
{: .no_toc}

One-size-fits-all licenses don’t suit every dataset. You can create customized terms and conditions of use. 

To customize terms: 

<p style="margin-top:25px;margin-left:30px">
<img src="figures/borealis-edit-terms.png" width="500"/> </p>

If you need help creating a custom license, contact research.data@ubc.ca.




