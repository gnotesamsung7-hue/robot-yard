# Robot Yard

A 3D sandbox for Voltnutt, Unit 7, Whirl, Ampera, Sparky and the factory toys, with the
8 toy factory stages and every robot's card-game powers. It runs fully offline: three.js
and the fonts are bundled inside the app.

## What's in this zip
- `app/src/main/assets/www/index.html` is the whole game. To update the game later, replace just this file.
- `app/src/main/java/.../MainActivity.java` is the full-screen Android shell around it.
- `app/robotyard-debug.keystore` signs every build with the same key, so new builds install over old ones.

## Build the APK on GitHub
1. Upload `robot-yard.zip` to the repo as it is. Don't extract it.
2. Add the workflow as `.github/workflows/build.yml`.
3. The Actions tab builds the APK. It appears under the run's Artifacts and as a Release.
