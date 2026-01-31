# App Store Rejections I Personally Faced (Apple + Google)

> **App Type:** Social Media App  
> **Timeframe:** 2025 (around DEC)

This document lists **real rejection reasons I faced firsthand** while publishing my app.
No theory. No generic policy dumps. Only practical issues that caused actual rejections.

---

## Apple App Store

### 1. Cross-platform references in metadata

**Issue**  
App description or screenshots mentioned Android or showed non-iOS UI.

**Apple Feedback**  
"App or metadata includes information about third-party platforms not relevant to App Store users."

**Fix**
- Remove all Android references
- Use iPhone-only screenshots
- Use iOS-specific wording everywhere

---

### 2. Misleading or unnecessary marketing language

**Issue**  
Using words like *first*, *best*, *only*, etc.

**Apple Feedback**  
"Misleading or inaccurate information in metadata."

**Fix**
- Describe what the app does functionally
- Avoid claims of ranking, uniqueness, or superiority

---

### 3. Reviewer misunderstanding app functionality

**Issue**  
Apple misunderstood how the app interacts with third-party platforms or how core flows work.

**Example**  
Reviewer thought the app was accessing user data incorrectly, when it was actually using standard OAuth login flow.

**Apple Feedback**  
"App functionality appears inconsistent or unclear."

**Fix**
- Explain app behavior clearly in **App Review Notes**
- Explicitly clarify what the app does and does not do
- Include step-by-step instructions for testing key flows

---

### 4. Missing or weak App Review Notes

**Issue**  
Reviewer lacked context for flows, delays, or edge cases.

**Apple Feedback**  
"App could not be fully evaluated."

**Fix**
- Add detailed App Review Notes covering:
  - Login credentials (if needed)
  - How to trigger key features
  - Expected empty states or delayed content
  - Any moderation or approval workflows

---

### 5. User-generated content moderation expectations

**Issue**  
Social app without clearly surfaced moderation explanation.

**Apple Feedback**  
Apps with UGC must include moderation tools and make them discoverable.

**Fix**
- Ensure report/block options exist and are easy to find
- Mention moderation and reporting clearly in App Review Notes
- Consider adding a "Community Guidelines" link in-app

---

## Google Play Store

### 1. Metadata policy violation due to marketing claims

**Issue**  
Using comparative or superiority language in store listing.

**Example Trigger**  
"Vibe is the first community-based social media platform"

**Google Feedback**  
"Violation of Metadata policy."

**Fix**  
Remove words like:
- first
- best
- #1
- top
- leading
- only

Stick to functional descriptions only.

---

### 2. Metadata issues across multiple locations

**Issue**  
Problematic wording existed in more than one place.

**Google Feedback**  
"Issue may be found in other locations."

**Fix**  
Audit all metadata locations:
- Full description
- Short description
- App title
- Promotional text
- Screenshot captions
- Store listing translations (all locales)

---

### 3. Child safety compliance requirements (social apps)

**Issue**  
App falls under social category and must meet child safety standards.

**Google Requirement**
- Child safety standards URL (public page)
- Designated contact for CSAE/CSAM compliance

**Fix**
- Create and host a public safety standards page
- Add a valid contact email for compliance inquiries
- Link both in Play Console under Policy declarations

---

## Key Lessons Learned

- **Apple** focuses on reviewer experience and clarity — help them understand your app
- **Google** focuses on strict metadata wording — be literal and factual
- Marketing language is the fastest way to get rejected on both platforms
- If a human reviewer can misunderstand your app, they will

---

## Final Advice for Fellow Developers

Describe **what your app does**, not **how good you think it is**.

If you can't prove it inside the app, **don't say it in the store listing**.

---

## Contributing

Faced a rejection not listed here? Open a PR or issue — let's help each other ship faster.
