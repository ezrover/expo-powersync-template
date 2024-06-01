# React Native Expo Template  
- ⚡ [Expo v51](https://expo.dev) - Built with Expo for cross-platform support
- ⚛️ [React Native v0.74](https://reactnative.dev) for building native apps using React
- 💎 Integrate with [NativeWind v4](https://www.nativewind.dev), Tailwind CSS for React Native
- 📁 Expo Router and Expo API
- 📦 [zustand](docs.pmnd.rs/zustand) - State management solution.
- 🎨 Common components : Icons, ThemeToggle, Avatar, Button, Card, Progress, Text, Tooltip
- 🌗 Dark and light mode - Android Navigation Bar matches mode and Persistant mode
- 💡 Absolute Imports using `@` prefix
- 📏 Linter and Code Formatter with [biome](https://biomejs.dev/)
- 🗂 VSCode recommended extensions, settings, and snippets to enhance the developer experience.

New :
- 💽 Local-first based on PowerSync [Expo SQLite for](https://docs.expo.dev/versions/latest/sdk/sqlite/) for native and [Sqlite.js](https://github.com/sql-js/sql.js) for Web
- 💽 Full integrated with [DrizzleORM](https://drizzle.dev)

### Requirements

- Node.js 20+ and pnpm or bun
- [iOS Simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Android Studio Emulator](https://docs.expo.dev/workflow/android-studio-emulator/)

### Getting started

Run the following command on your local environment:

```shell
bunx create-expo-app --template @ezrover/expo-powersync-template
```

Then, you can run locally in development mode with live reload:

```shell
bun run dev:ios
# Or
bun run dev:android
```

This will open the app in the iOS simulator or Android emulator.

### Contributions

Inspired by: 

Everyone is welcome to contribute to this project. Feel free to open an issue if you have question or found a bug. Totally open to any suggestions and improvements.

### License

Licensed under the MIT License, Copyright © 2024

See [LICENSE](LICENSE) for more information.

---
