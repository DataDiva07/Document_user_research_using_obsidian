table file.name as "Task", tags
from #task

list from #type/as-is-scenario


list from #type/user-requirement

list from #type/user-need 

list from #type/tools

table file.name as "Note", Related Notes from "Notes" where contains(
tags, "#project/ux-research") 