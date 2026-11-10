# Wanted Stuff (Forge 1.20.1)

Things Mojang wanted to add but never did.

- **Sharks**: spawn in oceans (Easy+), hunt players, drop Raw Shark Meat and Shark Teeth. Spawn egg included.
- **Bluestone**: ore (generates underground), Bluestone Dust, Block of Bluestone (an inverter: gives power 15 until it receives redstone power), Bluestone Lamp.
- **Vertical slabs** for 40 materials (stone types, bricks, copper, quartz, every plank). Craft 3 blocks in a column -> 6, or use the stonecutter -> 2. Place two in one block to make a full block; they can be waterlogged.

Everything is in the "Wanted Stuff" creative tab.

## Building the jar
1. Install JDK 17.
2. Get the Forge 1.20.1 MDK (47.3.0) from files.minecraftforge.net and copy its `gradlew`, `gradlew.bat` and `gradle/` folder into this folder (or install Gradle 8.1.1 and run `gradle wrapper`).
3. Run `./gradlew build` (Windows: `gradlew build`).
4. The mod is in `build/libs/WantedStuff-1.0.0.jar`. Put it in your `mods` folder with Forge 1.20.1.

## Building with GitHub (no install needed)
1. Create a free GitHub repo and upload everything in this folder (including `.github`).
2. Open the **Actions** tab, pick "Build Wanted Stuff", and wait for the green check.
3. Open the finished run and download **WantedStuff-jar** from Artifacts. Unzip it to get the .jar.
