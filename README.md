# CalorieNinjas (calorie-ninjas)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

CalorieNinjas provides an easy, free Nutrition Facts and Recipe API. Developers can retrieve nutrition information for over 100,000 foods and beverages using natural language queries, extract nutrition information from images of food-related text (menus, recipes, food journals), and search recipes matching search queries. All endpoints use a simple API key authentication model via the X-Api-Key header.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/calorie-ninjas/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/calorie-ninjas/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Beverages
- Foods
- Image Recognition
- Nutrition
- Recipes

## Timestamps

- **Created:** 2024-03-30
- **Modified:** 2026-05-19

## APIs

### CalorieNinjas API

The CalorieNinjas API returns nutrition and recipe data for 100,000+ foods and beverages. It offers three endpoints: GET /nutrition for natural-language nutrition lookups (returns calories, macros, vitamins, and minerals), POST /imagetextnutrition for extracting nutrition from images containing food/beverage text, and GET /recipe for searching recipes with titles, ingredients, servings, and instructions. All requests authenticate with an API key sent in the X-Api-Key header.

- **Human URL:** [https://calorieninjas.com/api](https://calorieninjas.com/api)
- **Base URL:** `https://api.calorieninjas.com/v1`

#### Tags

- Beverages
- Foods
- Image Recognition
- Nutrition
- Recipes

#### Properties

- [Documentation](https://calorieninjas.com/api)
- [OpenAPI](openapi/calorieninjas-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/calorieninjas.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/calorieninjas.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Review](openapi/calorieninjas-openapi-review.yml)

## Common Properties

- [Portal](https://calorieninjas.com/)
- [Documentation](https://calorieninjas.com/api)
- [Login](https://calorieninjas.com/signin)
- [Sign Up](https://calorieninjas.com/register)
- [Terms of Service](https://calorieninjas.com/tos)
- [Privacy Policy](https://calorieninjas.com/privacy)
- [Pricing](https://calorieninjas.com/pricing)
- [L L Ms Txt](https://calorieninjas.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
