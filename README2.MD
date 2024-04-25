# CCG Tabular Editor BPA  <img src="https://user-images.githubusercontent.com/90718398/134408155-30f92295-4866-47a4-b8b8-d497dad0be8d.png" width="60" height="60"> 
![image](https://user-images.githubusercontent.com/90718398/134407347-93a98c8e-6997-40bb-9f03-5d7772c9cb58.png) 

Tabular Editor provides an intuitive hierarchical view of every object in your Tabular Model metadata. Columns, Measures and Hierarchies are arranged in display Folders by default. You can edit properties of one or more objects, by (multi)selecting them in the tree. A DAX Editor with syntax highlighting lets you easily edit the expressions of Measures, Calculated Columns and Calculated Tables.

Tabular Editor 2 (TE2) is the original open source version. This is free to use and will continue to be supported. Tabular Editor 3 (TE3) is the commercial product version. It has a 30 day trial afterwards a paid license is required. This introduction covers TE2. 

CCG created a standard set of "best practices" stored in this repository to use when developing a tabular model. Please follow the directions below to download Tabular Editor and load these best practices into the application.

## Downloading Tabular Editor 2

[Download and Install Tabular Editor here](https://www.sqlbi.com/tools/tabular-editor/)

## Setup

**1. CONNECT TO A MODEL:**

   Open Tabular Editor > File > Open > from DB > Dropdown Menu from "Local Instance" (make sure you have your model open locally)
    
   Or
    
   Open PBI file you want to connect to Tabular Editor > External Tools > Tabular Editor
   
   <br/>
    
**2. SET PREFERENCES**
                
   Open Tabular Editor > File > Preferences > Check "Allow unsupported Power BI features (experimental)" 
   
   <br/>
    
**3.  CCG BEST PRACTICE RULES**

   Copy the code snippet from [LoadRules Folder](LoadRules) > Paste it into the advanced scripting window in Tabular Editor > Run > Exit out of Tabular Editor and restart to commit the new rules.
    
    
    
   
