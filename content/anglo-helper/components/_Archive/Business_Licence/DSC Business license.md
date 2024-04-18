---
type: class
component_name: DSC Business license
is_domain_specific: false
---
## `= this.component_name`
tag: #DSC_Business_license

#nieuwetag


### Versions of `= this.component_name`

```dataview
list from ""
where file.folder = this.file.folder + "/versions"
```

## Used by the following implementations / customers / 

```dataview
table without id 
link(file.name) as "version"
,link(file.inlinks.file.frontmatter.implementation_name) as "implementation"
,file.inlinks.file.frontmatter.customer_code as "customer"
from "anglo-helper/components"
flatten file
where file.folder = this.file.folder + "/versions"
sort file.inlinks.file.frontmatter.implementation_name asc
```


