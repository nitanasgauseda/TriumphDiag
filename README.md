# TriumphDiag

A small, free Android app for diagnosing Triumph motorcycles through a cheap
Bluetooth OBD adapter (ELM327 / OBDLink). No cables, no PC, no account — it runs
entirely on your phone.

> Tested on a 2021 Triumph Trident 660. Many other Triumph models use the same
> diagnostic protocols and should work too.

---

## Features

- **Auto-detect ECU** — tries all known Triumph protocols, no model picking
- **Fault codes** — reads **active** faults with plain-language descriptions, and
  clearly says when there are none; stored/history codes are kept out of the way
- **Clear fault codes**
- **Service interval reset** — shows the current readings first, then lets you set
  the next service distance (km) and date (by date, by years, or by days from
  today), and reads the value back to confirm the write
- **Live data** with mini real-time graphs (RPM, coolant temp, throttle, etc.)
- **Battery / charging** voltage with a plain reading
- **Share report** — send any result as text (email, messaging, notes)
- Clean screen, separate log window, and a result window after each operation

---

## What you need

| | |
|---|---|
| **Bike** | A Triumph with a diagnostic port |
| **Adapter** | A Bluetooth OBD adapter — an **OBDLink LX** or a generic **ELM327 Bluetooth** dongle |
| **Phone** | Android 6.0 (Marshmallow) or newer |

---

## Install

1. Download the latest `TriumphDiag-vX.Y.apk` from the
   [**Releases**](../../releases/latest) page onto your phone.
2. Tap the downloaded file. Android will warn that installs from this source are
   blocked — tap **Settings**, turn on **Allow from this source**, go back and tap
   **Install**. (This is normal for apps outside the Play Store.)
3. Open the app once it finishes installing.

## Use

1. Plug the adapter into the bike's diagnostic port and turn the **ignition ON**.
2. On the phone, open **Bluetooth settings** and **pair** the adapter
   (PIN is usually `1234` or `0000` if asked).
3. Open TriumphDiag, pick the adapter if needed, and tap **Connect**.
4. For live data and the battery check, start the engine.

---



---

## Disclaimer

This is a community tool, **not** an official Triumph product and is not affiliated
with or endorsed by Triumph Motorcycles Ltd. Use it at your own risk. The author
accepts no responsibility for any damage to your motorcycle, its modules, or data.
Do not write values you do not understand. Clearing codes or resetting the service
interval does not fix the underlying cause of a fault.
