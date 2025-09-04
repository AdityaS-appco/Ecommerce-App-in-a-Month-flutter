
# E-commerce Flutter App

This is a fully functional and production-ready e-commerce mobile application built using **Flutter** and **Firebase**. Developed in just one month, the app offers a complete shopping experience for users and a full-featured admin panel for sellers or app managers.

---

## 📱 Features

### 👥 User Module
- User registration and login (Firebase Authentication)
- Browse products across multiple categories
- Add to cart, wishlist, and place orders
- Order history and profile management
- Real-time updates from Firestore
- Push notifications via Firebase Cloud Messaging (FCM)

### 🛠️ Admin Panel
- Product upload with image support (Firebase Storage)
- View and manage orders
- Inventory and product list management
- Secure admin access

---

## 🚀 Tech Stack

| Layer        | Technology           |
|--------------|----------------------|
| Frontend     | Flutter              |
| Backend      | Firebase Firestore   |
| Auth         | Firebase Auth        |
| Storage      | Firebase Storage     |
| Notifications| Firebase Cloud Messaging (FCM) |
| State Mgmt   | Provider (or Riverpod) |

---

## 📂 Folder Structure

```

lib/
│
├── models/              # Data models (User, Product, Order)
├── screens/             # All UI screens (home, cart, login, admin, etc.)
├── services/            # Firebase integrations and utility functions
├── providers/           # State management logic
├── widgets/             # Custom reusable widgets
├── main.dart            # App entry point

````

---

## 📷 Screenshots

| Home Screen | Product Details | Admin Dashboard |
|-------------|------------------|------------------|
| ![](screenshots/home.png) | ![](screenshots/details.png) | ![](screenshots/admin.png) |

---

## ✅ How to Run

1. **Clone the repo:**
   ```bash
   git clone https://github.com/your-username/easy-mall-main.git
   cd easy-mall-main
````

2. **Install dependencies:**

   ```bash
   flutter pub get
   ```

3. **Add Firebase configuration:**

   * Add `google-services.json` in `android/app/`
   * Add `GoogleService-Info.plist` in `ios/Runner/` (if needed)

4. **Run the app:**

   ```bash
   flutter run
   ```

---

## 📈 Features to be Added

* Payment gateway integration
* Deep linking
* Order tracking with maps
* Review and rating system
* Product recommendations (AI-based)


---

## ⚖️ License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```


