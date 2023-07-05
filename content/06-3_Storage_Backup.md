---
layout: default
title: Storage & Backup 
parent: Data Management Plans
nav_order: 3
---

<p style="margin-top:25px">
<img src="figures/work-in-progress.png" width="600"/>
</p>

<p style="margin-top:25px;margin-left:30px;margin-bottom:25px"></p>

<details open markdown="block">
  <summary>
    Table of Content
  </summary>
  {: .text-delta }
 - TOC
{:toc}
</details>


---
# Storage and Backup
{: .no_toc}

Data storage and security considerations are essential aspects of managing research data and should be mapped out in your DMP. The following good practices are recommended for you to implement in your project and mapped out in your DMP.

## Estimate the Storage Space
At the beginning of any project, researchers should *estimate the required storage space* during the active phases of your project. This estimation should take into consideration factors such as file versioning, backups, and potential data growth. In deciding where to store your data, ensure that you understand your *organization's policies and infrastructure for data storage and backups*. This includes considering the most appropriate storage system for sensitive data and what institutional policies apply to its handling.

## Retain the Raw Data
An essential step in data storage is to retain an original, unedited copy of your raw data file. This file should be locked in a read-only format, which requires copying the file to make changes. It is imperative that you do not overwrite this file so you have a fail-safe to return to should something go awry.

## Follow the 3-2-1 Backup Rule 

``"I have saved my data. Is it safe?"``

The short answer is no &nbsp;<img src="figures/say-no.png" align="center" width="15"/> &nbsp;. Data can be lost for a number of reasons including:
- hardware failures software failures
- viruses or hacking
- power failures
- natural disasters
- human error
- theft of equipment

<p style="margin-top:25px;margin-left:30px;margin-bottom:25px">
<img src="figures/shock.png" width="250"/>
</p>

<img src="figures/thumbs-up.png" align="center" width="25"/> &nbsp;The best practice  is to have **three copies** stored in at least **two locations** (in case of a failure at one location), **one of them off-site**. Even if each location is a cloud-based server, do not store all of your backups on the same cloud-based server as a precaution. Cloud-based servers do have internal redundancies to prevent the loss of data, but *utilizing multiple services* is a good practice in the off-chance of a catastrophic loss.

<p style="margin-top:25px;margin-left:30px;margin-bottom:25px">
<img src="figures/hard-disk.jpeg" width="300"/>
</p>

## Bakcup All 
The backup copies should include all pertinent files, *including your README files*. Backing up the entire package of stored data helps ensure that everything can be understood in the future.

<p style="margin-top:25px;margin-left:30px;margin-bottom:25px">
<img src="figures/compressed-files.png" width="150"/>
</p>

## Update the Backups Regularly

Even if you are backing up your data, remember to check that the backups are working and that the data is accessible. *Every time you edit your working copy, the backup copies should be updated*! A backup copy from 6 months ago that contains none of your recent data is practically useless. 

Having a well-defined data backup schedule is essential, with **automatic backups** being the most ideal. 

Certain data storage options at UBC, such as TeamShare or Home Drive, already have automatic backup features in place. Consider leveraging these existing backup mechanisms to ensure data integrity and reliability.
{: .note }

## Team Access
To facilitate collaboration and teamwork, it is crucial to outline how your collaborators or research team will access, modify, contribute, and work with the data.

<p style="margin-top:25px;margin-left:30px;margin-bottom:25px">
<img src="figures/network.jpg" width="300"/>
</p>

## Security 
Safeguarding your research data throughout its lifecycle is paramount. Provide a brief overview of the security measures, controls, procedures, and processes that will be implemented to protect your data. This includes outlining the **security controls** that will be in place, as well as any specific **privacy considerations**. 

<p style="margin-top:25px;margin-left:30px;margin-bottom:25px">
<img src="figures/encryption.jpg" width="300"/>
</p>

For comprehensive guidance on security and privacy planning for research at UBC, you can refer to the resources available at <a href="https://arc.ubc.ca/planning-research-security-and-privacy" target="_blank">UBC ARC's website</a>.
{: .note }

By addressing these aspects and incorporating them into your data management plan, you can ensure the efficient and secure handling of your research data from storage and collaboration to backup and security measures.
