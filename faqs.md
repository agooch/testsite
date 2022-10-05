---
title: Frequently Asked Questions
has_children: false
nav_order: 2
---
<script src="https://unpkg.com/vanilla-back-to-top@7.2.1/dist/vanilla-back-to-top.min.js"></script>
<script>addBackToTop({
  diameter: 56,
  backgroundColor: 'rgb(75, 156, 211)',
  textColor: '#fff'
})</script>

# Frequently Asked Questions

Our FAQ may help you with a few of your more pressing questions. We've broken them down into two categories: General and Polices & Data Requirements

## General

<details>
  <summary><strong>What is UNC Dataverse?</strong></summary><br>
  
  UNC Dataverse is the University of North Carolina at Chapel Hill's data repository. It is available to all UNC-CH faculty, students, and staff, as well as to the general public for sharing and preserving research data and data related materials. UNC Dataverse is managed and maintained by <a href="https://odum.unc.edu" target="_blank">The Odum Institute</a>.
  <p></p>
  Users are encouraged to explore the tool using our <a href="https://demo-dataverse.odum.unc.edu/dataverse/root" target="_blank">UNC Demo Dataverse</a>, our tutorials (link), as well as this user guide. If you have further questions, please contact The Odum Institute Data Archive at <a href="mailto:odumarchive@unc.edu">odumarchive@unc.edu</a>. 
</details>
<p></p>
<details>
  <summary><strong>What is Dataverse?</strong></summary><br>
  
  Dataverse is an open source web-based platform for sharing, preserving, and finding research data. It was developed by the <a href="https://www.iq.harvard.edu/product-development" target="_blank">Institute for Quantitative Social Science at Harvard University</a> and has been enhanced and adopted by many institutions across the world. For a brief overview of Dataverse's history and features, please view the video below, or visit <a href="https://dataverse.org/" target="_blank">The Dataverse Project</a>. 
</details>
<p></p>
<details>
  <summary><strong>Dataverse vs. Dataset</strong></summary><br>
  
  A dataverse is a collection that can hold datasets as well as other dataverse collections. You can think of it as a container as depicted below. 
  <img src="https://agooch.github.io/testsite/assets/images/containerimage.png">
  This permits users to organize their research in various ways. For examples of how you can organize your data within UNC Dataverse, please see the Dataverse Organization Examples in the UNC Demo Dataverse. ADD LINK
</details>
<p></p>
<details>
  <summary><strong>Who manages UNC Dataverse?</strong></summary><br>
  
  UNC Dataverse is managed and maintained by <a href="https://odum.unc.edu">The Odum Institute for Research in Social Science</a> at the University of North Carolina at Chapel Hill. 
  <p></p>
  Systems development and technical support is provided by the <a href="https://odum.unc.edu/rdis/" target="_blank">Odum Institute Research Data and Information Systems</a> team. RDIS also offers custom Dataverse deployment and external tool development for integration with the Dataverse platform. External tools can range from metadata exploration and data analysis to data visualization applications and machine learning. To learn more about these services, please contact <a href="mailto:Jonathan_Crabtree@unc.edu">jonathan_crabtree@unc.edu</a>.  
  <p></p>
  Data management planning, archiving, curation, and training is provided by the <a href="https://odum.unc.edu/archive/" target="_blank">Odum Institute Data Archive</a>. UNC Dataverse support services are also offered in customizable packages that meet your project needs. Quotes are available upon request. We recommend setting up a brief, free consultation to discuss the needs of your project and your project timeline. To learn more about our services, please see <a href="https://odum.unc.edu/archive/#archive5" target="_blank">UNC Dataverse Support Services</a>.    
</details>
<p></p>
<details>
  <summary><strong>Why should I deposit my research data in UNC Dataverse?</strong></summary><br>
  
   Sharing and preserving research data is an important part of the research lifecycle. By depositing your data in a data repository like UNC Dataverse, you are ensuring that your research is accessible and reusable well into the future. Not only is this beneficial for your own research needs, but it permits others to build upon your work to advance scientific inquiry and discovery. 
  <p></p>
   The U.S. Office of Science and Technology Policy has released various memos (<a href="https://obamawhitehouse.archives.gov/sites/default/files/microsites/ostp/ostp_public_access_memo_2013.pdf" target="_blank">2013</a>, <a href="https://www.whitehouse.gov/wp-content/uploads/2022/08/08-2022-OSTP-Public-Access-Memo.pdf" target="_blank">2022</a>) charging federal funding agencies with developing and honing their <a href="https://odum.unc.edu/archive/#archive3" target="_blank">data management and sharing policies</a> for all funded research. In order to comply with these policies, researchers must share the outputs of their research with the public in appropriate data repositories.
  <p></p>
   In addition to government mandates, research communities are quickly adopting the <a href="https://www.go-fair.org/fair-principles/" target="_blank">FAIR Principles</a> for making data Findable, Accessible, Interoperable, and Reusable.  These principles offer guidance for ensuring that data are properly preserved, described, and shared for future access and reuse. UNC Dataverse is FAIR compliant.  

</details>

## Policies and Data Requirements

<details>
  <summary><strong>What kind of data can I deposit?</strong></summary><br>
  
   UNC Dataverse accepts all types of data; however, it offers optimized preservation for certain file types such as Stata, R, SPSS, and some Excel file types. Dataverse processes these optimized preservation file types during ingest and creates a software agnostic tab-delimited version as well as an RData version of the file for long-term preservation. It also permits users the ability to explore the data within the UNC Dataverse interface. All other file types are preserved at the bit-level only.
  <p></p>
   While UNC Dataverse can preserve all file types at the bit-level, it may not be the best data repository option for certain data types. If you are uncertain if UNC Dataverse is the best data repository for your research data, please contact <a href="mailto:odumarchive@unc.edu">odumarchive@unc.edu</a> to schedule a free consultation. 

</details>
<p></p>
<details>
  <summary><strong>What are the recommended data file types I should provide?</strong></summary><br>
  
   The file formats used by researchers are often informed by individual research practices and domain-specific standards. However, to avoid risks to long-term data preservation, access, and use that can arise from software obsolescence, the Odum Institute Data Archive recommends that data files be submitted in formats that are widely adopted, non-proprietary, free of external software dependencies, and well-documented.
  <p></p>
   The following file formats are supported with optimized preservation:
  <p></p>
   <table>
      <tr>
        <td><strong>IBM SPSS</strong></td>
        <td>.por OR .sav</td>
        <td>Versions 7 to 22</td>
      </tr>
      <tr>
        <td><strong>Stata</strong></td>
        <td>.dta</td>
        <td>Versions 4 to 15</td>
      </tr>
      <tr>
        <td><strong>R</strong></td>
        <td>.RData</td>
        <td>Versions 1 to 3</td>
      </tr>
      <tr>
        <td><strong>Excel</strong></td>
        <td>.xlsx</td>
        <td>.xls is not supported</td>
      </tr>
      <tr>
        <td><strong>Comma-separated values</strong></td>
        <td>.csv</td>
        <td>Limited support</td>
      </tr>
    </table> 
  <p></p>
   The following file formats for document files such as README files, codebooks/data dictionaries, instruments, and methodology reports are recommended:
  <p></p>
    <table>
      <tr>
        <td><strong>Text</strong></td>
        <td>.txt</td>
      </tr>
      <tr>
        <td><strong>Adobe Portable Document Format</strong></td>
        <td>.pdf/ua OR .pdf/a OR .pdf</td>
      </tr>
    </table>
  
</details>
<p></p>
<details>
  <summary><strong>Are there file size limits?</strong></summary><br>
  
   UNC Dataverse accepts self-deposit uploads of 2 GB per file. For individual files over 2GB in size, please contact <a href="mailto:odumarchive@unc.edu">odumarchive@unc.edu</a> for assistance or alternative storage solutions.
  <p></p>
   If your total file size is over 1TB, please contact <a href="mailto:odumarchive@unc.edu">odumarchive@unc.edu</a> for a quote for additional storage or to learn about alternative storage solutions. 

</details>
<p></p>
<details>
  <summary><strong>How many files can I upload into UNC Dataverse?</strong></summary><br>
  
   Currently there is no limit for how many files you may upload into UNC Dataverse; however, if your total file size is more than 1TB, please contact <a href="mailto:odumarchive@unc.edu">odumarchive@unc.edu</a> for a quote for additional storage or to learn about alternative storage solutions. 
</details>
<p></p>
<details>
  <summary><strong>Can I control access to my data?</strong></summary><br>
  
   Text here
</details>
<p></p>
<details>
  <summary><strong>Are there any fees for depositing data into UNC Dataverse?</strong></summary><br>
  
   Text here
</details>
<p></p>
<details>
  <summary><strong>May I share sensitive data within the UNC Dataverse?</strong></summary><br>
  
   Text here
</details>
<p></p>
<details>
  <summary><strong>If I leave my university or institution, can I transfer my UNC Dataverse account to my new institutional account?</strong></summary><br>
  
   Text here
</details>
