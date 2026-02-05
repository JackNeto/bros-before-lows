# Bros Before Lows - User Journey Maps

**Document Version:** 1.0
**Created:** February 2026
**Purpose:** Guide website redesign with user-centered journey mapping

---

## Table of Contents

1. [Executive Summary](#executive-summary)
2. [Journey 1: Someone in Crisis](#journey-1-someone-in-crisis)
3. [Journey 2: Potential Donor](#journey-2-potential-donor)
4. [Journey 3: Volunteer/Community Host](#journey-3-volunteercommunity-host)
5. [Journey 4: Sponsor/Partner](#journey-4-sponsorpartner)
6. [Journey 5: Family Member/Friend](#journey-5-family-memberfriend)
7. [Cross-Journey Insights](#cross-journey-insights)
8. [Recommended Site Architecture](#recommended-site-architecture)

---

## Executive Summary

Bros Before Lows serves five distinct user personas, each requiring tailored pathways through the website. This document maps the emotional and functional journey of each persona from first awareness through advocacy, identifying critical pain points and opportunities for the website redesign.

### Key Findings

| Persona | Primary Need | Critical Gap | Priority |
|---------|--------------|--------------|----------|
| Someone in Crisis | Immediate support access | Crisis resources buried, no clear pathway | **CRITICAL** |
| Potential Donor | Trust & transparency | Impact metrics not visible, no recurring option | HIGH |
| Volunteer/Community Host | Clear expectations & process | No application process, vague requirements | HIGH |
| Sponsor/Partner | ROI & visibility details | No partnership page or tiers | MEDIUM |
| Family Member/Friend | Resources to share | No dedicated section for loved ones | HIGH |

---

## Journey 1: Someone in Crisis

### Persona Profile

```
+------------------------------------------------------------------+
|  MARCUS, 34                                                       |
|  "I can't keep pretending I'm okay"                              |
+------------------------------------------------------------------+
|  Situation:    Recently divorced, struggling with depression      |
|  Emotional:    Desperate, ashamed, isolated, skeptical           |
|  Tech Comfort: Moderate - searches on phone late at night        |
|  Barriers:     Stigma, fear of judgment, doesn't want "therapy"  |
+------------------------------------------------------------------+
```

### Journey Map

```
AWARENESS          CONSIDERATION        DECISION           ACTION            ADVOCACY
    |                   |                  |                  |                  |
    v                   v                  v                  v                  v
+--------+        +-----------+      +-----------+      +-----------+      +-----------+
|Google  |        |Lands on   |      |Reads about|      |Joins      |      |Attends    |
|search: |------->|BBL        |----->|peer       |----->|waitlist / |----->|first      |
|"men's  |        |homepage   |      |support    |      |contacts   |      |group      |
|support |        |           |      |groups     |      |BBL        |      |session    |
|group"  |        |           |      |           |      |           |      |           |
+--------+        +-----------+      +-----------+      +-----------+      +-----------+
    |                   |                  |                  |                  |
 EMOTION:            EMOTION:           EMOTION:           EMOTION:           EMOTION:
 Desperate,          Cautious hope,     "These guys        Relief,            Connection,
 skeptical           "Is this real?"    get it"            nervous            belonging
                                                           excitement
```

### Detailed Stage Breakdown

#### Stage 1: AWARENESS

**Entry Points:**
- Google: "men's mental health support Toronto", "men's support group near me"
- Instagram discovery via @brosbeforelows
- Word of mouth from another man
- Crisis line referral (988)

**Emotional State:**
- Desperate, possibly suicidal
- Shame about needing help
- Skeptical of "therapy" or clinical approaches
- Searching late at night when alone

**What They Need IMMEDIATELY:**
```
+------------------------------------------------------------------+
|  CRITICAL: FIRST 5 SECONDS ON SITE                               |
+------------------------------------------------------------------+
|  1. Crisis line visible (988) - NOT buried in footer             |
|  2. "You're not alone" messaging                                 |
|  3. Clear this is FOR MEN, BY MEN (peer-led, not clinical)       |
|  4. Photo of real men (not stock photos)                         |
|  5. One clear action: "Find Support Now" button                  |
+------------------------------------------------------------------+
```

**Pain Points:**
- Current site buries 988 in footer
- No clear "I need help now" pathway
- Homepage focused on event/fundraising, not support
- No explanation of what peer support actually looks like

**Opportunities:**
- Sticky crisis banner at top of every page
- "What to Expect" section demystifying peer groups
- Anonymous chat or text option
- Video testimonial from a man who found help

---

#### Stage 2: CONSIDERATION

**Questions They're Asking:**
- "Will I be judged?"
- "Who are these people?"
- "Is this a cult/sales pitch/religious thing?"
- "Will anyone I know find out?"
- "What actually happens in a group?"

**Content Needed:**

| Content Type | Purpose | Format |
|--------------|---------|--------|
| "What is Peer Support?" | Demystify the experience | Short explainer + video |
| Founder's Story | Build trust through vulnerability | Written + video |
| Testimonials | Social proof from real men | Anonymous quotes, first names only |
| FAQ for First-Timers | Address fears directly | Expandable Q&A |
| Group Session Preview | Show what happens | "A typical session looks like..." |

**Trust Signals Required:**
- Real photos of groups (with consent)
- Named founder (Mathieu Harbec) with his story
- Clear statement: "Free, peer-led, no judgment"
- Privacy commitment: "What's shared stays here"

---

#### Stage 3: DECISION

**Conversion Triggers:**
- Sees a group in their city (Toronto, Brampton, etc.)
- Reads a testimonial that resonates
- Realizes it's free/pay-what-you-can
- Founder's story mirrors their experience

**Barriers to Overcome:**
- "I'll do it later" (may not survive later)
- "I'm not that bad" (minimize struggle)
- "What if someone sees me?" (privacy fear)

**CTAs at This Stage:**
```
PRIMARY:    [Find a Group Near You]
SECONDARY:  [Join the Waitlist]  |  [Talk to Someone First]
SAFETY:     [Need Help Now? Call 988]
```

---

#### Stage 4: ACTION

**Friction Points in Current Site:**
- Newsletter signup as only clear action
- No group finder/schedule visible
- No explanation of next steps after signup
- No immediate confirmation of being heard

**Ideal User Flow:**
```
Click "Find a Group"
        |
        v
+------------------+
| Select Your City |  (Toronto, Brampton, Mississauga, etc.)
+------------------+
        |
        v
+------------------+
| See Available    |  (Day/time, in-person vs virtual, group size)
| Groups           |
+------------------+
        |
        v
+------------------+
| Reserve Spot or  |  (Low commitment, not "join forever")
| Join Waitlist    |
+------------------+
        |
        v
+------------------+
| Confirmation     |  "You're in. Here's what to expect."
| + What's Next    |  (Location, what to bring, contact info)
+------------------+
```

---

#### Stage 5: ADVOCACY

**Transformation Moments:**
- First time they share in group
- Feeling genuinely heard
- Helping another man in the group
- Attending consistently for 3+ months

**Advocacy Actions:**
- Tell a friend about BBL
- Share on social media (if comfortable)
- Donate to support the cause
- Become a community host themselves

---

### Key Pages/Content Needed for Crisis User

| Page | Purpose | Priority |
|------|---------|----------|
| **Crisis Landing Page** | Immediate help, 988 prominent, "you matter" messaging | CRITICAL |
| **What is Peer Support?** | Demystify, set expectations, reduce fear | HIGH |
| **Find a Group** | Interactive locator with availability | HIGH |
| **Founder's Story** | Build trust through Mathieu's vulnerability | HIGH |
| **Testimonials** | Social proof from real men | HIGH |
| **First Session FAQ** | "What to expect" for newcomers | MEDIUM |
| **Privacy Commitment** | Explain confidentiality clearly | MEDIUM |

---

## Journey 2: Potential Donor

### Persona Profile

```
+------------------------------------------------------------------+
|  SARAH, 42                                                        |
|  "I lost my brother to suicide. I want to help other men."       |
+------------------------------------------------------------------+
|  Situation:    Lost a loved one, wants to prevent future loss    |
|  Emotional:    Grieving, determined, seeking meaning             |
|  Giving Style: Research-oriented, wants impact visibility        |
|  Budget:       $50-500/year, open to monthly giving              |
+------------------------------------------------------------------+
```

**Alternative Donor Types:**
- Corporate employee with matching gift program
- Man who attended BBL groups and wants to give back
- Local business owner wanting to support community
- Mental health advocate following on Instagram

### Journey Map

```
AWARENESS          CONSIDERATION        DECISION           ACTION            ADVOCACY
    |                   |                  |                  |                  |
    v                   v                  v                  v                  v
+--------+        +-----------+      +-----------+      +-----------+      +-----------+
|Hears   |        |Visits site|      |Reviews    |      |Makes      |      |Shares     |
|about   |------->|reads      |----->|impact,    |----->|donation,  |----->|with       |
|BBL via |        |mission &  |      |trusts     |      |receives   |      |network,   |
|social/ |        |story      |      |organization|     |confirmation|     |gives again|
|news    |        |           |      |           |      |           |      |           |
+--------+        +-----------+      +-----------+      +-----------+      +-----------+
    |                   |                  |                  |                  |
 EMOTION:            EMOTION:           EMOTION:           EMOTION:           EMOTION:
 Moved,              Curious,           Evaluating,        Generous,          Proud,
 inspired            hopeful            cautious           hopeful            connected
```

### Detailed Stage Breakdown

#### Stage 1: AWARENESS

**Entry Points:**
- Instagram post about BBL's impact
- News article about men's mental health
- Friend shares fundraiser link
- Attended "Talking Saves Lives" event
- Lost someone to suicide, searching for ways to help

**What Captures Attention:**
- Compelling story/statistic about men's mental health crisis
- Grassroots, authentic feel (not corporate charity)
- Clear cause: "Men don't have to die from silence"

---

#### Stage 2: CONSIDERATION

**Questions They're Asking:**
- "Is this organization legitimate?"
- "Where does my money actually go?"
- "What impact have they made?"
- "Are they registered/tax-deductible?"
- "Who runs this?"

**Trust Signals Required:**
```
+------------------------------------------------------------------+
|  DONOR TRUST CHECKLIST                                           |
+------------------------------------------------------------------+
|  [ ] Registered charity status (or clear explanation if not)     |
|  [ ] Founder bio with photo and story                            |
|  [ ] Financial transparency (% to programs vs overhead)          |
|  [ ] Impact metrics (men served, groups run, cities reached)     |
|  [ ] Testimonials from men helped                                |
|  [ ] Media coverage / third-party validation                     |
|  [ ] Contact information for questions                           |
+------------------------------------------------------------------+
```

**Pain Points in Current Site:**
- No "About Us" or team page
- Impact metrics not prominently displayed
- Fundraising goal shown but not what funds enable
- No breakdown of how donations are used

---

#### Stage 3: DECISION

**Conversion Triggers:**
- Seeing specific impact: "$50 covers one man's spot for a month"
- Founder's personal story resonates
- Clear, secure donation process
- Option to give in memory of someone

**Barriers:**
- Uncertainty about tax deductibility
- No monthly giving option visible
- Unclear if small donation matters
- No corporate matching information

**Content Needed:**

| Content | Example |
|---------|---------|
| Impact Ladder | "$25 = supplies, $50 = one man's spot, $100 = train a host" |
| Use of Funds | Pie chart: 80% programs, 15% outreach, 5% admin |
| Progress Meter | "$5,950 of $6,000 raised - 105 donors" (current, good!) |
| Donor Wall | "Join 105 supporters who believe men's lives matter" |

---

#### Stage 4: ACTION

**Donation Flow Requirements:**
```
+------------------------------------------------------------------+
|  IDEAL DONATION EXPERIENCE                                        |
+------------------------------------------------------------------+
|                                                                   |
|  1. CHOOSE AMOUNT                                                 |
|     [ $25 ]  [ $50 ]  [ $100 ]  [ $250 ]  [ Custom: $____ ]      |
|                                                                   |
|  2. FREQUENCY                                                     |
|     ( ) One-time    ( ) Monthly    ( ) Annually                  |
|                                                                   |
|  3. DEDICATION (optional)                                         |
|     [ ] In memory of _______________                             |
|     [ ] In honor of ________________                             |
|                                                                   |
|  4. PAYMENT                                                       |
|     [Credit Card]  [PayPal]  [Apple Pay]                         |
|                                                                   |
|  5. RECEIPT                                                       |
|     Email: ________________  [ ] Send tax receipt                |
|                                                                   |
+------------------------------------------------------------------+
```

**Post-Donation Experience:**
- Immediate thank you page with impact statement
- Confirmation email within minutes
- Social sharing option: "I just supported BBL"
- Invitation to follow journey on Instagram

---

#### Stage 5: ADVOCACY

**Keeping Donors Engaged:**
- Quarterly impact updates via email
- Invite to events (Talking Saves Lives concert)
- Anniversary of first donation recognition
- Upgrade prompts: "Make it monthly?"

**Advocacy Actions:**
- Share donation on social media
- Start a birthday fundraiser for BBL
- Encourage employer matching
- Become a recurring donor
- Bring friends to events

---

### Key Pages/Content Needed for Donors

| Page | Purpose | Priority |
|------|---------|----------|
| **Donation Page** | Clear, friction-free giving with impact tiers | HIGH |
| **Impact Report** | How funds are used, men helped, growth | HIGH |
| **About/Team Page** | Humanize organization, build trust | HIGH |
| **Ways to Give** | One-time, monthly, in-memory, matching gifts | MEDIUM |
| **Donor Stories** | Why others give (social proof) | MEDIUM |
| **Financials/Transparency** | Build trust with detailed breakdown | MEDIUM |

---

## Journey 3: Volunteer/Community Host

### Persona Profile

```
+------------------------------------------------------------------+
|  DAVID, 38                                                        |
|  "I found help here. Now I want to pay it forward."              |
+------------------------------------------------------------------+
|  Situation:    Attended BBL groups, transformed, wants to lead   |
|  Emotional:    Grateful, purposeful, ready to give back          |
|  Skills:       Active listener, stable mental health, reliable   |
|  Availability: 4-6 hours/month for group facilitation            |
+------------------------------------------------------------------+
```

**Alternative Host Types:**
- Mental health professional wanting community involvement
- Pastor/community leader seeking resources for men
- Recovery community member wanting to expand support
- HR professional starting workplace wellness program

### Journey Map

```
AWARENESS          CONSIDERATION        DECISION           ACTION            ADVOCACY
    |                   |                  |                  |                  |
    v                   v                  v                  v                  v
+--------+        +-----------+      +-----------+      +-----------+      +-----------+
|Sees    |        |Reads host |      |Reviews    |      |Applies,   |      |Leads      |
|"seeking|------->|opportunity|----->|requirements|---->|gets       |----->|groups,    |
|hosts"  |        |details    |      |& training |      |trained,   |      |recruits   |
|on site |        |           |      |info       |      |launches   |      |others     |
+--------+        +-----------+      +-----------+      +-----------+      +-----------+
    |                   |                  |                  |                  |
 EMOTION:            EMOTION:           EMOTION:           EMOTION:           EMOTION:
 Curious,            Interested,        Evaluating fit,    Nervous but        Fulfilled,
 purposeful          hopeful            "Can I do this?"   committed          empowered
```

### Detailed Stage Breakdown

#### Stage 1: AWARENESS

**Entry Points:**
- Contact page mention: "Seeking Community Hosts"
- Instagram call for volunteers
- Word of mouth from existing host
- Attended a group, asked how to help

**Current Site Gap:**
- "Seeking hosts" mentioned but no details
- No dedicated volunteer/host page
- No application process visible

---

#### Stage 2: CONSIDERATION

**Questions They're Asking:**
- "What does a community host actually do?"
- "Am I qualified? Do I need training?"
- "How much time is required?"
- "Will I be alone or supported?"
- "What if someone has a crisis in my group?"

**Information Needed:**
```
+------------------------------------------------------------------+
|  COMMUNITY HOST ROLE OVERVIEW                                     |
+------------------------------------------------------------------+
|                                                                   |
|  WHAT YOU'LL DO:                                                  |
|  - Facilitate weekly 90-minute peer support sessions              |
|  - Create safe space for men to share                             |
|  - Guide discussions (not provide therapy)                        |
|  - Connect with BBL support team as needed                        |
|                                                                   |
|  TIME COMMITMENT:                                                 |
|  - 4-6 hours/month (1 session/week + prep)                       |
|  - 6-month minimum commitment                                     |
|  - Training: 8-hour initial + monthly check-ins                  |
|                                                                   |
|  REQUIREMENTS:                                                    |
|  - Lived experience with mental health challenges (preferred)     |
|  - Currently in stable mental health                             |
|  - Strong listening skills                                        |
|  - Background check (required)                                    |
|  - Complete BBL facilitation training                            |
|                                                                   |
|  WHAT YOU GET:                                                    |
|  - Full training in peer support facilitation                     |
|  - Ongoing mentorship from experienced hosts                      |
|  - Community of fellow hosts                                      |
|  - The reward of changing men's lives                            |
|                                                                   |
+------------------------------------------------------------------+
```

---

#### Stage 3: DECISION

**Conversion Triggers:**
- Clear, achievable requirements
- Training provided (not expected to know everything)
- Support system in place
- Meaningful impact visible

**Barriers:**
- Fear of not being qualified
- Time commitment concerns
- Uncertainty about crisis situations
- No clear next step to apply

**Trust Builders:**
- Testimonials from current hosts
- "A day in the life" of a host
- Training curriculum overview
- Crisis protocol explanation

---

#### Stage 4: ACTION

**Application Process (Recommended):**
```
STEP 1: Interest Form
        |
        v
+------------------+
| Basic info,      |  (Name, city, why interested, availability)
| motivation       |
+------------------+
        |
        v
STEP 2: Screening Call
+------------------+
| 30-min video     |  (Assess fit, answer questions, explain role)
| call with BBL    |
+------------------+
        |
        v
STEP 3: Training
+------------------+
| 8-hour workshop  |  (Facilitation skills, crisis response, BBL values)
| (virtual/in-     |
| person)          |
+------------------+
        |
        v
STEP 4: Shadow Sessions
+------------------+
| Observe 2-3      |  (See real groups, ask questions)
| existing groups  |
+------------------+
        |
        v
STEP 5: Launch
+------------------+
| Start your group |  (With mentor support for first 3 months)
| with support     |
+------------------+
```

---

#### Stage 5: ADVOCACY

**Host Retention & Growth:**
- Monthly host community calls
- Annual host appreciation event
- Recognition on website
- Pathway to regional leadership

**Advocacy Actions:**
- Recruit new hosts
- Share experience on social media
- Speak at BBL events
- Mentor new hosts

---

### Key Pages/Content Needed for Hosts

| Page | Purpose | Priority |
|------|---------|----------|
| **Become a Host** | Dedicated landing page with role details | HIGH |
| **Host Application** | Simple form to express interest | HIGH |
| **Training Overview** | What training includes, timeline | MEDIUM |
| **Host Stories** | Testimonials from current hosts | MEDIUM |
| **Host Resources** | (Login area) Materials, crisis protocols | MEDIUM |
| **FAQ for Hosts** | Address common concerns | MEDIUM |

---

## Journey 4: Sponsor/Partner

### Persona Profile

```
+------------------------------------------------------------------+
|  JENNIFER, 45                                                     |
|  Marketing Director, Regional Construction Company                |
+------------------------------------------------------------------+
|  Situation:    Company wants community involvement, men's health  |
|                is relevant to workforce (85% male employees)      |
|  Goals:        Brand visibility + genuine impact + employee       |
|                wellness tie-in                                    |
|  Budget:       $2,000 - $10,000/year for sponsorships            |
+------------------------------------------------------------------+
```

**Alternative Sponsor Types:**
- Local business owner with personal connection to cause
- Mental health clinic wanting community presence
- Sports organization supporting men's wellness
- Media company wanting content partnership

### Journey Map

```
AWARENESS          CONSIDERATION        DECISION           ACTION            ADVOCACY
    |                   |                  |                  |                  |
    v                   v                  v                  v                  v
+--------+        +-----------+      +-----------+      +-----------+      +-----------+
|Learns  |        |Reviews    |      |Evaluates  |      |Signs      |      |Renews,    |
|about   |------->|sponsorship|----->|ROI, gets  |----->|agreement, |----->|expands,   |
|BBL     |        |opportun-  |      |internal   |      |receives   |      |refers     |
|events  |        |ities      |      |approval   |      |benefits   |      |others     |
+--------+        +-----------+      +-----------+      +-----------+      +-----------+
    |                   |                  |                  |                  |
 EMOTION:            EMOTION:           EMOTION:           EMOTION:           EMOTION:
 Intrigued,          Evaluating,        Justifying,        Partnership        Proud,
 aligned             comparing          presenting         excitement         invested
```

### Detailed Stage Breakdown

#### Stage 1: AWARENESS

**Entry Points:**
- Attended BBL event as individual
- Employee mentions BBL
- Instagram/news coverage
- Direct outreach from BBL
- Searching "men's mental health sponsorship Toronto"

---

#### Stage 2: CONSIDERATION

**Questions They're Asking:**
- "What sponsorship levels are available?"
- "What visibility do we get?"
- "How do we activate this with employees?"
- "Is this organization legitimate/safe to associate with?"
- "Can we get a presentation for leadership?"

**Sponsor Evaluation Criteria:**

| Criteria | What They Need to See |
|----------|----------------------|
| Brand Safety | Professional organization, clear values |
| Visibility | Logo placement, event presence, social mentions |
| Engagement | Employee participation opportunities |
| Impact | Measurable outcomes, stories |
| Flexibility | Partnership tiers, customization |

---

#### Stage 3: DECISION

**Partnership Tier Structure (Recommended):**
```
+------------------------------------------------------------------+
|  SPONSORSHIP TIERS                                                |
+------------------------------------------------------------------+
|                                                                   |
|  BRONZE - $1,000/year                                            |
|  - Logo on website sponsor page                                   |
|  - Social media thank you (2x/year)                              |
|  - 2 tickets to annual event                                      |
|                                                                   |
|  SILVER - $2,500/year                                            |
|  - All Bronze benefits                                            |
|  - Logo on event merchandise                                      |
|  - Social media features (4x/year)                               |
|  - 5 tickets to annual event                                      |
|  - Employee workshop option                                       |
|                                                                   |
|  GOLD - $5,000/year                                              |
|  - All Silver benefits                                            |
|  - Logo on all event materials                                    |
|  - Featured social media partnership story                        |
|  - 10 tickets to annual event                                     |
|  - On-site wellness workshop for employees                        |
|  - Quarterly impact report                                        |
|                                                                   |
|  PLATINUM - $10,000/year                                         |
|  - All Gold benefits                                              |
|  - Presenting sponsor at one event                               |
|  - Co-branded content opportunity                                |
|  - Speaking slot at annual event                                 |
|  - Custom employee program                                       |
|  - Monthly check-ins with BBL leadership                         |
|                                                                   |
|  CUSTOM PARTNERSHIPS                                              |
|  - In-kind donations (venue, services, products)                 |
|  - Event-specific sponsorship                                     |
|  - Workplace program partnerships                                |
|                                                                   |
+------------------------------------------------------------------+
```

**Barriers:**
- No visible sponsorship information on current site
- Need formal proposal/deck for internal approval
- Uncertain about organization's capacity
- No clear contact for partnerships

---

#### Stage 4: ACTION

**Partnership Process:**
```
STEP 1: Inquiry
        |
        v
+------------------+
| Contact form or  |  (Company, interest level, budget range)
| email outreach   |
+------------------+
        |
        v
STEP 2: Discovery Call
+------------------+
| 30-min call to   |  (Understand goals, explain options)
| explore fit      |
+------------------+
        |
        v
STEP 3: Proposal
+------------------+
| Custom proposal  |  (PDF deck for internal presentation)
| with options     |
+------------------+
        |
        v
STEP 4: Agreement
+------------------+
| Simple sponsor   |  (Clear deliverables, timeline, payment)
| agreement        |
+------------------+
        |
        v
STEP 5: Activation
+------------------+
| Kickoff call,    |  (Logo collection, event calendar, intro)
| onboarding       |
+------------------+
```

---

#### Stage 5: ADVOCACY

**Sponsor Retention:**
- Quarterly impact reports
- Exclusive sponsor updates
- Early access to event tickets
- Annual sponsor appreciation

**Advocacy Actions:**
- Refer other businesses
- Expand partnership level
- Promote partnership publicly
- Integrate BBL into corporate wellness

---

### Key Pages/Content Needed for Sponsors

| Page | Purpose | Priority |
|------|---------|----------|
| **Partner With Us** | Overview of sponsorship opportunities | HIGH |
| **Sponsorship Tiers** | Clear benefits at each level | HIGH |
| **Corporate Wellness** | How BBL can support employee mental health | MEDIUM |
| **Sponsor Contact Form** | Easy inquiry for interested businesses | HIGH |
| **Current Partners** | Showcase existing sponsors (social proof) | MEDIUM |
| **Downloadable Deck** | PDF for internal presentations | MEDIUM |

---

## Journey 5: Family Member/Friend

### Persona Profile

```
+------------------------------------------------------------------+
|  KAREN, 52                                                        |
|  "My son hasn't been himself since his divorce. I'm worried."    |
+------------------------------------------------------------------+
|  Situation:    Notices concerning changes in loved one           |
|  Emotional:    Worried, helpless, unsure how to help             |
|  Barriers:     Doesn't want to push, fears making it worse       |
|  Needs:        Resources to share, guidance on approach          |
+------------------------------------------------------------------+
```

**Alternative Supporter Types:**
- Wife worried about husband's mental health
- Friend who noticed withdrawal/changes
- Father concerned about adult son
- Colleague noticing coworker struggling

### Journey Map

```
AWARENESS          CONSIDERATION        DECISION           ACTION            ADVOCACY
    |                   |                  |                  |                  |
    v                   v                  v                  v                  v
+--------+        +-----------+      +-----------+      +-----------+      +-----------+
|Searches|        |Finds      |      |Reads how  |      |Shares     |      |Loved one  |
|"help   |------->|BBL        |----->|to talk to |----->|resources  |----->|gets help, |
|for my  |        |resources  |      |their      |      |with loved |      |Karen      |
|son"    |        |for family |      |loved one  |      |one        |      |advocates  |
+--------+        +-----------+      +-----------+      +-----------+      +-----------+
    |                   |                  |                  |                  |
 EMOTION:            EMOTION:           EMOTION:           EMOTION:           EMOTION:
 Desperate,          Hopeful,           Learning,          Nervous,           Grateful,
 scared              seeking            preparing          hopeful            relieved
```

### Detailed Stage Breakdown

#### Stage 1: AWARENESS

**Entry Points:**
- Google: "how to help a man with depression"
- Searching: "men's mental health resources Toronto"
- Referred by therapist or doctor
- Found via crisis line (988) resources
- Instagram discovery

**What They're Looking For:**
- Validation that their concern is valid
- Resources they can share with their loved one
- Guidance on how to approach the conversation
- Something that doesn't feel "clinical" to men

---

#### Stage 2: CONSIDERATION

**Questions They're Asking:**
- "Is this appropriate for my loved one?"
- "How do I bring this up without pushing them away?"
- "What if they get angry or defensive?"
- "Is this a cult or scam?"
- "Will this actually help?"

**Content Needed:**
```
+------------------------------------------------------------------+
|  CONTENT: "SUPPORTING A MAN YOU LOVE"                            |
+------------------------------------------------------------------+
|                                                                   |
|  UNDERSTANDING MEN'S MENTAL HEALTH                                |
|  - Why men struggle to seek help (stigma, masculinity norms)     |
|  - Warning signs to watch for                                     |
|  - Why peer support works for men                                |
|                                                                   |
|  HOW TO START THE CONVERSATION                                    |
|  - Dos: Choose right time, be patient, listen, offer specific    |
|         resources                                                 |
|  - Don'ts: Lecture, give ultimatums, force them                  |
|  - Script starters: "I've noticed...", "I'm here for you..."     |
|                                                                   |
|  RESOURCES TO SHARE                                               |
|  - Shareable link to BBL (not clinical-looking)                  |
|  - Downloadable conversation guide                               |
|  - Video they can watch together                                 |
|                                                                   |
|  TAKING CARE OF YOURSELF                                          |
|  - You can't force someone to get help                           |
|  - Resources for supporters (Al-Anon style)                      |
|  - When to involve professionals                                 |
|                                                                   |
+------------------------------------------------------------------+
```

---

#### Stage 3: DECISION

**What Convinces Them:**
- Seeing the peer-led, non-clinical approach
- Testimonials from men (or their families)
- Specific resources they can share
- Understanding what happens in groups

**Barriers:**
- Fear of making things worse
- Loved one may reject "mental health" framing
- Unsure if BBL is "serious enough" for their situation
- Don't know when crisis intervention is needed

---

#### Stage 4: ACTION

**Actions They Can Take:**
1. Share BBL website with loved one
2. Forward specific page: "What is Peer Support?"
3. Attend event together (non-threatening entry)
4. Leave information visible (not pushy)
5. Contact BBL for guidance

**Resources to Share:**

| Resource | Purpose | Format |
|----------|---------|--------|
| Website Link | Let them explore at own pace | URL |
| Conversation Guide | Help family member approach topic | PDF |
| "What is Peer Support?" | Demystify for reluctant men | Video/page |
| Event Info | Low-pressure way to experience BBL | Flyer/link |
| Crisis Resources | If situation is urgent | 988/911 info |

---

#### Stage 5: ADVOCACY

**When Loved One Gets Help:**
- Family member becomes BBL advocate
- Shares story with others in similar situations
- May donate or volunteer
- Spreads awareness in their community

---

### Key Pages/Content Needed for Family/Friends

| Page | Purpose | Priority |
|------|---------|----------|
| **Supporting Someone You Love** | Dedicated resource for family/friends | HIGH |
| **Warning Signs** | Help identify when someone needs support | HIGH |
| **How to Start the Conversation** | Scripts, dos/don'ts | HIGH |
| **Shareable Resources** | Easy-to-forward links, PDFs | MEDIUM |
| **FAQ for Family** | Address their specific concerns | MEDIUM |
| **Crisis Resources** | When to escalate, who to call | HIGH |

---

## Cross-Journey Insights

### Common Needs Across All Personas

```
+------------------------------------------------------------------+
|  EVERY USER NEEDS:                                                |
+------------------------------------------------------------------+
|                                                                   |
|  1. TRUST SIGNALS                                                 |
|     - Real photos of real people                                 |
|     - Named founder with story                                   |
|     - Testimonials                                               |
|     - Contact information                                        |
|                                                                   |
|  2. CLARITY                                                       |
|     - What BBL actually does                                     |
|     - How peer support works                                     |
|     - Geographic coverage                                        |
|     - Clear next steps                                           |
|                                                                   |
|  3. IMMEDIATE ACTIONS                                             |
|     - Relevant CTA visible                                       |
|     - Low-friction forms                                         |
|     - Confirmation of action                                     |
|                                                                   |
|  4. CRISIS AWARENESS                                              |
|     - 988 visible on every page                                  |
|     - Clear escalation path                                      |
|                                                                   |
+------------------------------------------------------------------+
```

### Conversion Priority Matrix

| Persona | Conversion Goal | Urgency | Page Views Likely |
|---------|----------------|---------|-------------------|
| Crisis User | Join group/contact | **CRITICAL** | 1-3 |
| Donor | Complete donation | HIGH | 3-5 |
| Host | Submit application | MEDIUM | 5-10 |
| Sponsor | Request info | MEDIUM | 5-10 |
| Family | Share resources | HIGH | 2-4 |

### Content Gap Analysis

| Content | Current State | Needed State |
|---------|--------------|--------------|
| Crisis Resources | Footer only | Sticky banner, dedicated page |
| What is Peer Support | Not present | Dedicated explainer page |
| About/Team | Not present | Full team page with founder story |
| Group Finder | Waitlist only | Interactive locator |
| Volunteer/Host | Brief mention | Full application flow |
| Sponsorship | Not present | Tiers and contact form |
| Family Resources | Not present | Dedicated section |
| Impact Metrics | Basic progress bar | Full impact report |

---

## Recommended Site Architecture

Based on journey analysis, the new site should have this structure:

```
HOME
|
+-- GET SUPPORT (For men seeking help)
|   |-- What is Peer Support?
|   |-- Find a Group (locator)
|   |-- Your First Session
|   |-- Testimonials
|   +-- Crisis Resources
|
+-- SUPPORT SOMEONE (For family/friends)
|   |-- Warning Signs
|   |-- How to Start the Conversation
|   |-- Resources to Share
|   +-- When to Get Professional Help
|
+-- GET INVOLVED
|   |-- Become a Community Host
|   |-- Volunteer Opportunities
|   |-- Attend an Event
|   +-- Spread the Word
|
+-- SUPPORT THE MISSION
|   |-- Donate
|   |-- Partner With Us
|   |-- Corporate Sponsorship
|   +-- Impact Report
|
+-- ABOUT
|   |-- Our Story
|   |-- Founder (Mathieu Harbec)
|   |-- Our Team
|   |-- Cities We Serve
|   +-- News & Press
|
+-- EVENTS
|   |-- Upcoming Events
|   |-- Talking Saves Lives Concert
|   +-- Past Events
|
+-- SHOP (Merch)
|
+-- CONTACT
|
[STICKY FOOTER: Crisis Line 988 | Instagram | Donate]
```

### Homepage CTA Hierarchy

```
+------------------------------------------------------------------+
|  HOMEPAGE - ABOVE THE FOLD                                        |
+------------------------------------------------------------------+
|                                                                   |
|  [STICKY CRISIS BANNER: Need help now? Call 988]                 |
|                                                                   |
|  HERO: "You don't have to face it alone."                        |
|  SUBHEAD: Men's peer support groups across the GTA               |
|                                                                   |
|  PRIMARY CTA:     [Find a Support Group]                         |
|  SECONDARY CTAs:  [Learn About Peer Support] [Support the Cause] |
|                                                                   |
+------------------------------------------------------------------+
```

---

## Appendix: CTA Reference by Persona

### Crisis User CTAs
- "Find Support Near You" (Primary)
- "Join the Waitlist"
- "Call 988 Now" (Always visible)
- "What to Expect"
- "Contact Us"

### Donor CTAs
- "Donate Today" (Primary)
- "Make it Monthly"
- "Give in Memory"
- "See Your Impact"
- "Share With Friends"

### Host CTAs
- "Become a Community Host" (Primary)
- "Learn About the Role"
- "Apply Now"
- "Talk to a Current Host"

### Sponsor CTAs
- "Partner With Us" (Primary)
- "View Sponsorship Tiers"
- "Download Partnership Deck"
- "Contact for Custom Partnership"

### Family/Friend CTAs
- "Resources for Loved Ones" (Primary)
- "How to Start the Conversation"
- "Share This Page"
- "Download Conversation Guide"
- "When to Call 988"

---

## Summary

This comprehensive user journey mapping identifies the following critical actions for the Bros Before Lows website redesign:

**Immediate Priorities:**
1. Add a sticky crisis banner with 988 visible on every page
2. Create a "What is Peer Support?" explainer page
3. Build an interactive group finder for the 6 GTA cities
4. Develop an About/Team page featuring Mathieu Harbec's story

**High Priority:**
5. Create a dedicated "Supporting Someone You Love" section for family/friends
6. Build a "Become a Community Host" page with application flow
7. Enhance donation page with impact tiers and recurring giving
8. Add testimonials throughout the site

**Medium Priority:**
9. Develop sponsorship tiers and partner contact form
10. Create downloadable resources (conversation guides, PDFs)
11. Build impact reporting/transparency page
12. Add host resources portal

The redesigned site should balance the urgency of crisis support (someone in immediate need should find help in under 10 seconds) with the longer consideration journeys of donors, sponsors, and potential hosts.

---

*Document prepared for Bros Before Lows website redesign project.*
