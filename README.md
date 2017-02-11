# 2000kcal Project

![Logo](http://i.imgur.com/ewtsGPn.png "Eat healthy, lose weight, shop like a pro and save money.")

# PITCH

https://gitpitch.com/plotti/2000kcal/master?grs=github&t=white

# PROBLEM

For most people who want to lose weight you are supposed to do only one thing: Consume less calories than you need. This often means:

1. Eat less than 2000 ckal
2. Still eat the right nutritional values. 

Trying to figure those two things out is very time consuming, you will have to track every food you eat with tools like http://myfitnesspal.com. These tools will tell you how much calories a certain food has and how much nutritional value it has. But:

1. Its hard to guess how much you actually ate of it. Unless it was the whole can. 
2. Those tools won't tell you WHAT to eat. 

So you are on your own, you have to create your own diet plans and try to tediously to stick to them. 

# IDEA: The 2kcal pack

So what if people sat together (think of community) and build daily 2000 kcal Packs that are build out of the existing products available in common super markets. These Packs can be either be:

1. Delivered to your door.
2. Picked up bundled in your supermarket (not very practical see final thoughts below)
3. With the use of an app the consumer can be guided to pick these up at the store.

![App](http://i.imgur.com/PNUL8oC.jpg "A little app helps you to find your 2kcal pack")


## The benefits are: 

1. Its healthy
2. You can be lazy while dieting
3. You will save money!

# EXAMPLE of a 2kcal Pack

Caloric Goals: 

- 2000 kcal

Recommended Nutritional Values (see e.g. http://www.myfitnesspal.com): 

- 125g Carbs
- 46g Fat
- 227g Protein

Optimally this pack is cheap and easy to prepare. Compare 14.95CHF of the pack vs. 60 CHF (10CHF for breakfast at bakery, 25CHF for lunch in a restaurant, and 25 CHF for dinner in a restaurant). 

## BREAKFAST
    2/6 of a pack of croissants: https://www.openfood.ch/de/products/14153 
    Calories: 276 kcal (extracted from API)
    Nutritional Values: 30g Carbs, 14g Fat, 6g Protein (extracted from API)
    Price for whole Package: 3 CHF (extracted via https://produkte.migros.ch/m-classic-buttergipfel-frischback)
    -
    Coffe from coffe machine at home. 

## LUNCH 
    Whole Pack of  Vegi Bulgursalat mit Hummus-Dip: https://www.openfood.ch/de/products/13264
    Calories: 523 kcal (extracted from API)
    Nutritional Values: Carbs 14g , Fat 5g, Proteins: 4g  (extracted from API)
    Price for whole Package: 6.40 CHF (extracted via https://produkte.migros.ch/vegi-bulgursalat-mit-hummus-dip)
    -
    Dessert M-CLASSIC KOKOS/SCHOKOLADE JOGHURT: https://www.openfood.ch/de/products/13541
    Calories: 223 kcal
    Nutritional Values: 27g Carbs, 10g Fat, 5g Protein
    Price for the whole Pacakge (1 Yoghurt) 0.55 CHF (extracted via https://produkte.migros.ch/m-classic-joghurt-kokosschokolade)
    - 
    Tap water


## DINNER
    Whole Pack of Migros Lasagne 1kg: https://www.openfood.ch/de/products/15016
    Calories: 1280kcal (extracted from API)
    Nutritional Values: 120g Carbs, 55g Fat, 72g Protein
    Price for whole Package: 5CHF (extracted from https://produkte.migros.ch/m-budget-lasagne-bolognese)
    - 
    Tap water

## SUMMARY
    Calories: 276+ 253 + 223 + 1280 = 2032 --> We could say the goal is met
    Nutritional values: 191g Carbs, 84g Fat, 87g Protein --> We overate on carbs and fat, but did not eat enough protein. (If there were stars I would rate this pack only 3/5 stars because those conditions are not met)
    Cost: 3 CHF + 6.40 CHF+ 0.55 CHF + 5 CHF = 14.95 CHF

# EVALUATION

- Problems:
 - openfood API is incomplete and does not contain all the necessary nutritional values. 
 - openfood API does not contain the price of the products. 
 - Unsolved how to link between openfood.ch and produkte.migros.ch

# FINAL THOUGHTS

- The 2000kcal packs would of course be "virtual", thus on a website or app, since bundling those projects together is not feasible for a supermarket because of different storage conditions (e.g. a yoghurt needs to be stored in the fridge, but you don't want your croissants to be frozen :))
- The app could of course combine the nutritions and the receipe. (e.g. how to prepare a salad using those 3 ingredients)
