# Sonicrypt

## Overview

Sonicrypt is an innovative organization dedicated to revolutionizing the user experience in the realm of crypto transactions. Our mission is to bridge the gap between digital transactions and tangible experiences, fostering trust and confidence among buyers and sellers alike.

## Products

### 1. Sonicrypt Device

The Sonicrypt Device is a compact and intuitive tool that provides immediate auditory and visual confirmation of successful payments. It is designed to enhance the user experience for both buyers and sellers engaging in crypto transactions.

#### Features

- Auditory confirmation of successful payments
- Visual confirmation of successful payments
- Voice confirmation of successful payments (Sonicrypt Plus & Sonicrypt Pro)
- Multi-wallet support (Sonicrypt Plus & Sonicrypt Pro)
- Multi-chain support (Sonicrypt Pro)
- On-the-fly QR code generation (Sonicrypt Pro)
- Off-chain transactions (Sonicrypt Pro)

#### Components (Sonicrypt)

- ESP32
- LED
- Buzzer
  
#### Components (Sonicrypt plus)

- ESP32
- LED
- Display
- Speaker

#### Components (Sonicrypt pro)

- Raspberry Pi
- LED
- Display
- Speaker
- Microphone

#### User Workflow

1. The seller generates a QR code using the Sonicrypt app.
2. The buyer scans the QR code using their wallet app.
3. The buyer sends the payment to the seller.
4. The Sonicrypt device plays a sound and lights up when the payment is confirmed and finalized.
5. The seller can then provide the product to the buyer.
6. The transaction is complete.

#### How it Works

1. The Sonicrypt device connects to the blockchain network (Solana) websocket to listen for account changes.
2. The device listens to the account changes of the seller's wallet address.
3. When the Sonicrypt device detects a change in the seller's wallet address, it retrieves the last transaction signature.
4. The device then fetches the transaction details using the transaction signature.
5. If the transaction is successful, the Sonicrypt device plays a sound and lights up.

### 2. Sonicrypt App

The Sonicrypt App is a mobile application that allows users to connect and configure their Sonicrypt devices seamlessly. It serves as a convenient interface for interacting with the device and managing various aspects of the crypto transaction process.

#### Tech Stack

- React Native
- Expo
- Tamagui
- React Native BLE PLX

#### Features of app

- Connect to Sonicrypt device
- View Sonicrypt device status and logs
- Mock Sonicrypt device
- Get transaction details and history
- Get daily transaction summary
- Customize Sonicrypt device settings

## Open-Source and No Hidden Costs

Sonicrypt is a completely open-source project, and we are committed to keeping it that way. The device does not connect to any servers or third-party services, ensuring privacy and transparency. It is a standalone device that you can use without any subscription fees or hidden costs. Both the software and hardware are open-source, allowing you to modify and customize the solution according to your needs.

## Get Involved

We welcome contributions from the community to further enhance the Sonicrypt ecosystem. Whether you're a developer, designer, or an enthusiast, there are numerous ways to get involved. Visit our [GitHub repository](https://github.com/Sonicrypt/sonicrypt) to explore the codebase, submit issues, or contribute to the project.

## Stay Connected

Stay up-to-date with the latest developments, announcements, and updates from the Sonicrypt team by following us on social media:

- Twitter: [@Sonicrypt](https://twitter.com/sonicrypt)

Join our vibrant community and be part of the revolution in crypto transactions!
