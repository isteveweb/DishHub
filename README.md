# DishHub is Modern food application, recently build with the lastest SDK 34


## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Developer Setup](#Developer-setup)
* [What I learnt](#What-I-learnt)
*[Contact](#Contact)
* [Screenshot](#Screenshot)

## General info
An application known as Dishhub where you can fetch dish online, you can also edit them and add them as your favorite 
The app relies upon the excellent spoontuna website that provides the caller with different food-based, ingredients and recipe 


The project basically have 4 screens:

1. The list of added food category screen
2. The list of Favorite Dishes screen 
3. A online dish which serve as random dish

Finally, the user can click one of these dishes to bring up the 3rd screen Dish detail screen and see information about the specific dish, how to cook it, ingredients, image etc.. the user can also share the food recipe to a friend directly on any of the social media handle.


## Technologies


* Minimum SDK level 22 
* Target SDK 34
* Hilt for dependency injection.
* MVVM Architecture (View - ViewBinding - ViewModel - Model)
* Repository Pattern (Local/Remote)
* Coordinator Layout
* View Pager for the daiteles activity
* Material Ui
* Navigation Component
* Room components for the database
* View binding to bind data
* DataStore to save the meal preferences when closing the app
* Recyclerview to sort the data
* Retrofit and RxJava to get the data from the api
* Coroutines to handel the api requests
* Lifecycle
* Permission 
* Coil for loading the food images from a url
* Gson to convert the data list into a Json file to save into the DataBase
* Shimmer for the glow effect when loading
* Jsoup to convert the Html data to a normal text
* Glide
* Navigation Component, Navigation Graph, Safe Args
* Android Palette

	
## Developer Setup
To run this project as a developer, install it locally using the compliler:
```
$ Android studio install 
$ change Sdk 
$ add permission 
$ have an active network 
$ successful installed 
```

## What I learnt
Since we keep learning everyday, here are the the few basic things I learnt more
* using Hilt
* using retrofit to get data from "https://spoonacular.com/food-api"
* use room database to save the favorite recipes
* using navigation control
* using page handler to set a page tab view
* using safe args
* using data store to save the meal preferences
* using animation to animate the buttons in the bottom bar
* Costume Views: -the Bottom animated bar, made by Shape Shifter and the Animated drawable

## Contact 

If you need help or more information please contact the developer at 
"isteveweb@gmail.com" or visit my website "https://isteveweb.com"

## Screenshot 

![image](https://github.com/isteveweb/DishHub/assets/130738521/b483c4e0-f81c-4bbf-af07-6e3f4736fce5)
