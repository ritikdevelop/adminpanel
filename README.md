# Admin Panel

A React Native Expo application designed for managing categories, users, and orders in an admin panel interface. This app provides a user-friendly mobile experience for administrative tasks.

## Description

This admin panel app allows administrators to manage product categories, view and edit orders, and access user information. Built with React Native and Expo, it features a tab-based navigation system with dedicated stacks for categories and orders.

## Features

- **Categories Management**: Add new categories, view category lists, edit existing categories, and view category details.
- **Orders Management**: List orders, view order details, and edit orders.
- **Users**: Basic user screen for viewing user information.
- **Navigation**: Bottom tab navigation with stack navigators for nested screens.
- **Form Handling**: Integrated with React Hook Form for form validation and management.
- **Styling**: Uses NativeWind (Tailwind CSS for React Native) for consistent and responsive UI.

## Tech Stack

- **React Native**: Framework for building native mobile apps.
- **Expo**: Platform for universal React applications.
- **TypeScript**: Typed JavaScript for better development experience.
- **React Navigation**: Navigation library for React Native.
- **NativeWind**: Utility-first CSS framework for React Native.
- **React Hook Form**: Performant forms with easy validation.
- **Expo Vector Icons**: Icon library for consistent iconography.

## Installation

1. Ensure you have Node.js and npm installed.
2. Install Expo CLI globally:
   ```
   npm install -g @expo/cli
   ```
3. Clone the repository and navigate to the project directory.
4. Install dependencies:
   ```
   npm install
   ```

## Usage

1. Start the Expo development server:
   ```
   npm start
   ```
2. Use the Expo Go app on your mobile device to scan the QR code, or run on an emulator/simulator:
   - For Android: `npm run android`
   - For iOS: `npm run ios`
   - For Web: `npm run web`

## Project Structure

```
adminpanel/
├── assets/                          # Static assets (icons, images)
├── src/
│   ├── api/                         # API-related code (currently empty)
│   ├── components/                  # Reusable components (currently empty)
│   ├── navigation/                  # Navigation configuration
│   │   ├── CategoriesStack.tsx      # Stack navigator for categories
│   │   ├── OrderStack.tsx           # Stack navigator for orders
│   │   └── RootNavigator.tsx        # Main tab navigator
│   └── screens/                     # Screen components
│       ├── AddCategoryScreen.tsx    # Screen for adding categories
│       ├── CategoriesScreen.tsx     # Main categories screen
│       ├── OrdersScreen.tsx         # Main orders screen
│       ├── UserScreen.tsx           # Users screen
│       ├── categories/              # Category-related screens
│       │   ├── CategoryDetailsScreen.tsx
│       │   ├── CategoryEditScreen.tsx
│       │   └── CategoryListScreen.tsx
│       └── orders/                  # Order-related screens
│           ├── OrderDetailScreen.tsx
│           ├── OrderEditScreen.tsx
│           └── OrderListScreen.tsx
├── App.tsx                          # Main app component
├── index.ts                         # Entry point
├── package.json                     # Dependencies and scripts
├── tsconfig.json                    # TypeScript configuration
├── tailwind.config.js               # Tailwind CSS configuration
├── babel.config.js                  # Babel configuration
├── metro.config.js                  # Metro bundler configuration
└── README.md                        # This file
```

## Contributing

Feel free to submit issues and pull requests for improvements or bug fixes.

## License

This project is private and not licensed for public use.
