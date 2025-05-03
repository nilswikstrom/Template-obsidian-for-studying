---
banner: "[[Image bank/kendrick-watching.jpg]]"
icon: 🎯
---
> [!tldr]+ Links
> [[Uni Courses]]
> [[Inbox]]

> [!tldr]+ Tasks
> ```tasks
> tags include "CourseName"
> ```

> [!check] Active projects
> ```dataview
> CALENDAR deadline
> FROM #project or #assignment or #report 
> WHERE status = "active"
> SORT deadline ASC
> ```

> [!example]- Holding Tank
> ```dataview
> TABLE course as "Course", deadline as "Deadline"
> FROM #school and -"_templates"
> WHERE status = "holding-tank"
> SORT deadline ASC
> ```

___