🐾 SaviPets Ecosystem


  <img width="1394" height="837" alt="image" src="https://github.com/user-attachments/assets/53bbd11d-4bc9-4973-99c8-90009fbf083e" />

  Overview


  SaviPets is a comprehensive, multi-platform pet care marketplace that connects pet owners, professional sitters, and administrators. The ecosystem
  provides a seamless experience for booking, real-time communication, visit tracking, and secure payments across iOS, Android, and Web.


  The project is built with a security-first approach, employing a modern tech stack (SwiftUI, Jetpack Compose, TypeScript) and a robust Firebase-backed
  infrastructure with granular Role-Based Access Control (RBAC V2).


  Core Ecosystem Components



  ┌──────────────────┬─────────────┬─────────────────────────────────────────┬─────────────┐
  │ Component        │ Platform    │ Tech Stack                              │ Status      │
  ├──────────────────┼─────────────┼─────────────────────────────────────────┼─────────────┤
  │ SaviPets iOS     │ iOS 17+     │ Swift, SwiftUI, MVVM                    │ Production  │
  │ SaviPets Android │ Android 14+ │ Kotlin, Jetpack Compose, Clean Arch     │ Production  │
  │ SaviPets Backend │ Cloud       │ Node.js, TypeScript, Firebase Functions │ Production  │
  │ Admin Dashboard  │ Web         │ React, TypeScript                       │ Operational │
  │ Landing Page     │ Web         │ Astro                                   │ Live        │
  └──────────────────┴─────────────┴─────────────────────────────────────────┴─────────────┘

  ---

  Core Features


  📅 Smart Booking System
   - Flexible Scheduling: One-time and recurring bookings with modification support.
   - Service Management: Support for multiple service types (walking, sitting, grooming).
   - Matching Engine: AI-powered sitter assignment based on skills, availability, and ratings.


  📍 Real-Time Visit Tracking
   - GPS Verification: Precise check-in/out with location validation and route tracking.
   - Live Updates: Visit timers, activity reporting, and status monitoring.
   - Verification: Mandatory photographic proof and detailed visit logs for owner peace of mind.


  💬 Integrated Communication
   - Real-Time Messaging: Instant chat between Owners and Sitters.
   - Rich Media: High-quality photo sharing for visit updates and pet reports.
   - Notifications: Multi-channel alerts via Push (FCM), Email (SendGrid), and SMS (Twilio).


  💳 Secure Payments
   - Square Integration: Enterprise-grade payment processing and secure transactions.
   - Automated Invoicing: Dynamic pricing based on service duration, type, and pet count.
   - Transparency: Complete payment history, receipt generation, and financial reporting.


  🛡️ Security & Administration
   - RBAC (V2): Granular Role-Based Access Control (Admin, Moderator, Sitter, Owner, System).
   - Pet Management: Comprehensive profiles including medical history and care instructions.
   - Audit Ready: Extensive logging, monitoring, and security audit documentation.

  ---

  Technology Stack


  Mobile (iOS & Android)
   - iOS: SwiftUI, Combine, Async/Await, Protocol-based Dependency Injection.
   - Android: Jetpack Compose, Hilt/Dagger, Coroutines, Material 3.
   - Common Features: Native Maps integration, CoreLocation, Biometric Authentication.


  Backend & Infrastructure
   - Language: TypeScript (Strict Mode) in a monorepo structure.
   - Runtime: Node.js 20+ (Firebase Cloud Functions).
   - Database: Firestore (with advanced security rules V2).
   - Security: Firebase Auth + Custom Claims for RBAC, Zod for schema validation.


  Web & Landing
   - Admin: React-based dashboard for system-wide oversight and user management.
   - Landing: Astro for high-performance, SEO-optimized public presence.

  ---

  Repository Structure


   1 SaviPets-PF/
   2 ├── savipets-ios/       # Native iOS Application (Swift/SwiftUI)
   3 ├── savipets-android/   # Native Android Application (Kotlin/Compose)
   4 ├── savipets-backend/   # Firebase Functions & Business Logic (TypeScript)
   5 ├── savipets-web-admin/ # Administrative Web Dashboard (React)
   6 ├── savipets-landing/   # Public Marketing Site (Astro)
   7 └── docs/               # System Architecture & Audit Documentation

  ---

  Development Principles


   - Modular Architecture: Clean separation of concerns (MVVM/Clean Architecture).
   - Security First: Mandatory RBAC, field-level encryption, and regular credential auditing.
   - Type Safety: End-to-end type safety from Backend to Mobile clients.
   - Native Experience: Prioritizing platform-native UI/UX patterns.
   - Comprehensive Documentation: Every feature is backed by detailed design and verification docs.

  ---

  Repository Classification

  Private & Proprietary


  All source code, assets, and business logic are the intellectual property of SaviPets LLC. Unauthorized distribution, reproduction, or reverse
  engineering is strictly prohibited.


  Last Updated: June 11, 2026
  Maintained By: SaviPets Engineering Team
