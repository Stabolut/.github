# Stabolut - USB Token Ecosystem

## Table of Contents
- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [API Endpoints](#api-endpoints)
- [Usage](#usage)
- [High-Level Process](#high-level-process)
- [Contact](#contact)

## Overview
Stabolut's USB Token Ecosystem encompasses a comprehensive backend service and a mobile wallet application designed to manage USB, a specific cryptocurrency ecosystem. This ecosystem is built to support user wallet creation, fund transfers, staking, gasless transactions, and seamless integration with various blockchain networks, focusing on scalability, security, and user experience.

## Technologies Used
- **Backend Framework:** Node.js with Express
- **Database:** MongoDB
- **Notification:** Firebase (for transaction notifications)
- **Live Updates:** Socket.io
- **Frontend (Mobile App):** React Native

## Installation
### Backend API
1. Clone the repository: `git clone https://github.com/Stabolut/backend.git`
2. Navigate to the project directory: `cd backend`
3. Install dependencies: `npm install`
4. Start the server: `npm run start`

### Mobile App
1. Clone the repository: `git clone https://github.com/Stabolut/mobile.git`
2. Navigate to the project directory: `cd mobile`
3. Install dependencies: `npm install`
4. For iOS, navigate to the iOS directory (`cd ios`), install CocoaPods dependencies (`pod install`), then return to the project directory (`cd ..`)
5. Run the app:
   - Android: `npx react-native run-android`
   - iOS: `npx react-native run-ios`

## API Endpoints
The backend provides various API endpoints for wallet management, fund transfers, staking, and more. Detailed documentation on each endpoint is available within the backend repository.

## Usage
The USB Token Ecosystem allows for the creation and management of USB wallets, conducting gasless transactions, staking USB tokens, and viewing transaction history through the mobile app. It supports multiple cryptocurrencies, enhancing the user's ability to transact with various digital currencies seamlessly.

## High-Level Process
The ecosystem follows a structured process flow, including wallet creation and association, transaction initiation and authorization, transaction processing, blockchain integration, and transaction history reporting, ensuring a secure and efficient platform for managing USB cryptocurrency assets.

## Contact
For inquiries, suggestions, or feedback, please reach out to us at press@stabolut.com. We're dedicated to providing a user-friendly and efficient token experience, enhancing the usability and accessibility of the USB token ecosystem.
