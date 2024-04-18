---
type: instance
component_name: DSC GST
component_version: tags&#x2F;2.2.1
svn_path: &#x2F;svn&#x2F;MTS_ANGLO&#x2F;GST
svn_core_folder: GST
---

## `= this.component_name + " " +this.component_version`

`= this.component_name + " " +this.component_version` is an [[GST]],
tag: #GST

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
