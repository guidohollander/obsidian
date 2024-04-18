---
type: instance
component_name: DSC Interim Stabilization Levy
component_version: tags&#x2F;2.0.0
svn_path: &#x2F;svn&#x2F;MTS_ANGLO&#x2F;Interim_Stabilization_Levy
svn_core_folder: Interim_Stabilization_Levy
---

## `= this.component_name + " " +this.component_version`

`= this.component_name + " " +this.component_version` is an [[Interim_Stabilization_Levy]],
tag: #Interim_Stabilization_Levy

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
