# CalorieNinjas (calorie-ninjas)

CalorieNinjas provides an easy, free Nutrition Facts and Recipe API. Developers can retrieve nutrition information for over 100,000 foods and beverages using natural language queries, extract nutrition information from images of food-related text (menus, recipes, food journals), and search recipes matching search queries. All endpoints use a simple API key authentication model via the X-Api-Key header.

**URL:** [Visit APIs.yml URL](https://raw.githubusercontent.com/api-evangelist/calorie-ninjas/refs/heads/main/apis.yml)

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
- **Modified:** 2026-04-23

## APIs

### CalorieNinjas API

The CalorieNinjas API returns nutrition and recipe data for 100,000+ foods and beverages. It offers three endpoints:

- `GET /nutrition` for natural-language nutrition lookups (returns calories, macros, vitamins, and minerals)
- `POST /imagetextnutrition` for extracting nutrition from images containing food/beverage text
- `GET /recipe` for searching recipes with titles, ingredients, servings, and instructions

All requests authenticate with an API key sent in the `X-Api-Key` header.

**Base URL:** `https://api.calorieninjas.com/v1`

**Human URL:** [https://calorieninjas.com/api](https://calorieninjas.com/api)

#### Tags

- Beverages
- Foods
- Image Recognition
- Nutrition
- Recipes

#### Properties

- [Documentation](https://calorieninjas.com/api)
- [OpenAPI](openapi/calorieninjas-openapi.yml)
- [Review](openapi/calorieninjas-openapi-review.yml)

## Common Properties

- [Portal](https://calorieninjas.com/)
- [Documentation](https://calorieninjas.com/api)
- [Login](https://calorieninjas.com/signin)
- [Sign Up](https://calorieninjas.com/register)
- [Terms of Service](https://calorieninjas.com/tos)
- [Privacy Policy](https://calorieninjas.com/privacy)
- [Pricing](https://calorieninjas.com/pricing)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
