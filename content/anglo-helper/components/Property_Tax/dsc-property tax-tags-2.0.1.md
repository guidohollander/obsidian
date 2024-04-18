---
type: instance
component_name: DSC Property Tax
component_version: tags&#x2F;2.0.1
svn_path: &#x2F;svn&#x2F;MTS_ANGLO&#x2F;Property_Tax
svn_core_folder: Property_Tax
---

## `= this.component_name + " " +this.component_version`

`= this.component_name + " " +this.component_version` is an [[Property_Tax]],
tag: #Property_Tax

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
