# Theme Management in Flutter using BLoC and Hive

This project demonstrates how to manage **Themes** in a Flutter app using:
- **BLoC** for state management.
- **Hive** for local storage.

---

## ✨ Features:
- **🎨 Theme Switching**: Users can switch between **Light**, **Dark**, and **System** themes effortlessly.
- **💾 Persistent Preferences**: User preferences are saved locally using **Hive**, ensuring a seamless experience across app restarts.
- **🖱️ Interactive UI**: Shows a **Popup** when the user selects the already active theme, providing instant feedback.

---

## 🧩 Components:
1. **`app_colors.dart`**: Defines app colors for consistent theming.
2. **`app_themes.dart`**: Defines **Light**, **Dark**, and **System** themes with customizable styles.
3. **`theme_cubit.dart`**: Manages theme state using **Cubit** for efficient state management.
4. **`theme_bottom_sheet.dart`**: Displays a **BottomSheet** for theme selection with a sleek design.
5. **`theme_card.dart`**: Displays the current theme and allows users to open the **BottomSheet** for theme changes.
6. **📱 Screens**:
   - **`home_screen.dart`**: The main screen displaying the **ThemeCard** for theme management.

---

## 📸 Screenshots:

### 1. 🏠 Home Screen
Displays the current theme and allows users to open the **BottomSheet** to change the theme.

![Home Screen](https://github.com/user-attachments/assets/6f518075-3124-4175-b2fd-faa7bbd9a3ff)

### 2. 🎚️ Theme BottomSheet
Allows users to select a theme (**Light**, **Dark**, or **System**) with a smooth and intuitive interface.

![Theme BottomSheet - Light](https://github.com/user-attachments/assets/e21b3bbc-3e71-4bac-a1e0-072e3a185ccb)

![Theme BottomSheet - Dark](https://github.com/user-attachments/assets/0c1954dd-3ea0-4dcd-889a-84aefbe73f7d)

![Theme BottomSheet - System](https://github.com/user-attachments/assets/60164464-eb78-4764-8e6e-d7988cfc7581)

---

## 🚀 How to Run:
1. **Install Dependencies**:
   ```bash
   flutter pub get
   flutter pub add flutter_bloc
   flutter pub add hive_flutter
