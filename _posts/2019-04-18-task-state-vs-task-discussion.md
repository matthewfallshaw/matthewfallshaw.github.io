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
scan the most recent comments in the discussion thread and get coding (or
writing, or digging, or building the wall). Many hours later you ship the
feature (document, hole, wall). To the task owner's eventual horror you
failed to:
1. Note that 45 of the 50 comment long discussion thread comments were
   collapsed
2. Read back through the discussion to piece together the critical parts
   of comments 3, 14, 15, 43, 44 and 45, from which it is obvious (in
   hindsight) that you implemented the thing that was originally requested
   modified by only the recent parts of the discussion, rather than the
   thing that is actually currently desired

## The Solution
Task management tools often allow a separation between a task *description* and
a (possibly threaded) task *discussion*. The separation between *description*
and *discussion* should not be ignored. Discuss the task in the *discussion
thread*, and whenever a decision is made or a milestone is achieved that
changes the current state of the task, update the task *description*. Read back
over the task *description* as you've left it and make sure that it's in a
state that would allow an intelligent but uninformed colleague having missed
parts of the *discussion* to quickly get up to speed and contribute.  (It's
perfectly fine to [refer](/rule-one) to content in the discussion rather than
transcribing it, just don't assume that anyone will have seen and remembered
anything down there.) *This moment* (when you've just made the relevant
decision) is the cheapest moment that is likely ever to exist to record the
decision (it's already all organised in your mind, you just have to write it
down), and it's likely that you and others will want to refer to the decision
many more times that the one time you'll have to write it down.

## Also Useful
When "completing" a task, update its description with a summary of the task
resolution, relevant links (the live feature, the completed document, etc.).
This is useful:
1. for others reviewing their system notifications (so that they can see &
   confirm that the task is complete to their satisfaction),
2. for future people who find the historical task (including future instances
   of *you*) as a way to find links to the reason the task existed in the
   first place, and
3. to use the exercise as an opportunity to review whether the task is actually
   complete to *your* satisfaction, and what you have learned from the exercise
   of completing it.

There is unlikely to be any time when you have all of the relevant information
better loaded up in your mind and making such updates will be as easy to do
as the moment you complete the task.
