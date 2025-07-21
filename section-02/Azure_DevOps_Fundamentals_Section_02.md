I’ve saved the full markdown content into a file for you:

# 📘 Azure DevOps Fundamentals – Section 02: Azure Boards and Team Setup

## 📚 Table of Contents
- [👥 Adding Users and Permissions](#-adding-users-and-permissions)
- [🗂 Area Paths vs Iteration Paths](#-area-paths-vs-iteration-paths)
- [🏃 Define a Sprint](#-define-a-sprint)
- [📋 Azure Boards Overview](#-azure-boards-overview)
- [🧱 Work Item Types](#-work-item-types)
- [📊 Boards, Backlogs, and Sprints](#-boards-backlogs-and-sprints)
- [🔍 Queries and Dashboards](#-queries-and-dashboards)
- [🧭 Coming Up Next](#-coming-up-next)
- [🧠 Expert Insight](#-expert-insight)

---

## 👥 Adding Users and Permissions

1. Go to **Project Settings** > **Permissions**.
2. Add users (e.g., QA, Devs, Leads) to the project.
3. Assign roles like:
   - **Project Admin**
   - **Contributor**
   - **Reader**

💡 Use **Teams** for logical grouping (e.g., Frontend, Backend, QA).

---

## 🗂 Area Paths vs Iteration Paths

| Type             | Purpose                          | Example                         |
|------------------|----------------------------------|----------------------------------|
| **Area Path**    | Organizes work by feature/team   | `CustomerSupport > Mobile`      |
| **Iteration Path** | Organizes work by time/sprint | `2025 > Q3 > Sprint 1`          |

📝 Area Paths = "What", Iteration Paths = "When".

---

## 🏃 Define a Sprint

A **Sprint** is a fixed-length timebox (e.g., 2 weeks) during which the team delivers a set of committed work.

### Why Define Sprints?
- Sets delivery rhythm.
- Enables burndown tracking.
- Supports continuous delivery.

### How to Define Sprints:
1. **Project Settings** > **Boards** > **Project Configuration**.
2. Click **Iterations**.
3. Add your sprints:
   - Sprint 1: `2025-07-01` – `2025-07-14`
   - Sprint 2: `2025-07-15` – `2025-07-28`
4. Assign iterations to teams.

---

## 📋 Azure Boards Overview

Use Azure Boards to:
- Plan (Epics → Features → Stories)
- Track (status, assignments)
- Prioritize (via backlogs and queries)

---

## 🧱 Work Item Types

Each work item helps organize delivery:

| Type       | Definition                                                                 |
|------------|------------------------------------------------------------------------------|
| **Epic**   | Large body of work spanning multiple sprints and teams. High-level goal. |
| **Feature**| Grouping of user stories that deliver part of an Epic's value.            |
| **User Story** | Smallest unit of user functionality. Fits in one sprint.             |
| **Task**   | Technical step to implement a story. Owned by developers/testers.         |
| **Bug**    | A defect needing resolution.                                               |

### 🧩 Example Hierarchy:
Epic: Improve Customer Experience
└─ Feature: Enhance Feedback Form
├─ User Story: Add rating stars
└─ User Story: Display thank-you message
└─ Task: Create popup



💡 Epics help with quarterly planning. Stories help daily work.

---

## 📊 Boards, Backlogs, and Sprints

Azure Boards is more than a task list — it's your team’s visual delivery control panel. Understanding **Boards**, **Backlogs**, and **Sprints** will help your team stay aligned and deliver faster.

---

### 🔹 Boards

Boards provide a **Kanban-style view** of work items. Each card on the board represents a work item (User Story, Bug, Task), and columns represent workflow stages like:

- **To Do**
- **Doing**
- **Code Review**
- **Done**

**Key uses:**
- Drag-and-drop to move work across columns
- Visualize bottlenecks (e.g., too much work stuck in “Code Review”)
- Customize per team or per work item type

💡 *Tip: Limit work-in-progress (WIP) to reduce context switching.*

---

### 🔹 Backlogs

Backlogs give you a **prioritized list** of all your work items.

- **Epic Backlog**: See high-level initiatives.
- **Feature Backlog**: Break Epics into more focused deliverables.
- **Story Backlog**: Day-to-day developer tasks.

**Why it matters:**
- Helps the Product Owner or Delivery Manager focus on what matters next
- Allows grooming/refinement during the sprint
- Supports sprint planning with visibility of all work

💡 *Tip: Use backlog levels to zoom in/out from strategy to detail.*

---

### 🔹 Sprints

A Sprint in Azure DevOps links directly to your Iteration Paths.

**Inside a Sprint view, you can:**
- Assign work items to the sprint
- View burndown charts
- Track capacity per team member
- Break stories into tasks

Sprint planning starts **from the Backlog**, moves into **Boards**, and is tracked through **Sprints**.

📌 *Use this flow:*
> Backlog grooming → Sprint planning → Sprint board tracking → Sprint review & retro

---

### ✅ Summary

| Component | Purpose | Key Benefit |
|----------|---------|--------------|
| **Boards** | Visual workflow | Team alignment, track status |
| **Backlogs** | Prioritized list | Plan future work, break down features |
| **Sprints** | Timebox delivery | Track velocity, deliver incrementally |

---

## 🔍 Queries and Dashboards

_(Section content placeholder — add saved queries for filtering bugs, dashboards for burndown, etc.)_

---

## 🧭 Coming Up Next

- How to manage your sprint backlog
- Using Azure Repos for source control
- Introduction to CI/CD Pipelines

---

## 🧠 Expert Insight

> If you're managing a team, use **Boards** for visual tracking and reporting. Set up **Iteration Paths** before your sprint starts and link **Features** to your **Epics**. Focus on visualizing flow to improve team communication and delivery.

---

<div style="display: flex; justify-content: space-between; margin-top: 20px;">
  <a href="#" style="background-color: #6c757d; color: white; padding: 10px 20px; text-decoration: none; border-radius: 5px;">⬅️ Previous Section</a>
  <a href="#" style="background-color: #0078d4; color: white; padding: 10px 20px; text-decoration: none; border-radius: 5px;">Next Section ➡️</a>
</div>

