<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/GridLights/.github/main/profile/assets/lockup-white.png">
  <img alt="GridLights" src="https://raw.githubusercontent.com/GridLights/.github/main/profile/assets/lockup-black.png" width="560">
</picture>

### Responsive light for the built environment

We turn ordinary surfaces — ceilings, walls, fixtures — into programmable, scene-reactive light.
Engineered end to end, in-house: from the copper on the PCB to the cloud that fleets it.

<br/>

![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat&logo=kicad&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat&logo=stmicroelectronics&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat&logo=espressif&logoColor=white)
![nRF / LTE-M](https://img.shields.io/badge/nRF9151%20LTE--M-00A9CE?style=flat&logo=nordicsemiconductor&logoColor=white)
![WLED](https://img.shields.io/badge/WLED-000000?style=flat&logo=arduino&logoColor=white)
![AWS IoT](https://img.shields.io/badge/AWS%20IoT-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat&logo=threedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Quasar](https://img.shields.io/badge/Quasar-1976D2?style=flat&logo=quasar&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)

</div>

---

## The thesis

The lighting industry is obsessed with lumens, color-temperature charts, and compliance specs. We think light is **atmosphere, identity, and experience** — and that the surfaces already around us are an untapped, intelligent canvas. So we build the whole stack required to make light responsive: sensing, control, and software that treats a room like a programmable instrument.

## What we engineer

A vertically integrated hardware company. Every layer is designed, written, and version-controlled here — no black boxes between the silicon and the screen.

| Layer | What we do |
|---|---|
| **Electrical / ECAD** | Custom multi-layer PCBs in KiCad — LED drivers, power, sensor front-ends, castellated edge-connect modules. |
| **Embedded firmware** | Real-time, multi-MCU systems in C/C++ across STM32 and ESP32, plus our own WLED forks and usermods. |
| **Connectivity** | Addressable LED buses, board-to-board UART links, and cellular LTE-M telemetry to the cloud. |
| **Cloud & data** | AWS-backed device fleets, multi-product dashboards, and OTA/observability for hardware in the field. |
| **Apps & simulation** | Cross-platform operator apps and real-time 3D tools for designing installations before they're built. |

## Engineering depth

**Multi-brain embedded architecture.** Our luminaires run a two-processor design: an **STM32** sensor-and-policy brain executing a real-time automation engine, linked over **UART** to an **ESP32** running our WLED fork for addressable LED control and app connectivity — with a dedicated **STM32 audio-DSP coprocessor** for sound-reactive sensing. Sensor fusion, weather reactivity, and battery management ship as first-class WLED usermods.

**Model-based, AI-first hardware.** Our ECAD repo is built for machine-assisted development. A single YAML model is the source of truth for the electrical *and* mechanical design; tooling auto-aggregates BOMs, enriches them with live distributor pricing, rolls up per-unit cost at volume, and runs CAD geometry analysis (wall thickness, draft, undercuts, tonnage) straight from Onshape. **KiBot CI runs ERC, DRC, and fab-output generation on every push**, and schematics are extracted into a machine-readable firmware contract that downstream repos pin by git SHA.

**Cellular IoT, silicon to dashboard.** Battery-aware **nRF9151 / LTE-M** edge devices stream telemetry into **AWS IoT**, surfaced through fleet dashboards — built for commercial environments where Wi-Fi isn't an option.

**Software-defined light.** From a **Three.js** authoring-by-demonstration workbench that lets designers compose venue scenes in 3D, to AI agents that generate lighting automation policies conversationally, to a cloud agent that gardens our repos (PR digests, Sentry triage) every night — the tooling is as engineered as the products.

## Products

- **GridLights** — programmable RGBW fixtures that retrofit standard T-bar ceiling grids. No electrician, no construction. WLED-compatible, app- and automation-controlled.
- **GridLights Studio** — bespoke architectural lighting, including large-scale and structurally-integrated installations.
- **Sol Spektrum** — a photonic stimulation device. Same engineering DNA, different domain.
- **Primer Wand** — *"No Spill. By Design."* A precision-engineered consumer product.

## Built on open source

We stand on — and contribute back to — [**WLED**](https://github.com/wled/WLED), [**PlatformIO**](https://platformio.org/), and [**KiCad**](https://www.kicad.org/). Open firmware and open tools, hardened for production and the field.

<div align="center">
<br/>

**[gridlights.co](https://gridlights.co)** · Houston, TX

*Responsive light for the built environment.*

</div>
