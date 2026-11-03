# E-Commerce Catalog App 🛒

A responsive mobile application built with **Flutter** that displays a catalog of products fetched from a public REST API. This project demonstrates clean architecture, state management, and seamless client-server communication.

> **Note:** This project is part of my portfolio to demonstrate my capabilities as a Junior Mobile App Engineer, specifically in **UI Implementation** and **API Integration**.

## 🚀 Key Features

*   **REST API Integration:** Fetches and parses JSON data in real-time from [FakeStoreAPI](https://fakestoreapi.com/).
*   **State Management:** Utilizes the `Provider` package to efficiently handle UI states (Loading, Success, Error).
*   **Responsive UI Implementation:** Features a dynamically adjusting `GridView` that looks great on various screen sizes, providing a smooth user experience.
*   **Clean Architecture:** Separates business logic, data models, and UI components for maintainability and scalability.

## 🛠️ Tech Stack

*   **Framework:** Flutter (Dart)
*   **HTTP Client:** `http` package
*   **State Management:** `provider` package
*   **Architecture Pattern:** MVC/Provider Pattern

## 📂 Project Structure

```text
lib/
├── models/         # Data classes and JSON serialization (e.g., product_model.dart)
├── services/       # Network calls and API integration (e.g., api_service.dart)
├── providers/      # Business logic and state management (e.g., product_provider.dart)
├── screens/        # UI components and layouts (e.g., catalog_screen.dart)
└── main.dart       # Application entry point
```

## 📸 Preview
<img width="1320" height="2868" alt="localhost_50490_(iPhone 16 Pro Max)" src="https://github.com/user-attachments/assets/164862da-a0de-4698-907c-baf68830c081" />


## 💻 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/username-anda/ecommerce_catalog.git
   ```
2. Navigate into the project directory:
   ```bash
   cd ecommerce_catalog
   ```
3. Install dependencies:
   ```bash
   flutter pub get
   ```
4. Run the app:
   ```bash
   flutter run
   ```

## 👨‍💻 Author

**Zahran Anugerah Rizqullah**
*   LinkedIn: [https://www.linkedin.com/in/zahran-anugerah-rizqullah/]
*   GitHub: [https://github.com/Zahran2]
