# KS-CS Carryover: Updated Landing Page Package

This package updates the KyaniteShift GitHub Pages landing page with Senior Clarity, Continuity Studio, and a KS-FF promotional video asset.

## Added

- Senior Clarity logo asset: `assets/ks-sc.png`
- Continuity Studio logo asset: `assets/ks-cs.png`
- KS-FF intro video asset: `assets/ks-ff-intro.mp4`
- Senior Clarity card in Logos, Versions, and Guide sections
- Continuity Studio card in Logos, Versions, and Guide sections
- Video section: `#video`
- Navigation link to Video

## Still needed before final public update

- Senior Clarity live GPT URL has been added: https://chatgpt.com/g/g-6a08a3ad3f6c81918fae599bb72b21fc-kyaniteshift-sc-senior-clarity
- Replace the Continuity Studio placeholder button with the live KS-CS Custom GPT URL once available.
- Review mobile video playback after publishing to GitHub Pages.

## Current page purpose

The page remains a static public front door for KyaniteShift. It does not use OpenAI API calls, backend hosting, or paid infrastructure. Users open the Custom GPTs inside ChatGPT with their own ChatGPT access.


KyaniteShift Continuity Studio / KS-CS live GPT link:
https://chatgpt.com/g/g-6a089ba1f5608191b09ef4cbc6fbce76-kyaniteshift-continuity-studio-ks-cs


Hero refinement:
The left-side “Structure before solution.” headline was slightly reduced to allow a short explanation of the advantage of using KyaniteShift directly beneath it.


## Repackaged update — 2026-05-18 15:06 UTC
- Confirmed KyaniteShift Continuity Studio / KS-CS live GPT link is active:
  https://chatgpt.com/g/g-6a089ba1f5608191b09ef4cbc6fbce76-kyaniteshift-continuity-studio-ks-cs
- Updated hero left side: smaller “Structure before solution.” headline with a short advantage statement beneath it.
- Added light hero explanation for IQuartz and K-Bridge.
- Removed obsolete KS-CS placeholder note from the Versions section.


Verified repackaged update 2026-05-18 15:06 UTC: KS-CS button in the Versions section now opens https://chatgpt.com/g/g-6a089ba1f5608191b09ef4cbc6fbce76-kyaniteshift-continuity-studio-ks-cs. Hero left-side advantage text and right-side IQuartz/K-Bridge notes are included.


## GA4 analytics update — 2026-05-21 15:41 UTC

Google Analytics 4 was added to `index.html`.

Measurement ID:
`G-VBENV022D0`

Included tracking:
- Page visits.
- Outbound Custom GPT button clicks as `gpt_link_click`.
- First video play events as `video_play`.

Privacy note:
This tracks landing page visits, GPT-link clicks, and video plays. It does not provide access to user conversations inside ChatGPT.


## Feedback module update — 2026-05-21 16:15 UTC

Added a bottom-page feedback module with a mailto link to:
KyaniteShift@gmail.com

Purpose:
- invite observations from visitors
- help improve the KyaniteShift framework and branches
- avoid backend/form infrastructure
- preserve static GitHub Pages architecture

If GA4 is active, the feedback email click is tracked as:
`feedback_email_click`

No user message is collected by the website itself; the visitor chooses whether to open and send an email.


## Feedback module refinement — 2026-05-21 16:27 UTC

The feedback module was simplified for reliability.

Current approach:
- No backend.
- No form service.
- No mailto button dependency.
- Visitors are asked to send comments or feedback directly to KyaniteShift@gmail.com.

Reason:
A true form submission from a static GitHub Pages site would require a backend or third-party form service. Mailto buttons can fail depending on browser/device/default email-app configuration.


## Feedback email display fix — 2026-05-21 23:22 UTC

Updated the feedback module so the address displays as a clickable, wrapped email link:

KyaniteShift@gmail.com

The CSS now uses `word-break: break-word` and `overflow-wrap: anywhere` to prevent mobile clipping or truncated display.


## KS Papers repository prep — 2026-05-26 03:16 UTC

Added:
- `#papers` section to the landing page
- Top navigation link for Papers
- `/papers/` repository landing page
- `/papers/README.md`
- Placeholder for first paper artifact: `Trust Architecture and the Future of AI Infrastructure`

No paper PDF/DOCX artifact is included yet. This update prepares the site structure first.
