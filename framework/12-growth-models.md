# Growth Models: Examples & Inspiration

A growth model maps how value flows through your business — from how people discover you, through the steps they take to become a customer, to the moment they experience real value. It's unique to YOUR business.

**These examples are not templates to pick from.** They're reference models showing how different types of businesses have mapped their value flow. Study the patterns, then build your own model from scratch for your specific business. The `/review` skill will walk you through this.

When building your growth model, identify:
- **Channels** — How do people actually find you?
- **Key Drivers** — The conversion steps you can influence with your daily work
- **North Star Metric** — The customer behavior that best represents value delivery
- **Referral/retention loops** — How satisfied customers bring in new ones or come back

## SaaS (Self-Serve, User-Based)

Best for: Freemium/free-trial products where users sign up without talking to sales.

```
Channels: Organic Social, Events, SEO, Webinars, Guest Blogs, Podcasts
                              ↓
                        [Traffic]  ←── Social Shares
                              ↓
                     Trial (conversion)  ←── Referral Program
                              ↓
                      [Engaged Users]     ← Key Driver
                              ↓
                   Paying Users (monetisation)
                              ↓
                    Net Promoters (referral)  ← Key Driver
```

**North Star:** Engaged Users (e.g., weekly active users)
**Key Drivers:** Conversion to trial, engagement/activation, referral rate
**Rate Limiting Step (typical):** Conversion to trial OR activation to engaged

## SaaS (Sales-Driven)

Best for: B2B products with a sales team, demos, and longer sales cycles.

```
Channels: Paid Ads, Organic Social, Events, SEO, Webinars, Outbound Campaigns
                              ↓
                          [Traffic]
                              ↓
                    Marketing Qual. Lead (MQL)
                              ↓
                     Sales Qual. Lead (SQL)
                              ↓
                  Free Trial / Proof-of-Concept
                              ↓
                    Sales Conversion Rate
                              ↓
                        Paying Users
                              ↓
                  [Onboarded & Active (Adoption)]   ← North Star
                              ↓
                    Net Promoters (referral) → loops back to MQL
```

**North Star:** Onboarded & Active users (adoption)
**Key Drivers:** MQL→SQL conversion, trial→paid conversion, onboarding completion
**Rate Limiting Step (typical):** MQL volume OR trial-to-paid conversion

## SaaS (Usage-Based)

Best for: Products that charge based on consumption (API calls, credits, actions).

```
Channels: Organic Social, PPC, SEO, Meta Paid, WoM, LLM referrals
                              ↓
                          [Traffic]
                              ↓
                    Create Account (~25% conv.)
                              ↓
                 Happy User (5+ actions) ←── Referral Program
                       ↓              ↓
              [Print-Ready Service]   Purchase Credits   ← Key Driver
                       ↓
                    Revenue
                       ↓
              Net Promoters (referral)
```

**North Star:** Core value-delivery action (e.g., "Print-Ready Service completed," or "Weekly Actions")
**Key Drivers:** Account creation rate, activation to happy user, credit purchases
**Variant:** If usage-based with active users + actions per user → NSM = Weekly Actions = Active Users × Actions per User

## eCommerce

Best for: Online stores selling physical or digital products.

```
Channels: SEO, Referrals, Paid, Influencers
                        ↓
                   [First Visit]     ← Key Driver
                    ↓       ↓
              Subscribe   Retarget
                    ↓       ↓
                  Repeat Visit
                        ↓
                  Browse Around  ←── # of interesting/sellable products
                        ↓
               [Find the Right Item]  ← North Star  ←── Events, Email, Content, 
                    ↓           ↓                        Customer Service, Loyalty
           Wishlist & Cart    (direct)
                    ↓           ↓
                   Purchase
                 ↓            ↓
         New Customers    Repeat Customers → Engaged Customers (VIP List)
              (30%)            (70%)
                 ↓              ↓
                  [# of Orders]
                        ↓
              # of Products Sold
```

**North Star:** Find the Right Item (Add to Cart/Wishlist) — this is the moment value clicks
**Key Drivers:** First visit volume, browse→find conversion, repeat purchase rate
**Rate Limiting Step (typical):** First visit OR product-market match rate

## Marketplace (Simple)

Best for: Two-sided marketplaces connecting buyers and sellers.

```
                    DEMAND SIDE
                        ↓
                     Traffic
                        ↓
                  Visitors Browse
                        ↓
       [Find the Right Product]  ←── Sellable Products (SUPPLY)
              (Add to Cart)               ↓
                        ↓          # of Creators × Products per Creator
                   Transaction
```

**North Star:** Transactions (or "Find the Right Product" as leading indicator)
**Key balance metric:** Are you supply-constrained or demand-constrained? This tells you which side to focus on.
**Key Drivers:** Traffic, product-match rate, sellable product count

## Marketplace (Detailed)

Adds complexity for marketplaces with engagement loops, trust-building, and multiple purchase paths.

Key additions:
- **Subscribe / Retarget** loops to bring visitors back
- **Fast purchase** vs **Slow purchase** paths (some buyers need trust-building via visits, Q&A, negotiation)
- **Creators promote their own work** — supply-side acquisition through seller marketing
- **Balance metric:** Supply quality vs. demand — track both sides

## Content / Events / Membership

Best for: Info products, courses, communities, coaching businesses.

```
Channels: Social Views, SEO, Email Blast, Organic Social, Partner Mktg, Paid Social, Cold Outreach
                              ↓
               Landing Page Visit → Lead Magnet(s)
                              ↓
                     Email List (Nurture)  ← track: Subscribers, Opens
                              ↓
                      [Course / Event / Membership]
                              ↓
              [Weekly Active Learners]   ← North Star
              (at least 2 engagements ever)
```

**North Star:** Weekly Active Learners (engagement = using a framework, consuming content, engaging with community)
**Key Drivers:** Lead magnet conversion, email-to-sale conversion, engagement loops

## Service Provider / Booking App

Best for: Apps that help service providers (fitness trainers, consultants, trades) get booked.

```
Channels: Marketplaces, WoM, Influencers, Partners
                        ↓
                   Landing Page  ← Key Driver
                        ↓
                    Install App → Create Account → Edit Site
                        ↓
                   First Booking
                        ↓
                  Real Bookings
                        ↓
             [H.A. 20+ Bookings]   ← North Star (Habituation threshold)
                    ↓         ↓
               Subscribe    Money
```

**North Star:** Habituated providers (20+ bookings — proves the platform delivers real value)
**Key Drivers:** Landing page conversion, first booking, habituation rate

## Fintech / Lending

Best for: Lending platforms, financial services with qualification steps.

```
Channels: Walk-ins, Advertising, Sales Prospecting, Purchased Lists
                              ↓
                    # of Qualified Leads
                              ↓
                      Client with Need  ←── Existing Customers (Analytics, CRM, In-app)
                              ↓
                        Credit-worthy → Ineligible (filtered out)
                              ↓
                          Offers
                              ↓
                    Client Acceptance Rate
                              ↓
                      [Loans/month]   ← North Star
```

**North Star:** Loans per month (or transactions completed)
**Key Drivers:** Qualified lead volume, credit-worthiness rate, client acceptance rate

## How Growth Models Scale

As your business grows, the model gets deeper — not wider. Each driver breaks down into sub-drivers, and those break into sub-sub-drivers. Your focus narrows to the **key drivers** (the ones with the highest leverage) at each level.

```
                    ★ North Star
                   /    |    \
              [KEY]   [   ]   [   ]           ← Drivers
             / | \    / \     / \
          [K][K][ ] [ ][ ] [ ][ ][ ]          ← Sub-drivers
         /|\ etc.
```

The filled boxes are your key drivers — where doubling performance would double the NSM. Everything else is "maintain." This is how you avoid spreading resources across 20 things and instead focus on the 2-3 that actually move the needle.

## How to Build YOUR Growth Model

Don't pick one of the above. Build your own. Use these examples to understand the *pattern*, then map your specific business:

1. **Start with your channels** — How do people actually find you today? (Be specific — not "social media" but "LinkedIn posts in founder communities")
2. **Map every step to value** — What happens after they find you? What steps do they go through before they experience real value?
3. **Identify the value moment** — At which step does the customer actually get what they came for? That's your North Star candidate.
4. **Find the loops** — Do satisfied customers bring in new ones? Do they come back? How?
5. **Identify your Key Drivers** — Which 1-3 steps have the most leverage on your North Star?
6. **Find your Rate Limiting Step** — Which key driver is the bottleneck right now?
7. **Put numbers on it** — What are your current conversion rates at each step?

The `/review` skill will walk you through this process conversationally and help you set up your metrics framework based on the model you build.
