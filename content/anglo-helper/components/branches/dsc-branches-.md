---
type: instance
component_name: DSC branches
component_version: 
svn_path: &#x2F;svn&#x2F;FRONT-END-PUBLIC&#x2F;SL_ANGLO&#x2F;branches
svn_core_folder: branches
---

## `= this.component_name + " " +this.component_version`

`= this.component_name + " " +this.component_version` is an [[branches]],
tag: #branches

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
