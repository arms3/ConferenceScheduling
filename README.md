# Conference Scheduling

Repo containing notebook and data for a recent conference scheduling issue I solved using the Mixed Integer Programming module from [Google OR Tools](https://developers.google.com/optimization/).

## Problem statement
Recently Slalom Seattle was planning it's annual Innovation Symposium, and I was on the planning committee.

The planning team wanted to assign each individual to a schedule. Attendees had been asked to rank their preference for attending each topic. The problem was a large number of schedules would have to manually be created; over 600 attendees, needed to be assigned to 7 different topics across 3 sessions. The original plan was to whiteboard it and manually create schedules and assign people to schedules, an excruciating process that may have to be rerun as new responses or constraints came in. It also seemed difficult to ensure the best solution: how do you even pick the best subset of possible schedules?

There were also some constraints about the capacity of available rooms, more popular sessions could be put in a larger room, and we wanted to avoid having rooms half empty in one session and then bursting at the seams in a later session.