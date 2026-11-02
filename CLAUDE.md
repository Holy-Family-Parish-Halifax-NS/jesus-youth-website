# CLAUDE.md

Guidance for anyone (human or AI) working in this repo.

## Project

Website for the **Jesus Youth Family Prayer Group** at Holy Family Syro-Malabar Catholic Parish, Halifax, Nova Scotia.

- **Site title:** Jesus Youth Holy Family Parish, Halifax
- **Address:** jy.holyfamilyhalifax.ca (until Oct 30, 2026 it forwards to the Rosary 2026 page; after that, point it back to the RSVP form or the main site)
- **Hosting plan:** GitHub Pages from this repo. On GitHub's free plan the repo must be public to use Pages.
- **Maintainers:** Tony Jose Kalavanal and Jobil
- **Chaplain:** Fr. Daris Cherian

## Status

**Main website: first draft built Nov 1, 2026 (`index.html` at the repo root) for the core team to review.** It is marked `noindex` until the core team approves. No WhatsApp join button (Tony's decision). The Mother Mary's Journey page ends with a "Visit our Jesus Youth family" button linking to the home page. To change the highlighted month, edit `CURRENT_MONTH` in the home page script.

One-time event pages live in `events/` (see below) and can be built when asked.

## Events

- Each event gets its own folder: `events/<event-name>-<year>/index.html`, e.g. `events/rosary-2026/`.
- Keep event pages self-contained (one HTML file, no build step) and hidden from search (`noindex`).
- After the event ends, remove home addresses and phone numbers, and keep the page as a record.
- **Current:** `events/rosary-2026/`, "മാതാവ് നമ്മുടെ ഭവനങ്ങളിലേക്ക് (Mother Mary comes to our homes)", 10-day Family Rosary, Oct 21 to 30, 7 PM. Families book through Tony on WhatsApp; Tony confirms and fills in the `DAYS` list at the top of the page's script.

### Planned: Rosary 2026 memory page (build after Oct 30, 2026)

Turn `events/rosary-2026/` into a keepsake page, "Mother Mary's Journey".

Inspired by the 10-day Rosary held in 2020 by the Jesus Youth Young Adults of St. Catherine of Siena Parish (per Tony).

- Opens with the title and a short line, e.g. "10 evenings, 10 homes, one parish family praying together."
- As the reader scrolls, a gold path draws from Day 1 to Day 10, with a small statue icon moving along it.
- One card per day: host family names, unit colour, 2 to 3 photos, one line about the evening.
- Ends with simple totals (days, units, neighbourhoods), a thank-you to all hosts, and the Prayer for Families.
- **Map:** hand-drawn style map of Halifax in the poster colours. Show **neighbourhoods only, never home addresses** (Beechville, Clayton Park, Dartmouth, Upper Sackville, Beaver Bank, Harrietsfield). The parish church can be the only exact pin.
- **Photos:** only with the host family's permission, especially when children are in them. Tony confirmed on Nov 1, 2026 that all host families agreed.
- **Done Nov 1, 2026:** home addresses and phone numbers removed from the page (neighbourhoods only), sign-up sections removed, page marked Completed. jy.holyfamilyhalifax.ca stays on this page for now (forwarding is set at the domain provider, not in the repo).
- Unit colours: St. Alphonsa purple, St. Chavara orange, St. Mariam Thresia teal, St. Mother Teresa blue, St. Thomas red, St. Euphrasia green, all units gold.

Memories collected so far:

| Day | Date | Host | Unit | Moment |
| --- | --- | --- | --- | --- |
| 1 | Wed, Oct 21 | Bibin & Febina, Beechville | St. Mariam Thresia | Angelus, Rosary, Prayer for Families, kids sang a Marian song, Bibin read the Bible, coffee and fellowship |
| 2 | Thu, Oct 22 | Franklin & Vinu, Halifax | St. Euphrasia | Beautiful prayer corner, Fr. Daris read the Bible, celebrated Jobin & Priyanka's 14th anniversary, statue handed to Jobin |
| 3 | Fri, Oct 23 | Jobin & Priyanka, Halifax | St. Chavara | Combined with St. Chavara unit prayer meeting, Fr. Daris's reflection, Kahoot quiz, anniversary celebrated again at home |
| 4 | Sat, Oct 24 | Akhil & Dona, Dartmouth | St. Thomas | Dona led all the prayers, prayer corner with flowers and lights, little ones made friends |
| 5 | Sun, Oct 25 | Parish church | All units | Rosary at 4:30 PM before Holy Mass, families from all units, altar table with candles |
| 6 | Mon, Oct 26 | Johns & Susanna, Halifax | St. Euphrasia | Angelus, Rosary, Prayer for Families, Johns read the Bible, Holy Family prayer corner, statue handed to Job |
| 7 | Tue, Oct 27 | Job & Reni, Upper Sackville | St. Mother Teresa | Beautiful lit prayer wall with statues of Mother Mary, the Sacred Heart and St. Joseph, many families kneeling in prayer, statue handed to Raphy & Lincy |
| 8 | Wed, Oct 28 | Raphy & Lincy, Beaver Bank | St. Mother Teresa | Angelus, Rosary, Prayer for Families, Bible reading; Raphy & Lincy built a special altar for Mother Mary (blue and white canopy, pink cloth, candles, teal and gold drape) |
| 9 | Thu, Oct 29 | Nyjo & Josna, Dartmouth | St. Thomas | Achan joined and read the Bible, lots of kids kneeling in prayer, Holy Family and Sacred Heart prayer corner |
| 10 | Fri, Oct 30 | Febin & Ann, Harrietsfield | St. Euphrasia | Final evening; Ann led the prayers, Achan read the Bible; beautiful wooden prayer wall with Sacred Heart and Holy Family pictures |

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

Decisions from the Nov 1, 2026 review (Tony):

- Next prayer meeting: Sat, Nov 21, shown with a **"Tentative"** tag until the venue is confirmed.
- Upcoming events: night vigil Fri, Nov 6, shown with a **"Tentative"** tag.
- 9-month journey: we are on **Month 3** (Jesus at the Center of the Home). Highlight it.
- Family prayer: no changes.
- Prayer intentions: leave out for now.
- Photos: all approvals received, including the Aug 23, 2026 group photo.
- Testimonies: keep the section with a placeholder; Tony is collecting sharings this week.
- Useful links: Jesus Youth Canada is https://jesusyouth.ca/ . Parish website is https://holyfamilyhfx.ca/ . Mass times are not copied onto our site; the "Mass times" card links to the parish website so they never go out of date.
- Sharing plan: share the Mother Mary's Journey link first; its last section links to the home page.

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
- **Logos:** Fr. Daris has approved using the Jesus Youth and parish logos.
- **Prayer intentions:** keep them private to a small group. Never show them on the site.
- **No guessing:** never invent dates, links, or names. Leave a clear `TODO` instead.

## Files

| Path | What it is |
| --- | --- |
| `index.html` | Home page (draft for core team review) |
| `favicon.ico`, `assets/favicon-32.png`, `assets/apple-touch-icon.png` | Jesus Youth logo as the browser tab icon and phone home-screen icon (linked from every page) |
| `assets/group-photo-aug-2026.jpg` | Aug 23, 2026 group photo, web size (parents approved Nov 1, 2026) |
| `content/9-month-journey.md` | The nine monthly topics |
| `content/prayer-english.md` | Family prayer, English |
| `content/prayer-malayalam.md` | Family prayer, Malayalam |
| `assets/jy-logo.png` | Jesus Youth logo (approved) |
| `assets/parish-logo.jpg` | Holy Family Parish logo (approved) |
| `assets/9-month-journey.jpg` | 9-month journey poster |
| `private/` | Files kept on the maintainer's computer only, never pushed (ignored by git). Holds the Aug 23, 2026 group photo until parents approve |
| `events/rosary-2026/index.html` | "Mother Mary's Journey" memory page for the 10-day Family Rosary (built Nov 1, 2026) |
| `events/rosary-2026/schedule.html` | The original sign-up page, kept as a record (no addresses or phone numbers) |
| `events/rosary-2026/photos/` | 3 photos per day (`dayNN-1.jpg` to `dayNN-3.jpg`), used with host families' permission |
| `assets/fonts/noto-serif-malayalam/` | Malayalam font used for printed material (SIL Open Font License) |
| `assets/fonts/web/` | Subset web fonts for the site: Lora (headings, English prayer) and Noto Serif Malayalam (SIL Open Font License) |
| `print/prayer-card/` | Folded wallet prayer card: print-ready PDF, previews, printing notes |

## Open decisions

- [x] Fr. Daris approves using the logos
- [x] Parents approve the group photo (approved Nov 1, 2026; move it from `private/` to `assets/` when building the site)
- [ ] Create the prayer intentions form, and decide who reads the intentions
- [x] Collect real links: parish website, Mass times, Jesus Youth Canada (Nov 1, 2026)
- [ ] Decide who updates the site after each meeting
- [ ] Core team agrees on the first version
