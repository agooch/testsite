---
title: Exploring Dataverse
parent: Getting Started
nav_order: 3
---
<script src="https://unpkg.com/vanilla-back-to-top@7.2.1/dist/vanilla-back-to-top.min.js"></script>
<script>addBackToTop({
  diameter: 56,
  backgroundColor: 'rgb(75, 156, 211)',
  textColor: '#fff'
})</script>

# Exploring Dataverse

## Searching Dataverse

Searching UNC Dataverse is relatively straightforward. Users may use either the search bar located above the Results list on the main page, or they can explore dataverse using the facets on the left side of the main page.

<details>
  <summary><strong>Basic Search</strong></summary><br>
  UNC Dataverse offers a search bar to help users locate data or research projects of interest. The bar is just above the Results list and functions like a typical search bar. Simply enter the keywords describing the type(s) of data you are looking for and click ‘Find’.
    <p></p>
  <img src="https://agooch.github.io/testsite/assets/images/searchgif2.gif">
</details>
<p></p>

<details>
  <summary><strong>Advanced Search</strong></summary><br>
  If the basic search bar is not providing specific search results, we recommend using the advanced search to narrow the list down. The advanced search allows users to search across individual metadata fields for relevant results at the Dataverse, Dataset, and File-level. 
  <p></p>
  To get started, click ‘Advanced Search’ beside the search bar on the main UNC Dataverse landing page. You will be redirected to a new search page.
  <p></p>
  From here you can decide to search across Dataverse, Datasets, or individual Files. Simply scroll to the section you wish to search through and then identify the field(s) you want to enter keywords into.
  <p></p>
   <img src="https://agooch.github.io/testsite/assets/images/advancedsearch1.png">
  <p></p>
  Once you’ve entered as many keywords as needed, click ‘Find’. Your results will load in a new UNC Dataverse page.
  <p></p>
  <img src="https://agooch.github.io/testsite/assets/images/advancedsearchgif1.gif">
  <p></p>
  If your search provides 0 results, we recommend removing a keyword or checking your spelling for any typos. 

</details>
<p></p>

## Browsing Dataverse

<details>
  <summary><strong>Dataverse vs. Dataset</strong></summary><br>
  A dataverse is a collection that can hold datasets as well as other dataverse collections. You can think of it as a container as depicted below.
  <p></p>
   <img src="https://agooch.github.io/testsite/assets/images/containerimage.png">
  <p></p>
  This permits users to organize their research in various ways.
  <p></p>
  You can search at the Dataverse level or filter down to the Dataset or File level by using the checkbox options on the far left of the UNC Dataverse page.

</details>
<p></p>

<details>
  <summary><strong>Facets</strong></summary><br>
  Facets are specific terms used to narrow down the results in the UNC Dataverse results list. You can find them on the far left of both the UNC Dataverse main page, but also within dataverses housed under UNC Dataverse. Clicking on a facet will only show those results related to the selected facet.
  <p></p>
  To remove the facet from your search, navigate to the top of the results list and click the ‘x’ beside the facet label.
  <p></p>
  <img src="https://agooch.github.io/testsite/assets/images/FacetRemove.png">
  
</details>
<p></p>

<details>
  <summary><strong>Results List</strong></summary><br>
  The results list is in the middle of the UNC Dataverse main page. This list will update every time you perform a search or select a facet. You can sort the list by clicking on the Sort button to the right.
  <p></p>
  <img src="https://agooch.github.io/testsite/assets/images/sortresults.png">
  <p></p>
  You will only see published Dataverses, Datasets, and Files in the results list. If you are the Admin, Curator, or Contributor of an unpublished draft Dataverse or Dataset, you may also see them in the results list. 
</details>
<p></p>

## Browsing a Dataset

<details>
  <summary><strong>Breakdown of Metadata</strong></summary><br>
  A dataset record within UNC Dataverse is comprised of standardized fields that contain information, or metadata, about the contents of the dataset record. 
  <p></p>
UNC Dataverse requires specific metadata fields to be populated before a dataset record can be published. These metadata fields are part of the citation metadata, as seen below. 
  <p></p>
  <img src="https://agooch.github.io/testsite/assets/images/citationmetadatablock.png">
  <p></p>
  <strong>Citation metadata</strong> are structured so users of the data within a dataset record can cite their source, thus giving credit to the original data producer(s). Within the citation metadata block you will find key information such as Author(s), Title, Date, Repository, Version, and DOI (the persistent URL of the dataset). Users can also export a data citation from the citation metadata block by selecting Cite Dataset and choosing an export format from the dropdown menu.
  <p></p>
  <strong>Domain specific metadata</strong> are also provided as part of a dataset record. These fields permit data producers the ability to further describe the contents of their dataset record. The advanced search feature allows users to narrow their search across these specific fields. In addition, any information entered in domain specific metadata fields is also automatically included in basic search results in UNC Dataverse.
  <p></p>
  <img src="https://agooch.github.io/testsite/assets/images/domainspecificmetadata.png">
  <p></p>
  <strong>File-level metadata</strong> may be included for each individual file. Unlike the domain specific metadata fields, file-level metadata describes the contents of a specific file instead of describing the dataset record. For example, a user may find information about the study conducted within the domain specific metadata fields; whereas they may learn what the contents of ‘womenssurveya.dta’ is from the file-level metadata.
  <p></p>
  <img src="https://agooch.github.io/testsite/assets/images/filelevelmetadata.png">
  
</details>
<p></p>

<details>
  <summary><strong>Contact Dataset Owner</strong></summary><br>
  When exploring a dataset, you may find that you have additional questions about the contents or availability of the data. For all dataset records within UNC Dataverse, users may click the Contact Owner button. A pop-up will appear on the page where you can write a message and send it to the dataset owner. The dataset owner will receive the inquiry through UNC Dataverse as well as through their account email.
  <p></p>
  <img src="https://agooch.github.io/testsite/assets/images/contactdatasetowner.png">
 
</details>
<p></p>

<details>
  <summary><strong>Accessing Files</strong></summary><br>
  Under the Files tab of the dataset record, users will find all data files provided by the data producer. Files are typically listed in alphabetical order; however, users may click the Sort button to sort by newest, oldest, type, size, or Z-A. UNC Dataverse automatically provides information about each file within the dataset record. This information includes file type, file size, number of downloads, and an MD5 checksum. If a data producer provides file-level metadata for a file, it will also show in the Files section.
  <p></p>
To download a single file, click the arrow icon to the right of the filename. Select an option from the ‘Download Options’ section of the dropdown menu. We typically recommend users to download the file in its original file format. In some instances, UNC Dataverse will create preservation formats of the data and alternative file formats will be available to download. This is particularly useful if you do not have access to the required statistical software to use the original file format. Please note that not all data files in UNC Dataverse are available in multiple formats. It depends on the original file format provided by the data producer.
  <p></p>
To download multiple files, or all files, within a dataset record, click on the checkbox next to the desired files. Alternatively, click the checkbox at the top of the file list and click ‘select all # files in this dataset’. Next, click the ‘Download’ dropdown menu at the top right of the files list. Choose ‘Original Format’. UNC Dataverse will create a zip that includes all files selected within that record. 
  <p></p>
There is a size limit for the zip files created by UNC Dataverse. If the total download size is larger than 1GB, you will be prompted to exclude larger files from the download. In this case you will need to download the larger files individually. 
 
</details>
<p></p>

<details>
  <summary><strong>Terms of Use & Creative Commons Licensing</strong></summary><br>
  Each dataset has its own Terms of Use which can be customized by the dataset owner. As a UNC Dataverse user, you should review the Terms of Use of the dataset record you are interested in downloading files from. These terms will outline any requirements for downloading, citing, and/or re-using the data files within a dataset record. 
  <p></p>
  <a href="https://creativecommons.org/about/cclicenses/" target="_blank">Creative Commons licenses</a> are assigned to a dataset record before publication and define what users may do with the contents of that record. There are six different licenses and one public domain license (CC0). Creative commons licenses can be used in combination with custom terms of use.
  <p></p>
Some dataset records will use the default CC0 license and have no additional terms of use; however, it is still a best practice to cite any data sources you may use in your own research and/or discuss in future publications. To learn more about licensing and data citations, please visit the <a href="https://dataverse.org/best-practices/dataverse-community-norms" target="_blank">Dataverse Community Norms</a>.
  
</details>
<p></p>

<details>
  <summary><strong>Versions</strong></summary><br>
  A versions tab exists for every dataset record. This tab provides a list of all published versions of a dataset with information that describes how each dataset version differs from its predecessor.
  <p></p>
Version history is important to track changes to dataset records over time. These changes can range from updates to metadata fields to deletion of obsolete files and upload of new files. The version history also notes the date a new version was published and the entity that published the new version.
  <p></p>
  <img src="https://agooch.github.io/testsite/assets/images/versionstab.png">
 
</details>
<p></p>

<details>
  <summary><strong>Data Explorer</strong></summary><br>
  The Data Explorer is a feature of UNC Dataverse that permits users to browse publicly available data files in particular formats within the Dataverse platform. Through Data Explorer, users can see every variable within a data file and review summary statistics, create cross tabulations, and download subsets from that file. Review the video below to learn more about Data Explorer within UNC Dataverse. 
  <p></p>
  [Video]
  
</details>
<p></p>

<details>
  <summary><strong>Document Previewer</strong></summary><br>
  UNC Dataverse also has a built-in document previewer. This feature allows users to read through TXT and PDFs within the Dataverse platform. Simply navigate to the text document you wish to preview, click the download icon, and choose ‘Read Document’ from the dropdown menu.   
</details>
<p></p>

<details>
  <summary><strong>Request Access to Restricted Data</strong></summary><br>
  Some data will not be completely accessible via the UNC Dataverse platform. These files are considered restricted and will have a red lock icon beside the file image within the dataset record. Instead of a download option, users will be able to ‘request access’ to a restricted file.
  <p></p>
  <img src="https://agooch.github.io/testsite/assets/images/restrictedaccessrequest.png">
  <p></p>
  You must be logged in with your UNC Dataverse account in order to request access. Once logged in, you may click Request Access and fill in the form to submit a request to the data owner. The data owner will be notified via email by UNC Dataverse and can grant or deny the access request. 
  <p></p>
  Please make sure to read the entirety of the dataset record before requesting access, as some data producers will include a Data Use Agreement and further instructions for requesting access to their data. These instructions may require you to email a completed data use agreement to the data owner outside of UNC Dataverse. 
  <p></p>
  When a data owner has granted you permission to access their data, you will receive an email from UNC Dataverse indicating the file is available for download. Simply log back into UNC Dataverse and navigate to the file via either the link provided in the email, or via the Notifications tab under your User Dashboard. 
  <p></p>
  User permissions may be revoked at any time by the data owner. 
</details>
<p></p>
