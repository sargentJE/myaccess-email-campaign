# Lead Magnet: 5 Things Disabled Users Find That Tools Miss

A one-page PDF to capture leads who aren't ready for the webinar. Gate with email only.

---

## Use cases

- Alternative CTA for email 1-3 non-converters
- LinkedIn lead gen form
- Exit intent on landing page
- Something tangible to share in DMs

---

## Content

### Headline
**5 Things Disabled Users Find That Automated Tools Miss**

### Subhead
Real examples from our testing – the gap between "passes checks" and "actually works."

---

### 1. Form labels that exist but aren't connected

**What the scan says:** "All form fields have labels" ✅

**What users experience:** Screen reader announces "edit blank" for every field. No indication of what to type where.

**Real quote:** "I couldn't tell which fields were which. I had no idea if I was typing my name or email address. I eventually gave up."

**The fix:** Labels need to be programmatically linked to fields, not just visually positioned near them.

---

### 2. Focus indicators that pass but are invisible

**What the scan says:** "Focus indicator present" ✅

**What users experience:** Focus state exists in the CSS, but it's the same colour as the background. Keyboard users can't see where they are.

**Real quote:** "I couldn't see which element had focus. I was essentially navigating blind, counting tab presses and guessing where I was on the page."

**The fix:** Test focus states against your actual colour scheme, not just whether they exist.

---

### 3. Navigation that requires 60+ tabs to reach

**What the scan says:** "All interactive elements are keyboard accessible" ✅

**What users experience:** Focus order is wrong. Users have to tab through dozens of elements to reach the main menu.

**Example:** We tested a site where the navigation menu looked fine with a mouse. But keyboard users had to press Tab 60+ times before focus reached it. Most gave up.

**The fix:** Check focus order matches visual layout. Skip links need to actually work.

---

### 4. Buttons that just say "button"

**What the scan says:** "Button has accessible name" ✅

**What users experience:** Screen reader announces "button" with no context. User has no idea what will happen if they click.

**Example:** A checkout flow where the "Pay Now" button just announced "button". No amount, no action, nothing.

**The fix:** Buttons need descriptive text or aria-labels that explain what they do.

---

### 5. Alt text that technically exists but says nothing

**What the scan says:** "Image has alt text" ✅

**What users experience:** Alt text is "image1.jpg" or "banner" or just empty quotes.

**Real quote:** "The accessibility statement says all images have alt text. However, the majority of images I've found have been unlabelled. It makes me feel as though the website is not built for screen reader users."

**The fix:** Alt text should describe the content or purpose, not just exist.

---

### Footer

**Want to see the full gap?**

We're running a free session in January showing what happens when real disabled users test sites that "passed" automated checks.

[Register for the webinar →](https://www.myvision.org.uk/disabled-user-testing/)

---

**MyVision Oxfordshire**
Supporting people living with sight loss since 1850.
Registered Charity No. 1140556

---

## Design notes

- One page, PDF format
- Clean, scannable layout
- Use brand colours
- Each section: scan result → user reality → quote (where available) → fix
- CTA at bottom to webinar/landing page
- No form fields in the PDF itself – gating happens before download

## Distribution

- Email 1-3: Add as secondary CTA ("Not ready for the webinar? Grab this quick guide instead")
- LinkedIn: Pin to profile, share in DMs, use as conversation starter
- Landing page: Offer as alternative for people who don't register
- Post-webinar: Include in replay email as additional resource
