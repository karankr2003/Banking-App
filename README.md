# Banking-App
Mobile Application

## Project Details

A Banking app developed for Android using Android Studio. This is a project to showcase my knowledge and practical skills in Android development with Java. The application follows the MVC architecture and adheres to proper programming conventions, including documentation, error/exception handling, thorough program structure, and memory efficiency.

### Features
- **Login and Profile Creation**: The app starts with a login screen where users can log in with an existing profile or create a new one. After logging in, users are taken to their dashboard, where they can create their first account if they are new users.
- **Navigation Menu**: A sliding menu from the left provides options such as Dashboard, Account Overview, Transactions, Deposits, Payments, Transfers, Profile Settings, and Logout.

## Android Development Concepts Used

### Multiple Activities
- **Login Activity**: Hosts the fragments for logging in and creating a profile.
- **Main Activity**: Contains all the features of the app, including account overview, payments, transactions, etc. Activities serve as containers for different fragments and use Intents to pass data between them.

### Multiple Fragments
- Fragments are used to display different views to the user. Bundles are utilized to pass data between fragments.

### Well-Designed UI Layouts
- Multiple layout files ensure a clean and functional design. Layouts are used for fragments, menus, and custom dialogs.

### Custom Toolbar
- The application uses a consistent custom toolbar throughout, defined in the styles.xml file. The toolbar's title changes based on the current fragment, and it includes options for navigation and a menu.

### DrawerLayout
- A DrawerLayout provides a sliding drawer menu from the left side of the screen, containing different features of the app. Each menu option navigates to a fragment or launches a dialog.

### SQLite Database
- Profile, Account, Payee, and Transaction information are stored in a local SQLite database, consisting of four tables with proper primary and foreign keys.

### Shared Preferences
- Used to save and load the current profile's data efficiently. Data is initially loaded from the database and stored in Shared Preferences, updated and accessed across different activities using JSON.

### Array Adapters
- Custom array adapters display information in ListView and Spinner components, specifically for accounts and transaction types (deposits, transfers, and payments).

## Notable Mentions
- The app follows Material Design guidelines, especially with icons, the DrawerLayout, custom toolbar, and 'Add' buttons in fragments.
- Resource files for strings, colors, drawables, and styles ensure best practices.
- The app runs on Android API 19 and up.

## Installation and Setup
1. Clone the repository:
    ```sh
    git clone https://github.com/karankr2003/Banking-App.git
    ```
2. Open the project in Android Studio.
3. Build and run the app on an Android device or emulator with API 19 or higher.

## Usage
1. Launch the app on your Android device.
2. Log in with an existing profile or create a new one.
3. Navigate through the app using the sliding menu to access different features.

## Contributing
We welcome contributions to enhance the Banking-App project. If you would like to contribute, please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Create a new Pull Request.

