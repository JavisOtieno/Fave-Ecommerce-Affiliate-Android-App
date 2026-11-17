# Fave – Ecommerce Affiliate Android App

A native Android application for affiliates to manage their e-commerce storefronts, track orders, commissions, products, and customer activity.

[![Android](https://img.shields.io/badge/Android-Java-3DDC84?style=flat&logo=android)](https://developer.android.com)
[![minSdk](https://img.shields.io/badge/minSdk-26-blue)](https://developer.android.com)

## Overview

**Fave** is the mobile companion app for the affiliate e-commerce platform. It allows affiliates to:

- View dashboard summaries and recent orders
- Manage and browse products
- Track customers and leads
- Monitor orders and payments
- Access their personalized storefront
- View profile and contact support

The app works alongside the **Laravel-based Affiliates Admin Dashboard & Ecommerce Frontend**.

**Package:** `com.javy.fave`  
**Backend API:** `https://gerund.av.ke/api/`

## Key Features

- Secure login & session management
- Dashboard with order overview
- Products listing and details
- Customers listing and details
- Orders listing and details
- Payments tracking
- Profile management
- Website / storefront access
- Contact support screen
- Image loading with Picasso
- Secure local storage (EncryptedSharedPreferences)

## Tech Stack

| Component          | Technology                  |
|--------------------|-----------------------------|
| Language           | Java                        |
| UI                 | AndroidX + Material Design  |
| Networking         | Retrofit 2 + OkHttp         |
| Image Loading      | Picasso                     |
| Security           | AndroidX Security Crypto    |
| Min SDK            | 26 (Android 8.0)            |
| Target / Compile   | 35                          |

## Prerequisites

- Android Studio (Ladybug or newer recommended)
- JDK 11+
- Android SDK 35
- Git

## Getting Started

```bash
# Clone the repository
git clone https://github.com/JavisOtieno/Fave-Ecommerce-Affiliate-Android-App.git
cd Fave-Ecommerce-Affiliate-Android-App

# Open in Android Studio
# File → Open → select the project folder

# Sync Gradle and run
# Build → Make Project
# Run on emulator or physical device
