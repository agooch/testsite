---
title: Create a Dataverse
parent: Getting Started
nav_order: 4
---
<script src="https://unpkg.com/vanilla-back-to-top@7.2.1/dist/vanilla-back-to-top.min.js"></script>
<script>addBackToTop({
  diameter: 56,
  backgroundColor: 'rgb(75, 156, 211)',
  textColor: '#fff'
})</script>

# Create a Dataverse

If you would like to view a step-by-step walkthrough of creating and customizing a project dataverse, please see our tutorial here.  
<p></p>
To share your research, you must first create a project dataverse within UNC Dataverse. After logging into UNC Dataverse, scroll down to the ‘Add Data’ button on the main page. Select ‘New Dataverse’. 
<p></p>
<img src="https://agooch.github.io/testsite/assets/images/createdataverse.png">
<p></p>
You will be taken to the New Dataverse page. UNC Dataverse requires the following information to create a new dataverse:
<p></p> 
<ul>
  <li>Dataverse Name:</li> 
  <li>Identifier: (the shortname used for the URL of the dataverse)</li>
  <li>Category:</li> 
  <li>Email:</li>
</ul>
<p></p>
A description of the dataverse can also be provided on this page. This will help users better understand the contents and purpose of your dataverse. 
<p></p>
<img src="https://agooch.github.io/testsite/assets/images/createdataversegif.gif">
<p></p>
<a name="metadatablocks"></a>Once you have filled in this information, scroll down to the Metadata Fields section. Here you can decide which metadata fields will be available to you when creating a dataset within your dataverse. You may choose the default ‘Use metadata fields from UNC Dataverse’ or select one or more of the metadata option(s) listed. If you are uncertain which metadata option is appropriate for your dataverse, you can click ‘[+] View Fields’ to see what each metadata option includes. 
<p></p>
<img src="https://agooch.github.io/testsite/assets/images/metadataoptions.png">
<p></p>
Beneath the Metadata Fields section is the Browse/Search Facets section. As the administrator of your project dataverse, you can determine which facets appear on the left side of your dataverse. These facets are available to users to refine the results list and can aid them in locating the most relevant datasets, dataverses, or files within your project dataverse.
<p></p>
The ’Use browse/search facets from UNC Dataverse’ is enabled by default, but you may deselect this option and instead choose from the list of facets underneath.
<p></p>
To remove an already selected facet, click on the facet under the ‘Selected’ list and then select the <- to remove it from the ‘Selected’ list.
<p></p>
<img src="https://agooch.github.io/testsite/assets/images/removefacetgif.gif">
<p></p>
To add a facet, select the desired facet(s) in the list on the left and then click the -> to move it to the ‘Selected’ list. The selected facets will now show up on the left side of your dataverse.
<p></p>
<img src="https://agooch.github.io/testsite/assets/images/addfacetgif.gif">
<p></p>
Once you have added all the necessary information and selected your metadata and facet customizations, click on ‘Create Dataverse’. Congratulations! You’ve successfully created your first dataverse within UNC Dataverse.
<p></p>
You may further customize your project dataverse by selecting ‘Edit’ and choosing from the dropdown menu. Additional customizations include setting permissions levels, assigning roles to other users or groups, adding design elements such as logos and project links, developing dataset templates, and creating guestbooks to track user metrics. 
<p></p>
<img src="https://agooch.github.io/testsite/assets/images/editdataverse.png">
<p></p>
 
## General Information

This page should look familiar to users who just created their project dataverse. The general information page is where dataverse admins may update the description of their dataverse, the contact information, and make changes to the metadata and facet selections that will display on their dataverse page. Dataverse admins may return to this page at any time to make updates as needed. 

## Themes & Widgets

Admin may customize the look of their project dataverse using the Themes & Widgets interface. 
<p></p>
From the Themes tab, users may upload a logo for their project dataverse, choose a different background color, link color, and text color for the header, include a tagline and URL to a project website, and add a footer image. This helps brand the project dataverse and differentiate it from the UNC Dataverse.
<p></p>
<img src="https://agooch.github.io/testsite/assets/images/themes.png">
<p></p>
The Widgets tab provides HTML code that you can embed within your project website. You may select the Dataverse Search Box HTML code to generate an embedded search box in your website that links back to results in your project dataverse, or you may select the Dataverse Listing HTML code which embeds your project dataverse results list within your website. This is another useful mechanism for branding your project dataverse and making it more accessible to users exploring your project website.

## Permissions
Dataverse allows admins to set permission and access levels to limit how users may interact with their project dataverse. Permission levels may be changed at any time; however, please keep in mind that if you change your permissions to be more stringent, you will need to review your users/groups to determine if previously approved users should retain their active role(s). To learn more about roles and users/groups, please see <a href="https://agooch.github.io/testsite/docs/gettingstarted/createdataverse.html#usergroup">Permissions – Users/Groups</a>.
<p></p> 
To edit permissions, select ‘Edit Access’ under the Permissions section. You will be prompted to answer two questions in the pop-up window. 
<p></p>
<details>
  <summary><strong>Who can add to this dataverse?</strong></summary><br>
  Dataverse provides you with varying levels of access in the options beneath this question:
  <p></p> 
  <strong>Option 1: Anyone adding to this dataverse needs to be given access.</strong>
  <p></p> 
The Admin of this dataverse is the only person permitted to add new sub-dataverses and datasets. If another user would like to add to this dataverse, the Admin will need to assign a role to that user. This is the most restricted level of access to a dataverse and is recommended for users creating personal or individual project dataverses, or groups creating a dataverse that will only require approved users to contribute content. Odum Institute Data Archive recommends most dataverses use this option.
  <p></p> 
  <strong>Option 2: Anyone with a Dataverse account can add sub dataverses.</strong>
  <p></p> 
Users with a Dataverse account are permitted to contribute sub dataverses to this project dataverse. They will be assigned the role of Admin to any sub dataverse they create and can then add datasets to their sub dataverse.
  <p></p> 
  <strong>Option 3: Anyone with a Dataverse account can add datasets.</strong>
  <p></p>
Users with a Dataverse account may only contribute datasets to the dataverse. Users who create new datasets will be assigned as a Dataset Creator and will only be able to edit their datasets. This is a particularly useful designation for groups who seek contributions, but only within the scope of their project. It is also the recommended permission level for journals who require data sharing as part of their publication process.
  <p></p>
  <strong>Option 4: Anyone with a Dataverse account can add sub dataverses and datasets.</strong>
  <p></p> 
This is a combination of options 2 and 3. Users are permitted to create sub dataverses and add datasets to those sub dataverses, or they may contribute to the project dataverse directly by adding new datasets there. This gives your contributors more options in how they share and organize the data and supporting materials within your project dataverse; however, it opens your dataverse to contributions from anyone with a Dataverse account.
</details>
<p></p>
<details>
  <summary><strong>When a user adds a new dataset to this dataverse, which role should be automatically assigned to them on that dataset?</strong></summary><br>
  The second question works in combination with the first. These options determine what roles are assigned to your users once they are permitted access to create new content. The two designations are Contributor or Curator. UNC Dataverse provides a description of the types of actions each role can make.
  <p></p>
  <strong>Contributors</strong> can edit metadata, upload files, and edit files, edit Terms, enable a guestbook, and submit their datasets for review. Contributors are not able to publish a dataset within your project dataverse. Instead, they can submit the dataset for review and an Admin or Curator may publish the dataset. See Submit for Review & Return to Author Feature (link) for more information.
  <p></p> 
The Contributor role is the recommended choice for those dataverses using <strong>Option 3: Anyone with a Dataverse account can add datasets</strong>. This combination permits Admins the ability to review all dataset records before publication, make any necessary edits, and then approve or deny the publication.
  <p></p> 
  <strong>Curators</strong> can edit metadata, upload files, and edit files, edit Terms, enable and create a guestbook, enable file restrictions and grant file access, edit permissions, assign roles, and publish a dataset record. Curators can do most things within a dataverse and is a good designation to assign to project team members responsible for sharing data such as project managers, data archivists, or research assistants.
  <p></p>
The Curator role is the recommended choice for those dataverses using <strong>Option 1: Anyone adding to this dataverse needs to be given access</strong>. This permits the Admin the ability to grant access to additional team members who will assist in making the research data available within the project dataverse.
  <p></p> 
Please keep in mind that once a role is assigned it can be removed at any time by an Admin or Curator. To learn more about assigning and revoking roles, please see <a href="https://agooch.github.io/testsite/docs/gettingstarted/createdataverse.html#usergroup">Permissions – Users/Groups</a>.   
</details>
<p></p>

### Users/Groups
<a name="usergroup"></a>
This section of the Permissions page allows Admin and Curators to assign roles to other UNC Dataverse users, granting them the ability to perform certain actions within their project dataverse.
<p></p>
To assign a user a role within your project dataverse, click the ‘Assign Roles to Users/Groups’ button. A pop-up window will appear where you may enter a username into the Users/Groups field.
<p></p>
<img src="https://agooch.github.io/testsite/assets/images/assignrole.png">
<p></p>
Find the user or group in the drop-down and select their name. Under Role select the role that is most appropriate for this user. When you click on a role, UNC Dataverse will provide a description of all actions that role type may take within a dataverse. Once you have decided on the appropriate role, select ‘Save Changes’. The pop-up window will disappear, and the Users/Groups section will update to reflect the new user and their assigned role. 
<p></p>
Please note that only users with existing UNC Dataverse accounts can be assigned permissions. If you wish to add someone who does not currently have a UNC Dataverse account, please request that they <a href="https://agooch.github.io/testsite/docs/gettingstarted/createaccount.html" target="_blank">Create an Account</a>. 
<p></p>
To remove a user from the Users/Groups and revoke their role, simply locate the user in the Users/Groups section and click on ‘Remove Assigned Role’. The user will no longer have access to the project dataverse. 
<p></p>
<img src="https://agooch.github.io/testsite/assets/images/removerole.png">
<p></p>

### Roles

The final section of the Permissions page is the Roles section. This is a list of all existing Roles within a dataverse that describes each action that role may take. We recommend using the pre-existing roles available; however, if you are interested in creating a custom role for your dataverse, please contact Odum Institute Data Archive first to ensure that the role will function as intended.

## Groups

Enter text here

## Dataset Template

Enter text here

## Dataset Guestbooks

<details>
  <summary><strong>Create Guestbook</strong></summary><br>
  Descriptive text about this section.  
</details>
<p></p>

<details>
  <summary><strong>Enable/Disable Guestbook</strong></summary><br>
  Descriptive text about this section.  
</details>
<p></p>

<details>
  <summary><strong>Generate Guestbook Report</strong></summary><br>
  Descriptive text about this section.  
</details>
<p></p>

## Featured Dataverses

Enter text here
