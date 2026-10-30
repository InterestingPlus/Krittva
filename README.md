# KRITTVA

A responsive, vegetarian household meal-planning website built with plain HTML, CSS and vanilla JavaScript. It is designed for everyday family cooking, with a strong Gujarati home-food collection and a few popular Indian favourites.

## Run locally
- Extract the ZIP.
- Open `index.html` in a modern browser, or run `python3 -m http.server 8000` in this folder and visit `http://localhost:8000`.
- No build step, backend, npm packages or API keys are required.

## Languages
Use the language selector in the header to switch between:
- English
- Hindi (हिंदी)
- Gujarati (ગુજરાતી)

The selection is saved in the browser. Dish names, ingredient labels, cuisine/meal labels, planner, filters, shopping list UI and recipe guidance update locally without a network translation service.

## Features
- 47 vegetarian dish ideas, with main and pantry ingredients, cooking time and difficulty
- Breakfast, lunch, dinner and snack filters
- Gujarat-aware summer, monsoon, winter and all-season suggestions
- Ingredient matcher with match score and missing main ingredients
- Weekly planner with automatic fill and localStorage persistence
- Shopping list, including ingredients from the weekly plan
- Favourites and recently cooked history
- Dish details and quick cooking guidance
- Print weekly planner and shopping list
- Responsive desktop and mobile layout

## Data and customization
The dish catalogue is in `app.js` in the `dishes` array. Language labels and ingredient translations are in the language layer near the end of that file. All content is bundled locally, so the website works without a translation API.

## Browser storage
The app stores favourites, history, weekly plans and shopping list in localStorage. The language preference is stored separately as `krittva_language`. Data stays on the current browser/device and is not synced across devices.
