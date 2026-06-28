# Helldivers 2 Stratagem Panel

Ready-to-use Stream Panel GK150 profiles and helper app for Helldivers 2 stratagems.

The profiles create categorized Stream Panel pages with stratagem icons and key sequences. The helper app can update icons/data, generate profiles, import them into Stream Panel, and repair scene links after import.

## Quick Start

Use this path if you only want to install the ready-made profiles.

1. Download this repository.
2. Open **Stream Panel GK150**.
3. Open **Options**.
4. Go to **Scenes**.
5. Use the import button.
6. Select the folder:

```text
profiles\Helldivers Stratagem Panel
```

7. Import the profiles.
8. Set **Helldivers General** as the main/default scene if needed.

After import, the panel should contain categorized Helldivers pages such as Support Weapons, Orbitals, Eagles, Sentries, Backpacks, Vehicles/Exosuits, Ship, Objective, Emplacements, and Other.

## Helper App

The helper app is included here:

```text
app\HelldiversStratagemPanelBuilder.exe
```

For icon conversion actions, an SVG renderer must be installed on the system. Recommended option:

```text
Inkscape
```

Other compatible renderers may also work, but without one the app can update data and profiles but cannot convert downloaded SVG icons into usable image files.

Use it when you want to:

- update stratagem data from the Helldivers wiki
- update missing icons
- generate new Stream Panel profiles
- import generated profiles into Stream Panel automatically
- repair Stream Panel scene links after import

Recommended simple flow:

1. Run `app\HelldiversStratagemPanelBuilder.exe`.
2. Keep default source URL unless you know what you are changing.
3. Click **Run**.
4. Let the app finish.
5. If Stream Panel was running, allow the app to close and restart it when needed.

## Advanced Mode

Advanced mode exposes individual actions for debugging or partial updates.

Typical advanced order:

1. Download / convert icons.
2. Update missing icons.
3. Update stratagem data.
4. Generate Stream Panel profile.
5. Import Stream Panel profiles.
6. Repair Stream Panel links.

The app stores generated data and profiles in the repo folders so they can be reviewed or committed later.

## Included Folders

```text
app\       Built Windows helper app
data\      Generated stratagem data
icons\     Stratagem icons used by profiles
profiles\  Stream Panel GK150 profiles
```

## Notes

- This project is made for **Stream Panel GK150**.
- Stratagem data/icons may change when Helldivers 2 receives updates.
- The app is free to use. If a support popup appears after repeated use, it is voluntary and does not block usage.
- This is a fan-made utility and is not affiliated with Arrowhead, Sony, Helldivers 2, or MadDog/Stream Panel GK150.

## Support

The app is free to use. If it saved you time and you want to support future updates, you can donate here:

```text
https://buymeacoffee.com/kacperkiluk
```
