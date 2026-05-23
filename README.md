# Fox Rothschild LLP

Fox Rothschild LLP is a national US law firm with approximately 1,000 attorneys
spread across 30+ offices, with a footprint that runs from the Mid-Atlantic
(Philadelphia, Princeton, Wilmington, New York) through the Southeast
(Charlotte, Raleigh, Greensboro, Greenville, Atlanta, Miami, West Palm Beach,
Sarasota), the Midwest (Chicago, Minneapolis, Kansas City), the Mountain and
Southwest (Denver, Dallas, Oklahoma City, Las Vegas), and the West Coast
(Los Angeles, San Francisco, Seattle). Per the firm's own services index, its
practice spans more than 50 named areas — from Affordable Housing and Antitrust
through Cannabis Law, Privacy & Data Security, ESG, Life Sciences, and White
Collar Criminal Defense.

This is **not** a developer-API provider. Fox Rothschild publishes no public
REST or GraphQL APIs, no OpenAPI specifications, no SDKs, and no GitHub
organization. The catalog here exists because the firm runs a substantial
LexBlog (WordPress) network of attorney-authored blogs that **are**
machine-consumable via standard RSS 2.0 feeds at `/feed/` on each blog
subdomain. That makes the firm's expert thought-leadership programmatically
reachable even though the firm itself ships no API product.

## What's indexed

- **21 LexBlog/WordPress topical blogs**, each with an `/feed/` RSS 2.0 endpoint
- **Firm publications hub** at `foxrothschild.com/publications` (60+ pages of
  alerts, articles, newsletters, podcasts; HTML only, no RSS surfaced)
- **Email subscription channel** at `foxrothschild.com/subscribe`
- **Podcast distribution** on Spotify, Apple Podcasts, and SoundCloud
  (e.g. *Labor Law Lineup*, *The Presumption of Innocence Podcast Series*)
- **Social channels**: LinkedIn, X, Facebook, Instagram

## Blog network (all on LexBlog, all RSS-able)

| Blog | Topic | RSS |
|---|---|---|
| Above the Fold | Advertising, Trademark & Copyright | https://advertisinglaw.foxrothschild.com/feed/ |
| California Employment Law | California labor & employment | https://californiaemploymentlaw.foxrothschild.com/feed/ |
| Delaware Chancery Law Blog | Delaware corporate / Chancery | https://delawarechancery.foxrothschild.com/feed/ |
| Employment Class Actions | Class action defense | https://employmentclassactions.foxrothschild.com/feed/ |
| NJ Family Law | New Jersey family law | https://njfamilylaw.foxrothschild.com/feed/ |
| PA Family Law | Pennsylvania family law | https://pafamilylaw.foxrothschild.com/feed/ |
| Federal Government Contracts & Procurement | GovCon | https://governmentcontracts.foxrothschild.com/feed/ |
| Franchise Law Update | Franchise & distribution | https://franchiselaw.foxrothschild.com/feed/ |
| Global Dispute Resolution Insights | International arbitration | https://globaldisputeresolutioninsights.foxrothschild.com/feed/ |
| Health Care Law Matters | Health care | https://healthcarelawmatters.foxrothschild.com/feed/ |
| Immigration View | US immigration | https://immigrationview.foxrothschild.com/feed/ |
| In Solvency | Bankruptcy & restructuring | https://insolvency.foxrothschild.com/feed/ |
| In the Weeds | Cannabis | https://cannabislaw.foxrothschild.com/feed/ |
| It's Just Business | NC Business Court | https://itsjustbusiness.foxrothschild.com/feed/ |
| North Carolina Appellate Blog | NC appellate | https://ncapb.foxrothschild.com/feed/ |
| Pay or Play | Entertainment & sports | https://payorplay.foxrothschild.com/feed/ |
| PFAS & Emerging Contaminants | Environmental | https://pfas.foxrothschild.com/feed/ |
| Plane-ly Spoken | Aviation & drone | https://plane-lyspoken.foxrothschild.com/feed/ |
| Privacy Compliance & Data Security | Privacy / cybersecurity | https://dataprivacy.foxrothschild.com/feed/ |
| Tax Controversy & Financial Crimes Report | Tax / white collar | https://taxcontroversy.foxrothschild.com/feed/ |
| Wage & Hour | FLSA / wage-and-hour | https://wagehourlaw.foxrothschild.com/feed/ |

RSS feed at `cannabislaw.foxrothschild.com/feed/` was verified live (RSS 2.0,
WordPress 6.8.5 / LexBlog generator).

## What's deliberately absent

- **No OpenAPI / AsyncAPI / JSON Schema artifacts** — there is no developer
  API surface to document. The `openapi/`, `asyncapi/`, `json-schema/`,
  `json-structure/`, `json-ld/`, `examples/`, `rules/`, `capabilities/`, and
  `vocabulary/` folders are intentionally omitted per the pipeline's "do not
  create empty/placeholder specs" rule.
- **No GitHub organization** for Fox Rothschild.
- **No public pricing, rate limits, or FinOps surface** — engagement is via
  attorney/client relationships, not metered API consumption.

## Source

- `apis.yml` — APIs.json index of the firm and its 21 RSS-able LexBlog feeds
- Provider home: https://www.foxrothschild.com
