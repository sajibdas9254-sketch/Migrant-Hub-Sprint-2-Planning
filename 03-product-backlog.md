# Product Backlog

**Project:** Migrant Hub — student onboarding and blogging platform
**Last refined:** 3 September 2026 (end of Sprint 1)

Ordered by value and dependency — item 1 is the highest priority. Items near the top are
refined and estimated; items near the bottom are deliberately left rough, because we may
not build them for several sprints.

---

## Ordered backlog

| # | User story | Epic | Points |
|---|---|---|---|
| 1 | As an arriving student, I want a checklist of what to do after landing, so that I do not miss an official step. | Must Do | 3 |
| 2 | As an arriving student, I want a DVV registration page with the documents and an official link, so that I know what to bring. | Must Do | 2 |
| 3 | As an arriving student, I want a police and residence permit page, so that I can complete my identity verification. | Must Do | 2 |
| 4 | As an arriving student, I want a bank account page, so that I know which documents I need to open one. | Must Do | 2 |
| 5 | As a new student, I want an HSL travel card page, so that I can use public transport from day one. | Must Do | 2 |
| 6 | As a student, I want a Tuudo page, so that I can access student services. | Must Do | 2 |
| 7 | As an arriving student, I want housing guidance with HOAS and other links, so that I can find accommodation. | Must Do | 2 |
| 8 | As a visitor, I want to read a blog post, so that I can learn from students who arrived before me. | Blog | 2 |
| 9 | As a visitor, I want to register and log in, so that I can write posts under my own name. | Auth | 5 |
| 10 | As a student, I want to write a post of up to 512 words with a live word counter, so that I can share advice concisely. | Blog | 5 |
| 11 | As a visitor, I want to browse and search posts by category, so that I can find answers to my question. | Blog | 3 |
| 12 | As a newcomer, I want to join a community, so that I can follow posts from people in my situation. | Community | 8 |
| 13 | As a student, I want an overview, tags and a category generated when I publish, so that others can find my post. | AI | 8 |
| 14 | As an admin, I want to review and remove posts, so that the platform stays useful and safe. | Admin | 5 |

## Future items — deliberately unrefined

These are recorded so they are not lost, but they are not estimated and not planned for a
specific sprint.

- Community chat, so members can ask quick questions.
- Community events, so members can meet people in person.
- A **Places** category — added after the Sprint 1 AI spike, which showed that a post about
  visiting somewhere in Helsinki has no home in our current six categories.

## Removed

- **Restaurant listing.** Cut during the Sprint 1 review: Google Maps already does this
  better than we could. Students writing about food experiences stays in scope as blog
  content; a directory of restaurants does not.
- **Housing booking.** We cannot integrate with HOAS, so housing is a guide with official
  links (item 7), not a booking feature.

## How this backlog is ordered

Value and dependency, in that order:

- **Must Do first** because it is cheap to build, it is the reason a new student opens the
  site at all, and it is what makes us more than a blogging platform.
- **Reading before writing**, because a platform with no posts to read has nothing to offer
  a first-time visitor.
- **Communities and AI last**, because both depend on posts existing first.

## Notes on refinement

Changes made during the Sprint 1 refinement session:

- Split the original "Must to do" card into five separate stories (items 2–6). As one card
  it could not be estimated and there was no way to say when it was done.
- Added the AI stories, which were missing from the board entirely despite AI being the
  central feature of the product.
- Removed duplicate cards and rewrote titles into user story form.
- Estimated using relative sizing, anchored on "read a blog post" as 2 points.
- Added acceptance criteria to the top items.
