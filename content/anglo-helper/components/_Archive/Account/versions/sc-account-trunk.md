---
type: instance
component_name: SC Account
component_version: trunk
svn_path: /SOLUTIONCOMPONENTS/SolutionDevelopment/Account/trunk/SC%20Account
svn_core_folder: Account
---

## `= this.component_name + " " +this.component_version`
tag: #SC_Account

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