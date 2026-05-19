# `xlsx-command-center`

A surprisingly serious issue tracking platform powered entirely by Excel workbooks.

Yes. Excel.
And somehow… it works frighteningly well.

---

## Live Demo

🌐 **Try the App:**  
[LINK 1 : Launch XLSX Command Center](https://rawcdn.rawgit.net/Archit2000/Excel-Jira-Lite/refs/heads/main/JiraLite.html)  
[LINK 2 : Launch XLSX Command Center](https://cdn.githubraw.com/Archit2000/Excel-Jira-Lite/refs/heads/main/JiraLite.html)

---

# What Is This?

`xlsx-command-center` is a lightweight Jira-style issue tracker that runs completely in the browser using Excel workbooks (`.xlsx`) as the only database.

No backend.
No servers.
No login system.
No cloud bill quietly setting your wallet on fire.

Just:

* browser
* Excel workbook
* operational chaos management

Think:

* Jira without infrastructure
* Linear without React hydration drama
* ServiceNow without needing three consultants and a ceremony

---

# Why Does This Exist?

Because sometimes you need:

✅ enterprise workflow tooling
✅ portability
✅ offline capability
✅ zero deployment complexity
✅ something the ops team can actually use

And sometimes the only universally accepted “database” inside organizations is:

> “Please update the Excel.”

So instead of fighting reality… this project weaponizes it.

---

# Features

## 📂 Workbook-Powered Persistence

* Upload Excel workbook
* Parse workbook safely
* Validate structure
* Edit data through UI
* Export updated workbook
* Auto-create missing sheets
* Preserve unknown columns
* Avoid workbook corruption like your career depends on it

Because sometimes it does.

---

## 🎯 Enterprise Issue Tracking

* Paginated issue table
* Sorting
* Filtering
* Bulk actions
* Inline editing
* Sticky headers
* Status badges
* Priority indicators
* Fast searching
* Responsive UI

All without pretending Excel is a frontend framework.

---

## 💬 Comments System

* Chronological comments
* Inline editing
* Multiline support
* Timestamp tracking
* Latest comment previews

No commenter names by design.

Because sometimes operational honesty improves dramatically when people aren’t visible.

---

## 🛠 Master Data Management

Manage:

* Users
* Projects
* Status
* Priorities

Includes:

* deduplication
* validation
* orphan prevention
* searchable dropdowns
* live refresh

Basically preventing the legendary enterprise scenario:

> “Done”, “DONE”, “done ”, “Closed”, and “close pls” all meaning different things.

---

# Tech Stack

Built with aggressively boring and reliable technology.

## Core

* HTML5
* Vanilla JavaScript (ES6+)
* Bootstrap 5

## Libraries

* [SheetJS](https://sheetjs.com?utm_source=chatgpt.com)
* [DataTables](https://datatables.net?utm_source=chatgpt.com)
* [SweetAlert2](https://sweetalert2.github.io?utm_source=chatgpt.com)
* [SortableJS](https://sortablejs.github.io/Sortable?utm_source=chatgpt.com)
* [Day.js](https://day.js.org?utm_source=chatgpt.com)
* [Tom Select](https://tom-select.js.org?utm_source=chatgpt.com)

---

# Things This Project Refuses To Use

❌ Backend servers
❌ React
❌ Angular
❌ Vue
❌ localStorage
❌ sessionStorage
❌ cookies
❌ mysterious state synchronization bugs from another dimension

State exists only in:

* memory
* uploaded workbook
* exported workbook

That’s it.

If you close the browser without exporting…

may the gods of operational discipline be with you.

---

# Workbook Structure

Supported sheets:

| Sheet             | Purpose         |
| ----------------- | --------------- |
| `MASTER_USERS`    | Users           |
| `MASTER_PROJECTS` | Projects        |
| `MASTER_STATUS`   | Status values   |
| `MASTER_PRIORITY` | Priority values |
| `ISSUES`          | Tickets         |
| `COMMENTS`        | Comments        |

Missing sheets?

No panic.

The app recreates them automatically during export like a responsible adult.

---

# Designed For Real Enterprise Problems

This app tolerates:

* malformed Excel files
* missing sheets
* extra columns
* duplicate values
* inconsistent casing
* corrupted rows
* questionable operational habits

Because production reality is rarely clean.

---

# Security

The app actively protects against:

* XSS
* HTML injection
* formula injection
* unsafe workbook content

Because Excel files from “someone in finance” should never be trusted blindly.

---

# Performance

Optimized for:

* 20,000+ tickets
* large comment datasets
* fast filtering
* low memory churn

Which means:

Your browser may still survive Monday morning operations review meetings.

---

# Running The App

## Option 1 — Open Directly

```bash
index.html
```

Yes. Really.

---

## Option 2 — Local Server

```bash
python -m http.server 8080
```

Then open:

```text
http://localhost:8080
```


---

# Philosophy

This project was engineered with one core belief:

> Enterprise tooling should feel reliable, fast, understandable, and slightly intimidating in a good way.

Not like:

* a spreadsheet pretending to be software
* or software pretending not to be broken

---

# Future Ideas

Potential future upgrades:

* Kanban board
* Gantt view
* workbook encryption
* audit trails
* dependency graphs
* offline PWA mode
* plugin architecture
* Excel-powered world domination

One step at a time.

---

# Final Words

This project answers an important engineering question:

> “How far can we push browser-only architecture before someone from enterprise procurement gets nervous?”

Apparently:

Very far.

---

Use responsibly.
And please do not store nuclear launch workflows in Excel.
