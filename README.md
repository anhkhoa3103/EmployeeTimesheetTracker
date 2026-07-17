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
- Sends an automated email report to the manager with the generated
  Timesheet and Leave Tracker files attached on successful runs
- On failure (e.g. missing or invalid input files), automatically sends
  an exception alert email listing exactly which files are missing,
  so the process can be corrected and re-run

## Demo
https://github.com/user-attachments/assets/5bb06722-f114-4597-bff5-6ea335489f5b

Email Sending

<img width="3180" height="1660" alt="image" src="https://github.com/user-attachments/assets/5eb68fa1-0b78-4e96-b178-1ef6e8b4f48c" />
<img width="3150" height="1375" alt="image" src="https://github.com/user-attachments/assets/3e2abbbf-e27f-40d1-8042-08e79899d849" />


## Tech
`UiPath` `Excel Automation` `Workflow Design` `Email Automation` `Exception Handling`
