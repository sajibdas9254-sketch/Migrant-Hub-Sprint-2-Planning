# Sprint 2 Backlog

**Project:** Migrant Hub
**Sprint 2:** 3 September – 17 September 2026
**Goal:** Build the React frontend and the Express backend separately, and agree the API
between them. Do not connect them.

---

## First — both teams together

This blocks everyone, so it happens first.

| # | Task | Who | When |
|---|---|---|---|
| 1 | Agree the API contract: endpoints, methods, request JSON, response JSON, field names and types | All five | Day 1–2 |
| 2 | Decide that Must Do content comes from the backend, not hardcoded in the frontend | All five | Day 1 |
| 3 | Commit the API contract to the repo so both teams work from the same file | Sehwinder | Day 2 |

Once this is done, the two teams can work without waiting for each other.

---

## Frontend — Sajib, Pratham, Prabhleen

Build in this order. If we run out of time, the last two are the ones we drop.

| # | Task | Notes |
|---|---|---|
| 1 | Set up the React project and folder structure | |
| 2 | Build the navbar and footer as shared components | Used on every page |
| 3 | Set up routing so the navbar links change the page | |
| 4 | Homepage | Hero, search box, category chips, post cards |
| 5 | Blog list page | |
| 6 | Single post page | |
| 7 | Write a post form, with the live 512-word counter | |
| 8 | Must Do overview page | Six cards |
| 9 | Must Do detail page | One component, different content for DVV, police, bank, HSL, Tuudo, housing |
| 10 | Login page | Only shows "Login successful" — no real login |
| 11 | Register page | Only shows "Registration successful" |
| 12 | Mock data file, written in the same shape as the agreed API | |
| 13 | Styling to match the Sprint 1 prototype | Same colours, same layout |
| 14 | Make every page work on a phone screen | |
| 15 | Community page | Drop this first if we run short |
| 16 | Search results page | Drop this second if we run short |

---

## Backend — Sehwinder, Yun

Posts first. It is the main thing our product does, and the other two are simpler versions
of the same pattern.

| # | Task | Notes |
|---|---|---|
| 1 | Set up the Express server | |
| 2 | Set up the MVC folder structure | models, controllers, routes, middleware |
| 3 | Create mock/array data for posts | |
| 4 | Post model and data structure | |
| 5 | Post controller with create, read, update, delete | |
| 6 | Post routes | |
| 7 | Test post endpoints in Postman | |
| 8 | Must Do items — model, controller, routes | Same pattern as posts |
| 9 | Communities — model, controller, routes | |
| 10 | Error handling middleware | |
| 11 | Refactor from array data to MongoDB and Mongoose | After it is taught in class, week 4 |
| 12 | Test everything again in Postman after the refactor | |

---

## Process work — everyone

Easy to forget, and it is worth marks.

| # | Task | Who |
|---|---|---|
| 1 | Write one line per daily scrum, committed to the repo | Sajib, then the next Scrum Master |
| 2 | Run the Sprint 2 retrospective using the 4Ls format — Liked, Learned, Lacked, Longed for | Whole team |
| 3 | Run the Sprint Review and write down what we finished | Whole team |
| 4 | Write down what each person did, with commits and pull requests as evidence | Whole team |
| 5 | Each person: LLM self-assessment of their frontend code | Everyone |
| 6 | Each person: LLM self-assessment of their backend code | Everyone |
| 7 | Build the 10–12 minute presentation | Sehwinder |
| 8 | Run a timed rehearsal before the presentation | Whole team |

**Open question for the teacher:** items 5 and 6 say every member does both. Three of us
only work on frontend and two of us only on backend, so we need to know whether we assess
only the code we wrote, or whether everyone should commit something on both sides.

---

## Rough plan

**Week 1 (3–10 September)**
Agree the API. Frontend sets up the project, navbar, routing, and the first pages. Backend
sets up the server, MVC structure and posts with array data. Test in Postman.

**Week 2 (10–17 September)**
Frontend finishes the remaining pages, forms, styling and responsive layout. Backend adds
Must Do and communities, then refactors to MongoDB and Mongoose. Write the process
documents, do the self-assessments, build and rehearse the presentation.

---

## Not in this sprint

- Connecting the frontend to the backend
- Real login, passwords, JWT or sessions
- API documentation
- Automated tests
- The AI feature

These are Sprint 3. We are not starting them early, even if we finish ahead of time.
