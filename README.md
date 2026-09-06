# Infinity Wellness Workspace

This workspace contains the Flutter Infinity Wellness shell and its Vue/Capacitor Reward Shop prototype.

| Folder | Purpose |
| --- | --- |
| `Infinity_App-main/` | Flutter main application and embedded Reward Shop host |
| `mini-app/` | Vue Reward Shop, Vercel site, and standalone Capacitor Android app |
| `output/apk/` | Local debug APK handoff files |

See [`mini-app/INTEGRATION.md`](mini-app/INTEGRATION.md) for the architecture, offline behavior, configuration and testing flow. See [`mini-app/README.md`](mini-app/README.md) for build commands.

The complete implementation and operations guide is [`Infinity_App-main/context/reward-shop-capacitor-guide.md`](Infinity_App-main/context/reward-shop-capacitor-guide.md).

## Vercel

When importing into Vercel, choose `mini-app` as the Root Directory. Framework preset: Vite. The committed `mini-app/vercel.json` already sets the build command and output directory.

Current deployment: https://flutter-mini-f42jdfr8z-tunaunglwin-devs-projects.vercel.app/
