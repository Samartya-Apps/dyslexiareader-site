# dyslexiareader.com — Single-Page Landing Site Spec

**Document Purpose:** Complete content specification for dyslexiareader.com — a single-page, conversion-optimized marketing site for Dyslexia Reader. This is *not* the full product page (that lives at samartya.com/dyslexia-reader). This is the link you put in cold emails, Facebook ads, Google Ads, MDA outreach materials, and conference handouts.

**Design Philosophy:** This page should feel like a door opening, not a wall of information. A teacher or parent lands here with a problem ("my student/child struggles to read") and should feel, within 10 seconds, that they've found something made specifically for them. The page is warm, clear, and direct. It leads with the child's experience, not the technology.

**Technical Notes:**
- Single page, no internal navigation (just smooth-scroll anchors)
- Must load fast on mobile (many teachers will open this on a phone from an email)
- No CMS needed — this can be a static HTML page or a single Webflow/Carrd page
- Separate deployment from app.dyslexiareader.com (the web application)
- Cookie consent banner for compliance

---

## Top Navigation (Minimal)

```
[Dyslexia Reader logo]                    [Open App ↗] [Download ▾]
```

- "Open App" links to app.dyslexiareader.com (appears once web version is live; until then, hide this or replace with "Coming to Web Soon")
- "Download" is a dropdown or scrolls to the download section: iOS / Android links

No other nav items. The page is self-contained. Links to samartya.com appear in context within the page and in the footer, but the header stays focused on the product.

---

## Section 1: Hero

**Headline:**
Reading should never feel impossible.

**Subheadline:**
Dyslexia Reader turns any page — a textbook, a worksheet, a novel — into a reading experience designed for your child. Scan it. Hear it. Understand it. Read it independently.

**CTA Buttons:**
[Try Free on Web] [Download on iOS] [Download on Android]

*(Before web launch, replace "Try Free on Web" with "Web Version Coming Soon — Join Waitlist" and show a simple email capture field inline.)*

**Supporting text below CTAs:**
Free to download. Full 14-day trial. No credit card required.

**Visual:** A short, looping video (10–15 seconds, autoplaying, muted) or a high-quality screenshot showing: a child's hand holding a tablet, with a real textbook page displayed in the app, one word highlighted with syllabification support visible. The visual should feel like a real moment — not a product mockup.

---

## Section 2: The Problem (Empathy-First)

**Headline:**
Your child isn't a struggling reader. They're a reader who needs different support.

**Body copy:**
Children with dyslexia are smart, creative, and capable. But when they open a textbook and the words blur, jump, or refuse to make sense, the message they hear isn't about the book — it's about themselves. "I'm not good enough. I'm not smart enough. Reading isn't for me."

It doesn't have to be this way. What if the book met your child halfway?

**Design note:** This section should breathe. Plenty of white space. No images or screenshots — just the words. Maybe a subtle background color change to set it apart from the hero.

---

## Section 3: The Solution (Product Introduction)

**Headline:**
Dyslexia Reader makes any reading material accessible.

**Three-column layout (or three stacked cards on mobile):**

**Column 1: Bring in any text.**
[Icon: camera/document]
Scan a physical page with your camera. Upload a PDF. Import a classroom worksheet. Dyslexia Reader works with your child's actual school materials — not a separate reading library they'll never open.

**Column 2: Get support on every word.**
[Icon: lightbulb/help]
Stuck on a word? Tap it. Hear it pronounced. See it split into syllables. Explore its onset and rime. Find words that rhyme with it. Look up its meaning. Every word becomes solvable.

**Column 3: Read independently.**
[Icon: person reading]
Choose how to read: listen to the whole page read aloud, follow along sentence by sentence, or read independently with on-demand help. The child controls their experience. Confidence grows.

---

## Section 4: Demo (Visual Walkthrough)

**Headline:**
See it in action.

**Option A (preferred):** An embedded product demo video, 60–90 seconds. The video should show:
1. Opening the app, tapping "Scan"
2. Pointing the camera at a real textbook page
3. The page appearing digitized in the app
4. Tapping a word and seeing supports appear (syllabification, pronunciation, rhyming words)
5. Tapping "Read Aloud" and hearing the text with synchronized word highlighting
6. A child's face (or hands) reacting — a moment of engagement or success

Voiceover or text captions, no music. Keep it real, not polished-corporate.

**Option B (if video isn't ready yet):** A horizontal scroll of 4–5 annotated screenshots walking through the same flow. Each screenshot has a one-line caption below it.

---

## Section 5: Key Features (Scannable)

**Headline:**
Everything your child needs to read with confidence.

**Feature list — two-column grid of compact cards, each with an icon, a bold title, and one sentence:**

📖 **Text-to-Speech**
High-quality voices read any page aloud, highlighting each word as it's spoken.

✂️ **Syllabification**
Tap any word to break it into syllables — the same strategy dyslexia specialists teach.

🔤 **Onset & Rime**
See how words are built from their beginning sounds and ending patterns.

🔗 **Word Families**
Discover related words that share the same rime. "Cat" connects to "bat," "hat," "sat."

🔍 **Dictionary**
Instant definitions for any word, right inside the reading experience.

📝 **Sentence Building**
Practice constructing sentences with words from the passage, reinforcing comprehension.

🎯 **Focus Tools**
Screen masking highlights one line at a time. A tracking pointer supports hand-eye coordination.

🎨 **Visual Customization**
Dyslexia-friendly fonts. Adjustable text size. Colored overlays for Irlen Syndrome. Dark mode.

📄 **Page / Sentence / Word View**
Switch between seeing the whole page, one sentence, or one word at a time.

☁️ **Cloud Library**
Save and organize materials. Teachers can prepare assignments and share them with students.

📱 **Works Offline**
No internet needed after download. Read anywhere.

---

## Section 6: What Makes Dyslexia Reader Different

**Headline:**
Not just another text-to-speech app.

**Body copy:**
There are many apps that read text aloud. Dyslexia Reader does something different. It doesn't just read *to* your child — it teaches your child *how to read*.

Every support feature in the app — syllabification, onset/rime, word families, sentence building — is a research-backed reading strategy used by dyslexia specialists around the world. These aren't add-ons. They're the core of how the app works.

And unlike general-purpose reading apps, Dyslexia Reader works with your child's actual school materials. The textbook chapter they were assigned. The worksheet they brought home. The novel the class is reading together. Your child uses the same materials as everyone else — they just get the support they need to access them.

**Design note:** This section is important for differentiating from Speechify, NaturalReader, Voice Dream Reader, etc. — all of which are primarily TTS tools. Keep it concise but pointed.

---

## Section 7: Built with the Madras Dyslexia Association

**Headline:**
20+ years of dyslexia research, in your child's hands.

**Body copy:**
Dyslexia Reader was co-developed with the Madras Dyslexia Association (MDA), a non-profit that has been working with children with dyslexia since 1992. MDA has trained thousands of teachers, supported tens of thousands of children, and developed evidence-based reading strategies refined over decades of clinical practice.

Those strategies — the ones that actually work in real classrooms and resource rooms — are built directly into Dyslexia Reader. This isn't technology guessing at what might help. It's technology encoding what educators have proven works.

[MDA logo]
[Learn more about MDA →] (links to mdachennai.com)

---

## Section 8: Who It's For

**Headline:**
Built for the people in a child's corner.

**Three audience cards:**

**For Teachers & Reading Specialists**
Upload your classroom materials once. Share prepared assignments with your entire class. Each student reads at their own pace with the supports they need. Works alongside your existing reading intervention programs.
[See how schools use Dyslexia Reader →] (links to samartya.com/for-schools)

**For Parents & Families**
Give your child a tool they can use at home, on their own, without frustration. Scan tonight's homework. Upload next week's assigned reading. Let them practice independently — with help always one tap away.

**For Therapists & Tutors**
Use Dyslexia Reader in remediation sessions. The app's supports mirror evidence-based strategies you already use — syllabification, onset/rime, phonological awareness. It reinforces your work between sessions.

---

## Section 9: Try It on the Web (Major CTA Section)

**This section changes based on whether the web version has launched:**

### Pre-Launch Version:

**Headline:**
Coming soon: Dyslexia Reader in your browser.

**Body copy:**
No app install. No device restrictions. Soon, you'll be able to upload a PDF and try the full Dyslexia Reader experience from any browser — on a Chromebook, a laptop, a tablet, anything.

Perfect for teachers who want to evaluate it for their classroom without going through an app install process. Perfect for parents who want to try it right now.

**Waitlist form:**
[Email input] [Notify Me When It Launches]

We'll email you once — when it's ready. No spam.

---

### Post-Launch Version:

**Headline:**
Try it right now. No download needed.

**Body copy:**
Open Dyslexia Reader in your browser. Upload a PDF or paste some text. Experience the reading supports for yourself — in under two minutes, from any device.

**CTA Button:**
[Open Dyslexia Reader on Web →] (links to app.dyslexiareader.com)

Free to try. No account required to start.

---

## Section 10: Testimonials

**Headline:**
What educators and families say.

**Testimonial cards (3–4):**

[Pull from actual App Store reviews, MDA feedback, and any direct testimonials you have. Examples:]

"The supports are exactly what we teach in remediation — syllabification, onset/rime — but available instantly for any text the child encounters. It bridges the gap between therapy and real-world reading."
— Reading Specialist

"My son used to cry over homework. Now he scans the page, listens to the hard words, and reads along. He still has dyslexia. But he doesn't have that feeling of being broken anymore."
— Parent

"We use it across our resource rooms. Teachers prepare the week's reading materials on Sunday night and share them with all their students. The consistency has been remarkable."
— Special Education Coordinator

[Note: If you don't yet have testimonials this specific, use the real App Store reviews you do have, and make collecting better testimonials a Month 1–2 priority.]

---

## Section 11: Pricing

**Headline:**
Free to try. Affordable to keep.

**Body copy:**
Dyslexia Reader is free to download with a full 14-day trial. After the trial, choose the plan that works for you.

**Pricing table:**

| Plan | USA | India |
|------|-----|-------|
| Monthly | $9.99/month | ₹99/month |
| Annual | $99/year | ₹999/year |
| Lifetime | $199 (one-time) | ₹1,999 (one-time) |

**For Schools & Districts:**
Lifetime licenses are available through Apple's Volume Purchase Program (VPP) with 50% off for 20 or more licenses. We also support purchase orders and institutional invoicing.

[See school pricing and request a trial →] (links to samartya.com/for-schools)

**Design note:** Show the India pricing only to visitors from India (via geolocation), or show both in a toggle ("Show prices in: USD / INR"). Don't show both by default — it clutters the page for US visitors, who are the primary conversion target.

---

## Section 12: Download / Final CTA

**Headline:**
Start reading with confidence today.

**Three CTA options, presented as equal choices:**

[Try Free on Web] → app.dyslexiareader.com
(Pre-launch: [Join the Web Waitlist])

[Download on iOS] → App Store link

[Download on Android] → Google Play link

**Subtext:**
Free 14-day trial on all platforms. No credit card required.

---

## Section 13: FAQ (Collapsed/Accordion)

**Headline:**
Common questions.

**Q: What devices does Dyslexia Reader work on?**
A: Dyslexia Reader is available on iPad and iPhone (iOS), Android tablets and phones, and soon on any web browser. The web version works on Chromebooks, laptops, and desktops.

**Q: Does my child need an internet connection?**
A: The iOS and Android apps work offline after download. The web version requires an internet connection.

**Q: Can I use my child's actual school textbooks?**
A: Yes — that's what Dyslexia Reader is designed for. Scan a physical page with your camera or upload a PDF. The app digitizes the text and makes it accessible.

**Q: Is this just text-to-speech?**
A: No. Text-to-speech is one of many features. Dyslexia Reader also provides syllabification, onset/rime analysis, word families, dictionary, sentence building, focus tools, and visual customization — all evidence-based reading strategies developed with the Madras Dyslexia Association.

**Q: Can teachers share materials with students?**
A: Yes. Teachers can prepare reading materials in the app and share them with students via the cloud library. Students receive the prepared material ready to read with all supports available.

**Q: How much does it cost?**
A: Free to download and try for 14 days. Plans start at $9.99/month, with annual ($99/year) and lifetime ($199) options. Schools get 50% off lifetime licenses through Apple VPP for 20+ licenses.

**Q: Who built this?**
A: Dyslexia Reader was co-developed by Samartya Apps and the Madras Dyslexia Association (MDA), a non-profit with 30+ years of experience in dyslexia education and remediation. [Learn more →] (links to samartya.com/about)

**Q: Is it safe for children?**
A: Yes. Dyslexia Reader is designed for use by children and is compliant with COPPA (Children's Online Privacy Protection Act) and FERPA (Family Educational Rights and Privacy Act). [See our privacy policy →]

---

## Footer

```
Dyslexia Reader is a product of Samartya Apps.

Products                Company                 Legal
FreeSpeech              About Samartya Apps      Privacy Policy
Dyslexia Reader         Research & Evidence      Terms of Use
For Schools             Blog
                        Contact

Download
[App Store badge]  [Google Play badge]

Follow Us
[Facebook] [Instagram] [LinkedIn] [YouTube]

© 2026 Samartya Apps. All rights reserved.
```

All "Company" links go to samartya.com.
"FreeSpeech" links to freespeechapp.com.
"For Schools" links to samartya.com/for-schools.

---

## SEO & Technical Specification

**SEO Title:** Dyslexia Reader — Make Any Reading Material Accessible | Reading App for Dyslexia
**Meta Description:** Scan a page or upload a PDF. Dyslexia Reader adds text-to-speech, syllabification, onset/rime, and more — turning classroom materials into accessible reading experiences. Built with 20+ years of dyslexia research. Free to try.
**Canonical URL:** https://dyslexiareader.com

**Target Keywords (primary):**
- dyslexia reading app
- reading app for dyslexic students
- dyslexia reader app
- scan and read aloud dyslexia

**Target Keywords (secondary):**
- dyslexia classroom app
- accessible reading app
- assistive reading technology
- reading support app dyslexia
- text to speech dyslexia

**Open Graph / Social Sharing:**
- og:title — "Dyslexia Reader — Make Any Reading Material Accessible"
- og:description — "Scan a page or upload a PDF. Text-to-speech, syllabification, onset/rime, and more. Free to try."
- og:image — Product screenshot or hero image (1200×630px)
- og:url — https://dyslexiareader.com
- twitter:card — summary_large_image

**Schema Markup:**
```json
{
  "@context": "https://schema.org",
  "@type": "SoftwareApplication",
  "name": "Dyslexia Reader",
  "operatingSystem": "iOS, Android, Web",
  "applicationCategory": "EducationApplication",
  "offers": [
    {
      "@type": "Offer",
      "price": "0",
      "priceCurrency": "USD",
      "description": "Free 14-day trial"
    },
    {
      "@type": "Offer",
      "price": "9.99",
      "priceCurrency": "USD",
      "description": "Monthly subscription"
    },
    {
      "@type": "Offer",
      "price": "99",
      "priceCurrency": "USD",
      "description": "Annual subscription"
    },
    {
      "@type": "Offer",
      "price": "199",
      "priceCurrency": "USD",
      "description": "Lifetime purchase"
    }
  ],
  "aggregateRating": {
    "@type": "AggregateRating",
    "ratingValue": "[actual rating]",
    "ratingCount": "[actual count]"
  },
  "author": {
    "@type": "Organization",
    "name": "Samartya Apps",
    "url": "https://samartya.com"
  }
}
```

**Analytics:**
- Google Analytics 4 (same property as samartya.com, but separate data stream)
- Event tracking on:
  - "Try Free on Web" clicks
  - App Store download clicks (iOS)
  - Google Play download clicks (Android)
  - Waitlist email submissions
  - "For Schools" link clicks (to samartya.com)
  - Demo video plays (if video is embedded)
  - FAQ accordion opens (which questions do people read?)
  - Scroll depth (how far do visitors scroll before leaving or clicking?)
  - Time on page

**Performance:**
- Target: <2 second load on mobile (3G connection)
- Lazy load all images below the fold
- Inline critical CSS
- No JavaScript frameworks needed — this page can be pure HTML/CSS with minimal JS for the FAQ accordion and waitlist form
- Host on a CDN (Cloudflare Pages, Netlify, or Vercel — all free tier)

---

## Page Variants

### Variant: Dyslexia Awareness Month (October)

During October, modify the hero section:

**Badge above headline:** 🟣 October is Dyslexia Awareness Month

**Modified headline:**
1 in 5 children has dyslexia. Reading doesn't have to be a battle.

**Additional CTA:**
[Share Dyslexia Reader with a teacher →] (pre-composed social sharing or email)

### Variant: India-Focused (for MDA distribution)

When sharing via MDA channels, use UTM parameters: dyslexiareader.com?utm_source=mda&utm_medium=whatsapp&utm_campaign=schools2026

Consider a /in path or language toggle for Hindi content in the future, but not for launch.

---

## Relationship to Other Sites (Summary)

```
dyslexiareader.com (THIS PAGE)
│
├── Links OUT to:
│   ├── app.dyslexiareader.com — "Try on Web" / "Open App"
│   ├── App Store — iOS download
│   ├── Google Play — Android download
│   ├── samartya.com/for-schools — school pricing, trial requests
│   ├── samartya.com/about — company info
│   ├── samartya.com/research — MDA partnership, evidence
│   ├── samartya.com/blog — articles and resources
│   ├── samartya.com/contact — inquiries
│   ├── freespeechapp.com — sister product (footer only)
│   └── mdachennai.com — MDA info
│
├── Links IN from:
│   ├── Email campaigns (cold outreach to teachers, reading specialists)
│   ├── Google Ads (dyslexia keyword campaigns)
│   ├── Facebook/Instagram ads and posts
│   ├── MDA WhatsApp and social media distribution
│   ├── QR codes on printed materials
│   ├── Conference handouts and slide decks
│   ├── App Store and Google Play developer website field
│   └── samartya.com/dyslexia-reader (cross-link)
│
└── Does NOT duplicate:
    └── samartya.com/dyslexia-reader (which has sub-pages
        for teachers, parents, and more detailed content)
```

---

## Build Priority and Timeline

**Pre-web-launch (build now):**
- Full page as specified above
- Waitlist form for web version (replace "Try on Web" CTA)
- iOS and Android download buttons
- All other sections as written

**At web launch (swap in ~3 months):**
- Replace waitlist with live "Try Free on Web" CTA → app.dyslexiareader.com
- Add "Open App" to top nav
- Send launch email to everyone on the waitlist
- Update FAQ to reflect web version availability
- Consider adding a "Web vs. App — Which Should I Use?" mini-section or FAQ item

**Post-launch iteration (ongoing):**
- Add real testimonials as they come in (replace placeholder quotes)
- Add a "Case Studies" link when samartya.com/blog has published school success stories
- Seasonal variant for Dyslexia Awareness Month (October)
- A/B test headlines if traffic warrants it (use Google Optimize or a simple A/B tool)

---

*End of dyslexiareader.com specification.*
