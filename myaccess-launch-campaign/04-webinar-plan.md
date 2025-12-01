# Webinar Plan: Beyond Automated Testing

**Date:** Friday, 30th January 2025
**Time:** 10am – 11am
**Format:** Online, free
**Presenter:** Jamie Sargent, Technology & Equipment Officer, MyVision Oxfordshire

The webinar is the main conversion point. It turns abstract stuff from the emails into something people can actually see.

---

## The Story Arc

The webinar follows a clear narrative:

1. **The problem is bigger than you think** (slides 1-13)
2. **Here's what actually works** (slides 14-19)
3. **Here's how we help** (slides 20-28)
4. **Here's what to do next** (slides 29-31)

---

## Full Slide-by-Slide Breakdown

### Part 1: Setting Up the Problem (Slides 1-5)

**Slide 1: Title – "Beyond Automated Testing"**
- Subtitle: "The Benefit Of Real Disabled User Testers"
- Your name, role, organisation
- **Talk to it:** Brief intro, one line on the problem ("most 'accessible' sites still fail disabled users in practice"), one line on what they'll get ("how to plug disabled user testing into your existing workflow without blowing budgets or timelines").

**Slide 2: "Today You'll Discover"**
Three outcomes:
- Why 94.8% of "compliant" sites actually fail
- The testing method automated tools can't replicate
- How to integrate authentic accessibility into proposals
- **Talk to it:** Reassure them this is practical, not theoretical. They'll leave with real ways to use DUT.

**Slide 3: "Quick Poll"**
- Prompt: "Which best describes your current accessibility testing approach?"
- Options (verbal/poll): Mostly automated, some manual, we don't really test, etc.
- **Talk to it:** Gauge the room. Normalise all answers. Use responses to justify why the rest matters.

**Slide 4: "The Uncomfortable Truth" (Tim Berners-Lee quote)**
> "The power of the Web is in its universality. Access by everyone regardless of disability is an essential aspect."
- **Talk to it:** Anchor in the original vision of the web. Set up the tension between ideal and reality. Pivot to: "Let's look at what's really happening…"

**Slide 5: "The Barriers Faced"**
- "12 Issues Found – Mostly Compliant"
- "Actually Unusable for Blind Users"
- **Talk to it:** Describe the scenario – an "almost compliant" site from an audit. Checklists ≠ lived experience.

---

### Part 2: The Specific Barriers (Slides 6-11)

**Slide 6: "The Visual Gap: Contrast & Color"**
- Low contrast text excludes 2.2 billion people globally
- Most common WCAG failure
- Examples: Grey on dark, "Click the red button" fails for colour-blind users
- WCAG AA 4.5:1 requirement
- **Talk to it:** Not pixel-peeping – this is mainstream. Show how brand decisions quietly lock people out.

**Slide 7: "The Navigation Maze: Keyboard Accessibility"**
- Many users rely entirely on keyboard
- Barriers: Focus traps, invisible focus (outline: none;), illogical tab order
- **Talk to it:** "If they can't tab to it, they can't use it." Invite them to imagine unplugging their mouse.

**Slide 8: "The Semantic Void: Screen Readers Need Structure"**
- Bare `<span>` is meaningless – use `<button>` or `<a>`
- Heading hierarchy – don't skip levels
- Every `<input>` needs a `<label>` – placeholders aren't enough
- **Talk to it:** "Table of contents" analogy for headings. Form labels help everyone, not just screen reader users.

**Slide 9: "The Silent Content: Images, Captions & Transcripts"**
- Alt text: describe purpose, empty alt="" for decorative, missing alt = filename read aloud
- Captions: aim for equivalent experience, auto captions often inaccurate
- Transcripts: help SEO and cognitive access
- **Talk to it:** Quick "good vs bad" alt example. Transcripts are cross-benefit, not just accommodation.

**Slide 10: "Navigating the Invisible – Experience: Screen Reader"**
- Imagine turning off your monitor and navigating by audio only
- 100% dependent on code structure
- Classic anti-pattern: `<span>` with onClick instead of real button
- **Talk to it:** Ask them to close their eyes and picture it. Connect DOM concepts to "what do I even do on this page?"

**Slide 11: "Motor Impairments"**
- Switch device access: single switch scanning through every element
- Menus with 50 links and no "Skip to content" are exhausting
- Precision & touch: users with tremors struggle with small targets
- Minimum 44×44 CSS pixels with padding
- **Talk to it:** "Nothing important should be smaller than your fingertip."

---

### Part 3: The Evidence (Slides 12-15)

**Slide 12: "Automated Tools vs. Reality"**
- "Real testing footage with Sarah, blind JAWS user"
- **Talk to it:** Introduce Sarah. Position the clip as theory meets reality. Debrief the mismatch after playing it.

**Slide 13: "The Gap Is Real"**
Key stats:
- 94.8% of top websites fail WCAG (WebAIM 2025)
- ~70% of issues missed by automation
- ~30% detection rate for the best tools
- **Talk to it:** Walk through each stat, tie back to Sarah's demo. "Automated tools aren't bad – they're incomplete by design."

**Slide 14: "The Agency Dilemma"**
Three problems:
- Legal Risk: clients face lawsuits, agencies face liability
- Pricing Pressure: can't charge premium without proof
- Disadvantage: losing RFPs to agencies with authentic testing
- **Talk to it:** Acknowledge they're juggling budgets and risk. Frame DUT as reducing risk and increasing deal value.

**Slide 15: "What Automated Tools Miss"**
Categories:
- Assistive tech compatibility (works in JAWS, fails in NVDA)
- Complex interactions (multi-step forms, dynamic content)
- Context & comprehension (technically correct but confusing)
- Real-world usage patterns (keyboard traps, focus issues)
- Cognitive load (overwhelming navigation, unclear language)
- **Talk to it:** Pick 1-2 concrete examples. This isn't an attack on tools – it's a scope issue.

---

### Part 4: The Solution (Slides 16-19)

**Slide 16: "Manual Auditing: The Essentials"**
Opens with: "There's a better way. Real disabled users. Real results."
Then lists baseline checks:
- Keyboard testing (unplug mouse)
- Zoom testing (200%)
- Screen reader basics (NVDA, VoiceOver)
- High contrast mode
- Tools: Lighthouse, axe DevTools, WAVE
- **Talk to it:** These are table stakes. Encourage them to adopt one new check this week. Use "Real disabled users. Real results." to segue to DUT.

**Slide 17: "The Missing Link – Real Disabled User Testing"**
- Title slide naming DUT explicitly
- **Talk to it:** "This is the core idea. This is where MyVision comes in."

**Slide 18: "Disabled User Testing (DUT)"**
Definition: "Authentic accessibility validation using real people with disabilities"
Tester groups:
- Screen reader users (blind/low vision)
- Keyboard-only users
- People with motor impairments
- Cognitive diversity (dyslexia, ADHD, autism)
"The Gold Standard: Real User Tester" – Experience > Compliance
- **Talk to it:** Walk through each group. DUT is structured and repeatable. Partnership with disabled communities, not tokenism.

**Slide 19: "Comparing Testing Approaches"**
3-column comparison: Automated / Expert Audits / DUT

| | Automated | Expert Audits | DUT |
|---|---|---|---|
| Coverage | 30% | 60-70% | 100% real-world |
| Perspective | Misses context | Theory-based | Lived experience |
| Character | Fast/cheap | Thorough/expensive | Authentic/defensible |

DUT labelled "The Gold Standard"
- **Talk to it:** Best setups use all three layers. Suggest where each fits in their projects.

---

### Part 5: How It Works (Slides 20-28)

**Slide 20: "The Solution"**
High-level elements:
- Partnership (join the programme)
- Validation (testing by real users against WCAG)
- Portal (MyAccess transparency)
- £500 Partner rate per test
- **Talk to it:** Concept to concrete offer. Explain partnership positioning (support agencies, don't compete). Emphasise portal and video evidence.

**Slide 21: "What's Your Biggest Concern?"**
- Opens space for objections: cost, time, sales, process
- **Talk to it:** Invite honest concerns. Use answers to tailor the rest.

**Slide 22: "Twelve Months Later"**
Future state metrics:
- 100% client retention (no losses due to accessibility)
- +40% RFP win rate on accessibility-focused projects
- +18% project value (DUT standard in proposals)
- 0 legal issues (confident recommendations)
- **Talk to it:** Composite outcome / example scenario. Emphasise business upside.

**Slide 23: "How DUT Actually Works"**
Four steps:
1. Agency submits site via MyAccess Portal
2. MyVision assigns disabled testers (screen reader, keyboard, cognitive, etc.)
3. Users test against WCAG criteria; sessions recorded
4. Full report generated (video + remediation guidance)
- **Talk to it:** Plain language walkthrough. Reassure on turnaround, integration, and how few people need to be involved their side.

**Slide 24: "MyAccess Portal Walkthrough"**
- Dashboard, video evidence
- Screenshots/demo of portal
- **Talk to it:** Show login, in-progress tests, completed tests, reports and videos. Stress how this supports client questions ("Can you prove you tested with disabled users?").

**Slide 25: "What Makes DUT Different"**
"Not just another accessibility service"
Key contrasts:
- Real disabled users – not simulations
- Video evidence – not just text reports
- WCAG + usability – not just compliance
- UK-based testers – local context
- Partnership – we don't compete
- **Talk to it:** One-liner per contrast. "Your clients can see their journeys breaking or working in the video."

**Slide 26: "Integration & Pricing"**
"How agencies use DUT in practice"
Usage patterns:
- As a line item in proposals
- As a pre-launch gate
- As annual checks
- **Talk to it:** 2-3 typical patterns for different agency sizes. Connect back to Agency Dilemma slide.

**Slide 27: "Simple, Transparent Pricing"**
Two tiers:

| | Partner Tier | Ad Hoc |
|---|---|---|
| Price | £500/test | £650/test |
| Commitment | 10+ tests/year | None |
| Benefits | Priority scheduling, co-marketing, team training | Pay as you go, standard turnaround |

Note: 15-20% markup typical for agencies
- **Talk to it:** Partner tier for agencies baking DUT into their offering. They're free to price it how they wish to clients.

**Slide 28: "When to Deploy DUT"**
Three timing options:
- Design phase – test prototypes
- Pre-launch – most common
- Post-launch – annual monitoring
- **Talk to it:** Quick example for each. Earlier = cheaper fixes, but any stage is better than none.

---

### Part 6: Close & CTA (Slides 29-31)

**Slide 29: "Language That Works For Your Clients"**
Example phrasing:
> "We employ real disabled user testing, not just automated scans. This ensures authentic accessibility that protects your organization."

Talking points:
- Educate the gap (70% issues missed)
- Risk mitigation
- Avoid "compliance theatre"
- Focus on real audience (serving users, not lawyers)
- **Talk to it:** Encourage adaptation to their tone. Highlight "serving users, not lawyers" as powerful reframing.

**Slide 30: "Take Action Today"**
Two CTAs:
- Apply for Partner Tier – "Ready to integrate DUT?"
- Download Toolkit – "Get templates & resources"
- **Talk to it:** Explain what happens after each action. Partner application → onboarding call. Toolkit → proposal wording, example reports.

**Slide 31: "Your Questions"**
- "Submit via Q&A feature"
- "We'll answer as many as possible in the next 7 minutes"
- **Talk to it:** Invite any type of question. Reassure you're happy to stay longer if needed.

---

## Timing Guide

| Section | Slides | Duration |
|---------|--------|----------|
| Intro & Problem Setup | 1-5 | 8 mins |
| Specific Barriers | 6-11 | 10 mins |
| Evidence & Stats | 12-15 | 8 mins |
| The Solution | 16-19 | 7 mins |
| How It Works | 20-28 | 15 mins |
| Close & CTA | 29-30 | 5 mins |
| Q&A | 31 | 7+ mins |
| **Total** | | **60 mins** |

---

## Key Stats to Remember

- **94.8%** of top websites fail WCAG (WebAIM 2025)
- **~70%** of issues missed by automation
- **~30%** detection rate for best tools
- **2.2 billion** people affected by low contrast globally
- **44×44 CSS pixels** minimum touch target

---

## Real User Quotes to Use

**On form accessibility:**
> "I couldn't tell which fields were which on the contact form. I had no idea if I was typing my name or email address. I eventually gave up."

**On keyboard navigation:**
> "I rely on keyboard navigation due to my motor disability. On your website, I couldn't see which element had focus. I was essentially navigating blind, counting tab presses and guessing where I was on the page."

**On the emotional impact:**
> "Very limiting, degrading, humiliating, discriminatory, frustrating, depressing, marginalising, excluding, unfair... it just feels like we are worth less than others sometimes. Like we don't matter."

**On false accessibility claims:**
> "Ironically, the accessibility statement says all images have alt text. However, the majority of images I've found on this website have been unlabelled. It makes me feel as though the website is not built for those who use screen readers."

---

## Polls & Engagement Points

**Slide 3 – Opening Poll:**
"Which best describes your current accessibility testing approach?"
- Mostly automated tools (Lighthouse, WAVE, etc.)
- Some manual checks alongside automation
- We don't really test accessibility specifically
- We've used disabled user testing before

**Slide 21 – Concerns Poll:**
"What's your biggest concern about offering disabled user testing?"
- Cost / pricing
- Time / turnaround
- Selling it to clients
- Process / integration
- Something else (drop in chat)

---

## Objection Handling (for Q&A)

| Objection | Response |
|-----------|----------|
| "This sounds expensive" | £500/test at partner rate. Can be passed through as a line item. Often becomes profit-neutral or positive when included in proposals. |
| "Our clients won't pay for this" | Works especially well for tenders – councils, universities, charities. Clear deliverable, competitive differentiator. |
| "We already use automated tools" | So do we. We run the scans too. This is what you layer on top – the human experience automated tools can't see. |
| "We don't have time to manage testers" | You don't manage them. We handle recruitment, scheduling, and synthesis. You get the report and debrief. |
| "How long does it take?" | Typically 5-7 working days from submission to report. Priority scheduling for partners. |
| "What if the site fails badly?" | That's valuable information. Better to find out from us than from a lawsuit or angry users. The report gives you a clear fix path. |

---

## Technical Setup

**Accessibility of the webinar itself:**
- Live captions enabled
- Describe visuals as you go ("On screen you can see...")
- Share slides afterwards in accessible format
- Offer audio description of any video clips

**Recording:**
- Record the whole session
- Trim start/end
- Host on landing page or private link
- Use for Email 8, LinkedIn recap, evergreen nurture

---

## Promotion

**Email:** 4-7 in the sequence
**LinkedIn:** Event + posts 5-9
**Registration:** Landing page at myvision.org.uk/disabled-user-testing/

Offer the recording to people who can't attend live.

---

## Reminders

- On registration (immediate confirmation)
- Day before (Email 7)
- 1-2 hours before (if using webinar platform reminders)

---

## After the Webinar

**Within 24 hours:**
- Send Email 8 (thanks + replay + pilot offer)

**3-5 days later:**
- Send Email 9 (final nudge)

**10-14 days later:**
- Send Email 10 (case study follow-up)

**High-intent attendees (asked questions, stayed to end):**
- Personalised email or LinkedIn DM

**No-shows:**
- Emphasise replay in follow-up

---

## If Things Go Wrong

**High registration, low attendance:**
- Improve reminders
- Emphasise live Q&A benefits
- Check timing (Friday morning should be fine)

**Low registration:**
- Rework subject lines and hooks
- Be more specific about outcomes
- Ask a few friendly agencies what would make it interesting

**Quiet Q&A:**
- Seed questions prepared:
  - "How do you handle sites with a lot of dynamic content?"
  - "What's the typical turnaround time?"
  - "Can we use the video evidence in our proposals?"
  - "How do you recruit your testers?"
- Invite questions ahead of time via email/LinkedIn

**Tech issues:**
- Have backup slides as PDF
- Test screen share and video playback beforehand
- Have a co-host who can manage chat/Q&A
