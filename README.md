# Mine-Sniffer-1
Advanced mine detection and safety research &amp; engineering project.

# Communication:
All communication related to the process of developing the necessary code and design segments of the Mine Sniffer (MS) is done using the Trello planner and Whatsapp group messages.

Any questions or uncertainties about the design and code decisions will initially be communicated via our WhatsApp group or in person at the agreed location.

# Trello planner:
Link to join the workspace: https://trello.com/invite/minesniffer1/ATTIca9166cfbc2599773fae5f89b989d98c401D9955
The design process should be kept up to date via Trello by every member of the team.

Trello instructions:
Backlog: A list of things we think we want to do.
Design & Research: Move from backlog to Design & Research when the idea is final.
To-Do: assign the name of the worker(s) and time interval required to complete the task.
Doing: These are the things members are working on. Every member should have at least one item in the list.
Code & Design review: When a task has gotten approval, it moves off to Testing.
Done: production and assembly.

# Git workspace:
When working on code, be aware to work on your own branch! Do not foget to give your branch a fitting name.

After your code has been reviewed during the Code Review phase, only then are you allowed to push the commits to the main branch. This is done in order to prevent as much branch conflicts as possible. 

Make a branch:
git branch issue_test # makes new branch
git checkout issue_test # switches to that branch

Commiting changes in the code:
git add issue_test.py # stash the changes.
git commit -m "what dit you change?"
git push # commit the changes

How to receive the most up to date code from our repository?
git pull origin issue_test_branch

or

git fetch origin issue_test_branch
git merge issue_test_branch
