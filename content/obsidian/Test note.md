---
tags:
type: idea
---

23202302011616
Status: #idea

# {{type}}





# ReferencesCaptains log!

Fuck that, I bumped into a site called [[Hollander Consulting]]. And you know what?

![[New note used for reference#^e9e5fd]]


hollanderconsulting
![[New note used for reference#^e9e5fd]]


Today I worked on JIRA:SDTSS-4114

```jira-search
resolution = Unresolved AND assignee = currentUser() AND status = 'In Progress' order by priority DESC
```

```jira-search  
query: status = 'In Progress' order by priority DESC  
columns: key, -key, type, -type, reporter, -reporter, created, -created  
```

```dataviewjs  
const projectKey = 'SDTSS'  
const sprint = await $ji.macro.getActiveSprint(projectKey)  
const chartData = await $ji.chart.getWorklogPerDay(projectKey, sprint.startDate, sprint.endDate)  
renderChart(chartData, this.container)  
```

JIRA:-SDTSS-4114  
- [x] QA validation  
- [ ] Load to production  
- [ ] Client Validation


Todays notes
```dataview 
list from "anglo-helper"
```
