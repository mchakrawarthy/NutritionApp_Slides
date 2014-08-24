---
title       : Nutrition Application using USDA Data
subtitle    : Course Project
author      : Chakri Matta
job         : 
framework   : io2012       # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow     # 
widgets     : [shiny, interactive]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Mission


We experiencing epidemic rates of overweight and obesity, the online resources and tools can empower people to make healthier food choices for themselves, their families, and their children. This application attempts to help identify unhealthy food easily so that we can make better food choices. The data for this application is sourced from USDA National Nutrient Database <http://www.ars.usda.gov/Services/docs.htm?docid=8964>

--- .class #id 

## Features

Find nutrient information on over 8,000 foods easily using Nutrition Facts.All data are based on the latest USDA data, SR26. It includes more than 15 nutrition values for most food items. Standard measures (ounces, cups, spoons, etc) for each food makes it easy to understand. Detailed classifications of food items for an even more accurate search.

1. Search our database of over 8000 foods by food name or food group. All indexed food is directly from the USDA.
2. Dairy & Egg, Spices & Herbs, Baby Foods, Fats & Oils, etc. Explore Food has a full selection of Food Categories allowing for easy search
3. User interface was designed with the user in mind. Intuitive side menu, appealing style and color, and a HUGE food database all have your satisfaction in mind.
4. Scatter Plot by nutrients function in Explore Food is a great way to pick out the right food for you. Simply select the nutrients in x and y axis and click any point on the plot, and find all the food that is high, or low, in your desired nutrient.
5. You can use the Data tab to easily review all the data in our database and search based on any column.


--- .class #id 


## Explore Food Items

<img style='margin-top: -10px' class="center" src='assets/img/ExploreFood.jpg' width=960px height=400px></img> 

--- &twocol w1:50% w2:50% 


## About Data


Number for food items included in the data are 8463.
Following are counts by food groups.

*** =left

|fdGrp.Desc                          | count|
|:-----------------------------------|-----:|
|American Indian/Alaska Native Foods |   165|
|Baby Foods                          |   362|
|Baked Products                      |   807|
|Beef Products                       |   864|
|Beverages                           |   312|
|Breakfast Cereals                   |   354|
|Cereal Grains and Pasta             |   182|
|Dairy and Egg Products              |   258|
|Fast Foods                          |   388|
|Fats and Oils                       |   219|
|Finfish and Shellfish Products      |   267|
|Fruits and Fruit Juices             |   335|
|Lamb, Veal, and Game Products       |   353|

*** =right

|   |fdGrp.Desc                        | count|
|:--|:---------------------------------|-----:|
|14 |Legumes and Legume Products       |   385|
|15 |Meals, Entrees, and Side Dishes   |   108|
|16 |Nut and Seed Products             |   131|
|17 |Pork Products                     |   337|
|18 |Poultry Products                  |   389|
|19 |Restaurant Foods                  |    82|
|20 |Sausages and Luncheon Meats       |   243|
|21 |Snacks                            |   172|
|22 |Soups, Sauces, and Gravies        |   511|
|23 |Spices and Herbs                  |    64|
|24 |Sweets                            |   347|
|25 |Vegetables and Vegetable Products |   828|


