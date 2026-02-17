# {{YYYY}}.{{MM}}.{{DD}} - {{DayOfWeek}} (Shared)

## ✱ Schedule
{{FROM references/calendar-upcoming.md: filter to today/this week}}
- {{time}} — {{summary}}
{{IF no events: "- (nothing scheduled)"}}

## □ Shared Tasks
{{FROM shared-daily-todo.md: Priority items first (with ! prefix), then others}}
- ! {{priority task}}
- □ {{regular task}}

## 🛒 Shopping ({{count}})
{{FROM shared-shopping-list.md: inline list}}
{{item}} · {{item}} · {{item}}
