# instructions.md

## Purpose
developer + builder instructions for tDelta

## Tech
- chrome extension (MV3)
- JS + HTML + CSS
- chrome.storage.local only

## Core Components
- background/service worker
- content script (bar injection)
- popup (task management)
- options (blocking toggle)

## Permissions
- tabs
- storage
- webNavigation
- optional: declarativeNetRequest (blocking)

## Bar Behavior
- inject below tab bar
- visible on all sites
- reacts to lock-in state
- color escalates over time

## Task Logic
- max 3 tasks
- each has estimate
- manual start
- manual complete
- one active lock-in at a time

## Tracking
- track active tab domain
- aggregate time per domain
- bucket into 15-min windows

## Blocking
- user-defined list
- toggleable per session
- only active during lock-in

## Data
- store sessions
- store task history
- store domain stats
- never leave device

## Testing
- fresh install
- lock-in on/off
- bar persistence
- blocking toggle
- data reset

## Commit
- When I expliclty say "commit to git" please stage everything and write a short comment for each stage and commit and push it to github. Please pull in a new branch and NEVER commit to main directly. Always generate a pull request and commit it as a new branch. 
