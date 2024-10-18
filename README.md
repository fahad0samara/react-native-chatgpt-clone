

# React Native ChatGPT Clone

This is a **React Native** project that mimics the ChatGPT user interface. The app provides a similar look and feel to the ChatGPT interface, with the ability to send messages and interact with the app through an animated input field.

## Features

- **Custom Input Component**: The app features a custom animated input component (`MainInput`) that reacts to user interactions such as typing and pressing buttons.
- **Loader Animation**: The app includes a reusable loader animation (`Loader`) that uses `react-native-reanimated` to smoothly animate a loading circle.
- **Keyboard Handling**: The app uses `KeyboardAvoidingView` to handle the keyboard behavior on both iOS and Android, ensuring that the input field remains visible when typing.
- **Animated Icons**: The project uses animated icons from the `lucide-react-native` package to create a modern and responsive user interface.
- **SVG Logo**: The app includes an SVG logo similar to ChatGPT's logo for branding consistency.

## Screens
![photo_2024-10-18_08-35-16](https://github.com/user-attachments/assets/52541724-a995-4db5-b7f7-a20b4924b406)


### Home Screen
- Displays the ChatGPT logo at the center of the screen.
- Contains an input field at the bottom where users can type and send messages.

## Installation

To run this project locally, follow these steps:

### Prerequisites

- Node.js installed on your system.
- React Native development environment set up (Android Studio for Android or Xcode for iOS).

### Steps

1. Clone the repository:

```bash
git clone https://github.com/fahad0samara/react-native-chatgpt-clone.git
```

2. Install dependencies:

```bash
npm install
```

3. Start the app:

For iOS:
```bash
npx react-native run-ios
```

For Android:
```bash
npx react-native run-android
```

## Usage

- Tap the input field to start typing your message.
- Press the microphone or image icons to trigger different actions (currently placeholders).
- Press the send button (arrow icon) to simulate sending a message.
- The loader animation will simulate a response being generated.

## Technologies Used

- **React Native**: For building the mobile app.
- **react-native-reanimated**: For smooth animations and transitions.
- **lucide-react-native**: For icons and UI elements.
- **Tailwind CSS** (via `className` syntax): For styling the components.
- **SVG**: For displaying the ChatGPT logo.

