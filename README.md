# Screenlake for Meta Quest: Privacy Policy

Last updated: 18 November 2026

Screenlake is made by Julian Mautner. It shows the screens of your own PC in your Meta Quest headset. This policy explains what the Screenlake headset app handles and where that data goes.

## In short

- Screenlake connects only to your own PC, the one running the Screenlake host software that you pair with the headset.
- There are no servers for Screenlake and we receive none of your data.
- The app has no analytics, no advertising and no tracking, and it shares nothing with third parties.

## What the app uses, and why

| Data | What it is used for | Where it goes |
|---|---|---|
| Your PC's screens, sound, mouse and keyboard input | Streaming your PC's monitors into the headset and controlling the PC from it | Between the headset and your own PC only |
| Avatar camera (Horizon OS) | Your picture as the PC's webcam, for video calls on the PC | Video goes to your own PC, only while streaming and only while an app on the PC uses the camera |
| Microphone | Your voice as the PC's microphone while you stream, and hearing a double clap (a shortcut) | Audio goes to your own PC, only while streaming; clap detection runs on the headset |
| Spatial data (Space Setup rooms and anchors) | Knowing which scanned room you are in, and keeping screens where you placed them | Processed on the headset; room and anchor identifiers, the names you give rooms and your screen positions are stored on your own PC |
| Hand and controller tracking | Pointing, clicking and arranging screens | Processed on the headset; only the resulting mouse movements and clicks go to your PC |
| Device information (headset model, battery level, whether the headset is worn, a random identifier created by the app) | Telling your headsets apart, showing battery on the PC, pausing the stream when you take the headset off | Your own PC only |
| Smart home controls (optional) | Showing Home Assistant devices you placed in the room and switching them | The headset sends your commands to your own PC, which talks to your own Home Assistant |

Apart from the avatar camera, the app does not access the headset's cameras. The passthrough view of your room is shown by the Quest's system; Screenlake never receives those images.

## What is stored on the headset

Your settings, the PCs you paired with, the pairing certificates and your per-screen view preferences are stored in the app's private storage on the headset. Uninstalling the app deletes them.

## What is stored on your PC

Your layouts, rooms, screen positions and smart home placements are stored by the Screenlake host software on your own PC, under your control. You can delete them there at any time.

## Network

The headset looks for Screenlake PCs on your local network and connects to the PC you choose. Pairing needs your approval on the PC, and the control connection between headset and PC is encrypted. The video and sound stream inside your network is not encrypted yet; use Screenlake on networks you trust. No data leaves your network unless you connect to your PC over a network you set up yourself (for example a VPN).

## Meta

Meta's own data handling for the Quest and the Meta Horizon Store is covered by Meta's privacy policy. Screenlake does not use Meta's platform services for user profiles, friends or similar data.

## Children

Screenlake is not directed at children under 13 and does not knowingly process their data.

## Changes

If a future version of Screenlake handles data in a new way, this policy is updated before that version is released. The date at the top shows the latest change.

## Contact

Questions about this policy: open an issue at https://github.com/julianmautner/screenlake-privacy/issues
