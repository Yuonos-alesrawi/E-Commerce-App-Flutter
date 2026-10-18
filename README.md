# E-Commerce App - Flutter

A clean and simple E-Commerce application built using **Flutter** and **Dart**. The application provides a seamless shopping experience and uses the `Provider` package for state management.

## 📁 Project Structure

The main codebase located inside the `lib/` directory consists of the following files:

* **`main.dart`**: The entry point of the application. It handles initial setup, configures the state management `Provider`, and sets up the app theme.

* **`cart_provider.dart`**: State management logic for the shopping cart (adding/removing items, calculating totals).

* **`cart_page.dart`**: The cart screen displaying added items with options to edit or remove them.

* **`homepage.dart`**: The main screen that links the product list and cart page using standard navigation/tabs.

* **`product_list.dart`**: A component displaying available products filtered by categories.

* **`product_card.dart`**: A UI widget for rendering individual product cards.

* **`product_page.dart`**: Details page showing product specifications, sizes, and the "Add to Cart" option.

* **`global.dart`**: Contains global variables and mock data (such as default product listings).

## 🚀 Features

1. **Browse Products**: Displays items in organized lists with filtering options based on categories.
2. **Product Details**: Inspect details, select sizes, and view specific product specifications.
3. **Cart Management**:
   * Add items to the shopping cart.
   * Remove items from the cart.
   * Notifications on cart updates.
4. **Responsive UI**: Modern layout tailored for both Android and iOS devices.

## 🛠️ Tech Stack

* **Language**: [Dart](https://dart.dev/)
* **Framework**: [Flutter](https://flutter.dev/)
* **State Management**: [Provider](https://pub.dev/packages/provider)

## 💻 Getting Started

### Prerequisites

* Install [Flutter SDK](https://docs.flutter.dev/get-started/install).
* A code editor such as VS Code or Android Studio.

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd your-repository-name
   ```

3. **Install dependencies:**
   ```bash
   flutter pub get
   ```

4. **Run the application:**
   ```bash
   flutter run
   ```

## 📝 Developer Notes

Make sure the `provider` package is listed in your `pubspec.yaml`:

```yaml
dependencies:
  flutter:
    sdk: flutter
  cupertino_icons: ^1.0.8
  provider: ^6.1.5+1
```