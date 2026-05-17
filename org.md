## Basic Org-mode
### Headlines and Outline mode
Tab

S-TAB

Use M-<Arrow> to move

C-c C-w to refile

### TODO KEYWORDS
```
#+SEQ_TODO: NEXT(n) TODO(t) WAITING(w) SOMEDAY(s) PROJ(p) | DONE(d) CANCELLED(c)
```

C-c C-t to choose status you want to give to headline

Use state machine to control the task

### Schedule, Deadline, Agenda View

C-c C-s set the schedule for task

C-c C-d set the deadline for task

S-<Arrow> to move and select the date

M-x org agenda to open agenda

f,b to go forward and backward in agenda view

a to view the week schedule

T to view the tasks by category

For repeating tasks, use `REPEAT(r)`, Also add this: `+STARTUP: nologrepeat`

+: timestamp will be rescheduled by the interal when the task is marked as done

++: make sure the timstamp rescheduled is always in the future, but calculated using the set date

.+: reschedule using the done date
### Checklist
C-c C-c used to mark the item

Use M-S-RET to quickly add checklist item
