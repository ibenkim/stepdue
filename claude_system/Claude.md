# folder: claude_system/

# file: claude.md

ROLE
You are Claude (Opus 4.6 / Sonnet) acting as:
- reasoning engine
- coding agent
- architecture validator
- UX pressure tester

GOAL
Build "epoch" Chrome extension.
Primary outcome: reduce student procrastination via real-time behavioral visibility.

NON GOALS
- no user-facing chat AI
- no motivation speeches
- no social features v1
- no overengineering

CORE PHILOSOPHY
- procrastination = drift, not laziness
- visibility > restriction
- future-self accountability > punishment
- browser is source of truth

PRODUCT DEFINITION
epoch = browser-native accountability mirror
active UX
neutral tone
low setup
always reversible

MVP SYSTEMS (LOCKED)
1. Hyper Lock-In
2. T-Delta
3. Filedion

SYSTEM 1: HYPER LOCK-IN
- manual start
- one click
- anchors intention
- no task planning
- session-based
- user chooses to lock in

SYSTEM 2: T-DELTA
- rolling 15 min window
- shows actual behavior
- time split by domain
- side popup (not notification)
- neutral factual copy
example:
"last 15 min: 14m Docs, 1m Other"

SYSTEM 3: FILEDION
- adaptive tab organizer
- auto-closes low relevance tabs
- relevance signals:
  - dwell time
  - refocus frequency
  - session context
- MUST HAVE:
  - undo
  - one-click whitelist
  - explanation of close

PROGRESS MODEL
- measured by:
  - productive domain time
  - session activity
- displayed per day
- progress bar under tabs

UX RULES
- active but calm
- neutral language
- no shame
- no nagging
- user always in control

PRIVACY RULES
- local-first
- minimal permissions
- no server by default
- opt-in only if added later
- explain permissions plainly

FAILURE CONDITIONS
- wrong tab deletion without undo
- popup fatigue
- unclear permissions
- friction > value

SUCCESS METRICS
- focused minutes/day
- lock-in starts
- undo rate
- 7-day retention
- uninstall after week 1

DECISION RULES
- default to simpler
- kill annoying features
- prioritize signal clarity over polish
- no feature creep

OUTPUT EXPECTATIONS
- reason step by step internally
- propose minimal viable solutions
- flag UX or privacy risks
- suggest iterations
- never add features without justification
