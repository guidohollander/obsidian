---
type: instance
component_name: SC Person Registration
component_version: tags&#x2F;2.2.0
svn_path: &#x2F;svn&#x2F;SOLUTIONCOMPONENTS&#x2F;SolutionDevelopment&#x2F;Person_Registration
svn_core_folder: Person_Registration
---

## `= this.component_name + " " +this.component_version`

`= this.component_name + " " +this.component_version` is an [[Person_Registration]],
tag: #Person_Registration

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
