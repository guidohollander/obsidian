---
type: instance
component_name: SC Property Registration
component_version: tags&#x2F;1.2.10
svn_path: &#x2F;svn&#x2F;SOLUTIONCOMPONENTS&#x2F;SolutionDevelopment&#x2F;Property_Registration
svn_core_folder: Property_Registration
---

## `= this.component_name + " " +this.component_version`

`= this.component_name + " " +this.component_version` is an [[Property_Registration]],
tag: #Property_Registration

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
