# GA4 Analytics Note

Created: 2026-05-21 15:41 UTC

Measurement ID:
G-VBENV022D0

This landing page now includes the Google Analytics 4 tag in `index.html`.

Tracked:
- Page views through the GA4 base tag.
- Custom GPT outbound clicks using event name: `gpt_link_click`.
- First video play using event name: `video_play`.

Privacy note:
This analytics setup tracks interaction with the public landing page only. It does not show what users type or do inside ChatGPT conversations.


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
