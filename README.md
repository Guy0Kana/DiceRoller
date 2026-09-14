# DiceRoller 

A SwiftUI app that lets you roll one or more virtual dice with a tap. Add or remove dice to simulate different games, and roll each die independently for a random result between 1 and 6.

## Features

- **Adjustable dice count** — add or remove dice (1 to 5) with animated transitions
- **Independent rolls** — each die rolls to a random face (1–6) on tap
- **SF Symbols dice faces** — clean, native-looking dice icons
- **Gradient background** — simple, polished visual styling with a white tint

## Screens

- `ContentView` — manages the number of dice on screen and the add/remove controls
- `DiceView` — renders a single die and handles its roll animation

## Requirements

- Xcode 15+
- iOS 17+
- Swift 5.9+

## Getting Started

1. Clone the repository
   ```bash
   git clone <repo-url>
   ```
2. Open `DiceRoller.xcodeproj` (or `.xcworkspace`) in Xcode
3. Build and run on a simulator or device

## Tech Stack

- SwiftUI
- `@State` for reactive UI updates

## License

MIT
