# Amadeus Traveler Media (amadeus-traveler-media)
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
