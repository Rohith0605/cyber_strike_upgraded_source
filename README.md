# Cyber Strike — upgraded Flutter space shooter

## Features
- Redesigned layered player fighter with wing fins, cockpit, engine flame, and shield effect.
- Score progression: Level 1 (0–19), Level 2 (20–49), Level 3 (50–99), Level 4 (100+).
- Four visually distinct enemy types: scout, interceptor, tank, and phantom.
- Enemy health, collision handling, score values, and increasing spawn pressure.
- Falling pickups: twin laser, spread shot, overdrive cannon, and shield.
- Pickups activate by touching the player's ship. Weapon upgrades temporarily change projectile patterns and fire rate.
- Pause/resume/restart, health HUD, level notifications, particles, starfield, neon grid.
- Flutter/Dart only; no external game engine or image assets required.

## Run on Windows
1. Install Flutter and verify `flutter --version`.
2. Extract this folder and open it in VS Code.
3. Run:
   ```powershell
   flutter pub get
   flutter run -d chrome
   ```
4. For a web build:
   ```powershell
   flutter build web
   ```
   Output is generated in `build/web`.

## Controls
Drag with a mouse or finger to move. Weapons fire automatically.
