---
type: instance
component_name: SC Revenue voucher
component_version: tags&#x2F;2.0.2
svn_path: &#x2F;svn&#x2F;SOLUTIONCOMPONENTS&#x2F;SolutionDevelopment&#x2F;Revenue_voucher
svn_core_folder: Revenue_voucher
---

## `= this.component_name + " " +this.component_version`

`= this.component_name + " " +this.component_version` is an [[Revenue_voucher]],
tag: #Revenue_voucher

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
