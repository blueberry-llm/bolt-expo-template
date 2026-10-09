# Expo Template

A starter template for [bolt.diy](https://github.com/stackblitz-labs/bolt.diy).

## Purpose

This template is designed for use with **<https://github.com/stackblitz-labs/bolt.diy>**. bolt.diy fetches
these files at runtime and imports them into a fresh WebContainer project when you ask for an Expo + React Native project,
so everything here needs to install and build with no extra setup.

Modified by [Dustin Loring](https://github.com/Dustinwloring1988) (Dustinwloring1988) in October 2026.

## Stack

| Package | Version |
| --- | --- |
| Expo | ^57.0.27 |
| React | ^19.0.0 |
| React-DOM | ^19.0.0 |
| React Native | ^0.87.1 |
| TypeScript | ~5.8.3 |

Node 20 or newer is required.

## Commands

```bash
npm install   # install dependencies
npm run dev   # EXPO_NO_TELEMETRY=1 expo start — dev server
npm run build:web # expo export --platform web — web export
npm run lint # expo lint — run linter
```

## About this template

An Expo + React Native bare project with React 19 and TypeScript. Includes Expo Router for navigation,
and Expo modules for camera, haptics, location, and other native device features.

## Upgraded to Expo 57, React Native 0.87, React 19 (October 2026)

This template was already on the latest Expo SDK versions:
- **Expo**: ^57.0.27 (latest)
- **React Native**: ^0.87.1 (latest)
- **React**: ^19.0.0 (latest)

No major version jumps were needed because the template was already on the latest Expo SDK. All Expo modules
(camera, haptics, blur, linear gradients, linking, splash screen, symbols, web browser, constants, fonts)
are at their latest compatible versions for Expo 57.

TypeScript ~5.8.3 is compatible with Expo 57 and React 19.

## Verification

- `npm install` completes successfully with all Expo 57 packages
- `npm run dev` starts the Expo dev server
- `npm run build:web` exports the web platform

## Notes

Expo 57 is the latest stable SDK as of October 2026. The template uses `expo-router` for file-based routing.
Native module permissions should be configured in `app.json` or `app.config.js` as needed.
**
<tool_call>