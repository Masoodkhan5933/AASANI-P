![aasani website admin management](https://github.com/user-attachments/assets/814b0ca9-f1b0-4259-b0c5-36ff9d8907d6)# AASANI - Peer-to-Peer Delivery Service

[![React Native](https://img.shields.io/badge/Built%20with-React%20Native-61dafb.svg)](https://reactnative.dev/)
[![Firebase](https://img.shields.io/badge/Backend-Firebase-ffca28.svg)](https://firebase.google.com/)
[![Node.js](https://img.shields.io/badge/Server-Node.js-339933.svg)](https://nodejs.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> ![Main Advertisement Image](screenshots/bgimageAasani.png)

## 📱 Overview

AASANI is a peer-to-peer delivery service application that connects travelers who regularly commute between cities with clients needing items delivered. By leveraging existing travel routes, AASANI reduces delivery costs and time, especially in underserved areas of Pakistan where traditional courier services are expensive, slow, or unavailable.

> Transforming package delivery through community connections

## 🎯 Problem Addressed

In places like Nowshera, Pakistan, sending packages is challenging:
- Traditional courier services (TCS, Leopard) are expensive
- Delivery to smaller towns is often unreliable
- Long waiting times for important items
- No platform for regular travelers to help with deliveries

## ✨ Key Features

- **Role-Based System**: Register as a client or traveler
- **Smart Matching**: Algorithm connects clients with nearby travelers
- **Real-Time Tracking**: GPS-based delivery tracking
- **In-App Chat**: Direct communication between clients and travelers
- **Rating System**: Build trust through user reviews
- **Complaint Handling**: Structured system for issue resolution
- **Payment Integration**: Secure transaction processing
- **Admin Panel**: Comprehensive management dashboard

## 🛠️ Tech Stack

| Component | Technology |
|-----------|------------|
| Mobile App | React Native |
| Admin Panel | React, Tailwind CSS |
| Backend | Node.js, Firebase |
| Database | Firebase Realtime Database |
| Authentication | Firebase Auth |
| Maps & Location | Google Maps API |
| Notifications | Firebase Cloud Messaging |
| Testing | Jest |

## 📱 Mobile App Screenshots

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="screenshots/1.png" alt="Home Screen" width="250"/>
        <br/>
        <em>Home Screen</em>
      </td>
      <td align="center">
        <img src="screenshots/2.png" alt="Login Screen" width="250"/>
        <br/>
        <em>Login Screen</em>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="screenshots/3.png" alt="Register Form" width="250"/>
        <br/>
        <em>Register Form Phase 1</em>
      </td>
      <td align="center">
        <img src="screenshots/4.png" alt="Notifications Screen" width="250"/>
        <br/>
        <em>Notifications Interface</em>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="screenshots/5.png" alt="Post Info Live Tracking" width="250"/>
        <br/>
        <em>Post Info Live Tracking</em>
      </td>
      <td align="center">
        <img src="screenshots/6.png" alt="Payment Screen" width="250"/>
        <br/>
        <em>Stripe Payment Screen</em>
      </td>
    </tr>
  </table>
</div>

## 💻 Admin Panel Screenshots

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="screenshots/Web.png" alt="Web Public Website" width="500"/>
        <br/>
        <em>Web Public Website</em>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="screenshots/adminPanel.png" alt="Admin Management" width="500"/>
        <br/>
        <em>Admin Management</em>
      </td>
    </tr>
  </table>
</div>

## 🏗️ Architecture

AASANI follows a three-tier architecture:
- **Frontend**: React Native mobile app for clients/travelers + React web admin panel
- **Backend**: Node.js server with Firebase integration
- **Database**: Firebase Realtime Database for data storage and synchronization

The system uses Firebase Authentication for user management and Google Maps API for location services and delivery tracking.

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- React Native development environment
- Firebase account
