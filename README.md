# Flutter Learning Projects

A small collection of Flutter practice work created while learning Dart, Flutter UI development, state updates, dialogs, and interactive mobile interfaces.

> **Repository status:** Learning workspace. The Flashcard Quiz App has source code in this repository. An earlier Random Quote Generator experiment was also part of this workspace, but its reproducible source is not currently included.

## Flashcard Quiz App

A Flutter flashcard interface with a card-flip interaction.

Current features:

- Question and answer flashcards
- Tap-to-flip animation
- Previous and next navigation
- Add new flashcards
- Edit existing flashcards
- Delete flashcards
- In-memory card state
- Material 3 interface

Main source:

```text
flashCard Quiz App/main.dart
```

The project uses:

```yaml
flip_card: ^0.7.0
```

> Cards are stored in memory in the current version, so user-created cards are not saved after the app closes.

## Run the app

Requirements:

- Flutter SDK
- Dart 3 compatible SDK

From the Flashcard app directory:

```bash
flutter pub get
flutter run
```

## Repository layout

```text
Flutter-project/
├── flashCard Quiz App/
│   ├── main.dart
│   ├── pubspec.yaml
│   └── README.md
├── .gitignore
└── README.md
```

Generated Flutter folders such as `build/` and `.dart_tool/` are intentionally excluded from version control.

## Notes

This repository documents hands-on Flutter practice rather than production-ready mobile applications.

Useful next improvements would be persistent flashcard storage, a standard Flutter project layout, and widget tests.

## Author

**Anfal Qureshi**  
Computer Science student exploring mobile development alongside web, backend, and machine-learning projects.
