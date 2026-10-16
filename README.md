# Business Intelli Solutions — website (static build)

A conversational website for Business Intelli Solutions: one set of company content presented ten ways. Visitors ask
in their own words or follow guided paths, and every view answers from the same published content. It is a static
site — no server or database.

## Open it

- On a computer: double-click `index.html` (Chrome, Edge or Firefox). No server is needed.
- On a web host: upload everything in this folder, keeping the folders as they are (see `HOSTING.txt`).

The site starts in the **Conversation** view; the company logo returns there from every view. Other views open from
the **View** button or a link such as `index.html?flavor=guided`:
`conversation`, `guided`, `enterprise`, `masonry`, `story`, `dashboard`, `immersive`, `hyperframe`, `orbit3d`, `spatial`.

## What's in it

| File | What it is |
| --- | --- |
| `index.html` | the page |
| `app.bundle.js` | the site engine (all ten views) |
| `site-data.js` | the published content and site settings |
| `assets/` | styles and the Business Intelli logos |
| `HOSTING.txt` | hosting notes |

## Build

Revision **C-6** (16 October 2026). Every view's home page now leads with "Trusted Business Solutions Provider for
Enterprises" and the six Business Solutions for Enterprises (ServiceNow, Salesforce, Oracle applications, Snowflake,
Databricks, SAP S/4HANA), followed by delivery experience, how we deliver, company facts, broader capabilities, and
people and contact. The previous revision, C-5, scored 8/10 or higher from an independent AI reviewer in every view;
the review of C-6 is pending.

- `app.bundle.js` SHA-256 `f779be9a6a0dea10d371e0c4b484c97267b820792d57fc96522538ee370e3ba5`
- `site-data.js` SHA-256 `e668c881dd876a8d79be1f3e6eebadd93fab197188b3dc1f587a9fff40fd2309`

Pending owner decisions: the wording of the AI and agentic services and of the enterprise solution cards; the
certifications and partner level are shown as stated by the company; a home for the policy and privacy pages (they
currently link to the WordPress site).
