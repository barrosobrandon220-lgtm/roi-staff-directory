# ROI Staff Directory

A mobile staff directory app built with **React Native** and **Expo**, created as part of my Certificate IV in Information Technology (Mobile Application Development) at TAFE, based on a client brief for Red Opal Innovations.

## Features

- **Home screen** with navigation to the directory and settings
- **Staff directory** with search by name, role or department
- **Add staff** form with validation (name and role required, phone must be numeric and at least 8 digits)
- **Staff details** screen with the option to delete a staff member
- **Settings screen** with brightness, text size and sound controls

## Tech stack

- React Native 0.81 / React 19
- Expo SDK 54
- React Native Paper
- Expo Linear Gradient and Expo Vector Icons

## Project structure

```
App.js            # App state and simple screen navigation
screens/          # Home, Directory, AddStaff, StaffDetails, Settings, TopBar
assets/           # Images and icons
```

## Run it locally

1. Install [Node.js](https://nodejs.org) (LTS) and the **Expo Go** app on your phone.
2. Clone the repo and install dependencies:
   ```
   git clone https://github.com/<your-username>/roi-staff-directory.git
   cd roi-staff-directory
   npm install
   ```
3. Start the app:
   ```
   npm start
   ```
4. Scan the QR code with Expo Go (phone and computer on the same WiFi).

## Known limitations

- Staff data is stored in memory only, so it resets when the app is closed.
- The settings controls are interface-only for now and do not change the device settings.

## What I'd improve next

- Save staff data on the device with AsyncStorage
- Replace the state-based screen switching with React Navigation
- Let users edit existing staff members
