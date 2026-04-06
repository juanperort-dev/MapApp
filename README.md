# 🗺️ MapApp — SwiftUI Interactive Locations App

<p align="center">
  <a href="https://juanperort.dev">
    <img src="https://img.shields.io/badge/Portfolio-juanperort.dev-111827?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://www.linkedin.com/in/juanperort/">
    <img src="https://img.shields.io/badge/LinkedIn-Juan%20Jos%C3%A9%20Per%C3%A1lvarez%20Ortiz-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Swift-5.0-orange.svg" alt="Swift 5.0" />
  <img src="https://img.shields.io/badge/Platform-iOS%2018.2%2B-blue.svg" alt="iOS 18.2+" />
  <img src="https://img.shields.io/badge/UI-SwiftUI-0A84FF.svg" alt="SwiftUI" />
  <img src="https://img.shields.io/badge/Framework-MapKit-34C759.svg" alt="MapKit" />
  <img src="https://img.shields.io/badge/Architecture-MVVM-green.svg" alt="MVVM" />
</p>

**MapApp** is an interactive iOS application built with **SwiftUI** and **MapKit**, designed to explore iconic locations around the world through a clean, map-first user experience.  
The project focuses on custom annotations, map-driven navigation, detail presentations, and a lightweight MVVM structure for clear separation between UI state and view logic.

> 🚀 Explore this and other projects in my portfolio: **[juanperort.dev](https://juanperort.dev)**

---

## 🎬 Demo

- **Portfolio case study:** [juanperort.dev](https://juanperort.dev)
- **App preview:** Screenshots and demo GIF coming soon

---

## ✨ Why this project stands out

This project was built to demonstrate how to create a polished map-based iOS experience using native Apple frameworks.

It focuses on:

- A **map-first SwiftUI interface**
- Interactive exploration of multiple landmarks
- Custom **MapKit annotations**
- Reusable SwiftUI components for previews, lists, and detail screens
- A lightweight **MVVM** structure for state-driven UI updates
- Smooth transitions between map selection, list navigation, and detail presentation

---

## 🚀 Features

- **Interactive Map Navigation:** Browse multiple landmarks directly on the map
- **Custom Annotations:** Tappable map markers with custom SwiftUI visuals
- **Location Previews:** Contextual preview card for the currently selected place
- **Expandable Locations List:** Quick navigation between all available locations
- **Detail View:** Rich destination page with images, description, embedded map, and external reference link
- **Next Location Flow:** Easily cycle through locations using the built-in next action

---

## 🏗️ Architecture

The project follows a simple and effective **MVVM** architecture tailored for SwiftUI.

- **Models**
  - Domain representation of each location
  - Geographic coordinates, metadata, image references, and external links

- **ViewModels**
  - Centralized UI state management
  - Selected location handling
  - Map camera updates
  - List visibility state
  - Detail sheet presentation logic

- **Views**
  - Main map screen
  - Header and expandable list
  - Preview card
  - Detail screen
  - Custom map annotation UI

- **DataServices**
  - Static in-memory location dataset
  - Clean separation between source data and presentation logic

---

## 🧭 User Flow

The app experience is centered around discovering locations in an intuitive way:

1. The app launches into a full-screen map
2. The current location is highlighted with a custom annotation
3. Users can:
   - tap an annotation
   - open the list of all locations
   - navigate using the preview card
4. Selecting **Learn more** opens a full detail sheet
5. The detail screen provides:
   - image gallery
   - destination information
   - a secondary map preview
   - a quick external reference link

---

## 🧱 Project Structure

```bash
MapApp/
├── DataServices/               # Static location source
├── Models/                     # Location model
├── ViewModels/                 # Map state and selection logic
├── Views/                      # Main screen, previews, list, detail, annotations
├── Assets.xcassets/            # Images, colors, app assets
├── Preview Content/            # SwiftUI preview assets
├── ContentView.swift           # Default template file
├── Info.plist
└── MapAppApp.swift             # App entry point
```

---

## 🛠️ Tech Stack

- **Language:** Swift 5
- **UI Framework:** SwiftUI
- **Maps:** MapKit
- **Architecture:** MVVM
- **State Management:** `ObservableObject` + `@Published`
- **Navigation Pattern:** State-driven sheet presentation and map selection
- **Data Source:** Static in-memory dataset
- **Target Devices:** iPhone and iPad

---

## ✅ Code Quality Highlights

This project keeps the implementation intentionally focused and readable.

- Clear separation between **model**, **view model**, **view**, and **data source**
- Reusable UI components for different map-related interactions
- State-driven updates for map camera and selected locations
- Clean SwiftUI composition with dedicated subviews
- Good foundation for future enhancements such as persistence, filtering, and live location services

---

## 📍 Included Sample Locations

The current dataset includes multiple well-known landmarks across different cities, such as:

- Colosseum
- Pantheon
- Trevi Fountain
- Eiffel Tower
- Louvre Museum
- Statue of Liberty
- Big Ben
- Great Wall of China
- Sydney Opera House
- Machu Picchu

This makes the project useful as both a **MapKit learning project** and a strong **portfolio piece** focused on map-based interaction design.

---

## ⚙️ Getting Started

### Requirements

- Xcode 16.2+
- iOS 18.2+
- macOS with support for recent iOS simulators

### Installation

1. Clone the repository:

```bash
git clone https://github.com/juanperort-dev/MapKit.git
```

2. Open the project in Xcode:

```bash
open MapApp.xcodeproj
```

3. Build and run on a simulator or physical device

> No external API keys or third-party dependencies are required.

---

## 🚧 Roadmap

- [ ] Add dark mode refinements
- [ ] Add user location support
- [ ] Add search and filtering by city or landmark
- [ ] Add favorites persistence
- [ ] Add route/directions support
- [ ] Improve accessibility and VoiceOver support
- [ ] Replace placeholder `ContentView` or remove unused template files
- [ ] Add screenshots and a demo GIF to the README

---

## 👨‍💻 Author

**Juan José Perálvarez Ortiz**

iOS developer focused on building clean, scalable, and modern applications for Apple platforms.

- [Portfolio](https://juanperort.dev)
- [LinkedIn](https://www.linkedin.com/in/juanperort/)
