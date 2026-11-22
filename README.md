# RR310 Connect — beta releases

An **unofficial** companion app for the **TVS Apache RR 310 (2022–23 model)**. Not made by or affiliated with
TVS Motor Company.

## Connects by itself — the feature everything else builds on
Pair your bike once. From then on, **switch the ignition on and the app connects on its own** — no opening the
app, no tapping "connect", the phone stays in your pocket. It reconnects after a drop, keeps listening after the
phone restarts or the app updates, and saves battery while the bike is off.

That's what makes the rest seamless:
- **Google Maps turn-by-turn on the cluster** — start navigation as usual; the arrows and distances appear on the
  dash, with rerouting and "no GPS" signs
- **Call alerts on the cluster**, answer or reject from the handlebar
- **Every ride recorded automatically** — start, stops and end detected for you; map, speed / rpm / throttle /
  temperature charts (pinch to zoom), top speed and hardest acceleration and braking marked on the map
- **Bike warnings** (engine lamp, temperature, fuel, battery) as phone notifications and on the cluster
- **Fuel log** with refuels detected automatically, **service reminders**, **bike health** learned from your own
  rides, a **ride character and score** for every ride
- Live dashboards on the phone, DJI Osmo Action recording from the handlebar

## Install (first time) — with Obtainium
In India, **Google Play Protect blocks this APK if you open it from a browser or the Files app** ("App blocked to
protect your device", only an OK button) — it does that to every sideloaded app that reads notifications, which
the app needs for Google Maps arrows. Installing through **Obtainium**, a free open-source app store that installs
straight from GitHub releases, works:

1. **Get Obtainium** from its [GitHub releases](https://github.com/ImranR98/Obtainium/releases/latest)
   (`app-arm64-v8a-release.apk` fits almost every phone from the last 6 years) or from F-Droid, and install it.
2. Open Obtainium › **Add app** › paste this page's address:
   `https://github.com/adarshrajendran0/RR310-Connect-releases` › **Add**.
3. Tap **Install**. The first time, Android asks to **allow Obtainium to install apps** — turn it on, go back.
4. If Play Protect shows **"App scan recommended"**: tap **Scan app** (takes a few seconds), or
   *More details › Install without scanning*.
5. Open **RR310 Connect**. It walks you through permissions and **Pair your bike** (ignition on, pick your
   "TVS…" cluster). Allow *Nearby devices*, *Location — all the time* and *Battery — unrestricted*: auto-connect
   needs them.

Works on Android 7 and newer. Have a computer with Android tools? `adb install RR310-Connect-v1.xx.apk` works too.

**Check the file** (optional): every release has a `.sha256` next to the APK — it must match
`sha256sum RR310-Connect-v1.xx.apk` (or any SHA-256 app on the phone).

## Updates
Once installed, updates come **from inside the app**: Settings › About › *Update available* shows what's new, then
**Download update** → **Install update**. Android may offer a Play Protect scan — tap *Scan app*. (Obtainium can
also keep it updated; either is fine — they install the same signed file.)

## Problems or ideas
Settings › About › **Report a problem** creates a file with the phone and app details — send it to the
developer in the community group. Nothing is sent anywhere automatically.

**Use at your own risk** — this is beta software. Set it up while parked; while riding, everything appears on the
cluster.
