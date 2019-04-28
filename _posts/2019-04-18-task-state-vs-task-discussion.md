---
layout: post
title: "Task state vs task discussion"
redirect_from: "/task-state-vs-discussion"
last_modified_at: 2019-04-18
---

Extract *current task state* to the task *description* and record *discussion*
in the *discussion thread*.

## The Problem
You open a task in your [issue tracker](https://www.pivotaltracker.com/) or
[project collaboration tool](https://asana.com/), read the task description,
scan the most recent comments in the discussion thread and get coding. Many
hours later you ship the feature. To the task owner's eventual horror you
failed to:
1. Note that 45 of the 50 comment long discussion thread comments were
   collapsed
2. Read back through the discussion to piece together the critical parts
   of comments 3, 14, 15, 43, 44 and 45, from which it is obvious (in
   hindsight) that you implemented the thing that was originally requested
   rather than the thing that is currently desired

## The Solution
Task managers often allow a separation between a task *description* and a
(possibly threaded) task *discussion*. The separation between *description* and
*discussion* should not be ignored. Discuss the task in the *discussion
thread*, and whenever a decision is made or a milestone is achieved that
changes the current state of the task, update the task *description*. Read back
over the task *description* as you've left it and make sure that it's in a
state that would allow an intelligent but uninformed colleague having missed
parts of the *discussion* to quickly get up to speed and contribute.  (It's
perfectly fine to [refer](/rule-one) to content in the discussion rather than
transcribing it, just don't assume that anyone will have seen and rememberd
anything down there.)
