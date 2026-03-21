# Outli Homepage — Build Brief

## Overview
Build a single-page marketing website for **Outli**, a location-based social app for students to meet up and do activities together. The site lives at **outli.live** and serves two audiences: potential users (students) and potential partners (university organisations like student unions and international offices).

The page must be **live before April 1st 2026**. It is the destination for all outreach currently in progress.

---

## Brand
- **App name:** Outli
- **Domain:** outli.live
- **Tagline / motto:** [insert your motto here]
- **Logo:** [attach logo file]
- **Tone:** Warm, direct, peer-to-peer — not corporate. Feels like it was built by a student, for students.
- **Colour palette:** Derive from logo, keep clean and minimal

---

## Audience

### Primary — Students (users)
New to Berlin or new to university. Wants to do things and meet people but doesn't have the social circle yet. Arrives via QR code, Instagram, or a friend's message. On mobile.

### Secondary — Partners (orgs)
Student unions (e.g. Freitagsrunde at TU Berlin), international offices, Erasmus coordinators. Checks the site after receiving an outreach email to verify legitimacy. On desktop.

---

## Page Structure

Build as a **single scrolling page**, mobile-first.

---

### Section 1 — Hero

**Headline (lead with the feeling, not the features):**
```
New city. Want to do something.
Don't know who to ask yet.
```

**Subheadline:**
```
Outli shows you what's happening around you — and who's going.
```

**CTA button:** `Download on App Store` → links to App Store listing  
**Secondary CTA (subtle):** `Learn more ↓` → scrolls to How It Works

Include logo at top. Hero should take up full viewport on mobile.

---

### Section 2 — How It Works

**Title:** `It's simple`

Three steps, displayed as icons + short labels:

1. **Sign up** → You post something you want to do — coffee, football, museum, anything
2. **Others join** → People nearby who are down for the same thing find your activity
3. **Meet up** → Show up, do the thing, meet someone new

Keep copy minimal. Visual icons preferred over text-heavy explanation.

---

### Section 3 — The Feeling (social proof placeholder)

**Title:** `For the moments when you don't want to go alone`

Short paragraph:
```
Whether it's exploring a new neighbourhood, finding someone to train with,
or just grabbing food without eating alone — Outli is for the version of
you that wants to do something, right now.
```

If a testimonial or real meetup story exists, insert it here as a pull quote. Otherwise leave a placeholder comment in the code: `<!-- INSERT FIRST TESTIMONIAL HERE -->`.

---

### Section 4 — For Partners / Organisations

**Title:** `Want to bring Outli to your students?`

Short paragraph:
```
We're working with student unions, international offices, and Erasmus
coordinators at universities across Berlin. If you'd like to partner
or feature Outli in your orientation programme, get in touch.
```

**CTA:** `Contact us → hello@outli.live` (mailto link)

This section should feel understated — not a full sales pitch, just a clear door for orgs to walk through.

---

### Section 5 — Footer

- Outli logo (small)
- App Store download link
- Contact email: hello@outli.live
- Instagram handle (if exists — leave placeholder if not): @outli
- One line: `Built by students, for students. Berlin 2026.`
- Privacy Policy link (placeholder href="#" if not ready)

---

## Technical Requirements

- **Single HTML file** — no frameworks, no build step, deploys anywhere instantly
- **Mobile-first** — majority of visitors will be on iPhone/Android
- **Fast** — no heavy libraries, no video autoplay, minimal JS
- **App Store button** — use official Apple badge SVG or PNG; link to actual App Store URL (add placeholder if not live yet: `href="#"`)
- **No cookies / tracking** — keep it clean for now, no analytics scripts unless explicitly added later
- **Smooth scroll** — anchor links scroll smoothly
- **Accessible** — proper heading hierarchy, alt text on images, sufficient colour contrast

---

## Assets to provide before building

- [ ] Logo file (SVG preferred, PNG fallback)
- [ ] Tagline / motto text
- [ ] App Store URL
- [ ] At least one app screenshot or mockup (for hero or how-it-works section)
- [ ] Brand colours (hex codes) — or derive from logo
- [ ] Instagram handle (if exists)

---

## What success looks like

A visitor landing on the page on mobile should:
1. Immediately feel understood ("that's exactly me right now")
2. Know what the app does within 10 seconds
3. Be one tap away from the App Store

A partner landing on the page on desktop should:
1. See it's credible and student-built
2. Find a clear contact route within one scroll
3. Not feel like they're being sold to

---

## Deadline
**March 31, 2026** — must be live before April 1st International Office orientation at TU Berlin.
