---
solution: mts
project folder: c:/repo/mts_grenada/
repo: https://svn.bearingpointcaribbean.com/svn/mts_grenada/trunk
customer_code: gd_ird
---
# IRD Grenada

![[Pasted image 20230228191731.png|200]]

## evaluation test
`= contains(this.customer,"aia_ssb")`
`= this.file.name`

## implementations
```dataview
TABLE WITHOUT ID link(file.link, Title) AS "Title", creation_date  from "anglo-helper/implementations"
where contains(customer_code,this.customer_code)
```

## components


![[draaiboek - script]]