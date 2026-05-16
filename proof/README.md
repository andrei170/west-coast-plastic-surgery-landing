# Proof / Screenshot Capture Instructions

> Aaron: read this at T-30 minutes before the meeting.

This folder is where you save the live screenshots that prove the bombshell. Andrei could not capture these in the audit because Instagram is login-walled and Meta Ad Library was bot-blocked, so the proof has to be captured fresh on your phone the morning of the meeting.

## What to capture

1. **`ig-profile.png`** — Open https://www.instagram.com/westcoastplasticsurgerysrq/ on your phone in the Instagram app while logged in. Screenshot showing follower count, post count, bio.
2. **`ig-recent-posts.png`** — Same handle, scroll to recent posts. Screenshot showing the last 6 to 9 posts (content mix: before/afters? surgeon-on-camera? testimonials? marketing graphics?).
3. **`serp-best-plastic-surgeon-sarasota.png`** — Google search "best plastic surgeon sarasota" on your phone. Screenshot the AI Overview at the top.
4. **`serp-mommy-makeover-sarasota.png`** — Google "mommy makeover sarasota." Screenshot the AI Overview.
5. **`serp-rhinoplasty-sarasota.png`** — Google "rhinoplasty sarasota best surgeon." Screenshot the AI Overview.
6. **`serp-facelift-sarasota.png`** — Google "facelift sarasota." Screenshot the AI Overview.
7. **`serp-breast-aug-sarasota.png`** — Google "breast augmentation sarasota." Screenshot the AI Overview.
8. **`serp-tummy-tuck-sarasota.png`** — Google "tummy tuck sarasota." Screenshot the AI Overview.
9. **`serp-plastic-surgery-sarasota.png`** — Google "plastic surgery sarasota." Screenshot the AI Overview.
10. **`meta-ad-library.png`** — Visit https://www.facebook.com/ads/library/?q=west+coast+plastic+surgery+sarasota on your phone. Screenshot showing whether any ads are currently running.
11. **`competitor-sessa-ig.png`** — Visit https://www.instagram.com/sarasotasurgicalarts/ (Dr. Sessa, 163K followers). Screenshot follower count and recent post cadence.

## Filename rules

- Lowercase, hyphens-only, descriptive (the names above)
- PNG preferred; JPG fine if your iPhone or Android default outputs JPG
- Crop tightly (don't include your phone notification bar if possible)

## What Aaron does with these screenshots

- Bring them on your phone to the meeting (already in your Photos app from step 1).
- When you deliver the bombshell on slide 4, swipe through `serp-best-plastic-surgeon-sarasota.png`, `serp-rhinoplasty-sarasota.png`, `serp-facelift-sarasota.png` so Dr. Lambiris can see the AI Overviews himself. Show the screen, not the cropped version, so he sees the date stamp.
- After the meeting, AirDrop or text these to Andrei so he has them on file. Andrei will use them on the follow-up call with Dr. Lambiris to validate the audit.

## What if Google's AI has updated to cite West Coast in the 48 hours since the audit

Possible but unlikely. If `serp-best-plastic-surgeon-sarasota.png` now shows West Coast Plastic Surgery cited in the AI Overview, do not lie about the score. Adjust the bombshell line in the room from "0 of 7" to whatever the new number is ("1 of 7" or "2 of 7"). The reframe still holds: even one citation is luck without schema. The fix is still the same fix.

## DO NOT capture

- Patient before/after photos from anyone's Instagram or website. ASPS Code of Ethics + HIPAA.
- The interior of Dr. Lambiris's office without his consent.
- Anything from his GBP that contains patient reviews with names (paraphrase if needed, do not screenshot).

---

This folder ships to the live hub as `/proof/`. If you populate it before pushing, the screenshots are accessible at https://andrei170.github.io/west-coast-plastic-surgery-hub/proof/ as live evidence (handy for the follow-up call with Dr. Lambiris's marketing person).

If you populate it AFTER the meeting, run `bash Scripts/deploy-prospect.sh west-coast-plastic-surgery --skip-preflight --skip-lint` to re-push the hub repo with the screenshots embedded.
