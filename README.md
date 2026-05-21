# KyaniteShift GitHub Pages Landing Page

Static public landing page for KyaniteShift.

## Included files

- index.html
- README.md
- KS-CS-CARRYOVER-NOTE.md
- assets/ks-main-logo.png
- assets/ks-ff.png
- assets/ks-chatside.png
- assets/ks-sc.png
- assets/ks-cs.png
- assets/ks-ff-intro.mp4

## Deployment

Upload these files to the repository root of `mrizek-ks/KyaniteShift` and deploy with GitHub Pages:

Settings → Pages → Deploy from branch → main → /root

## Notes

- CSS is inline inside index.html.
- No API calls are used.
- No backend or OpenAI API cost is required.
- Custom GPT links open inside ChatGPT and require ChatGPT access.
- Senior Clarity now uses its live Custom GPT link. Continuity Studio currently uses a placeholder button until its final live GPT URL is available.
- The page includes a local MP4 intro video asset for KS-FF.

## Current design direction

- Main logo upper-left.
- Large “Structure before solution.” headline.
- Continuous right-side description/disclaimer/buttons panel.
- Branch cards for Main, FF, ChatSide, Senior Clarity, and Continuity Studio.
- KS-FF video section for public/social introduction.


KyaniteShift Continuity Studio / KS-CS live GPT link:
https://chatgpt.com/g/g-6a089ba1f5608191b09ef4cbc6fbce76-kyaniteshift-continuity-studio-ks-cs


## Hero left-side refinement

The hero headline was slightly reduced to make room for a short explanation of the advantage of using KyaniteShift directly beneath “Structure before solution.”


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
