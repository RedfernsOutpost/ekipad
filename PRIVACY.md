# Ekipad Privacy Policy

*Effective: November 22, 2026*

This policy covers **Ekipad** for iPhone and **Ekipad Host** for Mac (together, "Ekipad").

## The short version

Ekipad doesn't collect, store or share any personal data. It has no accounts, no analytics, no advertising and no
servers. Everything it does happens on your iPhone and your own Mac.

## What Ekipad uses, and why

| What | Why | Where it goes |
|---|---|---|
| **Bluetooth** | To send controller input from your iPhone to your Mac | Directly between your two devices |
| **Local network / peer-to-peer Wi-Fi** | To find your Mac and send input and the screen stream with low delay | Directly between your two devices. Ekipad doesn't use the internet. |
| **USB cable** (when plugged in) | The same, over the cable | Directly between your two devices |
| **Camera** (iPhone, only when you tap *Scan*) | To read the pairing QR code shown on your Mac | Processed on the phone. No images are saved or sent. |
| **Motion sensors** (iPhone, only if you turn on Gyro) | To aim by tilting the phone | Sent only to your paired Mac, as controller input |
| **Accessibility / input control** (Mac) | To press the keys and move the mouse your controller is mapped to, and to create the virtual game controller | Stays on your Mac |
| **Screen Recording** (Mac, only if you turn on Screen Share) | To show your Mac's screen on your paired phone | Streamed only to your paired phone, over your local connection |
| **Update check** (Mac download version only) | About once a day, Ekipad Host reads the public list of releases on GitHub to see if a newer version exists. Turn it off in the menu bar: **Check for Updates Automatically**. | A plain web request to GitHub. It sends nothing about you; like any web request, GitHub sees your IP address and the app's version. See GitHub's privacy statement. |

## What's stored on your devices

- Your settings, button layouts and routes.
- A cryptographic key pair for each device (in the Keychain), used to pair your phone and Mac securely. Your
  phone remembers your Mac's public key, and your Mac remembers which phones you've allowed. Your device names
  appear in each other's apps so you can tell them apart.

This information never leaves your devices except between your own paired phone and Mac. Deleting the app
removes it (the Keychain key may remain until you reset the device or remove it in Keychain Access).

## What Ekipad doesn't do

- No data is sent to us or to anyone else. We have no servers that receive data from the app. The only internet
  request is the Mac app's update check described above, which downloads public information and uploads none.
- No tracking, no advertising identifiers, no third-party SDKs, no crash or analytics reporting.
- No data is sold or shared.

## Children

Ekipad is suitable for all ages and collects no information from anyone, including children.

## Changes

If this policy changes, the new version will be posted at this address with a new effective date. Because Ekipad
collects no data, a change could never apply retroactively to data we hold: we hold none.

## Contact

Questions: open an issue at <https://github.com/RedfernsOutpost/ekipad/issues>.
