BrewByte – Android Coffee Ordering App

BrewByte is an Android application that allows users to select menu items, add them to a cart, place an order, and track the order status through Firebase Firestore. The app also includes an admin dashboard for updating the status of any order.

Features

Users can add items such as coffee, tea, sandwiches, and pastries to the cart

Cart screen with total calculation

Checkout screen with payment selection

Orders are stored in Firebase Firestore

Real-time order status updates retrieved from Firestore

Order history screen with scrolling support

Admin dashboard to load an order and update its status

Technologies Used

Android Studio (Kotlin)

Firebase Firestore

ViewBinding

Material Design UI

Firestore Structure
orders (collection)
   └── orderId (document)
         userId
         items[]
         total
         payment
         status
         createdAt

How to Run the Project

Clone or download the project.

Add the google-services.json file inside the app/ folder.

Open the project in Android Studio.

Connect Firebase and enable Firestore in the Firebase console.

Sync Gradle and run the application.

Admin Dashboard

The admin dashboard allows:

Loading any order using its Order ID

Viewing the current status

Updating the status to Pending, Preparing, or Ready
