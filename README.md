<p align="center">
  <img src="https://github.com/KeremOzcn/FoodDeliveryApp/blob/master/foodDelivery.png" alt="Food Paradise Banner"/>
</p>

# Food Paradise - Android Food Ordering App

**Food Paradise** is a modern and user-friendly food ordering application developed for Android. This project allows users to browse categories, view product details, add items to their cart, and place orders. The application is built entirely with **Kotlin** and **Jetpack Compose**, showcasing contemporary Android development practices.

## ✨ Features

-   **Dynamic Home Page**: A dynamically updated home screen featuring banners and categories fetched from Firebase.
-   **Category-Based Listing**: Users can tap on categories like "Main Course" or "Dessert" to view related products.
-   **Product Detail Page**: A dedicated page for each product, displaying details such as price, calories, and estimated delivery time.
-   **Shopping Cart Management**:
    -   Add products to the cart.
    -   Increase or decrease the quantity of items in the cart.
    -   View order summary including total amount, tax, and delivery fee.
-   **Modern UI Design**: A clean, reactive, and modern user interface built with Jetpack Compose.

## 🛠️ Architecture and Technologies Used

The application is developed following the **MVVM (Model-View-ViewModel)** architectural pattern, which enhances code maintainability, testability, and readability.

-   **Language**: [Kotlin](https://kotlinlang.org/)
-   **UI Toolkit**: [Jetpack Compose](https://developer.android.com/jetpack/compose)
-   **Backend**: [Firebase Realtime Database](https://firebase.google.com/docs/database) - Used to dynamically fetch banner, category, and product data.
-   **Asynchronous Programming**: `LiveData` and `ViewModelScope`
-   **Image Loading**: [Coil](https://coil-kt.github.io/coil/) - For asynchronous loading and displaying images from URLs.
-   **Local Storage (for Cart)**: `SharedPreferences` (via TinyDB library) - Used to persistently store cart data on the device.

## 🚀 How to Run

To set up and run the project on your local machine, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/KeremOzcn/FoodDeliveryApp.git](https://github.com/KeremOzcn/FoodDeliveryApp.git)
    ```
2.  **Open the project in Android Studio.**
3.  **Firebase Setup:**
    -   Create your own Firebase project and enable Realtime Database.
    -   Import the data structure (e.g., from `project222-ba297-default-rtdb-export.json` if provided) into your Firebase database.
    -   Download the `google-services.json` file from your Firebase project and place it in the root directory of the `app` module.
4.  **Build and run the application on an Android emulator or a physical device.**
