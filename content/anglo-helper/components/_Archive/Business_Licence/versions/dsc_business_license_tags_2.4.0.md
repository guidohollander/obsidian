
---
type: instance
component_name: DSC Business license
component_version: tags/2.4.0
svn_path: /MTS_ANGLO/Business_Licence/tags/2.0.1/DSC%20Business%20license
svn_core_folder: Business_Licence
---

## `= this.component_name + " " +this.component_version`
tag: #DSC_Business_license

`= this.component_name + " " +this.component_version` is an [[DSC Business license]]],

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