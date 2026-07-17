# UiPath Timesheet & Leave Tracker Automation

A UiPath workflow automating the monthly timesheet generation process.

## What it does
- Reads employee OT records (date, OT hours, OT reason) and leave records 
  (leave date, leave type) from Excel input files
- Reads the public holiday calendar for the relevant period
- Copies a timesheet template and generates a new timesheet per employee, 
  auto-filling OT, leave, weekend, and holiday entries
- Extracts consolidated data (holidays, OT days, leave days) and updates 
  the Leave Tracker accordingly

## Demo
https://github.com/user-attachments/assets/5bb06722-f114-4597-bff5-6ea335489f5b

## Tech
`UiPath` `Excel Automation` `Workflow Design`
