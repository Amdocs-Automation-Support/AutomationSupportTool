# Automation Support Tool
Automation Support Tool

# Genral Idea
To create a web java project, as an automation plataform for support team that can be used by them to create utilites to detect and fix data issues.

The idea is to create the basic arquitecture of this support tool and let the Support team to start adding, as needed, the automation tools/services

# Points to improve
Currently we have several self-employed-done & used automations not shared beetwen all the team and of course not with other teams.
We have some other scripts that are shared with all the team but
  Some of them are personally addapted by some members of the team for self use.
  Some are never updated/improved becuase, as we don’t have the plsql code in modules, is difficult to read and risky to modify (plsql has   to much coupling).
  
The general knowledge and expertice level of PLSQL and Phyton is  low.

# Improvements using Java
The final user utilities can be used by anybody (Service desk team or even TEF).
We can create utilities that can be reused, avoiding double work
Java code is much more easy to read and mantain than plsql or shell scripts.
Support team will invest more time automating and this tools services/code will be automatically shared with all.

# What do we need to develop the tool?
We could need to integrate the new application with lock servers as we are going to be updating database frequently.
We may need to deploy this application in the same server as OMS ear.
We will need aproval from architecture point of view (to avoind risk and to guarantee long term use of the application ).
Some changes to the OMS Main Project can affect the suport tool so we Will need at least test cases in common.

#
