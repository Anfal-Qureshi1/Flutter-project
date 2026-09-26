# Flutter Learning Projects

A small collection of Flutter experiments created while learning Dart, Flutter UI development, state updates, dialogs, and interactive mobile interfaces.

> **Repository status:** Learning workspace. The Flashcard Quiz App includes readable source code in the repository. The Random Quote Generator folder currently contains build output rather than a complete reproducible source project, so it is not presented as a finished showcase app.

## Projects

### 1. Flashcard Quiz App

A Flutter flashcard interface with a card-flip interaction.

Implemented in the current source:

- Question/answer flashcards
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

Dependency used for the flip interaction:

```yaml
flip_card: ^0.7.0
```

> Cards are currently stored only in memory, so user-created cards are not persisted after the app closes.

### 2. Random Quote Generator App

A second Flutter learning experiment is present in the repository, but the current GitHub snapshot mainly contains generated build files. The source required to reproduce and document the app properly is not currently included.

## Run the Flashcard Quiz App

Requirements:

- Flutter SDK
- Dart SDK compatible with Dart 3

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
└── Random Quote Generator App/
    └── build/
```

## Why this repository exists

This repository documents hands-on Flutter practice rather than claiming production-ready mobile applications. It is useful as a record of UI experimentation and early mobile-development work.

## Future cleanup

- Add the missing Random Quote Generator source
- Move generated build output out of version control
- Use the standard Flutter `lib/main.dart` project layout
- Add persistent storage to the flashcard app
- Add widget tests

## Author

**Anfal Qureshi**  
Computer Science student exploring mobile development alongside web, backend, and machine-learning projects.
