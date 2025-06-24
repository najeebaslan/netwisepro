# <div align="center">NetWise Pro - Wireless Network Management System 📡</div>

<div align="center">
  <a href='https://play.google.com/store/apps/details?id=com.network.netwisepro'>
<img src="https://upload.wikimedia.org/wikipedia/commons/7/78/Google_Play_Store_badge_EN.svg" width="150">
</a>
<a href='https://apps.apple.com/ye/app/%D9%86%D9%8A%D8%AA%D9%88%D8%A7%D9%8A%D8%B2-%D8%A8%D8%B1%D9%88/id6747299953'>
<img src="https://upload.wikimedia.org/wikipedia/commons/3/3c/Download_on_the_App_Store_Badge.svg" width="150">
</a> 
  
---- 

  <td><img src="https://firebasestorage.googleapis.com/v0/b/weddinghallbooking-2ba28.appspot.com/o/protiflio_images%2FNetWisePro2.webp?alt=media&token=29a63ef2-ff4c-42d7-abee-6ca72950ab70" alt="Image 2"></td>
  <td><img src="https://firebasestorage.googleapis.com/v0/b/weddinghallbooking-2ba28.appspot.com/o/protiflio_images%2FNetWisePro1.webp?alt=media&token=39147e6c-a806-4001-8c18-604d09f7caaf" alt="Image 2"></td>
  <td><img src="https://firebasestorage.googleapis.com/v0/b/weddinghallbooking-2ba28.appspot.com/o/protiflio_images%2FNetWisePro3.webp?alt=media&token=4fa8c213-ef26-45f3-83ea-40f29efa66a2" alt="Image 2"></td>
</div>

---

## Overview

NetWise Pro is a modern Flutter-based application for managing and monitoring wireless networks. It empowers users and administrators with robust tools for network operations, analytics, and security. The app features a clean, responsive UI and supports multiple languages for a global audience.

---

## Description

- Manage, monitor, and analyze wireless networks with ease.
- Secure, multi-language, and responsive for all devices.
- Designed for both network admins and everyday users.

---

## What Does This App Do? (Step-by-Step)

1. **User Authentication:** Secure login and session management.
2. **Network Management:** Add, edit, and delete network details, cards, packages, and offers.
3. **Sales & Reports:** Sell balances, view sales, and generate detailed reports.
4. **Notifications:** Receive real-time updates and alerts.
5. **Settings:** Customize preferences, themes, and language.

---


## Technology Stack

<table>
  <tr>
    <td align="center" width="96">
      <img src="https://storage.googleapis.com/cms-storage-bucket/ec64036b4eacc9f3fd73.svg" width="48" height="48" alt="Flutter" />
      <br>Flutter
    </td>
    <td align="center" width="96">
      <img src="https://dart.dev/assets/shared/dart/icon/64.png" width="48" height="48" alt="Dart" />
      <br>Dart
    </td>
    <td align="center" width="96">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" width="48" height="48" alt="MongoDB" />
      <br>MongoDB
    </td>
    <td align="center" width="96">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" width="48" height="48" alt="Node.js" />
      <br>Node.js
    </td>
    <td align="center" width="96">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original-wordmark.svg" width="48" height="48" alt="Redis" />
      <br>Redis
    </td>
    <td align="center" width="96">
      <img src="https://jwt.io/img/pic_logo.svg" width="48" height="48" alt="JWT" />
      <br>JWT
    </td>
    <td align="center" width="96">
      <img src="https://cdn.worldvectorlogo.com/logos/rest.svg" width="48" height="48" alt="REST API" />
      <br>REST API
    </td>
    <td align="center" width="96">
      <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" width="48" height="48" alt="Postman" />
      <br>Postman
    </td>
  </tr>
</table>

---

## Key Features

- Add, edit, and manage network details, cards, and packages
- Multi-language support (English, Arabic)
- Responsive UI (Sizer)
- Dark/Light theme
- Custom animations and transitions
- Secure authentication and permission management
- Comprehensive reporting and analytics
- Real-time notifications

---

## Core Technical Features

- **State Management:** Provider
- **Localization:** flutter_localizations, intl
- **Network Requests:** http
- **Data Storage:** shared_preferences
- **Animations:** lottie, custom transitions
- **Charts & Visualization:** syncfusion_flutter_charts
- **Functional Programming:** dartz
- **SVG & Media:** flutter_svg, image_picker, file_picker

---

## Development Skills Applied

- Clean architecture and modular codebase
- Advanced Flutter UI/UX design
- State management with Provider
- RESTful API integration
- Secure local storage and permission handling
- Responsive and adaptive layouts
- Internationalization (i18n)

---

## Mobile Development

- Built with Flutter for cross-platform (Android & iOS)
- Uses Sizer for responsive design
- Supports both light and dark themes
- Optimized for performance and smooth animations

---

## Tools & Methodologies

| Tool/Methodology         | Purpose                        |
|-------------------------|--------------------------------|
| Flutter                 | Cross-platform development     |
| Dart                    | Programming language           |
| Provider                | State management               |
| REST API                | Backend communication          |
| Postman                 | API testing                    |
| Git                     | Version control                |
| VS Code/Android Studio  | Development environment        |
| JWT                     | Authentication                 |
| MongoDB/Redis           | Backend data & cache           |

---


## Application Structure

```mermaid
flowchart TD
    A[lib/] --> B[config/]
    A --> C[core/]
    A --> D[data/]
    A --> E[domain/]
    A --> F[ui/]
    A --> G[utils/]
    
    B --> B1[l10n/]
    B --> B2[theme/]
    B --> B3[extensions/]
    
    F --> F1[pages/]
    F --> F2[widgets/]
    
    D --> D1[repositories/]
    D --> D2[models/]
    
    E --> E1[entities/]
    E --> E2[usecases/]
```

---


## Screen Architecture

- **Authentication Screens:** Login, Registration, Forgot Password, Verification
- **Home Screen:** Dashboard, quick stats, navigation
- **Menu:** Profile, Settings, Account Switch, About, Logout
- **Network Management:** Edit network, manage coverage, offers, engineers
- **Reports:** Sales, exports, imports, analytics
- **Notifications:** Real-time updates, filterable by type

---

## 📦 Packages Used

| Package                   | Purpose                        |
|---------------------------|--------------------------------|
| provider                  | State management               |
| sizer                     | Responsive UI                  |
| dartz                     | Functional programming         |
| http                      | Network requests               |
| flutter_svg               | SVG rendering                  |
| lottie                    | Animation support              |
| syncfusion_flutter_charts | Data visualization             |
| intl                      | Internationalization           |
| image_picker              | Image selection                |
| file_picker               | File selection                 |
| awesome_dialog            | Custom dialogs                 |
| fluttertoast              | Toast notifications            |
| path_provider             | File system access             |
| permission_handler        | Permissions                    |
| skeletons                 | Loading skeletons              |
| animations                | Custom animations              |
| flutter_native_splash     | Splash screen                  |

---

<div align="center">
  <b>Made with ❤️ using Flutter</b>
</div> 
