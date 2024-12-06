---
# Insert this YAML header (including the opening and closing ---) at the beginning of the document and fill it out accordingly

# We use this key to indicate the last reviewed date [manual entry, use MM/DD/YYYY]
# Uncomment and populate the next line accordingly
date: 12/06/2024

# We use this key to indicate the last modified date [automatic entry]
date-modified: last-modified

# Do not modify
lang: en
language: 
  title-block-published: "Last reviewed"
  title-block-modified: "Last modified"

# Title of the document [manual entry]
# Uncomment and populate the next line accordingly
title: TU Delft data storage

# Brief overview of the document (will be used in listings) [manual entry]
# Uncomment and populate the next line and uncomment "hide-description: true".
description: In this document we provide an overview of the data storage options that are accessible to TU Delft staff (researchers, research staff, etc.)
hide-description: true

# Authors of the document, will not be parsed [manual entry]
# Uncomment and populate the next lines accordingly
#author_1:
#author_2:

# Maintainers of the document, will not be parsed [manual entry]
# Uncomment and populate the next lines accordingly
maintainer_1: Joao Guimaraes
#maintainer_2:

# To whom reach out regarding the document, will not be parsed [manual entry]
# Uncomment and populate the next line accordingly
#corresponding:

# Meaningful keywords, newline separated [manual entry]
# Uncomment and populate the next line and list accordingly
#categories: 
# - 
# - 

---

Storing your data in a secure location is a key element of a successful project with a data component. TU Delft recommends using a [TU Delft Project Data Storage](https://tudelft.topdesk.net/tas/public/ssp/content/detail/service?unid=846ebb16181c43b5836c063a917dd199&from=03aa10b9-c5aa-4e0a-80b1-28ee7ab383df) for storing research data. This solution enables secure data storage and facilitates access to your data to other researchers from your research group during the duration of the project. It also allows TU Delft researchers to have access to the data after your project is completed. 

Furthermore, TU Delft offers various data storage options. A complete list is available in [TU Delft Storage Finder](https://storagefinder.tudelft.nl/), where you can find the data storage options that best match your use case(s).

Some data storage options may require a request via the [Service desk](https://tudelft.topdesk.net/tas/public/ssp/content/detail/service?unid=f359caaa60264f99b0084941736786ae&from=feffb489-e1f9-49cd-8223-53ae0b70b609) (TU delft login required). There you can also find a list of all the data storage options that you may get access upon request.


# TU Delft's DCC Take on Data Storage Options

In this section we list a selection of data storage options provided within and outside TU Delft that we recommend based on the knowledge we gathered by supporting TU Delft researchers and other staff members.

For each option you can find advice on the data storage options's purpose, tips on why you should use it, and

### TU Delft Project Data Storage (U:)
- **Purpose:** to have your (research) data secured, backed up and have it shared with colleagues within TU Delft.
- **Tips**:
   - Recommended option for storing the data linked to your project throughout its duration.
   - The option to store and document your data to keep it findable and accessible to your colleagues after the completion of your project.
   - Accessible via Microsoft Windows' File Explorer. PowerShell or Command Prompt, and via SSH tunneling. For MacBook Users...
- **Access:** granted upon request via [Service Desk](https://tudelft.topdesk.net/tas/public/ssp/content/detail/service?unid=846ebb16181c43b5836c063a917dd199&from=03aa10b9-c5aa-4e0a-80b1-28ee7ab383df) with storage capacity from 250GB up to 5TB. or a request of more than 5TB, your request will be forwarded to the Faculty ICT Manager.

For more information check [here](https://storagefinder.tudelft.nl/package/2/).


<details>

<summary>Short-term Solutions</summary>

### SURFDrive
- **Purpose:** short-term storage option alternative to **TUDelft Project Data Storage (U:)** in getting a backed-up and shareable storage space for the first subsets of data that will allow us to estimate the computational demands of the project.
   - Not suited for long-term storage
-**Access:** Available to everyone Dutch Academic Education-wise, offering upfront up to 1TB of storage that can be partially synchronized locally in your computer using [Desktop client](https://servicedesk.surf.nl/wiki/display/WIKI/Desktop+client+login)

For more information check in [Storage Finder](https://storagefinder.tudelft.nl/package/3/) or [SURF](https://www.surf.nl/en/services/surfdrive).


### DelftBlue
- **Purpose:** short-term alternative to **TUDelft Project Data Storage (U:)** in getting a backed-up and shareable storage space for the first subsets of data that will allow us to estimate the data preprocessing-related computational demands of the project.
    - Not suited for long-term storage
- **Access:** any TU Delft Student has access to 30GB in /home directory (backed up) and 5TB in /scratch directory (not backed up). For more it is possible to apply for Delftblue project storage via Topdesk -> Research support -> IT for researchers -> delftblue supercomputer -> request project storage.


### HuggingFace
- **Purpose:** short-term alternative to **TUDelft Project Data Storage (U:)** in getting shareable storage space for the first subsets of data that will allow us to estimate the AI-related computational demands of the project. Potentially advantageous for feeding data onto [RunPod](https://huggingface.co/RunPod)
-**Access:** everyone with a log in account can upload up to 500GB worth of data public or privately following their free plan (HF documentation states [300GB](https://huggingface.co/docs/hub/en/repositories-recommendations) but it is not up to date).
    - Interesting long-term option to promote the dataset once the data becomes public