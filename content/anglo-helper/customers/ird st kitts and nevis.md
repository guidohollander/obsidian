---
solution: mts
project folder: c:/repo/mts_skn/
repo: https://svn.bearingpointcaribbean.com/svn/mts_skn/trunk
customer_code: skn_ird
---
# IRD Saint Kitts & Nevis

![[Pasted image 20230228191644.png|200]]

## evaluation test
`= contains(this.customer,"aia_ssb")`
`= this.file.name`

## implementations
```dataview
TABLE WITHOUT ID link(file.link, Title) AS "Title", creation_date  from "anglo-helper/implementations"
where contains(customer_code,this.customer_code)
```

## components