# Clean Your Home MVP Roadmap

This document is the working plan for building a lean MVP to validate whether students would actually use a home management and routine app.

## Mission

Prove that users will regularly:
- choose a home type
- explore rooms and objects
- learn how to care for items
- save a preferred method
- add tasks to a routine
- complete a checklist

This MVP is not about 3D scanning or advanced AR. The goal is to validate the core habit loop.

## Recommended stack

- Design: Figma
- App prototype: FlutterFlow
- Backend: Firebase
- Auth: Firebase Authentication
- Database: Firestore
- Storage: Firebase Storage
- Notifications: Firebase Cloud Messaging (optional)
- AI help: ChatGPT / Copilot / Cursor for code generation and ideation

## Tools and resources

- FlutterFlow: https://flutterflow.io/
- Firebase: https://firebase.google.com/
- Figma: https://www.figma.com/
- Flutter docs: https://docs.flutter.dev/
- Firebase docs: https://firebase.google.com/docs
- ChatGPT: https://chat.openai.com/
- GitHub: https://github.com/

## MVP scope

### Include
- Home type selection (apartment, dorm, house)
- Room list
- Object detail pages
- Cleaning or care instructions
- Saved cleaning methods
- Recurring routine creation
- Checklist / Today view
- Task completion tracking
- Minimal onboarding

### Exclude for now
- 3D walking simulation
- AR scanning
- AI home detection
- Household sharing
- Brand partnerships
- Commerce integrations
- Generic productivity dashboards

## 30-day timeline

## Week 1 — Define and design the MVP

### Day 1: Decide the real problem to validate
- Finalize the single goal: do users actually use the routine-building loop?
- Define target user: university students and young adults
- Write a 1-page problem statement

Checklist:
- [ ] Write a short problem statement
- [ ] Identify the primary user
- [ ] Clarify what success means

### Day 2: Define the product promise
Create a short, simple promise like:
- “A simple app that helps you manage your home and build routines without overwhelm.”

Checklist:
- [ ] Write the product promise
- [ ] Note the target user pain point
- [ ] Write 3 outcomes the app should help with

### Day 3: Define the MVP user flow
Map the basic loop:
1. User chooses home type
2. User sees room list
3. User taps a room
4. User taps an object
5. User sees cleaning instructions
6. User saves preferred method
7. User adds to routine
8. User sees checklist for today
9. User completes task

Checklist:
- [ ] Finalize basic flow
- [ ] List all screens needed
- [ ] Remove anything not required for validation

### Day 4: Create the app screens in Figma
Create these screens:
- Welcome / onboarding
- Home type selection
- Room selection
- Room detail
- Object detail
- Saved methods
- Checklist / Today
- Routine setup

Checklist:
- [ ] Design onboarding screen
- [ ] Design home type screen
- [ ] Design room screen
- [ ] Design object detail screen
- [ ] Design checklist screen
- [ ] Design routine screen

### Day 5: Test the flow with yourself
Walk through the full flow as if you are a user.
Ask:
- Is it intuitive?
- Is it calm?
- Is it too heavy?
- Is the emotional tone right?

Checklist:
- [ ] Run through each screen in order
- [ ] Note confusing areas
- [ ] Simplify labels and wording

### Day 6: Review and simplify
Remove anything that feels like extra complexity.
This app should feel supportive, not overwhelming.

Checklist:
- [ ] Remove extra screens
- [ ] Remove clutter
- [ ] Reduce cognitive load

### Day 7: Lock the prototype direction
At the end of Week 1, you should have a clear MVP direction and a designed flow.

Checklist:
- [ ] Finalize screen set
- [ ] Finalize content tone
- [ ] Confirm MVP goal

## Week 2 — Build the prototype

### Day 8: Set up the project
Create the app in FlutterFlow and connect Firebase.

Checklist:
- [ ] Create FlutterFlow project
- [ ] Create Firebase project
- [ ] Connect FlutterFlow to Firebase
- [ ] Set up Firebase Authentication

### Day 9: Build user onboarding
Create welcome / onboarding flow.

Checklist:
- [ ] Add welcome screen
- [ ] Add home type selection screen
- [ ] Add room setup or home setup screen

### Day 10: Build room and object model
Set up the core data structure.

Suggested data model:
- User
- Home
- Room
- Object
- Task
- Routine
- SavedMethod

Checklist:
- [ ] Create user collection
- [ ] Create home collection
- [ ] Create room collection
- [ ] Create object collection

### Day 11: Build room list screen
Show rooms in a home and allow selecting rooms.

Checklist:
- [ ] Add room cards
- [ ] Add room selection behavior
- [ ] Display room count and status

### Day 12: Build object detail screen
Create object cards with:
- object title
- description
- cleaning frequency
- instructions
- save method action
- add to routine action

Checklist:
- [ ] Create object card design
- [ ] Add object description section
- [ ] Add cleaning frequency section
- [ ] Add method actions

### Day 13: Build saved methods
Users should be able to save their preferred method for an item.

Checklist:
- [ ] Add save method button
- [ ] Store method in database
- [ ] Display saved methods in a list

### Day 14: Build routine creation
Users should be able to assign a task to a recurring routine.

Checklist:
- [ ] Add routine creation screen
- [ ] Add recurrence options
- [ ] Add scheduling flow

## Week 3 — Test the habit loop

### Day 15: Build the checklist / Today screen
This is where the app proves usefulness.

Checklist:
- [ ] Add Today view
- [ ] Show tasks due today
- [ ] Allow marking tasks complete
- [ ] Show next task suggestion

### Day 16: Add recurring tasks
Support:
- daily
- weekly
- biweekly
- monthly
- quarterly
- yearly

Checklist:
- [ ] Add recurring task logic
- [ ] Show due dates
- [ ] Allow task completion

### Day 17: Add object-to-routine flow
Make sure users can go from object detail to routine creation easily.

Checklist:
- [ ] Connect object detail to add routine flow
- [ ] Ensure path is intuitive
- [ ] Remove friction

### Day 18: Add saved method library
Users should see a list of their saved cleaning methods.

Checklist:
- [ ] Create saved method list
- [ ] Add edit/remove actions
- [ ] Show method details

### Day 19: Create a simple personal routines section
This can be separate from home for now.

Checklist:
- [ ] Add personal routines tab
- [ ] Add face, teeth, hair, body routines or placeholders
- [ ] Keep it optional and simple

### Day 20: Add an “I have 10 minutes” mode
This is a high-value feature for low-energy users.

Checklist:
- [ ] Add time selector
- [ ] Suggest tasks based on selected duration
- [ ] Keep suggestions realistic

### Day 21: End-of-week usability pass
Review early product flow and reduce friction.

Checklist:
- [ ] Test all flows end-to-end
- [ ] Remove confusing labels
- [ ] Check text tone
- [ ] Check visual hierarchy

## Week 4 — Validate with users

### Day 22: Write the user testing script
Create a 15-minute user testing script.

Questions:
- What do you think this app is for?
- Would you use it?
- What part feels most useful?
- What part feels annoying?
- Would you use it weekly?
- What would make you come back?

Checklist:
- [ ] Write testing script
- [ ] Set up interview questions
- [ ] Prepare consent instructions

### Day 23: Test with 3–5 student users
Talk through the prototype.

Checklist:
- [ ] Run 3–5 user tests
- [ ] Record reactions
- [ ] Document friction points

### Day 24: Review feedback and identify patterns
Focus on repeat feedback.

Checklist:
- [ ] Group feedback into themes
- [ ] Identify top 3 pain points
- [ ] Find strongest feature requests

### Day 25: Improve the onboarding and core flow
Respond to what users actually need.

Checklist:
- [ ] Adjust onboarding based on feedback
- [ ] Simplify the most confusing step
- [ ] Create smoother object-to-routine actions

### Day 26: Add a basic engagement layer
Make it feel useful enough to return.

Checklist:
- [ ] Add simple “due soon” indicators
- [ ] Add “today” summary
- [ ] Add completion states

### Day 27: Run another round of testing
Test again with 2–3 users after changes.

Checklist:
- [ ] Retest with users
- [ ] Check if friction is reduced
- [ ] Check if users are more engaged

### Day 28: Final polish and bug fixing
Fix obvious issues before demo.

Checklist:
- [ ] Fix broken interactions
- [ ] Review visual design consistency
- [ ] Remove dead ends
- [ ] Ensure app flows are smooth

### Day 29: Create the demo and pitch deck
Prepare the key story for your prototype.

Checklist:
- [ ] Capture screen recordings
- [ ] Write short product summary
- [ ] Create 3 key user value points

### Day 30: Decide the next step
Based on gathered evidence, decide:
- continue with this app
- adjust the concept
- find a technical co-founder
- switch to stronger validation

Checklist:
- [ ] Review metrics and feedback
- [ ] Decide whether concept has traction
- [ ] Write next-step plan
- [ ] Choose whether to build, pivot, or recruit support

## What to measure

Track these metrics across the prototype:
- number of sign-ups
- number of home setups
- number of rooms created
- number of objects viewed
- number of saved methods
- number of routines created
- number of checklist tasks completed
- number of users returning after 3–7 days

If users do not return or do not complete routines, this concept needs refinement.

## Decision gates

### Continue if:
- users understand the app quickly
- they can create a routine without confusion
- they save methods or tasks
- they complete tasks during testing
- they say they would use it weekly

### Pivot if:
- users do not understand the purpose
- they say the app feels too cluttered
- they struggle to navigate rooms and objects
- they don’t see value beyond a checklist

## Suggested launch-ready statement after validation

“A simple home and routine app for students and young adults that turns everyday tasks into visual, calm, manageable routines.”

## Key principle

Do not overbuild the product before proving that people want the core action:
- choose a home
- understand a task
- save a method
- build a routine
- complete it regularly

That is the core validation loop.

## Repository and planning resources

- GitHub repo: https://github.com/777lilacs-coder/clean-your-home-mvp-roadmap
- Figma: https://www.figma.com/
- FlutterFlow: https://flutterflow.io/
- Firebase: https://firebase.google.com/
- Flutter docs: https://docs.flutter.dev/

## Optional next step

After finishing this 30-day roadmap, the next document to create could be:
- MVP screen-by-screen specification
- Firebase data model schema
- user interview script
- technical onboarding checklist for FlutterFlow + Firebase

## Final note

This roadmap is intentionally lean. It focuses on validating whether users will actually engage with the product, which is the most important question right now.
