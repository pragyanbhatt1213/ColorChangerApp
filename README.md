# Background Color Changer App

This React Native app changes the background color to a random one when you press a button. It was created using [`@react-native-community/cli`](https://github.com/react-native-community/cli).

## Getting Started

### Step 1: Start Metro Server

Run the following in your project root:

```bash
npm start
# OR
yarn start
```

### Step 2: Launch the App

In a new terminal:

#### For Android

```bash
npm run android
# OR
yarn android
```

#### For iOS

```bash
npm run ios
# OR
yarn ios
```

### Step 3: Use the App

- Tap the **"Press me"** button to change the background color.

## Modifying the App

1. Open `App.tsx` to make changes.
2. Reload the app:
   - **Android**: Press <kbd>R</kbd> twice or use **Developer Menu** (<kbd>Ctrl</kbd>/<kbd>Cmd</kbd> + <kbd>M</kbd>).
   - **iOS**: Press <kbd>Cmd</kbd> + <kbd>R</kbd>.

## Features

- **Random Colors**: Changes the background color with each button press.
- **Simple UI**: A clean layout with a single button.

## Code Highlights

- `useState`: Manages the color state.
- `TouchableOpacity`: Handles user taps.
- `StyleSheet`: Styles for the UI.

## Troubleshooting

- Refer to the [Troubleshooting Guide](https://reactnative.dev/docs/troubleshooting).
- Ensure the emulator/simulator is properly configured.

