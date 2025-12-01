Subject: What Lighthouse can't tell you
Preheader: The difference between "technically accessible" and "actually works"

Hi {{first_name}},

Quick question: what do you say to clients when they ask "is the site accessible?"

Most agencies we talk to say something like "we run Lighthouse and fix what comes up." Which is fair – it's a sensible starting point.

But here's the thing: there's a big gap between "passes automated checks" and "actually works for disabled people."

I mentioned that donation form last time – Lighthouse score of 94, but every field read as "edit blank" to a screen reader. The labels were there in the HTML. They just weren't connected to the form fields.

Tools saw labels. Our tester saw a dead end.

We see this a lot:
- Focus states that technically exist but are invisible against the background colour
- Skip links that are present but don't actually do anything
- Headings that look right but are in the wrong order for screen readers

None of this shows up in an automated report.

We tested a community organisation's website recently. Their contact form had a 0% completion rate for screen reader users – every single field announced as "edit blank". The automated scan? All green. One of our testers said:

> "I couldn't tell which fields were which. I had no idea if I was typing my name or email address. I eventually gave up."

That's the gap we're talking about.

---

The interesting bit is what happens when you can show a client both views side by side.

"Here's what the automated scan found. And here's what happened when 8 disabled people tried to complete key journeys on your site."

For clients in public sector, education, charity – that's a much stronger story. Especially in tenders.

We've been putting together reports that work this way: automated findings mapped against what real users experienced. Two views – one for stakeholders (impact, quotes, priorities) and one for developers (issues by component, suggested fixes).

If you'd like to see what that looks like:

👉 **[View an example report]({{sample_report_link}})**

Or just reply "quick chat" and we can find 15 minutes to talk it through.

Mark
