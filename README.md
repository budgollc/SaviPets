# 🐾 SaviPets


<img width="1394" height="837" alt="image" src="https://github.com/user-attachments/assets/53bbd11d-4bc9-4973-99c8-90009fbf083e" />


## Overview

SaviPets is a native iOS pet care platform that connects pet owners, pet sitters, and administrators through a unified booking, communication, tracking, and payment system.

The application is built with SwiftUI and Firebase using a modular MVVM architecture and protocol-based dependency injection.

Primary objectives:

- Manage pet care bookings
- Enable real-time communication
- Track sitter visits
- Process payments securely
- Provide administrative oversight
- Maintain a scalable foundation for future growth

---

## Current Status

Version: 1.0

Development Phase: Production

Supported Platforms:

- iOS 17+
- iPhone
- iPad

Core systems are operational, including:

- Authentication
- Booking management
- Pet management
- Messaging
- GPS visit tracking
- Payment processing
- Push notifications
- Administrative tools

---

## Core Features

### Booking System

- One-time bookings
- Recurring bookings
- Multiple service types
- Booking modifications
- Schedule management

### Pet Management

- Pet profiles
- Vaccination information
- Care instructions
- Emergency contacts
- Photo uploads

### Messaging

- Real-time chat
- Owner ↔ Sitter communication
- Visit updates
- Photo sharing
- Push notifications

### Visit Tracking

- GPS verification
- Check-in / Check-out
- Visit timers
- Route tracking
- Activity reporting

### Payments

- Square integration
- Invoice generation
- Payment history
- Booking-based pricing

### Administration

- User management
- Booking oversight
- Platform monitoring
- Reporting tools

---

## Architecture

### Pattern

MVVM

### State Management

- AppState
- Observable Objects
- Async/Await
- Combine

### Dependency Management

Protocol-based dependency injection through DependencyContainer.

### Backend

Firebase provides:

- Authentication
- Firestore
- Storage
- Cloud Functions
- Push Notifications

---

## Technology Stack

| Layer | Technology |
|---------|------------|
| Language | Swift 5.9+ |
| UI | SwiftUI |
| Architecture | MVVM |
| Backend | Firebase |
| Database | Firestore |
| Storage | Firebase Storage |
| Authentication | Firebase Auth |
| Payments | Square |
| Location | CoreLocation |
| Maps | MapKit |
| Notifications | Firebase Messaging |

---

## Project Structure

text SaviPets ├── Auth/ ├── Booking/ ├── Dashboard/ ├── Features/ ├── Services/ ├── Models/ ├── Design/ ├── Utilities/ ├── Resources/ └── Tests/ 

---

## Development Requirements

- macOS Sequoia or later
- Xcode 16+
- Swift 5.9+
- Firebase Project
- Square Developer Account

---

## Setup

1. Clone repository

bash git clone <repository-url> 

2. Add:

text GoogleService-Info.plist 

3. Configure Firebase environment

4. Configure Square credentials

5. Build and run

---

## Development Principles

- Keep views lightweight
- Business logic belongs in services
- All external dependencies are abstracted through protocols
- Prefer composition over inheritance
- Maintain feature modularity
- Follow existing design system patterns
- Preserve backward compatibility when possible

---

## Repository Classification

Private Repository

Confidential and proprietary.

All source code, assets, documentation, architecture, and business logic contained within this repository are the intellectual property of SaviPets LLC.

Unauthorized distribution or reproduction is prohibited.
