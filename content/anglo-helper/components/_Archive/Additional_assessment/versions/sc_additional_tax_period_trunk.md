---
type: instance
component_name: SC Additional tax period
component_version: 2.2.0
svn_path: /SOLUTIONCOMPONENTS/SolutionDevelopment/Additional_assessment/tags/2.2.0/SC%20Additional%20Tax%20period
svn_core_folder: Additional_assessment
---
## `= this.component_name + " " +this.component_version`
tag: #SC_Additional_tax_period

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