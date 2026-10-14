<h1 align="center">Utku Berkay TAN</h1>

<p align="center">
  <b>Autonomous systems · Offensive security · Embedded hardware</b><br>
  <sub>Aerospace &amp; Aviation Technologies student — Özdemir Bayraktar Havacılık ve Uzay Teknolojileri MTAL</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/focus-UAV%20autonomy-0b1b2b?style=flat-square" />
  <img src="https://img.shields.io/badge/focus-red%20team-7a1121?style=flat-square" />
  <img src="https://img.shields.io/badge/focus-embedded%20%26%20PCB-1c4b3a?style=flat-square" />
</p>

---

### whoami

I build things that fly and things that get in. Most of my work sits where software meets hardware:
flight controllers, computer vision on the edge, low-level Windows internals, and PCBs I actually
have to solder afterwards.

Started with drones, ended up caring about the whole stack underneath them: MAVLink packets,
the autopilot's control loop, the SoC running inference, the radio link carrying it all, and the
security of every hop in between.

Long game: defense industry engineering.

---

### What I work on

| Domain | What that means in practice |
|---|---|
| **UAV & Autonomy** | Fixed-wing / VTOL airframes, Pixhawk + ArduPilot, PyMAVLink & MAVSDK offboard control, PID tuning, YOLO-based detection and tracking on NVIDIA Jetson / Raspberry Pi |
| **Offensive Security** | Windows internals, PE format, process injection, MITRE ATT&CK mapping, C2 tooling, encryption primitives, wordlist & credential auditing utilities |
| **Embedded & Hardware** | KiCad schematic + PCB design, STM32, ESP32 |
| **AI / Personal Agents** | FastAPI backends, vector databases, local LLM integration, mobile clients |
| **Systems & Infra** | Linux, C, self-hosted homelab, networking and traffic-shaping experiments |

---

### Selected work

| Project | What it does | Stack |
|---|---|---|
| **[TEAM_BERKUT-OPENSOURCE](https://github.com/utkuberkaytan/TEAM_BERKUT-OPENSOURCE)** | Open-source codebase from Team Berkut — autonomous UAV competition stack including mission planning, telemetry handling, and computer vision. | `Python` `MAVLink` `YOLO` |
| **[usb-lisance-lock](https://github.com/utkuberkaytan/usb-lisance-lock)** | Hardware-bound software licensing — RSA-signed licenses tied to a USB device serial, so a key only works on the physical stick it was issued for. | `C#` `.NET` `RSA` |
| **[PassSmith](https://github.com/utkuberkaytan/PassSmith)** | Lightweight wordlist generator for pentesting and password auditing. Feed it keywords, it builds realistic candidate passwords. | `C` |
| **[xor_enc_to_arraykey](https://github.com/utkuberkaytan/xor_enc_to_arraykey)** | XOR encryption utility that encodes payloads into obfuscated array-key format — useful for shellcode staging and AV evasion research. | `C` |
| **[file_pumper](https://github.com/utkuberkaytan/file_pumper)** | Inflates a file to an arbitrary size with junk data — useful for testing size-based AV/EDR bypasses and upload filters. | `Python` |
| **[dualsense-toolkit](https://github.com/utkuberkaytan/dualsense-toolkit)** | USB control panel and CLI for the Sony DualSense on Windows — haptics, lightbar, triggers, straight over the wire. | `Python` `USB HID` |
| **[xinput-toolkit](https://github.com/utkuberkaytan/xinput-toolkit)** | Xbox controller control panel for Windows built directly on the XInput API. No third-party dependencies. | `Python` `XInput` |

<sub>More in <a href="https://github.com/utkuberkaytan?tab=repositories">repositories</a> — including private UAV, AI, and red-team work.</sub>

---

### Toolbox

<p>
  <img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-000000?style=flat-square&logo=linux&logoColor=white" />
</p>
<p>
  <img src="https://img.shields.io/badge/ArduPilot-4B8BBE?style=flat-square" />
  <img src="https://img.shields.io/badge/PX4-00A6D6?style=flat-square" />
  <img src="https://img.shields.io/badge/MAVLink-FF6F00?style=flat-square" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/YOLO-111F68?style=flat-square" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
</p>
<p>
  <img src="https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white" />
  <img src="https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white" />
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white" />
  <img src="https://img.shields.io/badge/Jetson-76B900?style=flat-square&logo=nvidia&logoColor=white" />
  <img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white" />
</p>
<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
</p>

---

### Currently

- **Mini sumo robotics** — STM32-based combat robot, custom sensor + motor driver board
- **AI personal agent (EDITH)** — FastAPI + vector DB backend with a mobile client
- **Windows internals** — PE parsing, memory mapping, injection primitives
- **VTOL** flight tuning and multi-modal (RGB + thermal) detection pipelines
- Deepening in **C** — memory management, low-level tooling, no safety net

---

<p align="center">
  <a href="mailto:utkutanberkay@gmail.com"><img src="https://img.shields.io/badge/email-333?style=flat-square&logo=gmail&logoColor=white" /></a>
</p>

<p align="center"><sub>Good vibecoder btw.</sub></p>

---

<p align="center">
  <sub><code>curl -sL https://raw.githubusercontent.com/utkuberkaytan/utkuberkaytan/main/card.txt</code></sub>
</p>
