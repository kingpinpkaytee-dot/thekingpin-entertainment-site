# SEO Phase 10 — Business Entity & Promotional Image Signals
Date: 2026-11-19

## Scope
Strengthen the public business entity signals for The Kingpin Entertainment Pty Ltd and clarify its relationship with the DiggerMan artist entity. This phase deliberately uses the existing official company identity and approved Cloudinary imagery.

## Implemented
- Expanded the Organization description to clearly identify the company as an independent South African entertainment company based in Johannesburg, Gauteng.
- Added the company founding month (2025-09), consistent with the company's stated registration period.
- Added the official company Facebook page to Organization sameAs.
- Refined knowsAbout topics to describe the company's actual music, artist-promotion, media-kit and archive activities.
- Preserved the existing email contact, contactPoint, areaServed (South Africa, Gauteng and Johannesburg), logo, image collection and canonical URL.
- Added a high-priority preload for the existing official company logo already used in the navigation and social preview, helping the browser discover this brand image earlier.
- Preserved the existing Open Graph and Twitter large-image metadata and descriptive image alt text.

## Cross-entity connection
A companion change in the DiggerMan artist site links the MusicGroup entity to this company's Organization entity using parentOrganization. This makes the artist/company relationship explicit without merging their identities.

## Structured-data decision
The company remains represented as Organization, not LocalBusiness. No verified public street address or business telephone was supplied in the site content, so this phase does not invent a physical storefront, postal address, coordinates, opening hours or telephone number. Existing service-area information is retained.

## Not claimed
- No Google ranking, rich-result eligibility, or Knowledge Panel outcome is guaranteed.
- No Search Console indexing request was submitted as part of this phase.
- No GTM or GA4 changes were made.
- No new image was generated or uploaded; existing approved brand imagery was reused.

## QA checklist
- [x] Existing canonical and robots directives retained.
- [x] Existing company contact details and service areas retained.
- [x] Existing logo and social preview URLs retained.
- [x] Existing Organization and WebSite JSON-LD graph retained and enriched.
- [x] Company-to-artist identity relationship documented.
- [x] Production deployment and live HTML verification after merge (2026-11-19): company site and DiggerMan artist site both returned HTTP 200; live company HTML contains foundingDate, official Facebook sameAs and logo preload; live artist HTML contains parentOrganization.
