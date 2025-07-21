
# 📘 Azure DevOps Fundamentals – Section 01: Introduction

## 📚 Table of Contents
- [🎯 Course Goal](#-course-goal)
- [💡 Why Should You Care About DevOps?](#-why-should-you-care-about-devops)
- [🔹 What is Azure DevOps?](#-what-is-azure-devops)
- [🔹 Why Use Azure DevOps?](#-why-use-azure-devops)
- [🔹 Core Components Overview](#-core-components-overview)
- [🔹 DevOps vs Agile vs CI/CD](#-devops-vs-agile-vs-cicd)
- [🔹 Azure DevOps Roles – Focus on Delivery Lead](#-azure-devops-roles--focus-on-delivery-lead)
- [🛠 How to Create a Project in Azure DevOps](#-how-to-create-a-project-in-azure-devops)
- [🧭 Coming Up Next](#-coming-up-next)
- [🧠 Expert Insight](#-expert-insight)

---

## 🎯 Course Goal

> Build confidence using Azure DevOps to plan, build, test, and release software. Learn how to bring structure, automation, and transparency to your development process.

Whether you're a developer, QA, or Delivery Lead, the goal is to:
- **Understand the tools**
- **Apply them to real delivery challenges**
- **Support teams through smoother, faster releases**

---

## 💡 Why Should You Care About DevOps?

### 🔥 The Reality:
In today's delivery environments, it's not enough to just "build software." You need to:
- Release it **quickly**
- Maintain **quality**
- Support **collaboration** between Dev, QA, and Ops
- **Measure** your progress

That’s where **DevOps** comes in.

### 🚫 Misconceptions:
| Myth                             | Reality                                                                 |
|----------------------------------|-------------------------------------------------------------------------|
| “DevOps is just for developers.” | It’s for **the whole delivery team**: QA, Ops, and leadership too.     |
| “We’re Agile, so we don’t need DevOps.” | Agile ≠ automation. DevOps makes Agile **deliverable**.         |
| “DevOps is just tools.”          | It’s a **culture**, not just Jenkins and Git.                          |

### ✅ Why It Matters to You
| Role          | Why DevOps Helps You                                                       |
|---------------|---------------------------------------------------------------------------|
| Delivery Lead | Better visibility, faster cycles, fewer escalations                        |
| Developers    | Faster feedback on code, fewer manual steps                                |
| QA            | Integration into pipelines, less friction with dev teams                   |
| Ops           | Predictable deployments, reduced production firefighting                   |

### 🧠 Mental Model:

```
PLAN → CODE → BUILD → TEST → RELEASE → MONITOR
 ^        ^       ^      ^       ^        ^
 Boards  Repos  Pipelines TestPlans Pipelines Dashboards
```

---

## 🔹 What is Azure DevOps?

**Azure DevOps** is Microsoft's platform for modern software delivery. It gives teams one unified space to:
- Plan and track work
- Host code in version control
- Automate build and release pipelines
- Manage tests and track quality
- Share and consume internal packages

🔎 Unlike other toolchains that require 4–5 separate tools (e.g., Jira + GitHub + Jenkins + Artifactory), Azure DevOps brings all of these **into one secure environment.**

---

## 🔹 Why Use Azure DevOps?

### 📌 Business Value:
| Benefit             | How It Helps                                                          |
|---------------------|-----------------------------------------------------------------------|
| One Source of Truth | Keeps planning, code, tests, and releases in sync                    |
| Faster Time to Value| Automate the slow, manual steps in testing and deployment            |
| Lower Risk          | Integrated quality gates prevent defects from reaching production    |
| Role Flexibility    | Tailored access for Dev, QA, Managers, and Contractors               |

### 🤝 Who Uses Azure DevOps?
- Small Agile teams
- Enterprise delivery teams with complex compliance needs
- Government and regulated industries
- Hybrid teams (on-prem + cloud)

---

## 🔹 Core Components Overview

| Component           | Functionality Summary                                                | Example Use Case                                             |
|---------------------|----------------------------------------------------------------------|--------------------------------------------------------------|
| **Azure Boards**     | Plan work items, sprints, and Kanban boards                         | Track a new feature across several teams                     |
| **Azure Repos**      | Git-based version control with pull requests and branching           | Developers collaborating on a new module                     |
| **Azure Pipelines**  | CI/CD for automated builds, tests, and deployments                   | Run unit tests, build Docker images, deploy to staging       |
| **Azure Test Plans** | Manual and exploratory testing toolset                               | QA runs regression tests before release                      |
| **Azure Artifacts**  | Package manager for NuGet, npm, Maven, Python                        | Share a versioned API library across microservices teams     |

---

## 🔹 DevOps vs Agile vs CI/CD

| Concept   | What It Really Means                                                             |
|-----------|-----------------------------------------------------------------------------------|
| **Agile** | Helps us **plan and prioritize** smaller pieces of work for fast delivery         |
| **DevOps**| Helps us **collaborate and automate** delivery through shared ownership           |
| **CI/CD** | Helps us **build, test, and deploy** software more often with fewer risks         |

### 🔁 Analogy:
Think of Agile as **deciding what route to take**, DevOps as **tuning the engine**, and CI/CD as **the autopilot system** that drives it.

---

## 🔹 Azure DevOps Roles – Focus on Delivery Lead

As a **Delivery Lead**, Azure DevOps helps you:
- Visualize progress via **Boards and Dashboards**
- Track **team velocity, blockers, and cycle time**
- Surface build and test failures early via **Pipelines**
- Coordinate with QA on test coverage using **Test Plans**
- Use **Queries** to extract data for retros, reviews, or risk reports

### 📊 Metrics You Can Drive:
| Metric               | Where to Get It       |
|----------------------|-----------------------|
| Lead Time            | From Boards + Pipelines |
| Deployment Frequency | From Pipelines         |
| Bug Fix Rate         | From Boards (Bug work items) |
| Sprint Completion    | From Boards Dashboards |

---

## 🛠 How to Create a Project in Azure DevOps

### 🔧 Step-by-Step:

1. **Go to:** [https://dev.azure.com](https://dev.azure.com)
2. Click **“New Project”**
3. Enter:
   - **Name**: e.g., `CustomerSupport-Portal-Q3`
   - **Description** (optional)
   - **Visibility**: `Private` (default)
   - **Version Control**: `Git` (recommended)
   - **Work Item Process**: `Agile` or `Scrum`

4. Click **Create**

### ✅ What You Get:
- Project Home with Repos, Boards, and Pipelines tabs
- Default team group with permissions
- Ready-to-use Agile templates for Epics, Features, and User Stories

💡 Pro Tip:
Set up **iteration paths** to match your sprint cadence (e.g., `2025 > Q3 > Sprint 1`).

---

## 🧭 Coming Up Next

In **Section 02**, we’ll:
- Add users to your DevOps org
- Organize areas and iterations
- Navigate the Boards UI
- Start populating your first backlog

---

## 🧠 Expert Insight

> Azure DevOps succeeds when it's not just used by one team, but by the **whole delivery ecosystem** — Dev, QA, PM, and Ops.

As a Delivery Lead:
- Think beyond the tools: focus on removing delays and creating **feedback loops**
- Don't be afraid to start small: even one good **pipeline** or **burndown chart** can change a team's habits
- Review pipeline failures like you'd review code — they are as valuable as any bug

---

<div align="right">

➡️ [**Next: Section 02 – Team Setup and Navigation**](./section-02.md)

</div>
