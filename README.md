# Amadeus Traveler Media (amadeus-traveler-media)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The Amadeus Traveler Media APIs provide access to travel-related media and destination content, including photos, ratings, and information for points of interest, hotels, and destinations worldwide. These APIs power travel apps, destination guides, and travel planning platforms with rich content for tourist attractions, hotel sentiment ratings, travel recommendations, and location scoring.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amadeus-traveler-media/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Content, Destination, Media, Photos, Points of Interest, Tourism, Travel

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### Points of Interest API
The Amadeus Points of Interest API provides data on tourist attractions, restaurants, museums, nightlife, shopping, and parks near a specified location. Returns POI name, category, geographic coordinates, and ranking scores to help travelers discover what to do at a destination.

**Human URL:** [https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/points-of-interest](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/points-of-interest)

#### Tags:

 - Destinations, Points of Interest, Tourism, Travel

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/points-of-interest)
- [APIReference](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/points-of-interest/api-reference)
- [OpenAPI](openapi/amadeus-traveler-media-points-of-interest-openapi.yaml)

### Hotel Ratings API
The Amadeus Hotel Ratings API uses sentiment analysis of hotel reviews to provide overall hotel ratings and ratings for specific categories including location, comfort, service, staff, internet, food, facilities, pool, and sleep quality.

**Human URL:** [https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-ratings](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-ratings)

#### Tags:

 - Hotels, Ratings, Reviews, Sentiment, Travel

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-ratings)
- [APIReference](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-ratings/api-reference)
- [OpenAPI](openapi/amadeus-traveler-media-hotel-ratings-openapi.yaml)

### Travel Recommendations API
The Amadeus Travel Recommendations API provides personalized destination recommendations based on a traveler's origin city and travel history. Returns top recommended cities with descriptions, scoring, and links to destination content.

**Human URL:** [https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/travel-recommendations](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/travel-recommendations)

#### Tags:

 - Destinations, Recommendations, Tourism, Travel

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/travel-recommendations)
- [OpenAPI](openapi/amadeus-traveler-media-travel-recommendations-openapi.yaml)

### Location Score API
The Amadeus Location Score API scores geographic locations for different traveler personas including Shopping, Restaurant, Nightlife, Sightseeing, and Beach. Helps travelers and travel apps understand the character of a neighborhood or destination.

**Human URL:** [https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/location-score](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/location-score)

#### Tags:

 - Destinations, Location, Scoring, Tourism, Travel

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/location-score)
- [OpenAPI](openapi/amadeus-traveler-media-location-score-openapi.yaml)

## Common Properties

- [Portal](https://developers.amadeus.com/)
- [GettingStarted](https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/)
- [Authentication](https://developers.amadeus.com/self-service/apis-docs/guides/authorization-262)
- [SignUp](https://developers.amadeus.com/register)
- [Pricing](https://developers.amadeus.com/pricing)
- [Blog](https://developers.amadeus.com/blog)
- [FAQ](https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/faq/)
- [Support](https://developers.amadeus.com/support)
- [TermsOfService](https://developers.amadeus.com/legal/terms-and-conditions)
- [PrivacyPolicy](https://developers.amadeus.com/legal/privacy-policy)
- [GitHubOrganization](https://github.com/amadeus4dev)
- [Python SDK](https://github.com/amadeus4dev/amadeus-python)
- [Node.js SDK](https://github.com/amadeus4dev/amadeus-node)
- [Java SDK](https://github.com/amadeus4dev/amadeus-java)
- [StatusPage](https://developers.amadeus.com/status)

## Features

| Name | Description |
|------|-------------|
| Points of Interest Discovery | Discover tourist attractions, restaurants, museums, and nightlife venues near any geographic location with ranking scores. |
| Hotel Sentiment Ratings | Access sentiment-based hotel ratings derived from thousands of traveler reviews covering all key aspects of the hotel experience. |
| Personalized Travel Recommendations | Get AI-powered destination recommendations tailored to a traveler's origin and travel history patterns. |
| Location Scoring by Persona | Score any neighborhood for specific traveler personas including Shoppers, Foodies, Nightlife Seekers, Sightseers, and Beach Lovers. |
| Rich Destination Content | Combine POI data, hotel ratings, and location scores to create comprehensive destination guides and travel media content. |

## Use Cases

| Name | Description |
|------|-------------|
| Travel App Destination Guide | Build destination guide features in travel apps showing attractions, restaurants, and nightlife with ratings and location context. |
| Hotel Comparison Platform | Display sentiment-based ratings alongside hotel pricing to help travelers choose accommodation based on experience quality. |
| Personalized Travel Inspiration | Power "where should I go next" features with personalized destination recommendations based on traveler history and preferences. |
| Neighborhood Explorer | Help travelers understand the character of hotels or Airbnb locations using location scores for shopping, dining, and nightlife. |
| AI Travel Concierge | Enable AI travel assistants to recommend attractions, rate hotels, and suggest destinations based on traveler interests. |

## Integrations

| Name | Description |
|------|-------------|
| Amadeus Hotel Search | Combine hotel ratings with hotel search results to display sentiment scores alongside pricing for better hotel selection. |
| Amadeus Hotel Content API | Pair hotel ratings with property images and descriptions from the Hotel Content API for complete hotel profiles. |
| Amadeus Tours and Activities | Extend POI discovery with bookable tours and activities from the Amadeus Tours and Activities API. |
| Amadeus City Search | Use city search to identify destination cities before fetching POIs and travel recommendations for that location. |
| Amadeus Flight Inspiration Search | Combine travel recommendations with flight inspiration search to suggest both destinations and available flights. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amadeus Points of Interest OpenAPI](openapi/amadeus-traveler-media-points-of-interest-openapi.yaml)
- [Amadeus Hotel Ratings OpenAPI](openapi/amadeus-traveler-media-hotel-ratings-openapi.yaml)
- [Amadeus Travel Recommendations OpenAPI](openapi/amadeus-traveler-media-travel-recommendations-openapi.yaml)
- [Amadeus Location Score OpenAPI](openapi/amadeus-traveler-media-location-score-openapi.yaml)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Points of Interest API](capabilities/shared/points-of-interest.yaml) — 2 operations for POI search and retrieval
- [Hotel Ratings API](capabilities/shared/hotel-ratings.yaml) — 1 operation for hotel sentiment ratings

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Destination Discovery](capabilities/destination-discovery.yaml) | Points of Interest API, Hotel Ratings API | 3 | Travel App Developer, Destination Content Manager |

## Vocabulary

- [Amadeus Traveler Media Vocabulary](vocabulary/amadeus-traveler-media-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 2 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amadeus Traveler Media Spectral Rules](rules/amadeus-traveler-media-spectral-rules.yml) — 12 rules across 5 categories enforcing Amadeus Traveler Media API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
