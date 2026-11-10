# Flutter Week 8 – Animations

Two Flutter examples introducing explicit animations and common animation effects.

## Exercises

| File | Description |
|---|---|
| `8(a)` | Uses an `AnimationController` and tweens to animate size, color and rotation |
| `8(b)` | Demonstrates multiple animation types, including fade, slide, scale, rotation and size |
| `output_8a.jpeg`, `output_8b.jpeg` | Screenshots of the exercise outputs |

## Concepts covered

- `SingleTickerProviderStateMixin` and animation controllers
- `Tween` and `ColorTween`
- `CurvedAnimation` and animation curves
- Fade, slide, scale, rotation and size transitions
- Coordinating animation values over time
- Disposing controllers when a state object is removed

## Run the examples

The repository contains extensionless Dart source files and output screenshots rather than a standalone Flutter project.

```bash
flutter doctor
flutter create flutter_animation_demo
cd flutter_animation_demo
```

Copy the selected source into `lib/main.dart` and run `flutter run`.

## Learning objective

Learn how an animation controller drives changing values and how Flutter uses those values to animate widget appearance and movement.
