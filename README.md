# Clean Your Home MVP Roadmap

This is the working roadmap for the MVP. You can edit this file directly in GitHub and click the checkboxes as you complete tasks.

## Goal

The goal is to validate whether students and young adults actually use an app that helps them:
- choose a home type
- explore rooms and objects
- learn how to care for items
- save their preferred method
- add tasks to a routine
- complete a checklist

This MVP is intentionally focused on the core habit loop. It does not include 3D scanning, AR, or advanced AI features yet.

## Recommended stack

- Design: Figma
- App prototype: FlutterFlow
- Backend: Firebase
- Auth: Firebase Auth
- Database: Firestore
- Storage: Firebase Storage
- AI help: ChatGPT / Copilot / Cursor

## Tools and links

- FlutterFlow: https://flutterflow.io/
- Firebase: https://firebase.google.com/
- Figma: https://www.figma.com/
- Flutter docs: https://docs.flutter.dev/
- Firebase docs: https://firebase.google.com/docs
- GitHub: https://github.com/

## MVP scope

### Included
- [ ] Home type selection (apartment, dorm, house)
- [ ] Room list
- [ ] Object detail pages
- [ ] Cleaning or care instructions
- [ ] Saved cleaning methods
- [ ] Recurring routine creation
- [ ] Checklist / Today view
- [ ] Task completion tracking
- [ ] Minimal onboarding

### Excluded for now
- [ ] 3D walking simulation
- [ ] AR scanning
- [ ] AI home detection
- [ ] Household sharing
- [ ] Brand partnerships
- [ ] Commerce integrations
- [ ] Heavy productivity dashboards

## 30-day roadmap

### Week 1 — Define and design the MVP

#### Day 1: Define the real problem
- [ ] Write a short problem statement
- [ ] Identify the primary user
- [ ] Write what success looks like

#### Day 2: Define the product promise
- [ ] Write the product promise in one sentence
- [ ] Describe the core user pain point
- [ ] Write 3 outcomes the app should support

#### Day 3: Define the MVP user flow
- [ ] Map the user journey from home setup to task completion
- [ ] List the screens needed
- [ ] Remove anything that is not essential for validation

#### Day 4: Create the Figma screens
- [ ] Welcome / onboarding screen
- [ ] Home type selection screen
- [ ] Room selection screen
- [ ] Room detail screen
- [ ] Object detail screen
- [ ] Saved methods screen
- [ ] Today checklist screen
- [ ] Routine setup screen

#### Day 5: Walk through the flow yourself
- [ ] Run through the prototype in order
- [ ] Note where the flow feels confusing
- [ ] Simplify wording and layout

#### Day 6: Simplify the product
- [ ] Remove extra screens
- [ ] Remove unnecessary text
- [ ] Reduce cognitive load

#### Day 7: Lock the prototype direction
- [ ] Finalize the screen set
- [ ] Finalize the tone and app personality
- [ ] Confirm the day-1 MVP goal

### Week 2 — Build the prototype

#### Day 8: Set up the project
- [ ] Create FlutterFlow project
- [ ] Create Firebase project
- [ ] Connect FlutterFlow to Firebase
- [ ] Set up Firebase Authentication

#### Day 9: Build onboarding
- [ ] Welcome screen
- [ ] Home type selection screen
- [ ] Home setup screen

#### Day 10: Build the data model
- [ ] User collection
- [ ] Home collection
- [ ] Room collection
- [ ] Object collection
- [ ] Task collection
- [ ] Routine collection
- [ ] SavedMethod collection

#### Day 11: Build room list screen
- [ ] Room cards
- [ ] Room selection interaction
- [ ] Display home status

#### Day 12: Build object detail screen
- [ ] Object title
- [ ] Description
- [ ] Cleaning frequency
- [ ] Instructions
- [ ] Save method action
- [ ] Add to routine action

#### Day 13: Build saved methods
- [ ] Save method button
- [ ] Store method in database
- [ ] Display saved methods list

#### Day 14: Build routine creation
- [ ] Add routine creation flow
- [ ] Add recurrence options
- [ ] Connect to task scheduling

### Week 3 — Test the habit loop

#### Day 15: Build the Today checklist
- [ ] Add Today screen
- [ ] Show tasks due today
- [ ] Allow marking tasks complete
- [ ] Show next task suggestion

#### Day 16: Add recurring tasks
- [ ] Daily tasks
- [ ] Weekly tasks
- [ ] Biweekly tasks
- [ ] Monthly tasks
- [ ] Quarterly tasks
- [ ] Yearly tasks

#### Day 17: Improve the object-to-routine flow
- [ ] Connect object detail to routine creation
- [ ] Remove friction from the path
- [ ] Test that the journey is obvious

#### Day 18: Create the saved method library
- [ ] Create saved method list
- [ ] Add edit/remove actions
- [ ] Show method details

#### Day 19: Add a personal routines section
- [ ] Add a simple personal routines tab
- [ ] Add face / teeth / hair / body placeholders if needed
- [ ] Keep it optional and lightweight

#### Day 20: Add an “I have 10 minutes” mode
- [ ] Add a duration selector
- [ ] Suggest tasks based on selected time
- [ ] Keep suggestions realistic and calm

#### Day 21: Run a usability pass
- [ ] Test all flows end-to-end
- [ ] Remove confusing labels
- [ ] Review visual hierarchy

### Week 4 — Validate with real users

#### Day 22: Write the user testing script
- [ ] Prepare a 15-minute test script
- [ ] Draft interview questions
- [ ] Prepare notes template

#### Day 23: Test with student users
- [ ] Run 3-5 tests
- [ ] Record reactions
- [ ] Note pain points

#### Day 24: Review the feedback
- [ ] Group feedback into themes
- [ ] Find repeat pain points
- [ ] Identify the strongest feature requests

#### Day 25: Improve onboarding and core flow
- [ ] Reduce confusion in onboarding
- [ ] Simplify the hardest step
- [ ] Improve the route from object to routine

#### Day 26: Add engagement cues
- [ ] Add due-soon indicators
- [ ] Add summary for today
- [ ] Add completion states

#### Day 27: Run a second round of testing
- [ ] Test again with 2-3 users
- [ ] Check whether friction improved
- [ ] Check whether users are more engaged

#### Day 28: Final polish and bug fixing
- [ ] Fix broken interactions
- [ ] Review visual consistency
- [ ] Remove dead ends
- [ ] Ensure the core flow feels smooth

#### Day 29: Create the demo and pitch summary
- [ ] Capture screen recordings
- [ ] Write a short product summary
- [ ] Write 3 key value points

#### Day 30: Decide the next step
- [ ] Review evidence and feedback
- [ ] Decide if the concept has traction
- [ ] Choose whether to continue, pivot, or recruit support

## Metrics to watch

- [ ] Number of sign-ups
- [ ] Number of home setups
- [ ] Number of rooms created
- [ ] Number of objects viewed
- [ ] Number of methods saved
- [ ] Number of routines created
- [ ] Number of checklist tasks completed
- [ ] Number of users returning after 3-7 days

## Decision gates

### Continue if
- [ ] Users understand the app quickly
- [ ] They can create a routine without confusion
- [ ] They save methods or tasks
- [ ] They complete tasks during testing
- [ ] They say they would use it weekly

### Pivot if
- [ ] Users do not understand the purpose
- [ ] They say the app feels cluttered
- [ ] They struggle to navigate rooms and objects
- [ ] They do not see value beyond a checklist

## Suggested validated product statement

“A simple home and routine app for students and young adults that turns everyday tasks into visual, calm, manageable routines.”

## Final principle

Do not overbuild before proving that users want the core action:
- choose a home
- understand a task
- save a method
- build a routine
- complete it regularly

That is the key validation loop.

## Optional next step

After this roadmap, the next useful document would be:
- [ ] MVP screen-by-screen specification
- [ ] Firebase data model schema
- [ ] User interview script
- [ ] FlutterFlow + Firebase onboarding checklist

## Notes

This roadmap is intentionally lean and focused on validation. The most important question right now is whether the product pattern is useful enough to keep building.
