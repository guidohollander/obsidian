---
type: instance
component_name: SC Licence Assessment
component_version: tags&#x2F;2.0.0
svn_path: &#x2F;svn&#x2F;SOLUTIONCOMPONENTS&#x2F;SolutionDevelopment&#x2F;Licence_Assessment
svn_core_folder: Licence_Assessment
---

## `= this.component_name + " " +this.component_version`

`= this.component_name + " " +this.component_version` is an [[Licence_Assessment]],
tag: #Licence_Assessment

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
