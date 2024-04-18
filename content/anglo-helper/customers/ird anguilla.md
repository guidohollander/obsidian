---
solution: mts
project folder: c:/repo/mts_anguilla_21/
repo: https://svn.bearingpointcaribbean.com/svn/mts_anguilla/trunk
customer_code: aia_ird
---
# IRD Anguilla
![[Pasted image 20230228190942.png|200]]

## implementations
```dataview
TABLE WITHOUT ID link(file.link, Title) AS "title", release_date  from "anglo-helper/implementations"
where contains(customer_code,this.customer_code)
sort release_date desc
```
## component classes of last implementation
```dataview
table without id link(file.outlinks.file.frontmatter.component_name) as "Component class"
from "anglo-helper/implementations"
where contains(customer_code,this.customer_code)
SORT file.link DESC LIMIT 1
```