# CLAUDE.md

Guidance for anyone (human or AI) working in this repo.

## Project

Website for the **Jesus Youth Family Prayer Group** at Holy Family Syro-Malabar Catholic Parish, Halifax, Nova Scotia.

- **Site title:** Jesus Youth Holy Family Parish, Halifax
- **Address:** jy.holyfamilyhalifax.ca (today it forwards to the RSVP Google Form)
- **Hosting plan:** GitHub Pages from this repo. On GitHub's free plan the repo must be public to use Pages.
- **Maintainers:** Tony Jose Kalavanal and Jobil
- **Chaplain:** Fr. Daris Cherian

## Status

**Main website: planning only. Do not build it until asked.** Decisions are still being made with the core team. Collect content and decisions here first.

One-time event pages live in `events/` (see below) and can be built when asked.

## Events

- Each event gets its own folder: `events/<event-name>-<year>/index.html`, e.g. `events/rosary-2026/`.
- Keep event pages self-contained (one HTML file, no build step) and hidden from search (`noindex`).
- After the event ends, remove home addresses and phone numbers, and keep the page as a record.
- **Current:** `events/rosary-2026/`, "മാതാവ് നമ്മുടെ ഭവനങ്ങളിലേക്ക് (Mother Mary comes to our homes)", 10-day Family Rosary, Oct 21 to 30, 7 PM. Families book through Tony on WhatsApp; Tony confirms and fills in the `DAYS` list at the top of the page's script.

## Audience

- Families of Holy Family Parish, mostly Malayali, many with young children
- People new to Jesus Youth
- Most visitors will open the site on a phone from a WhatsApp link

## Site sections (in this order)

| Section | What goes in it | Notes |
| --- | --- | --- |
| Next prayer meeting | Date, time, place, RSVP link | Update after every meeting |
| Upcoming events | e.g. 10-day Rosary in homes, Campus Alpha | Remove events once they pass |
| 9-month journey | Monthly topics and subtopics | See `content/9-month-journey.md` |
| Family prayer | Prayer in English and Malayalam, reader can switch | See `content/prayer-*.md` |
| Prayer intentions | Link to a form to send an intention | Form not created yet |
| Photos | A few photos from past meetings | Permission rules below |
| Testimonies | Short sharings from families | Only with their permission |
| Useful links | Parish website, Mass times, Jesus Youth Canada | Real links still needed |

Ideas for later: Welcome / About us, Bible verse of the month, volunteer sign-up, WhatsApp group join request, Teens prayer meeting, outreach landing page.

## Writing style

- Simple English. Many readers speak Malayalam as their first language.
- Warm and welcoming. Use the line: "All families welcome, kids too. New to Jesus Youth? Everyone's welcome."
- Say **"Family prayer meeting"**, not "Family Ministry prayer meeting".
- Avoid em dashes (—).
- Malayalam text must stay exactly as written in the content files.

## Design

- Brand colours used so far: navy `#14335C`, orange `#D9622B`, cream `#FBF3E7`. Later posters also used sage green and warm gold.
- Mobile first, fast to load, readable for older parents.
- Make sure Malayalam renders properly on phones.
- Keep it simple: plain HTML and CSS, no build step, so non-technical people can edit it on github.com.

## Rules

- **Photos:** only with parents' permission, especially when children's faces are visible.
- **Logos:** only use the Jesus Youth and parish logos once Fr. Daris has approved.
- **Prayer intentions:** keep them private to a small group. Never show them on the site.
- **No guessing:** never invent dates, links, or names. Leave a clear `TODO` instead.

## Files

| Path | What it is |
| --- | --- |
| `content/9-month-journey.md` | The nine monthly topics |
| `content/prayer-english.md` | Family prayer, English |
| `content/prayer-malayalam.md` | Family prayer, Malayalam |
| `assets/jy-logo.png` | Jesus Youth logo (approval pending) |
| `assets/parish-logo.jpg` | Holy Family Parish logo (approval pending) |
| `assets/9-month-journey.jpg` | 9-month journey poster |
| `private/` | Files kept on the maintainer's computer only, never pushed (ignored by git). Holds the Aug 23, 2026 group photo until parents approve |
| `events/rosary-2026/index.html` | Sign-up page for the 10-day Family Rosary |

## Open decisions

- [ ] Fr. Daris approves using the logos
- [ ] Parents approve the group photo (then move it from `private/` to `assets/`)
- [ ] Create the prayer intentions form, and decide who reads the intentions
- [ ] Collect real links: parish website, Mass times, Jesus Youth Canada
- [ ] Decide who updates the site after each meeting
- [ ] Core team agrees on the first version
