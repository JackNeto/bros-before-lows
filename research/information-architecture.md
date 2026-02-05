# Bros Before Lows - Information Architecture & Site Structure

**Document Version:** 1.0
**Date:** February 2026
**Project:** Website Redesign

---

## Table of Contents

1. [Executive Summary](#executive-summary)
2. [Site Map](#1-recommended-site-map)
3. [Page Inventory](#2-page-inventory)
4. [Navigation Patterns](#3-navigation-patterns)
5. [Content Prioritization](#4-content-prioritization)
6. [Conversion Paths](#5-conversion-paths)
7. [SEO Structure](#6-seo-structure)

---

## Executive Summary

Bros Before Lows (BBL) is a men's mental health organization operating peer support groups across the Greater Toronto Area. The website redesign must serve three primary user groups while maintaining the organization's grassroots, authentic brand personality:

| User Type | Primary Need | Secondary Need |
|-----------|--------------|----------------|
| **Men Seeking Support** | Find/join a peer group | Access crisis resources |
| **Donors/Supporters** | Make a donation | Attend events, buy merch |
| **Partners/Volunteers** | Host a group in their city | Sponsor an event |

The recommended structure prioritizes **peer support access** (core mission) while creating clear pathways for **fundraising** (operational sustainability) without overwhelming users in crisis.

---

## 1. Recommended Site Map

### Primary Navigation (5 Items + CTA)

```
+---------------------------------------------------------------------+
|                        PRIMARY NAVIGATION                           |
+---------------------------------------------------------------------+
|  HOME  |  SUPPORT GROUPS  |  EVENTS  |  ABOUT  |  SHOP  | [DONATE] |
+---------------------------------------------------------------------+
                                                              ^
                                                     CTA Button (accent)
```

### Complete Site Hierarchy

```
HOME
|
+-- SUPPORT GROUPS (Dropdown/Mega Menu)
|   +-- What to Expect
|   +-- Find a Group
|   |   +-- Toronto
|   |   +-- Brampton
|   |   +-- Mississauga
|   |   +-- Barrie
|   |   +-- Hamilton
|   |   +-- Kitchener
|   +-- Virtual Groups
|   +-- Host a Group (Lead form)
|
+-- EVENTS
|   +-- Upcoming Events
|   +-- Past Events / Gallery
|   +-- Sponsor an Event
|
+-- ABOUT
|   +-- Our Mission
|   +-- Mathieu's Story (Founder)
|   +-- Impact & Transparency
|   +-- Contact
|
+-- SHOP (External or Integrated)
|   +-- Merchandise
|   +-- Event Merch
|
+-- DONATE (CTA Button)
|   +-- One-Time Donation
|   +-- Monthly Giving
|   +-- Corporate Giving
|
+-- [FOOTER PAGES]
    +-- Terms of Service
    +-- Privacy Policy
    +-- Returns & FAQ
    +-- Contact Support
    +-- Crisis Resources
```

### Visual Hierarchy Diagram

```
+----------------------------------------------------------------------------+
| +----------+                                                    +---------+ |
| |  LOGO    |  Home  Support Groups  Events  About  Shop        | DONATE  | |
| +----------+                  v                                 +---------+ |
+----------------------------------------------------------------------------+
|                                                                            |
|  +----------------------------------------------------------------------+  |
|  |                           HERO SECTION                               |  |
|  |            Mission statement + Primary CTA                           |  |
|  +----------------------------------------------------------------------+  |
|                                                                            |
|  +---------------------+  +---------------------+  +---------------------+ |
|  |   SUPPORT GROUPS    |  |      EVENTS         |  |      DONATE         | |
|  |   Find your city    |  |   Upcoming show     |  |   Support the       | |
|  |   [Join a Group]    |  |   [Get Tickets]     |  |   movement          | |
|  +---------------------+  +---------------------+  +---------------------+ |
|                                                                            |
|  +----------------------------------------------------------------------+  |
|  |                     IMPACT / SOCIAL PROOF                           |  |
|  |        "105 donors"  "6 cities"  "$5,950 raised"                    |  |
|  +----------------------------------------------------------------------+  |
|                                                                            |
+----------------------------------------------------------------------------+
|  FOOTER                                                                    |
|  +--------------+ +--------------+ +--------------+ +------------------+  |
|  | Organization | |   Support    | |  Get Help    | | CRISIS: 988      |  |
|  | About        | | Contact      | | Find a Group | |   Emergency: 911 |  |
|  | Mission      | | FAQ          | | Virtual      | |                  |  |
|  | Impact       | | Terms        | | Cities       | |  Newsletter      |  |
|  | Contact      | | Privacy      | |              | |  [Subscribe]     |  |
|  +--------------+ +--------------+ +--------------+ +------------------+  |
|                                                                            |
|  (c) Bros Before Lows 2026 | @brosbeforelows                              |
+----------------------------------------------------------------------------+
```

### Secondary Navigation (Footer)

| Column 1: Organization | Column 2: Support | Column 3: Get Help | Column 4: Crisis |
|------------------------|-------------------|--------------------|--------------------|
| About | Contact Us | Find a Group | 988 (Canada) |
| Our Mission | FAQ | Virtual Groups | 911 Emergency |
| Impact | Terms of Service | Host a Group | |
| Mathieu's Story | Privacy Policy | | Newsletter Signup |
| | Returns Policy | | |

### Utility Navigation (Header)

```
[Crisis Help: 988] ------- [Instagram] [Email] ------- [CAD v]
```

Small utility bar above main nav with crisis resources always visible.

---

## 2. Page Inventory

### Homepage

| Attribute | Details |
|-----------|---------|
| **URL** | `/` |
| **Purpose** | Introduce BBL mission, provide clear pathways to core offerings |
| **Key Content Blocks** | 1. Hero with mission + CTA<br>2. "How We Help" cards (Groups, Events, Donate)<br>3. Upcoming Event feature<br>4. Impact metrics<br>5. Newsletter signup<br>6. Crisis resources |
| **Primary CTA** | "Find a Support Group" or "Join a Group" |
| **Secondary CTAs** | "Donate Now", "View Events" |

---

### Support Groups Section

#### /support-groups (Landing Page)

| Attribute | Details |
|-----------|---------|
| **URL** | `/support-groups` |
| **Purpose** | Explain peer support model, drive signups |
| **Key Content Blocks** | 1. What peer support is<br>2. What to expect at a meeting<br>3. City selector/map<br>4. Virtual option card<br>5. FAQ accordion<br>6. "Host a Group" CTA |
| **Primary CTA** | "Find Your City" (anchor to city cards) |

#### /support-groups/[city]

| Attribute | Details |
|-----------|---------|
| **URL** | `/support-groups/toronto`, `/support-groups/brampton`, etc. |
| **Purpose** | Local landing page for SEO + specific group info |
| **Key Content Blocks** | 1. City-specific hero<br>2. Meeting schedule/location<br>3. Signup form (waitlist or registration)<br>4. Testimonial from local member<br>5. Virtual alternative |
| **Primary CTA** | "Join the Waitlist" or "Register for Next Meeting" |

**City Pages Required:**
- `/support-groups/toronto`
- `/support-groups/brampton`
- `/support-groups/mississauga`
- `/support-groups/barrie`
- `/support-groups/hamilton`
- `/support-groups/kitchener`

#### /support-groups/virtual

| Attribute | Details |
|-----------|---------|
| **URL** | `/support-groups/virtual` |
| **Purpose** | Serve users not near a physical location |
| **Key Content Blocks** | 1. Virtual format explanation<br>2. Schedule<br>3. Technology requirements<br>4. Registration form |
| **Primary CTA** | "Join Virtual Group" |

#### /support-groups/host

| Attribute | Details |
|-----------|---------|
| **URL** | `/support-groups/host` |
| **Purpose** | Recruit community hosts to expand to new cities |
| **Key Content Blocks** | 1. What hosting involves<br>2. Training provided<br>3. Requirements<br>4. Application form |
| **Primary CTA** | "Apply to Host" |

---

### Events Section

#### /events

| Attribute | Details |
|-----------|---------|
| **URL** | `/events` |
| **Purpose** | Showcase fundraising events, drive attendance |
| **Key Content Blocks** | 1. Featured upcoming event<br>2. Event calendar/list<br>3. Past event gallery<br>4. Sponsor CTA |
| **Primary CTA** | "Get Tickets" (for next event) |

#### /events/[event-slug]

| Attribute | Details |
|-----------|---------|
| **URL** | `/events/talking-saves-lives-2025` |
| **Purpose** | Individual event details and registration |
| **Key Content Blocks** | 1. Event hero (date, time, location)<br>2. Lineup/speakers<br>3. Ticket/donation tiers<br>4. Map/directions<br>5. FAQ |
| **Primary CTA** | "Get Tickets" or "Donate to Attend" |

#### /events/sponsor

| Attribute | Details |
|-----------|---------|
| **URL** | `/events/sponsor` |
| **Purpose** | Recruit corporate sponsors |
| **Key Content Blocks** | 1. Sponsorship value proposition<br>2. Tier options<br>3. Past sponsors (if any)<br>4. Contact form |
| **Primary CTA** | "Become a Sponsor" |

---

### About Section

#### /about

| Attribute | Details |
|-----------|---------|
| **URL** | `/about` |
| **Purpose** | Build trust, share mission, introduce founder |
| **Key Content Blocks** | 1. Mission statement<br>2. Vision for the future<br>3. Mathieu's story preview<br>4. Team/advisors (if applicable)<br>5. Media/press mentions |
| **Primary CTA** | "Support Our Mission" (to donate) |

#### /about/mathieu

| Attribute | Details |
|-----------|---------|
| **URL** | `/about/mathieu` or `/about/our-story` |
| **Purpose** | Personal connection through founder's journey |
| **Key Content Blocks** | 1. Mathieu's personal story<br>2. Why he started BBL<br>3. Photo/video content<br>4. Call to action |
| **Primary CTA** | "Join the Movement" |

#### /about/impact

| Attribute | Details |
|-----------|---------|
| **URL** | `/about/impact` |
| **Purpose** | Transparency, build donor confidence |
| **Key Content Blocks** | 1. Key metrics (groups, cities, attendees, funds raised)<br>2. How funds are used<br>3. Goals for 2026<br>4. Annual report (when available) |
| **Primary CTA** | "Make an Impact" (to donate) |

#### /contact

| Attribute | Details |
|-----------|---------|
| **URL** | `/contact` |
| **Purpose** | General inquiries, media, partnerships |
| **Key Content Blocks** | 1. Contact form<br>2. Email addresses by type<br>3. Response time expectations<br>4. Social links |
| **Primary CTA** | "Send Message" |

---

### Donate Section

#### /donate

| Attribute | Details |
|-----------|---------|
| **URL** | `/donate` |
| **Purpose** | Primary donation conversion page |
| **Key Content Blocks** | 1. Impact statement<br>2. Donation amount selector ($10, $25, $50, $100, custom)<br>3. Monthly vs one-time toggle<br>4. What each amount provides<br>5. Donor testimonials<br>6. Fundraising progress bar |
| **Primary CTA** | "Donate Now" |

#### /donate/monthly

| Attribute | Details |
|-----------|---------|
| **URL** | `/donate/monthly` |
| **Purpose** | Recurring donation signup |
| **Key Content Blocks** | 1. Benefits of monthly giving<br>2. Suggested amounts<br>3. "Founding Supporter" or similar recognition tier |
| **Primary CTA** | "Become a Monthly Supporter" |

#### /donate/corporate

| Attribute | Details |
|-----------|---------|
| **URL** | `/donate/corporate` |
| **Purpose** | Corporate giving and matching programs |
| **Key Content Blocks** | 1. Corporate partnership benefits<br>2. Recognition opportunities<br>3. Contact form |
| **Primary CTA** | "Partner With Us" |

---

### Shop Section

#### /shop

| Attribute | Details |
|-----------|---------|
| **URL** | `/shop` or external Fourthwall link |
| **Purpose** | Merchandise sales supporting the mission |
| **Key Content Blocks** | 1. Product grid<br>2. Limited edition callouts<br>3. "100% supports peer groups" messaging |
| **Primary CTA** | "Shop Now" |

**Note:** Shop may remain on Fourthwall with seamless linking, or be migrated to integrated e-commerce depending on platform choice.

---

### Legal/Support Pages

| Page | URL | Purpose |
|------|-----|---------|
| Terms of Service | `/terms` | Legal compliance |
| Privacy Policy | `/privacy` | PIPEDA compliance |
| Returns & FAQ | `/faq` | Pre-purchase questions, return policy |
| Contact Support | `/support` | Order issues, merch problems |
| Crisis Resources | `/crisis` | Comprehensive crisis support links |

---

### Crisis Resources Page

| Attribute | Details |
|-----------|---------|
| **URL** | `/crisis` |
| **Purpose** | Immediate access to professional crisis support |
| **Key Content Blocks** | 1. Clear 988 and 911 callout<br>2. Other Canadian mental health resources<br>3. What to do in a crisis<br>4. BBL's role (peer support, not crisis intervention) |
| **Primary CTA** | "Call 988 Now" (tel: link) |

---

## 3. Navigation Patterns

### Mobile Navigation Approach

**Pattern:** Hamburger menu with slide-in drawer

```
+----------------------------+
| (=) BBL LOGO      [DONATE] |  <-- Sticky header
+----------------------------+
|                            |
|   SLIDE-IN DRAWER          |
|   ---------------------    |
|   Home                     |
|   Support Groups     >     |  <-- Expandable submenu
|   Events             >     |
|   About              >     |
|   Shop                     |
|   ---------------------    |
|   Contact                  |
|   Crisis Help: 988         |  <-- Always visible
|   ---------------------    |
|   [@] Instagram            |
|                            |
+----------------------------+
```

**Mobile-Specific Considerations:**

1. **Donate button** stays visible in header at all times (not hidden in hamburger)
2. **Crisis resources (988)** pinned to bottom of drawer
3. **Tap-to-call** enabled for crisis numbers
4. **Support Groups submenu** expands to show cities without page reload
5. **Sticky CTA bar** on support group pages: "Join This Group" fixed to bottom

### Crisis Resources Accessibility

Crisis resources must be accessible within **1 tap/click** from any page:

| Location | Implementation |
|----------|----------------|
| **Utility bar** (desktop) | `Crisis Help: 988` - small link above main nav |
| **Footer** (all devices) | Dedicated footer column with crisis numbers |
| **Mobile drawer** | Pinned item at bottom of slide-out menu |
| **Dedicated page** | `/crisis` with comprehensive resources |
| **Homepage** | Crisis callout in footer area |
| **Support group pages** | "In Crisis? Call 988" banner |

**Crisis Banner Component:**

```
+--------------------------------------------------------------+
| ! In crisis? You're not alone. Call 988 (Canada) or 911      |
+--------------------------------------------------------------+
```

This banner should appear:
- At top of site on first visit (dismissible)
- On all Support Groups pages (non-dismissible)
- On Crisis Resources page (prominent)

### Search Functionality

**Recommendation:** Search is **not required** for initial launch.

**Reasoning:**
- Site is relatively small (<30 pages)
- Clear navigation structure
- Primary user needs (find a group, donate, events) don't require search
- Users in crisis need direct paths, not search

**Future Consideration:** If content grows (blog, resources library), implement:
- Simple search modal (Cmd/Ctrl + K pattern)
- Algolia or similar for instant results
- Prioritize Support Groups and Events in results

---

## 4. Content Prioritization

### Above-the-Fold Strategy by Page

#### Homepage

```
+--------------------------------------------------------------+
|                                                              |
|     "A movement for men's mental health grounded in         |
|      healing, brotherhood and purpose."                      |
|                                                              |
|              [Find a Support Group]                          |
|                                                              |
|        v Scroll for events and how to help v                |
|                                                              |
+--------------------------------------------------------------+
```

**Priority:** Mission clarity + Support Group CTA

#### Support Groups Landing

```
+--------------------------------------------------------------+
|                                                              |
|     "Safe, judgment-free spaces where men can connect,      |
|      heal, and grow."                                        |
|                                                              |
|     MAP [Select Your City: Toronto v]                        |
|                                                              |
|     Don't see your city? [Virtual Groups Available]         |
|                                                              |
+--------------------------------------------------------------+
```

**Priority:** City selection (immediate action)

#### Donate Page

```
+--------------------------------------------------------------+
|                                                              |
|     "Support Healing, Empower Community"                     |
|                                                              |
|     $5,950 raised from 105 supporters                       |
|     ################.......... $6,000 goal                  |
|                                                              |
|     [$25]  [$50]  [$100]  [Other]     [DONATE NOW]          |
|                                                              |
+--------------------------------------------------------------+
```

**Priority:** Progress bar + donation selector

### User Type Content Priorities

#### Men Seeking Support

| Priority | Content | Location |
|----------|---------|----------|
| 1 | Find a peer group near them | Homepage hero, Support Groups |
| 2 | What to expect at a meeting | Support Groups landing |
| 3 | Crisis resources | Utility nav, footer, crisis page |
| 4 | Virtual group option | Support Groups landing |
| 5 | Newsletter/waitlist signup | Homepage, Support Groups city pages |

#### Donors/Supporters

| Priority | Content | Location |
|----------|---------|----------|
| 1 | Clear donation pathway | Homepage, Donate page, nav CTA |
| 2 | Impact/how funds are used | Donate page, About/Impact |
| 3 | Upcoming events | Homepage, Events |
| 4 | Merchandise | Shop (secondary nav) |
| 5 | Founder story | About/Mathieu |

#### Partners/Volunteers

| Priority | Content | Location |
|----------|---------|----------|
| 1 | Host a group in their city | Support Groups/Host |
| 2 | Sponsor an event | Events/Sponsor |
| 3 | Contact information | Contact page |
| 4 | Organization credibility | About, Impact |

### Balancing Fundraising vs. Support Resources

**Principle:** Support resources take visual priority; fundraising takes persistent presence.

**Implementation:**

| Element | Approach |
|---------|----------|
| **Hero CTA** | "Find a Support Group" (not "Donate") |
| **Donate button** | Accent color in nav, always visible but not intrusive |
| **Homepage cards** | Support Groups first, Events second, Donate third |
| **Footer** | Support resources get dedicated column equal to fundraising |
| **Exit intent** | No donation popups (inappropriate for mental health audience) |
| **Event pages** | "Pay what you can" messaging (accessible, not guilt-inducing) |

**Tone Guidelines:**
- Never use guilt or fear-based donation asks
- Frame donations as "joining the movement" not "saving lives"
- Always pair donation requests with impact statements
- Keep crisis resources clearly separate from fundraising

---

## 5. Conversion Paths

### Donation Flow

```
ENTRY POINTS                    CONVERSION
-----------------------------------------------------------------------------

Homepage "Donate" CTA -----+
                           |
Nav "Donate" button -------+-----> /donate -----> Amount Selection ----+
                           |                                           |
Event page donation -------+                    +-----------------------+
                           |                    |
Impact page CTA -----------+                    v
                                         Payment Form
                                         (Stripe/PayPal)
                                                |
                                                v
                                         Thank You Page
                                         + Share prompt
                                         + Newsletter opt-in
                                         + Receipt email
```

**Optimization Points:**

1. **Amount selector:** Pre-select $25 (matches event minimum)
2. **Impact statements:** "$25 = covers one group member's materials"
3. **Progress bar:** Show campaign progress
4. **Monthly toggle:** Encourage recurring with "Founding Supporter" title
5. **Thank you page:** Social share buttons, newsletter signup, impact story

---

### Peer Group Signup Flow

```
ENTRY POINTS                    CONVERSION
-----------------------------------------------------------------------------

Homepage "Find a Group" -------+
                               |
Support Groups landing --------+-----> /support-groups/[city]
                               |              |
Google "mens support           |              v
group [city]" -----------------+       Group Info +
                                       Meeting Schedule
                                              |
                                              v
                                       Registration Form
                                       (Name, Email, Phone opt)
                                              |
                                              v
                                       Confirmation Page
                                       + Calendar invite
                                       + What to expect email
                                       + SMS reminder opt-in
```

**Optimization Points:**

1. **City auto-detection:** Geo-locate to suggest nearest city
2. **Clear schedule:** Day, time, address with Google Maps link
3. **Low-friction form:** Name + email only (phone optional)
4. **Immediate confirmation:** Calendar invite download
5. **Follow-up sequence:** What to expect email, reminder 24h before

---

### Volunteer/Host Application Flow

```
ENTRY POINTS                    CONVERSION
-----------------------------------------------------------------------------

Support Groups "Host" CTA -----+
                               |
Contact page ------------------+-----> /support-groups/host
                               |              |
Footer link -------------------+              v
                                       Host Program Info
                                       + Requirements
                                       + Training overview
                                              |
                                              v
                                       Application Form
                                       (Multi-field: name, city,
                                        why interested, availability)
                                              |
                                              v
                                       Confirmation +
                                       Scheduling email
                                       for intro call
```

**Optimization Points:**

1. **Clear requirements:** Set expectations before application
2. **Multi-step form:** Break into sections (Personal, Location, Motivation)
3. **City interest:** Dropdown for cities + "Other" with text field
4. **Follow-up:** Personal email from Mathieu within 48 hours

---

### Newsletter Signup Placement

| Location | Context | Messaging |
|----------|---------|-----------|
| **Homepage** (above footer) | General audience | "Stay connected. Get updates on events and new group locations." |
| **Support Groups landing** | Support seekers | "Join the waitlist for new groups in your area." |
| **City pages** (when no active group) | Local interest | "Be the first to know when [City] groups launch." |
| **Post-donation** | Donors | "Stay updated on how your support makes a difference." |
| **Event pages** | Attendees | "Get notified about future events." |
| **Footer** | All pages | Single field: "Enter your email" |

**Form Fields:** Email only (minimize friction). Optionally collect city preference on Support Groups pages.

---

## 6. SEO Structure

### URL Patterns

| Page Type | Pattern | Example |
|-----------|---------|---------|
| Homepage | `/` | `brosbeforelows.com/` |
| Support Groups hub | `/support-groups` | `brosbeforelows.com/support-groups` |
| City pages | `/support-groups/[city]` | `brosbeforelows.com/support-groups/toronto` |
| Virtual groups | `/support-groups/virtual` | `brosbeforelows.com/support-groups/virtual` |
| Events hub | `/events` | `brosbeforelows.com/events` |
| Individual events | `/events/[slug]` | `brosbeforelows.com/events/talking-saves-lives-2025` |
| About pages | `/about/[page]` | `brosbeforelows.com/about/mathieu` |
| Donate | `/donate` | `brosbeforelows.com/donate` |
| Shop | `/shop` | `brosbeforelows.com/shop` |
| Legal | `/[page]` | `brosbeforelows.com/terms` |

### Key Landing Pages for Search

| Target Keyword | Landing Page | Search Intent |
|----------------|--------------|---------------|
| "mens mental health support group toronto" | `/support-groups/toronto` | Find local support |
| "mens peer support brampton" | `/support-groups/brampton` | Find local support |
| "men's mental health charity canada" | `/about` | Learn about org |
| "donate mens mental health" | `/donate` | Contribute |
| "start mens support group" | `/support-groups/host` | Volunteer |
| "talking saves lives event" | `/events/talking-saves-lives-2025` | Event info |

### Local SEO Considerations (GTA Cities)

**Google Business Profiles:**
Create separate Google Business profiles for each city where physical meetings occur:
- Bros Before Lows - Toronto
- Bros Before Lows - Brampton
- Bros Before Lows - Mississauga
- Bros Before Lows - Barrie
- Bros Before Lows - Hamilton
- Bros Before Lows - Kitchener

**City Page SEO Elements:**

| Element | Implementation |
|---------|----------------|
| **Title tag** | "Men's Mental Health Support Group in [City] \| Bros Before Lows" |
| **Meta description** | "Join a free peer support group for men in [City]. Safe, judgment-free space to connect, heal, and grow. Meetings every [day]." |
| **H1** | "Men's Peer Support Group in [City]" |
| **Schema markup** | LocalBusiness + Event (for scheduled meetings) |
| **NAP consistency** | Name, Address, Phone consistent with Google Business |
| **Local content** | Mention venue name, neighborhood, transit access |

**Structured Data (Schema.org):**

```json
{
  "@context": "https://schema.org",
  "@type": "LocalBusiness",
  "name": "Bros Before Lows - Toronto",
  "description": "Men's mental health peer support group in Toronto",
  "url": "https://brosbeforelows.com/support-groups/toronto",
  "address": {
    "@type": "PostalAddress",
    "addressLocality": "Toronto",
    "addressRegion": "ON",
    "addressCountry": "CA"
  },
  "parentOrganization": {
    "@type": "NGO",
    "name": "Bros Before Lows",
    "url": "https://brosbeforelows.com"
  }
}
```

### Technical SEO Checklist

| Item | Requirement |
|------|-------------|
| **Canonical URLs** | Self-referencing canonicals on all pages |
| **Hreflang** | Not needed (Canada-only, English) |
| **XML Sitemap** | Auto-generated, submitted to Google Search Console |
| **Robots.txt** | Allow all public pages, block `/cart`, `/checkout` |
| **Page speed** | Target <2.5s LCP (Largest Contentful Paint) |
| **Mobile-first** | All pages mobile-responsive |
| **HTTPS** | Required (already in place) |
| **Internal linking** | City pages link to each other, all link to main Support Groups |

---

## Summary: Total Page Count

| Section | Pages |
|---------|-------|
| Homepage | 1 |
| Support Groups | 9 (landing + 6 cities + virtual + host) |
| Events | 3 (landing + template + sponsor) |
| About | 4 (landing + mathieu + impact + contact) |
| Donate | 3 (landing + monthly + corporate) |
| Shop | 1 (or external link) |
| Legal/Support | 5 (terms, privacy, faq, support, crisis) |
| **TOTAL** | **26 pages** |

---

## Next Steps

1. **Wireframing:** Create low-fidelity wireframes for key pages (Homepage, Support Groups landing, City page, Donate)
2. **Content inventory:** Audit existing copy, identify gaps
3. **Design system:** Extend brand analysis into component library
4. **Technical spec:** Choose platform, define build requirements
5. **SEO foundation:** Set up Google Search Console, plan redirects from Fourthwall

---

*Document prepared for Bros Before Lows website redesign project.*
