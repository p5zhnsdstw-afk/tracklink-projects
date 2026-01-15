# Tracklink Ecuador - Project Repository

## Overview

This repository tracks all active and planned projects for Tracklink Ecuador. Projects are managed via a Kanban board with priority levels and assigned owners.

---

## Project Status Workflow

| Status | Description |
|--------|-------------|
| **Backlog** | Ideas and future projects not yet started |
| **To Do** | Approved projects ready to begin |
| **In Progress** | Currently being worked on |
| **Review** | Completed, awaiting review/approval |
| **Done** | Finished and deployed |

---

## Priority Levels

| Priority | Color | Description |
|----------|-------|-------------|
| **Critical** | Red | Urgent, needs immediate attention |
| **High** | Orange | Important, should be done soon |
| **Medium** | Yellow | Standard priority |
| **Low** | Green | Nice to have, no rush |

---

## Team Members

| Name | Role | Initials |
|------|------|----------|
| (To be added) | | |

---

## File Structure

```
tracklink-ecuador-projects/
├── CLAUDE.md           # This file - project context
├── projects.json       # Project data (source of truth)
├── kanban.html         # Visual Kanban board
└── archive/            # Completed projects archive
```

---

## How to Use

1. **View Projects**: Open `kanban.html` in a browser
2. **Add/Edit Projects**: Modify `projects.json` and refresh the board
3. **Archive**: Move completed projects to `archive/` folder periodically

---

## Data Fields per Project

| Field | Type | Description |
|-------|------|-------------|
| id | string | Unique identifier |
| name | string | Project name |
| description | string | Brief description |
| owner | string | Person responsible |
| priority | string | critical/high/medium/low |
| status | string | backlog/todo/in_progress/review/done |
| deadline | string | Target completion date (YYYY-MM-DD) |
| progress | number | 0-100 percentage complete |
| created | string | Date created |
| updated | string | Last updated |

---

## Notes

- All dates in YYYY-MM-DD format
- Progress is updated manually
- Kanban board auto-refreshes when file changes detected
