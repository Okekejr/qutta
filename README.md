# Qutta

A mobile service-booking marketplace that connects clients with local businesses. Clients discover and book appointments; businesses manage their listing, schedule, and bookings. Built with Expo and React Native.

## Features

**Onboarding**
- Role-based sign-up — register as a **client** or a **business**, with email/password and Apple sign-in

**For clients**
- Discover and search local businesses
- Book appointments through a guided flow (select service, date, and time)
- Save favorite businesses
- Manage upcoming and past bookings

**For businesses**
- Multi-step business onboarding — business info, location, services, staff, and images
- Dashboard with a bookings overview
- Schedule and availability management
- Service menu and waitlist management

**Platform**
- Push notifications (expo-notifications, native-notify)
- Maps and location
- Currency selection and localization

## Tech stack

- **Framework:** Expo SDK 53, React Native 0.79, Expo Router 5, TypeScript
- **Data:** TanStack React Query
- **Maps & location:** react-native-maps, expo-location
- **Notifications:** expo-notifications, native-notify
- **Dates:** date-fns, react-native-paper-dates
- **UI/UX:** Moti, Reanimated, Lottie, Gorhom Bottom Sheet
- **Auth & storage:** expo-secure-store, expo-apple-authentication
- **i18n:** expo-localization

The REST API for this app lives in [qutta-backend](https://github.com/Okekejr/qutta-backend).

## Getting started

```bash
npm install
npx expo start
```

Open the app in an iOS simulator, Android emulator, or a development build. Create a `.env` file with your API base URL before running.

### Scripts

| Command | Description |
| ------- | ----------- |
| `npm start` | Start the Expo dev server |
| `npm run ios` | Build and run on iOS |
| `npm run android` | Build and run on Android |
| `npm run web` | Run in the browser |
| `npm run lint` | Run ESLint |
