# User Journey — Developer

---

## 1. Who Is Using the App

| Field            | Details                                      |
|------------------|----------------------------------------------|
| **Persona**      | Software Developer                           |
| **Role**         | Frontend / Backend / Full-stack Engineer     |
| **Technical Level** | High                                      |
| **Goals**        | Create projects, perform analysis review |
| **Frustrations** | Unclear requirements, missing context, slow feedback loops |

---

## 2. How They Access the App

- **Entry point:** Installation file provided by the developer
- **Auth method:** OAuth (e.g. GitHub login)
- **Device:** Primarily desktop/laptop browser

---

## 3. What Is the First Thing They See

- **Landing screen:** Personal dashboard showing 
- **Key elements visible:**
  - Dashboard
  - 2 main elements of create project and browse project
  - Header with additional elements
  - Sidebar with current projects and tab to switch to performance analysis

---

## 4. What Is the First Action They Take

- Login with the necessary oauth methods
- Confirm they are logged in

---

## 5. Flow of Actions (Step-by-Step)

```
[Login] → [Dashboard] → [Create Project] → [Assign Issues]
    → [Select branch] → [Assign commit to related bug]
        → [Push/Merge Code] → [Build/deploy]
[Check performance analysis] → [Review individual analysis]
    → [Provide self review] → [Submit self review]
```

---

## 6. Ideal Flow — When Everything Goes Right

- ✅ Logged in without issue
- ✅ Project created successfully
- ✅ Bugs and branches are shown and linked with no issue
- ✅ Correct commits are shown
- ✅ Ai connects correct commits to linked bugs 
- ✅ Merge and build work with no issue
- ✅ 

---

## 7. What Happens When Something Goes Wrong

| Scenario | Impact | Recovery Steps |
|---|---|---|
| Requirements are vague or incomplete | Work blocked before it starts | Developer comments on the task, tags PM or designer, awaits clarification |
| PR review takes too long | Task stuck, sprint at risk | Developer sends a reminder ping, escalates to team lead if needed |
| CI/CD pipeline fails | PR cannot be merged | Developer reads build logs, fixes the issue, re-pushes |
| Merge conflict detected | PR blocked | Developer pulls latest from main, resolves conflicts locally, force-pushes |
| Task scope changes mid-sprint | Work already done may be wasted | Developer flags to PM, original task is updated or split into a new one |
| App is down or unreachable | Cannot update task status | Developer works offline, updates the app once it's restored |

---

## 8. Steps Taken Before Exiting the App

- Confirms all task statuses are up to date on the board
- Leaves a progress note or end-of-day comment on any in-progress tasks
- Checks for any pending review requests or unread comments to action
- Verifies that the sprint board accurately reflects current state
- Logs out (if on a shared or non-personal device)

---

## 9. What They Do After Exiting the App

- Pushes any final local commits to the remote branch
- Notifies teammates on Slack/Teams about completed work or blockers
- Updates personal task notes or to-do list for the next session
- Attends standup and references the board for their update
- Picks up the next task when returning to the app

---

*Document version: 1.0 | Persona: Developer | Last updated: [date]*
