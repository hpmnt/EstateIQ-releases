# EstateIQ Privacy Policy

*Last updated: November 5, 2026*

EstateIQ is a household and firearm inventory for Windows, with an Android app that works with it. This policy covers both. In short: **your inventory stays on your own devices.** EstateIQ has no account, no cloud service and no server of its own, and its makers never receive your data.

## What EstateIQ keeps, and where

- Everything you enter (items, photos, serial numbers, documents, values, places, notes, logs) is kept **on your Windows PC**, encrypted with AES-256-GCM under a key protected by your master password.
- The **Android app** keeps its own copy of that inventory on the phone, encrypted with the same key and once more with a key held in the phone's secure hardware (Android Keystore). It syncs directly with your PC over your home network.
- Your **master password** is never stored or sent anywhere. Fingerprint unlock uses a random secret kept in the phone's secure hardware, never your password.

## What leaves your devices

EstateIQ sends nothing about your inventory to its makers or anyone else. It connects to these services only:

| When | Sent to | What is sent |
| --- | --- | --- |
| Your phone syncs with your PC | Your own PC, on your home network | Your encrypted inventory, over an encrypted connection pinned to your PC |
| The Android app checks for a newer version of itself | Your own PC, on your home network | A request for the app version your PC carries; updates download from your PC |
| You scan a barcode EstateIQ doesn't know, or check ammunition prices (phone app, after you agree once) | UPCitemdb.com | Only the barcode number |
| You open a map | OpenStreetMap (tile.openstreetmap.org); for satellite pictures, Mapbox (api.mapbox.com) or the U.S. Geological Survey (basemap.nationalmap.gov, imagery.nationalmap.gov) | Requests for the map pictures of the area shown, as any map app makes |
| You search for an address on a map | OpenStreetMap's Nominatim (nominatim.openstreetmap.org) | The text you typed |
| The Windows app checks for updates | GitHub (github.com/hpmnt/EstateIQ-releases) | A request for the latest version number; nothing else |

These services receive your device's IP address, as with any internet request, and handle it under their own privacy policies. EstateIQ does not use analytics, advertising, tracking or crash-reporting services.

## Sharing reports

When you share a report (for example an insurance inventory), EstateIQ makes a PDF and hands it to the app you choose, such as your email app. Sending it is up to you and that app. EstateIQ keeps a log of shared reports on your own devices only.

## Permissions (Android app)

- **Camera**: to take photos of your belongings and scan barcodes. Photos are stored only in your encrypted inventory.
- **Biometrics**: for optional fingerprint unlock.
- **Internet and network state**: to sync with your PC and, when you use them, for maps and barcode lookups.
- **Install apps**: so the app can install its own updates, which it downloads from your PC and checks before installing.
- **Notifications** (optional): to tell you when your PC has a newer version of the app.
- **Location** (optional): only when you tap **Here** or **My location** to put a map pin where you're standing. The location becomes that pin in your encrypted inventory and is not sent anywhere else; EstateIQ never tracks your location in the background.

## Your control and deleting data

All of your data is on devices you control. Deleting an item deletes it from your inventory, and syncing removes it from your phone too. Removing a paired phone in the Windows app's Settings erases that phone's copy the next time it connects. Uninstalling the Android app deletes its copy. To delete everything on your PC, uninstall EstateIQ and delete the `%APPDATA%\EstateIQ` folder. Because EstateIQ's makers never receive your data, there is nothing for them to delete.

## Children

EstateIQ is not directed at children under 13 and does not knowingly collect any information from them.

## Changes

If this policy changes, the new version is posted here with a new date.

## Contact

Questions about this policy can be asked on the issue tracker at [github.com/hpmnt/EstateIQ-releases/issues](https://github.com/hpmnt/EstateIQ-releases/issues), or privately through **Security › Report a vulnerability** on that site.
