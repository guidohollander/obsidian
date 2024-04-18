---
type: instance
component_name: SC Application Parameters
component_version: tags&#x2F;2.3.0
svn_path: &#x2F;svn&#x2F;SOLUTIONCOMPONENTS&#x2F;SolutionDevelopment&#x2F;Application_Parameters
svn_core_folder: Application_Parameters
---

## `= this.component_name + " " +this.component_version`

`= this.component_name + " " +this.component_version` is an [[Application_Parameters]],
tag: #Application_Parameters

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
