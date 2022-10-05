# H.Partner Application
H.Partner is a mobile application developed using Flutter. It supports both Android and IOS.

H.Partner is a Nutrition System application. It allows the user to calculate daily his calories, protein, car, and fat,.
the user can buy from market off app healthy products,
the user can follow her health by charts that used in our app

## Table of contents
- ### [main packages used](https://github.com/Atevaz/health_partner/edit/master/README.md#main-packages-used)
- ### [Folder structure](https://github.com/Atevaz/health_partner/edit/master/README.md#folder-structure)
- ### [Screenshots](https://github.com/Atevaz/health_partner/edit/master/README.md#screenshots)
- ### [Demo video](https://github.com/Atevaz/health_partner/edit/master/README.md#demo-video)

## Main packages used
- [firebase_core](https://pub.dev/packages/firebase_core) to make integration database
- [firebase_auth](https://pub.dev/packages/firebase_auth) to handle authentication
- [firebase_storage](https://pub.dev/packages/firebase_storage) to save media of app in it
- [tflite](https://pub.dev/packages/tflite) to used machine learning model in our app
- [fl_chart](https://pub.dev/packages/fl_chart) to handle charts of analytics
- [flutter_bloc](https://pub.dev/packages/flutter_bloc) as state management
- [shared_preferences](https://pub.dev/packages/shared_preferences) to handle caching data
- [internet_connection_checker](https://pub.dev/packages/internet_connection_checker) to handle internet connection
- [image_picker](https://pub.dev/packages/image_picker) to pick image from mobile storage
- [flutter_localizations](https://pub.dev/packages/easy_localization) to handle localization

## Folder structure
We have applied clean archeticture concept and here is the basic folder structure:

core folder structure that flutter provides:

```
h_partner
├── android
├── assets
├── build
├── ios
├── lib
└── test

```

Here is the folder structure we have been using in this project:
```
lib
├── layout
├── model
├── modules
├── shared
└── main.dart
```

### layout
This folder containes the business logic of the application specificly state management.

```
layout
├── admin layout
└── home-layout
```

### model
This folder contains all models related to the application
```
model
├── feedback_model.dart
├── meals_model.dart
├── new_order_model.dart
├── product_model.dart
├── recipes_model.dart
└── user_model.dart
```

### modules
This folder contains all screens and designs related to the application
```
modules
├── add_info
├── change_address_and_phone
├── block_user
├── breakfast
├── buy_now
├── camera
├── cart
├── complete_diary
├── customer_dashboard
├── dinner
├── edit_goal
├── feedback
├── home
├── login
├── lunch
├── market
├── meal_item
├── nutrition
├── onBoarding
├── order_layout
├── recipe
├── register
├── result_of_detection
├── search_recipe_screen
├── snacks
└── water_track
```

### shared
This folder contains everything used anywhere in the app .
```
shared
├── components
├── localization
├── network
├── styles
└── bloc_observer
```
## Screenshots
|<img src="https://user-images.githubusercontent.com/101355785/194030068-629ee6ee-84ef-453b-9ec5-d22d9cdddddb.jpg" width ="200">|<img src="https://user-images.githubusercontent.com/101355785/194030092-84584391-dbbe-4e66-a819-f0f063e38f64.jpg" width="200">|<img src="https://user-images.githubusercontent.com/101355785/194030115-f1279a10-bdcc-4bae-8951-d45e33ca1565.jpg" width="200">||<img src="https://user-images.githubusercontent.com/101355785/194030133-1847ac30-990c-4091-ba00-72af9583c966.jpg" width ="200">|


## Demo

https://www.youtube.com/watch?v=FR8rsPSzJb4&ab_channel=omaressam

