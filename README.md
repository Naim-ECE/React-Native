# React-Native# React Native Expo Learning Journey 🚀

I’m learning React Native with Expo by following this video:  
[https://www.youtube.com/watch?v=XCifkDC0yXA&t=906s](https://www.youtube.com/watch?v=XCifkDC0yXA&t=906s)

## The project I'll be building is:
# MacroZone - React Native Crash Course

A macro tracking app built with React Native and Expo as part of the [React Native Crash Course](https://youtu.be/XCifkDC0yXA) on YouTube by Traversy Media. Track your daily meals and monitor your macros (calories, protein, carbs, fat) with a clean, modern UI.

> **📝 Following along with the course?** Check out the [STEPS.md](STEPS.md) file for the complete step-by-step guide with all the code for each section. The drawing from the video is also in this repo.

<p align="center">
  <img src="assets/screen.png" alt="MacroZone App" width="300" />
</p>

## Features

- Add meals with calorie and macro information
- Track daily totals for calories, protein, carbs, and fat
- View all meals or recent meals on the home screen
- Share and copy meal data
- Haptic feedback for interactions
- Daily reminder notifications (iOS)
- Data persistence with AsyncStorage
- Tab-based navigation with a modern UI

## Tech Stack

- [React Native](https://reactnative.dev/) with [Expo](https://expo.dev/) (SDK 55)
- [Expo Router](https://docs.expo.dev/router/introduction/) (file-based routing)
- [AsyncStorage](https://react-native-async-storage.github.io/async-storage/) for local data persistence
- [Expo Notifications](https://docs.expo.dev/versions/latest/sdk/notifications/) for reminders
- [Expo Haptics](https://docs.expo.dev/versions/latest/sdk/haptics/) for tactile feedback
- TypeScript

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (LTS)
- [Expo Go](https://expo.dev/go) app on your phone, or an Android/iOS emulator

### Installation

```bash
git clone https://github.com/bradtraversy/macrozone.git
cd macrozone
npm install
```

### Run the App

```bash
npx expo start
```

Scan the QR code with Expo Go (Android) or the Camera app (iOS) to run on your device.

## Course Steps

The full step-by-step guide with all the code for the crash course is available in the [STEPS.md](STEPS.md) file.

## License

MIT

This README is my learning guide. It explains what I’m gonna learn, how I’ll use it, why it matters, and what I’ll build.
---

## 📋 Prerequisites

Before I start, I need:

- Node.js installed
- npm or yarn
- Expo Go app on my phone, or an iOS/Android simulator
- VS Code or another code editor
- Basic JavaScript and React knowledge

---

## 🎯 My Learning Goals + GIF Placeholders

These are the things I’m gonna learn from the video. For each goal, I’ve written what I’ll learn, how I’ll use it, why it matters, and what kind of Pokémon GIF I should add there.

### 1. Setting Up a React Native Expo Project

I’m gonna learn how to create a new Expo app with TypeScript. I’ll learn what files Expo gives me, how to start the development server, and why Expo makes React Native easier for beginners.


<div align="center">
<img align="center" src="https://media.tenor.com/3IACtMvxwdsAAAAj/pikachu-happy.gif" alt="Pokemon Jumping" width="300" />
</div>

### 2. Navigation with Expo Router

I’m gonna learn how to add navigation using Expo Router. I’ll learn how to create a two-screen layout with native tabs, how file-based routing works, and why navigation is important for real apps.

<div align="center">
<img align="center" src="https://media1.tenor.com/m/YJ59VV_gB2EAAAAC/bulbasaur.gif" alt="Focused Bulbasaur typing on a laptop while I learn Expo Router navigation" width="300" />
</div>

### 3. Layout and Flexbox

I’m gonna learn how to break down an app layout using Flexbox. I’ll learn how rows, columns, alignment, spacing, and sizing work, and why Flexbox is the main way to style React Native layouts.

<div align="center">
<img align="center" src="https://media1.tenor.com/m/XnjYv6K5T5cAAAAC/cutie.gif" alt="Charmander carefully arranging blocks while I learn Flexbox layout" width="300" />
</div>

### 4. Expo UI Components and Native Buttons

I’m gonna learn how to create native buttons and use Expo UI components. I’ll also learn how platform-specific files work, how to handle different platforms, and why some components look different on iOS and Android.

<div align="center">
<img align="center" src="https://media1.tenor.com/m/y8_GcVWBbFoAAAAC/squitle-arroz.gif" alt="Squirtle giving a thumbs-up because my Expo buttons work on iOS and Android" width="300" />
</div>

### 5. Picking Images from the Media Library

I’m gonna learn how to pick images from the device’s media library. I’ll learn how permissions work, how to display the selected image, and why media access is useful for photo and sticker apps.

<div align="center">
<img align="center" src="https://media1.tenor.com/m/WF9ahkVEZZUAAAAC/eevee-eevee-wow.gif" alt="Curious Eevee looking at a picture while I learn how to pick images from the media library" width="300" />
</div>

### 6. Bottom Sheets and FlatList

I’m gonna learn how to build an emoji picker using an Expo UI bottom sheet and React Native’s `FlatList`. I’ll learn how to render lists efficiently, how to select items, and why `FlatList` is better than mapping over large lists.

<div align="center">
<img align="center" src="https://media.tenor.com/Y0AnWAY8QlIAAAAi/meloetta-pokemon.gif" alt="Meloetta happily singing while I scroll through emojis in a FlatList" width="300" />
</div>

### 7. Touch Gestures and Stickers

I’m gonna learn how to add touch gestures to stickers. I’ll learn how to handle taps, drags, and movement, and why gestures make mobile apps feel interactive and fun.

<div align="center">
<img align="center" src="https://media1.tenor.com/m/cEVQyzJrVsQAAAAd/mrmime.gif" alt="Mr. Mime pretending to move something with its hands while I learn touch gestures" width="300" />
</div>

### 8. Screenshots and Saving Images

I’m gonna learn how to capture a screenshot of my app view. I’ll learn how to save it to the Android/iOS media library and download it on web, and why saving screenshots is useful for sharing creations.

<div align="center">
<img align="center" src="https://media1.tenor.com/m/GCVR0l-_aN4AAAAC/smeargle.gif" alt="Smeargle painting a picture while I learn how to save screenshots" width="300" />
</div>

### 9. App Polish: Status Bar, Splash Screen, and Icons

I’m gonna learn how to configure the status bar, splash screen, and app icon. I’ll learn where Expo app config lives, how to customize the app appearance, and why polish makes an app feel professional.

<div align="center">
<img align="center" src="https://media1.tenor.com/m/_mQwj8JmH_gAAAAC/pikachu-correndo-pok%C3%A9mon.gif" alt="Pikachu with sparkles while I polish my app with a splash screen and icon" width="300" />
</div>

### 10. Testing and Debugging

I’m gonna learn how to test my app on a physical device, simulator, and web. I’ll learn how to read logs, fix errors, and why testing on multiple platforms matters.

<div align="center">
<img align="center" src="https://media1.tenor.com/m/Rc1GWDr71WIAAAAC/psyduck.gif" alt="Psyduck figuring out a bug and then celebrating while I test and debug my app" width="300" />
</div>


---

## 🛠️ Project Setup Commands

These are the commands I’ll use to start my Expo project:

```bash
npm install -g expo-cli
npx create-expo-app@latest my-app --template blank-typescript
cd my-app
npx expo start
```


