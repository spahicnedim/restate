## Introduction
Build a full-stack Real Estate application with React Native, featuring Google authentication, dynamic property listings, and user profiles. Designed with modern tools like Expo SDK 52, Appwrite, Tailwind CSS, and TypeScript for a seamless and scalable experience.

## Tech Stack
- Expo
- React Native
- TypeScript
- Nativewind
- Appwrite
- Tailwind CSS

## Features
- Authentication with Google: Secure and seamless user sign-ins using Google’s authentication service.

- Home Page: Displays the latest and recommended properties with powerful search and filter functionality.

- Explore Page: Allows users to browse all types of properties with a clean and intuitive interface.

- Property Details Page: Provides comprehensive information about individual properties, including images and key details.

- Profile Page: Customizable user settings and profile management

- Centralized Data Fetching: Custom-built solution inspired by TanStack’s useQuery for efficient API calls.

and many more, including code architecture and reusability



## Quick Start
Follow these steps to set up the project locally on your machine.

Prerequisites

Make sure you have the following installed on your machine:

- Git
- Node.js
- npm (Node Package Manager)

Cloning the Repository

```bash
git clone https://github.com/spahicnedim/restate.git
cd yc-directory
Installation
```

Install the project dependencies using npm:
```bash
npm install
```
Set Up Environment Variables
Create a new file named .env.local in the root of your project and add the following content:
```bash
EXPO_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
EXPO_PUBLIC_APPWRITE_PROJECT_ID=
EXPO_PUBLIC_APPWRITE_DATABASE_ID=
EXPO_PUBLIC_APPWRITE_GALLERIES_COLLECTION_ID=
EXPO_PUBLIC_APPWRITE_REVIEWS_COLLECTION_ID=
EXPO_PUBLIC_APPWRITE_AGENTS_COLLECTION_ID=
EXPO_PUBLIC_APPWRITE_PROPERTIES_COLLECTION_ID=
```
Replace the values with your actual Appwrite credentials. You can obtain these credentials by signing up & creating a new project on the Appwrite website.

Running the Project

npx expo start

In the output, you'll find options to open the app in a

- development build
- Android emulator
- iOS simulator
- Expo Go, a limited sandbox for trying out app development with Expo



