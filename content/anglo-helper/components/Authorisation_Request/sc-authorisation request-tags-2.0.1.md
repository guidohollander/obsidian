---
type: instance
component_name: SC Authorisation Request
component_version: tags&#x2F;2.0.1
svn_path: &#x2F;svn&#x2F;SOLUTIONCOMPONENTS&#x2F;SolutionDevelopment&#x2F;Authorisation_Request
svn_core_folder: Authorisation_Request
---

## `= this.component_name + " " +this.component_version`

`= this.component_name + " " +this.component_version` is an [[Authorisation_Request]],
tag: #Authorisation_Request

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
