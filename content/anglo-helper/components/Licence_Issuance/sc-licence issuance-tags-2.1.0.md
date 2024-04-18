---
type: instance
component_name: SC Licence Issuance
component_version: tags&#x2F;2.1.0
svn_path: &#x2F;svn&#x2F;SOLUTIONCOMPONENTS&#x2F;SolutionDevelopment&#x2F;Licence_Issuance
svn_core_folder: Licence_Issuance
---

## `= this.component_name + " " +this.component_version`

`= this.component_name + " " +this.component_version` is an [[Licence_Issuance]],
tag: #Licence_Issuance

Used in the following implementations:
```dataview
table customer
 ,implementation_name as "implementation"
 ,component_version  as "version"
 ,solution
 ,country  
from "anglo-helper/implementations"
where contains(file.outlinks,this.file.link)
```


## List of jira issues
