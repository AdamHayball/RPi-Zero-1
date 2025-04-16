## Raspberry Pi Zero (Non-WH) – Minimal Hardware, Maximum Use

This project explores squeezing real-world functionality out of the original Raspberry Pi Zero (non-WH model)—a single-core, low-memory board once considered obsolete. Using only **Raspbian Lite 22.04**, and with **no HDMI output connected**, the Pi Zero is transformed into a silent, headless workhorse running multiple lightweight but useful services on the home network.

### Setup Details

- The only data Micro-USB port is connected to a Micro-B to Ethernet (10/100) adapter, providing stable wired LAN access.
- The Pi is housed in a custom 3D-printed case, giving it a clean, permanent spot in the network setup.

---

## Retro Game Server (EmulatorJS)

Using **EmulatorJS**, the Pi serves a single-page emulator portal. Just drag and drop your ROMs into a web browser and start playing instantly.

**Emulates:**
- NES, SNES, GBA, Genesis, Atari, and more
- Fully browser-based (no installs needed)

<p align="center">
  <img src="[https://github.com/AdamHayball/MultiBootRescueDrive/blob/main/usbsticks.jpg](https://github.com/AdamHayball/RPi-Zero-1/blob/main/ejs.jpg)" alt="Old USB Sticks" height="200px" width="200px" />
</p>

---

## Ad Blocking for Entire Network (Pi-hole)

By running **Pi-hole**, the Pi Zero becomes a DNS-level ad blocker, scrubbing ads and trackers from all connected devices.

**Benefits:**
- Removes ads across phones, PCs, smart TVs
- Works silently in the background
- Saves bandwidth and boosts privacy

<!-- Add screenshot here -->

---

## Experimental Crypto Mining (cpuminer-multi)

Popular mining software like XMRig couldn’t compile on the Pi Zero's ARMv6 CPU—but **cpuminer-multi** worked!

**Achieved:**
- Mined Quark and Qubit via Zergpool
- Fully functional (but very slow) miner
- Used purely for testing and fun

<summary>CPU Load Warning</summary>
<!-- Add CPU usage graph or top output here -->

> **Note:** This is not profitable. It’s an exercise in pushing low-end hardware to its limits.

---

## Project Goals

- Use only Raspbian Lite 22.04
- Run in headless mode (no HDMI display connected)
- Maintain all network connectivity via Micro-B to Ethernet adapter
- Contain the Pi in a custom 3D-printed enclosure
- Maximize the functionality of the Pi Zero using minimal resources

---

## Summary Table

| Service         | Purpose                      | Status         |
|-----------------|------------------------------|----------------|
| CUPS            | Print sharing                | ✅ Working      |
| EmulatorJS      | Drag-and-drop retro games    | ✅ Working      |
| Pi-hole         | DNS-level ad blocker         | ✅ Working      |
| cpuminer-multi  | Experimental crypto mining   | ✅ Working (slow) |
| 3D-printed case | Custom housing for stability | ✅ Functional   |
| Ethernet via USB| Network access without Wi-Fi | ✅ Stable       |

