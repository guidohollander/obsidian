---
type: instance
component_name: SC Account
component_version: tags/2.4.0
svn_path: /SOLUTIONCOMPONENTS/SolutionDevelopment/Account/tags/2.4.0/SC%20Account
svn_core_folder: Account
---

## `= this.component_name + " " +this.component_version`

`= this.component_name + " " +this.component_version` is an [[SC Account]],
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

## List of jira issues

JIRA:SDTSS-1200
JIRA:SDTSS-1201
JIRA:SDTSS-1203
JIRA:SDTSS-1204


``=this.component_name``


