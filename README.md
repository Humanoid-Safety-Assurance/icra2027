# Assurance Under Change

Website for **Assurance Under Change: Keeping Learning-Enabled Humanoid Robots Safe After Deployment**, a proposed full-day workshop at ICRA 2027.

Final workshop acceptance and scheduling are pending. The proposed date is **24 or 28 May 2027**, at Coex, Seoul, South Korea.

## Website

This repository contains the independent ICRA workshop website: [Humanoid-Safety-Assurance/icra2027](https://github.com/Humanoid-Safety-Assurance/icra2027). Workshop content was aligned with the organizers' working proposal on November 1, 2026. The page includes a tentative two-column agenda from 08:30 to 18:00, the shared warehouse-humanoid discussion case and its original worker-access condition, concrete discussion-record fields, and planned contribution routes. All agenda times are tentative; no talk number is assigned to a speaker.

Planned papers are 2–4 non-archival pages plus references, with two non-conflicted reviewers. A separate brief-abstract route supports fresh ideas without an accepted paper; paper acceptance does not guarantee a lightning slot. The call is not open, and submission instructions, deadlines, the final schedule, talk titles, and speaker roles remain pending. Speaker and organizer profiles were checked against their academic, institutional, or professional pages on October 29–30, 2026.

- `index.html` — workshop page
- `styles.css` — responsive styles
- `favicon.svg` — local icon
- `assets/banner/` — generated humanoid illustration and its generation prompt
- `assets/people/` — original portraits and source references

No dependencies or build step are required. Preview from this directory:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open `http://127.0.0.1:8000/`.

## Publication status

GitHub Pages publishes the root of `main` at:

[https://humanoid-safety-assurance.paiagent.ai/icra2027/](https://humanoid-safety-assurance.paiagent.ai/icra2027/)

The project inherits the organization's Pages domain. The existing Humanoids 2026 website is maintained in a separate repository; this project uses only its own styles and image assets.

Bowen Weng, Ibrahim Habli, Taisuke Kobayashi, and Haimin Hu have agreed to participate, subject to final workshop acceptance and scheduling. Haimin Hu's profile and portrait were added on October 30, 2026. Other candidates are not listed as speakers. Talk titles have not been announced.

Two additional speaker positions are shown as “To be announced,” consistent with the planned six invited talks. The four speaker profiles use a two-column desktop layout. Portraits use rectangular 4:5 frames with individual framing in `styles.css`. Xinye Liu is represented by initials until a verified photograph is available.

Confirm workshop acceptance, the final date, and submission details before updating the corresponding public claims. Portrait and biography sources are recorded in [`assets/people/SOURCES.md`](assets/people/SOURCES.md).

The organizing-experience paragraph links to PI² 2025, RSS 2026, IROS 2026, and ICRA 2026 with Chuchu Chen's and Guoquan Huang's respective roles. Prior-event photographs are intentionally excluded from this website at the user's request.

The hero uses a generated humanoid-laboratory illustration, a translucent dark-teal text panel, and a separate event-information strip. On narrower screens, the image and text stack to preserve the complete robot. The built-in image-generation tool and exact prompt are documented in [`assets/banner/SOURCES.md`](assets/banner/SOURCES.md). It is a conceptual illustration, not a photograph from this proposed workshop.
