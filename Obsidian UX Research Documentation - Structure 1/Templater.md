
---
<%* 
tR += "---" + "\n" 
const project = await tp.system.prompt("Please enter the project name")
const name = await tp.system.prompt("Please enter the task name")
let date = tp.date.now("DD.MM.YYYY") 
tR += "date: " + date + "\n"
tR += "project: " + [[project]] + "\n"
let title = "Task - "+ name + " - " + project 
tR += "title: " + title + "\n"
await tp.file.rename(title)
tR += "---" 
%>


Template: [[Templater]]
Project: [[As-Is-Scenario - Purchasing Ticket in Germany]]
Part of: [[Tasks]]
User Group: [[User Group - International Students]]
Resource:
Environment:

## Subtask: 
### Phase in task lifecycle: 
(plan, prepare, perform, evaluate result, communicate result, system-induced, other)
### Task Object: 
### User Requirement:
### Source / Link to Assumption node:
