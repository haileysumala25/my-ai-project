# Smart Pantry: AI Meal & Waste Reducer

Final project for the Building AI course

## Summary

Smart Pantry is a mobile app that scans household groceries using a phone camera and suggests recipes based on ingredients that are about to expire. It helps families save money and reduce everyday food waste.

## Background

Millions of tons of edible food are thrown away every year simply because people forget what is inside their refrigerators or do not know how to combine leftover ingredients. This problem happens daily in busy households worldwide. My personal motivation is to make home cooking easier, lower grocery bills, and cut down on unnecessary household waste.

Problems this idea solves:
* Forgotten ingredients: Tracks food items before they spoil.
* Meal planning stress: Answers the daily question of what to cook with limited items.
* Household waste: Reduces the amount of money and food thrown in the trash.

## How is it used?

The solution is used at home in the kitchen, right after grocery shopping or before cooking a meal. The primary users are busy individuals, students, and families who cook at home. 

1. The user takes a quick photo of their open fridge or grocery receipt.
2. The AI identifies the ingredients and estimates their shelf life.
3. When an item is close to expiring, the app sends a reminder and suggests simple recipes using those exact ingredients.

## Data sources and AI methods

To build this system, the AI needs two main types of data and methods:
* Image Recognition (Computer Vision): Trained on public food image datasets like [Food-101](https://ethz.ch) and open grocery databases like [Open Food Facts](https://openfoodfacts.org) to identify fruits, vegetables, and packaged goods from photos.
* Recommendation System: Uses a database of open-source recipes and natural language processing to match available ingredients with meals that have high user ratings and short prep times.

## Challenges

* Hidden items: The camera cannot see food hidden behind other containers in a crowded refrigerator.
* Expiration accuracy: Visual inspection cannot always tell if dairy or meat has spoiled safely, so the app must include clear food-safety disclaimers.
* Dietary bias: The recipe database must be carefully balanced to include diverse cultural dishes, allergies, and budget-friendly meals.

## What next?

In the future, this project could connect directly with local grocery delivery services to automatically restock missing staple items. To build a working prototype, I would need skills in mobile app development, basic Python programming, and assistance from a nutritionist to verify food storage guidelines.

## Acknowledgments

* Project template provided by Reaktor Innovations and the University of Helsinki for the Building AI course.
* Inspired by open data initiatives from [Open Food Facts](https://openfoodfacts.org).
