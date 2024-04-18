---
type: instance
component_name: SC Work Items
component_version: tags&#x2F;2.0.3
svn_path: &#x2F;svn&#x2F;SOLUTIONCOMPONENTS&#x2F;SolutionDevelopment&#x2F;Work_Items
svn_core_folder: Work_Items
---

## `= this.component_name + " " +this.component_version`

`= this.component_name + " " +this.component_version` is an [[Work_Items]],
tag: #Work_Items

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
