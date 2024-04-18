---
type: instance
component_name: DSC Business Licence
component_version: tags&#x2F;2.0.1
svn_path: &#x2F;svn&#x2F;MTS_ANGLO&#x2F;Business_Licence
svn_core_folder: Business_Licence
---

## `= this.component_name + " " +this.component_version`

`= this.component_name + " " +this.component_version` is an [[Business_Licence]],
tag: #Business_Licence

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
