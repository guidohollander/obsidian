---
type: instance
component_name: SC Reallocate Payment
component_version: tags&#x2F;2.0.1
svn_path: &#x2F;svn&#x2F;SOLUTIONCOMPONENTS&#x2F;SolutionDevelopment&#x2F;Reallocate_Payment
svn_core_folder: Reallocate_Payment
---

## `= this.component_name + " " +this.component_version`

`= this.component_name + " " +this.component_version` is an [[Reallocate_Payment]],
tag: #Reallocate_Payment

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
