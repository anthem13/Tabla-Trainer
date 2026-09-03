# Tabla Trainer

A simple iOS SpriteKit project created as a starting point for a tabla training app.

> This project is currently an early SpriteKit prototype. The default scene demonstrates touch interaction with animated shapes and does not yet include tabla-specific lessons, rhythms, or audio playback.

## Features

- SpriteKit-based iOS application
- Touch interaction for began, moved, ended, and cancelled touches
- Animated touch indicators with different colors:
  - Green when a touch begins
  - Blue while a touch moves
  - Red when a touch ends
- Basic unit-test and UI-test targets
- Portrait and landscape orientation support
- Hidden status bar and SpriteKit debug statistics

## Requirements

- macOS
- Xcode
- An iOS simulator or physical iOS device

The project was originally created with Xcode 8.1 and Swift 3. It may require project migration or compatibility updates in modern versions of Xcode.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/anthem13/Tabla-Trainer.git
   cd Tabla-Trainer
   ```

2. Open the Xcode project:

   ```bash
   open "Tabla Trainer.xcodeproj"
   ```

3. Select the `Tabla Trainer` scheme.

4. Choose an iOS simulator or connected device.

5. Build and run the app with `Cmd+R`.

## Project Structure

```text
Tabla-Trainer/
├── Tabla Trainer/
│   ├── AppDelegate.swift
│   ├── GameScene.swift
│   ├── GameScene.sks
│   ├── GameViewController.swift
│   ├── Actions.sks
│   ├── Assets.xcassets
│   └── Info.plist
├── Tabla TrainerTests/
│   └── Tabla_TrainerTests.swift
├── Tabla TrainerUITests/
│   └── Tabla_TrainerUITests.swift
└── Tabla Trainer.xcodeproj/
```

## Testing

Run the test suite in Xcode using:

```text
Product > Test
```

or press `Cmd+U`.

The repository includes targets for:

- Unit tests
- UI tests
- Performance-test scaffolding

The included tests are currently Xcode-generated examples and should be expanded as tabla-training functionality is added.

## Roadmap

- Add tabla bols and rhythm patterns
- Add audio playback and recording
- Add tempo controls and metronome support
- Add practice exercises and progress tracking
- Add visual feedback for timing accuracy
- Add custom tests for training workflows
- Update the project to current Swift and Xcode versions

## License

No license has been specified for this repository. Contact the repository owner before redistributing or incorporating the code into another project.
