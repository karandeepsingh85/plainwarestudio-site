# Website Update Requests

When you need to update the Plainware Studio website (https://plainwarestudio.com),
produce a structured update request using the format below.

Do not push to the website repo directly. The website is maintained by a separate
Claude Code instance. Your job is to produce the spec. The human will relay it.

## What You Own

You may propose changes to your app's sections only:
- Homepage: your app's card
- Privacy page: your app's section
- Support page: your app's support topics

Do not propose changes to:
- The studio hero or brand copy
- Another app's section
- Global styles, layout, or site structure
- Routes or file names

## Update Request Format

When something changes that affects the website, produce this:

---
## Website Update Request

App: [your app name]
Sections affected: [homepage / privacy / support — list only what changes]
Reason: [one-line summary of why this is changing]

### [Section name] changes

[Describe exactly what to add, change, or remove. Quote existing text where you are replacing it.]

---

## Rules

- Only state what is actually true about the app.
- Do not add tracking, analytics, cookies, or permissions language unless confirmed true.
- Keep privacy claims specific and factual.
- Keep support topics practical and short.
- One update request per meaningful change. Do not batch unrelated changes.
