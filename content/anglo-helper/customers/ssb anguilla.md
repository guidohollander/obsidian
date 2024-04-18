---
solution: mbs
project folder: c:/repo/mbs_anguilla_21/
repo: https://svn.bearingpointcaribbean.com/svn/mbs_anguilla/trunk
customer_code: aia_ssb
---
# SSB Anguilla

![[Pasted image 20230228191348.png|200]]

## front matter:
this.file.name: `= this.file.name`
this.customer_code: `= this.customer_code`


## evaluation test
`= contains(this.customer,"aia_ssb")`
`= this.file.name`

## implementations
```dataview
TABLE WITHOUT ID link(file.link, Title) AS "Title", creation_date  from "anglo-helper/implementations"
where contains(customer_code,this.customer_code)
```
## components


