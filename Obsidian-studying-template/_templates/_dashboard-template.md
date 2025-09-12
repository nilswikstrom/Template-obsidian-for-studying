---
banner: "[[Image bank/kendrick-watching.jpg]]"
icon: 🎯
---
> [!columns-2] Columns
> > [!tldr]+ Links
> > [[Uni Courses]]
> > [[Inbox]]
> > [[semester-link]]
> > [Studentweb - FHS](https://fsweb.no/studentweb/)
> > [Wiseflow](https://europe.wiseflow.net)
> > [webpage](url)
> > [webpage](url)
> 
> > [!example] Active Subjects
> > ## [[subject-1]]
> > ## [[subject2]]
> > ## [[subject-3]]

> [!bug] Next deadlines
> ```tasks
> not done
> sort by scheduled
> hide created date
> hide backlink
> hide tags
> hide task count
> hide postpone button
> show edit button
> limit 3

> [!columns-3] Columns
> > [!todo]+ Upcoming tasks
> > ```tasks
> > (status.type is TODO) OR (status.type is IN_PROGRESS)
> > # (tags include "elektronikk") OR (tags include "telekommunikasjon") OR (tags include "transmisjon")
> > (tags include assignment) OR (tags include report) OR (tags include lab) OR (tags include test)
> > (due after 2025-01-01) OR (due before 2025-07-12)
> > sort by scheduled
> > hide created date
> > hide backlink
> > hide tags
> > show task count
> > hide postpone button
> > show edit button
> > ```
> 
> > [!todo]- Completed tasks
> > ```tasks
> > done
> > # (tags include "elektronikk") OR (tags include "telekom") OR (tags include "transmisjon")
> > (tags include assignment) OR (tags include report) OR (tags include lab)
> > (due after 2025-01-01) OR (due before 2025-07-12)
> > sort by heading
> > hide created date
> > hide backlink
> > hide tags
> > # group by function
> > show task count
> > hide postpone button
> > show edit button
> > ```
> 
> > [!warning]- Cancelled tasks
> > ```tasks
> > status.type is CANCELLED
> > # (tags include "elektronikk") OR (tags include "telekom") OR (tags include "transmisjon")
> > (tags include assignment) OR (tags include report) OR (tags include lab)
> > (due after 2025-01-01) OR (due before 2025-07-12)
> > sort by heading
> > hide created date
> > hide backlink
> > hide tags
> > # group by function
> > show task count
> > hide postpone button
> > show edit button
> > ```

> [!check] Assignment progress
> ```chart
> type: pie
> labels: [Upcoming,Completed,Cancelled]
> series:
>  - title: Assignments
>    data: [4,16,4]
> tension: 0
> width: 50%
> labelColors: true
> fill: true
> beginAtZero: true
> bestFit: false
> bestFitTitle: undefined
> bestFitNumber: 0
> ```

> [!error] [[Exams]]
> ```tasks
> tags include exam
> tags include semester-5
> sort by scheduled
> hide created date
> hide backlink
> hide tags
> hide task count
> hide postpone button
> show edit button
> ```

___