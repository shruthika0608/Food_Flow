# Food Flow 🍽️

> Connecting surplus food with those in need - A comprehensive platform bridging restaurants and NGOs to combat food waste and hunger.

[![Figma Design](https://img.shields.io/badge/Figma-Design-F24E1E?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/design/I5dJPgS0szyXwRX7XUx5gN/Food-Flow?node-id=0-1&p=f)

## 📋 Table of Contents

- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Solution](#solution)
- [Key Features](#key-features)
- [User Flows](#user-flows)
- [Screenshots](#screenshots)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## 🌟 Overview

Food Flow is an innovative platform designed to tackle two critical issues simultaneously: food waste and hunger. By creating a seamless connection between restaurants with surplus food and NGOs working to feed communities in need, we're building a more sustainable and compassionate food ecosystem.

## 🎯 Problem Statement

Every day, thousands of restaurants dispose of surplus food while millions go hungry. The disconnect between food availability and distribution creates:

- **Environmental Impact**: Massive food waste contributing to landfill overflow and greenhouse gas emissions
- **Social Crisis**: Communities struggling with food insecurity despite nearby food surplus
- **Economic Loss**: Restaurants losing resources while NGOs struggle to source food donations
- **Logistical Challenges**: Lack of efficient systems to coordinate food redistribution

## 💡 Solution

Food Flow provides a comprehensive platform that:

- **Streamlines the Donation Process**: Direct communication channels between restaurants and NGOs
- **Facilitates Logistics**: Real-time coordination for food pickup and delivery
- **Optimizes Resource Utilization**: Intelligent matching algorithms to connect supply with demand
- **Enables Bulk Redistribution**: Scalable system for handling large-volume donations
- **Ensures Food Reaches Those in Need**: Efficient tracking and verification systems

## ✨ Key Features

### For Restaurants

- **Inventory Management**: 
  - Real-time tracking of available food items
  - Set quantities and expiry dates
  - Update inventory with ease

- **NGO Communication**:
  - Direct messaging with verified NGOs
  - Request approval system
  - Order tracking

- **Dashboard Analytics**:
  - Track donation history
  - Monitor impact metrics
  - View active requests

### For NGOs

- **Restaurant Discovery**:
  - Browse available restaurants and food items
  - View real-time inventory
  - Location-based search

- **Order Management**:
  - Add items to cart
  - Submit food requests
  - Track approval status

- **Communication Hub**:
  - Direct chat with restaurants
  - Receive notifications
  - Coordinate pickup times

### Platform Features

- **Smart Matching**: Algorithms that connect restaurants with nearby NGOs based on availability and need
- **Verification System**: Ensure legitimacy of both restaurants and NGOs
- **Real-time Updates**: Instant notifications for requests, approvals, and messages
- **Impact Tracking**: Monitor total food saved and people served
- **Scalable Architecture**: Built to handle growth from local to regional scale

## 🔄 User Flows

### Restaurant Flow

1. **Welcome & Setup**
   - Create account / Login
   - Complete restaurant profile
   - Verify credentials

2. **Inventory Management**
   - View current inventory
   - Add new food items with details (quantity, expiry)
   - Update or remove items

3. **Request Handling**
   - Receive requests from NGOs
   - Review NGO profiles and past interactions
   - Approve or decline requests
   - Set pickup times

4. **Communication**
   - Chat with NGOs
   - Coordinate logistics
   - Confirm pickups

### NGO Flow

1. **Discovery**
   - Browse available restaurants
   - Search by location or food type
   - View restaurant menus and availability

2. **Ordering**
   - Add items to cart
   - Specify quantities needed
   - Add special requests or notes
   - Submit request

3. **Approval & Coordination**
   - Wait for restaurant approval
   - Receive notifications
   - Confirm pickup details
   - Track order status

4. **Pickup & Completion**
   - Navigate to restaurant
   - Complete pickup
   - Confirm receipt

## 📱 Screenshots

### Restaurant Interface

#### Welcome Page
<img src="screenshots/restaurant-welcome.png" alt="Restaurant Welcome Page" width="200"/>

The welcoming dashboard for restaurants featuring quick access to feedback viewing and NGO search functionality.

#### Inventory Management
<img src="screenshots/restaurant-inventory.png" alt="Inventory Management" width="200"/>

Easy-to-use interface for tracking available food items with quantities, expiry dates, and quick edit/add options.

#### Messaging System
<img src="screenshots/restaurant-messaging.png" alt="Restaurant Messaging" width="200"/>

Direct communication channel with NGOs for coordinating donations and logistics.

#### Approval Screen
<img src="screenshots/restaurant-approval.png" alt="Approval Confirmation" width="200"/>

Streamlined approval process showing successful request handling with clear confirmation.

### NGO Interface

#### Home Dashboard
<img src="screenshots/ngo-home.png" alt="NGO Home" width="200"/>

User-friendly home screen displaying available restaurants with active donation programs.

#### Restaurant Menu
<img src="screenshots/ngo-restaurant-page.png" alt="Restaurant Menu" width="200"/>

Detailed view of restaurant offerings with quantities and easy-to-use add-to-cart functionality.

#### Shopping Cart
<img src="screenshots/ngo-cart.png" alt="Shopping Cart" width="200"/>

Cart interface for reviewing selected items and submitting requests to restaurants.

#### Request Tracking
<img src="screenshots/ngo-request-chat.png" alt="Request Chat" width="200"/>

Real-time communication system showing request status and coordination details.

#### Success Confirmation
<img src="screenshots/ngo-request-success.png" alt="Request Success" width="200"/>

Clear confirmation of approved requests with pickup time and tracking information.

## 🛠️ Tech Stack

### Frontend
- **Framework**: React.js / React Native (for mobile)
- **UI Library**: Material-UI / Custom Components
- **State Management**: Redux / Context API
- **Navigation**: React Router / React Navigation

### Backend
- **Server**: Node.js with Express
- **Database**: MongoDB / PostgreSQL
- **Authentication**: JWT / OAuth
- **Real-time**: Socket.io for messaging
- **APIs**: RESTful / GraphQL

### Infrastructure
- **Cloud Hosting**: AWS / Google Cloud / Azure
- **Storage**: AWS S3 / Cloud Storage
- **Maps Integration**: Google Maps API
- **Push Notifications**: Firebase Cloud Messaging

## 🚀 Installation

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- MongoDB / PostgreSQL
- Git


## 💻 Usage

### For Restaurants

1. **Register your restaurant**
   - Provide business details and verification documents
   - Set up your profile with location and contact information

2. **Manage inventory**
   - Log in to your dashboard
   - Add food items with quantities and expiry dates
   - Update inventory as items are donated or removed

3. **Handle requests**
   - Review incoming requests from NGOs
   - Approve or decline based on availability
   - Coordinate pickup times through the messaging system

### For NGOs

1. **Create an NGO account**
   - Submit organization details and verification
   - Complete profile with mission statement and areas served

2. **Browse and request**
   - Search for nearby restaurants with available food
   - Add desired items to cart
   - Submit requests with notes about your needs

3. **Coordinate pickup**
   - Receive approval notifications
   - Communicate with restaurants about logistics
   - Confirm successful pickup



### Suggesting Features

Have an idea? Open an issue with:
- Feature description
- Use case and benefits
- Mockups or examples (if available)

### Code Contributions

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

**Design**
- Figma: [View Design Files](https://www.figma.com/design/I5dJPgS0szyXwRX7XUx5gN/Food-Flow?node-id=0-1&p=f)

## 🎯 Roadmap

### Phase 1 (Current)
- ✅ Core platform functionality
- ✅ Restaurant and NGO interfaces
- ✅ Basic matching and messaging

### Phase 2 (Coming Soon)
- 🔄 Advanced analytics and reporting
- 🔄 Multi-language support
- 🔄 Integration with food safety systems
- 🔄 Automated pickup scheduling

### Phase 3 (Future)
- 📋 AI-powered demand forecasting
- 📋 Expanded to include grocery stores and farms
- 📋 Blockchain for donation tracking
- 📋 Mobile apps for iOS and Android

---

**Made with ❤️ by the Food Flow Team**

*Together, we can end food waste and hunger, one meal at a time.*
