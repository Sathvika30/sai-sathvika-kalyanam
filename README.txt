SAI VENKAT & SATHVIKA — ATTEMPT 95 — OPTIMISED WEBSITE
======================================================
Deployment: Publish the CONTENTS of this folder (index.html and assets/) from your GitHub Pages publishing root. Do not upload the ZIP directly as a GitHub Pages web page.

What changed from Attempt 94:
- Converted large *actively used* transparent PNG artworks to visually high-quality WebP (same image dimensions, bit-identical transparency), and updated their references in HTML/CSS/JS. Gold scroll borders, placement CSS and section structure were not edited.
- Deleted unused image/SVG assets only after static-referencing safeguards, including cross-CSS paths and JS-created image sources.
- Replaced assets/audio/wedding-music.mp3 with the uploaded "Die With a Smile Indo Instrumental.mp3" (original audio bytes preserved). The music controls, original volume, pause/resume, looping, and user-initiated playback behaviour remain unchanged.
- Kept the source of all RSVP form validation, backend URL, submission logic and animation transitions exactly as Attempt 94.

IMPORTANT: RSVP sends data to a configured Google Apps Script using fetch(mode: "no-cors"). Such a response cannot prove Google Sheets saved the response. Perform a real backend row check before sharing publicly. This optimisation intentionally did NOT alter that submission flow.

Open index.html locally for preview, or serve the folder using a static host. Font requests and live RSVP delivery require the necessary network access. Check the site on real phones and verify RSVP rows in Google Sheets before publication.

---------------- ARCHIVED PREVIOUS RELEASE NOTES ----------------
SAI VENKAT & SATHVIKA — ATTEMPT 74 FINAL REFINEMENTS
===================================================
Base: uploaded Attempt 73. Applied the approved Section 1–4 editorial,
spacing, image, divider and typography changes and the global divider
standardisation. New tiny matching gold 2D SVG icons were added for the
Muhurtham lunch and Dinner & DJ dress code.

All approved standalone dividers use the exact supplied file
assets/section4/divider_2d_lotus.png. The Section 2 miniature lotus is
an extraction of that approved illustration. The top lotus within the
Section 2 frame was reduced by approximately 12% in the two frame assets.

Source interactions and RSVP form logic (external section4.js and both
inline scripts) are identical to Attempt 73. Checks on text replacements,
image references, JS syntax and asset identity pass. A live visual browser
screenshot test could not be performed in the execution environment.

IMPORTANT — EXISTING BACKEND LIMITATION
The RSVP is still a front-end prototype: no live RSVP submission endpoint
or persistent guest data storage is connected. Do not present it as a
working public RSVP collection service until the backend is connected.

PREVIEW
Extract this ZIP and open index.html in a current browser. Keep the
assets directory alongside it. Google Fonts and optional music playback
may require an internet connection.

------------------------------------------------------------
PREVIOUS CHECKPOINT NOTES

Sathvika & Sai Venkat — Wedding Website — Attempt 72
====================================================

SOURCE CHECKPOINT
Latest: Attempt 72 is based directly on the corrected Attempt 71 website.
Only the Section 4 CSS is updated for the optical-centre correction;
all other files, including scroll artwork and Sections 1–3, are unchanged.
Previous release notes are retained below for reference.

SECTION 4 — COMPLETE FRONT-END REVIEW
- Closed invitation: refined Kindly RSVP heading and an inclusive,
  warm question about joining in person.
- YES form: name, contact phone, required arrival date/time, numeric
  guest count (including yourself), approved four event icons and
  checkbox selection logic, optional DJ song/album/artist, optional note.
- NO form: name, contact phone and optional note or blessing.
- Phone format validated: 7–15 digits; optional leading country code;
  optional spaces, hyphens and matched parentheses. This is format
  validation, not country-specific number allocation verification.
- Guest counts accept positive integers only, without a dropdown.
- Back link available only prior to submission. No back to submitted form.
- Thank You screens: approved YES / NO wording, approved diya and
  livestream illustration; quiet Submit another response link.
- Reload always returns to the fresh invitation, rather than an old
  completion state; all fields reset on a new response.
- Unfurl time is 1000ms (reduced motion preference skips animation).
- Form appears as the scroll begins opening; touch scrolling does not
  trigger any JS auto-scroll correction during unfurling.
- SS monogram is the same size and the same artwork-relative position
  across closed, YES, NO and Thank You states.
- Approved thin, flat 2D lotus divider is used throughout.
- Gold decorative Submit RSVP / Submit Response SVG button background.

MATCHING COMPLETE SCROLL ARTWORK
Each state uses one complete transparent PNG image; the website does not
assemble rollers, borders, bells or the lower lotus as separate elements.
The approved scroll illustrations were edited only in their repeating
middle fabric/border length. The top 610 native rows and last 490 native
rows are unchanged compared to their respective approved master PNGs.
Responsive mobile variants keep the same 941px artwork width and exact
approved upper ornament position, with longer lengths where the small
screen requires extra room for readable fields.

BACKEND STILL PENDING
This checkpoint is a complete front-end prototype. Submitting changes
only the local screen; responses are NOT sent to the couple, to WhatsApp,
or to any database. Nothing personally identifiable is stored. A real
submission endpoint, server validation, successful-delivery handling,
and destination data protection MUST be connected before the site goes live.

HOW TO PREVIEW
Extract Attempt 72.zip and open Attempt 72/index.html in a modern browser.
If served from a website, serve the folder's contents together with its
assets subfolder. External Google Fonts / optional music may need internet.


ATTEMPT 68 REFINEMENTS
- Shared gold ornate submit-button PNG asset with editable HTML text (YES / NO).
- Back reveals closed invitation immediately and returns viewport to gold roller top.
- Open scroll images shortened, preserving identical top 610px and bottom 490px artwork.
- Specific visible phone-format tooltip on invalid input, plus existing validations.
- Thank You text/icon spacing relaxed; Sections 1-3 are unchanged.
- FRONTEND PREVIEW ONLY: no RSVP backend, storage, or delivery.


Attempt 69 animation-only refinement
- One-second progressive visual reveal of full scroll artwork and form.
- Open layout height reserved immediately; document height is never animated.
- No swipe/touch locks or forced viewport correction during unfurling.
- Back restores closed invitation immediately at its top.
- All original artwork, wording, forms, icons, validation and sections 1-3 unchanged.
- RSVP submission still demo-only; no backend connected.

Attempt 70 refinements:
- Every RSVP state change (YES, NO, Back, Submit, Submit another response) scrolls to the stationary gold roller beneath the fixed header. Native scrolling remains available during unfurl.
- Complete phone-only YES scrolls are shortened within the fabric, retaining the identical roller, borders and bottom ornament pixels; no website-time assembly.
- Form fields share a narrower centred safe width; submit and opening choice buttons are reduced proportionally.
- Existing validation, forms and backend-placeholder behaviour preserved.

Attempt 71 adjustments:
- Arrival date is now a required dropdown with November 18, 19 and 20 (2026) only.
- YES and NO forms narrowed symmetrically by 2px, increasing right and left border clearance by 1px.
- Section 1–3 artwork, RSVP scroll PNGs, animations and all other interactions unchanged.

Attempt 72 centring refinement:
- Centre the closed invitation, both RSVP forms and both Thank You screens on
  the actual maroon fabric/border midline (5 native pixels left of the PNG canvas
  centre), using one consistent container-width-relative CSS rule.
- All inputs, celebration cards, decorative submit buttons and monograms follow
  that same shared anchor. No asset resizing, editing or reconstruction.
- No validation, wording, RSVP animation or backend behaviour changed.
