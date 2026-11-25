# Awesome OSC [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of Open Sound Control (OSC) resources, tools, libraries, and implementations

OSC is a protocol for communication among computers, sound synthesizers, and other multimedia devices that is optimized for modern networking technology. It enables real-time control and data exchange across networks with high precision.

## Contents

- [Specifications & Learning](#specifications--learning)
- [Controllers](#controllers)
- [Debugging & Utilities](#debugging--utilities)
- [Game Engines & Creative Coding](#game-engines--creative-coding)
- [Audio & Music Software](#audio--music-software)
- [Code Libraries](#code-libraries)
- [IoT, Embedded & Hardware](#iot-embedded--hardware)
- [Example Projects & Templates](#example-projects--templates)

## Specifications & Learning

- [OpenSoundControl.org](https://opensoundcontrol.stanford.edu/) - Official site with specification 1.0 and comprehensive documentation
- [OSC Specification 1.0](https://opensoundcontrol.stanford.edu/spec-1_0.html) - The official protocol specification
- [Wikipedia: Open Sound Control](https://en.wikipedia.org/wiki/Open_Sound_Control) - Overview with OSC vs MIDI comparison, addressing schemes, bundles, and time tags
- [OpenSoundControl.org Page List](https://opensoundcontrol.stanford.edu/page-list.html) - Comprehensive directory of OSC resources

## Controllers

### Touch & Desktop Control Surfaces

- **[TouchOSC](https://hexler.net/touchosc)** - *Active / Paid*  
  The modular touch control surface standard. Actively maintained for iOS, Android, Windows, and macOS with extensive MIDI/OSC capabilities.

- **[Open Stage Control](https://openstagecontrol.ammd.net/)** - *Active / Open Source*  
  Browser-based OSC/MIDI controller. Runs as a local web server and works with any modern touch device. Highly scriptable and customizable.

- **[OSC Pilot](https://oscpilot.com/)** - *Active / Paid*  
  High-performance, GPU-accelerated control surface for Windows/macOS, designed for touring visual artists and live performance.

- **[OSCAR](https://www.oscar-app.de/)** - *Active*  
  Modern, user-friendly controller app for iOS and Android with pre-built layouts for REAPER and RME TotalMix.

- **[OSCAR by createwithoscar](https://www.createwithoscar.com)** - *Active / Open Source*  
  Design control surfaces in the browser, then open them on any phone or tablet with no install, or in its Android and iOS apps. Sends OSC, MIDI and DMX (Art-Net, sACN). Windows, macOS and Linux. [Source](https://github.com/trafalmejo/OSCAR).

- **[Lemur](https://www.midikinetics.com/lemur/)** - *Legacy*  
  Multitouch OSC/MIDI controller on iOS. Still widely used but maintenance status is limited.

## Debugging & Utilities

- **[Protokol](https://hexler.net/protokol)** - *Active / Free*  
  Essential debugging tool. Lightweight utility to monitor incoming OSC and MIDI traffic in real-time.

- **[Packet Sender](https://packetsender.com/)** - *Active / Open Source*  
  Network testing tool for manually sending UDP/TCP packets. Great for testing OSC connectivity.

## Game Engines & Creative Coding

### Unreal Engine

- **[Official OSC Plugin](https://dev.epicgames.com/documentation/en-us/unreal-engine/osc-plugin-overview-for-unreal-engine)** - Built-in to UE5 with Blueprint API
- **[UE-OSC](https://github.com/monsieurgustav/UE-OSC)** - Community alternative with additional features

### Unity

- **[OSC Jack](https://github.com/keijiro/OscJack)** - *Active*  
  Lightweight, high-performance OSC implementation for Unity (C#). Gold standard for Unity OSC.
- **[extOSC](https://assetstore.unity.com/packages/tools/input-management/extosc-open-sound-control-72005)** - *Active / Paid*  
  Robust, full-featured asset widely used in professional installations.

### Godot

- **[GodOSC](https://github.com/afarra6/godOSC)** - *Active*  
  GDScript implementation providing OSC send/receive via nodes for Godot 4.x.
- **[GodOSC (Asset Library)](https://godotengine.org/asset-library/asset/2538)** - Official asset library entry

### Other Platforms

- **[Max/MSP](https://cycling74.com/products/max)** - First-class OSC citizen via built-in objects
- **[Pure Data](https://puredata.info/)** - Native OSC support via bundled externals
- **Processing** - See [OpenSoundControl.org implementations](https://opensoundcontrol.stanford.edu/implementations.html)
- **[TouchDesigner](https://derivative.ca/)** - Built-in OSC support for creative coding
- **[openFrameworks](https://openframeworks.cc/)** - Multiple OSC addon implementations available

## Audio & Music Software

### DAWs with Native OSC Support

- **[REAPER](https://www.reaper.fm/sdk/osc/osc.php)** - *Active*  
  Deepest native OSC support of any DAW. Fully customizable `.ReaperOSC` control surface files.

- **[Ableton Live - Connection Kit](https://www.ableton.com/en/packs/connection-kit/)** - *Active / Free*  
  Official Max for Live pack with "OSC Send" and "OSC Receive" devices.

- **[Bitwig Studio - Mossgrabers Scripts](http://www.mossgrabers.de/software/Bitwig/Bitwig.html)** - *Active*  
  Community standard for advanced controller scripts, including generic "Open Sound Control" extension.

- **Cubase** - Native OSC control surface support
- **Unify** - Built-in OSC control capabilities

## Code Libraries

### Python

- **[python-osc](https://pypi.org/project/python-osc/)** - *Active*  
  Modern standard for Python OSC. Supports UDP/TCP with threading/forking server examples. Use this instead of legacy pyOSC.

### JavaScript / TypeScript

- **[osc.js](https://github.com/colinbdclark/osc.js/)** - *Active*  
  Works in both browser (via WebSocket) and Node.js (via UDP/Serial). Highly maintained and feature-complete.
- **[node-osc](https://github.com/MylesBorins/node-osc)** - *Active*  
  Simpler alternative specifically for Node.js users.

### C / C++

- **[oscpack](https://github.com/rossbencina/oscpack)** - *Stable*  
  Classic C++ library by Ross Bencina. Rock solid and widely used. Rarely updated because it "just works."
- **[liblo](https://liblo.sourceforge.net/)** - *Stable*  
  Standard C library. Lightweight and POSIX-compliant.

### Other Languages

- **Java** - Multiple implementations available (see OpenSoundControl.org)
- **Rust** - Community implementations on crates.io
- **Perl** - Legacy implementations available

## IoT, Embedded & Hardware

### Arduino & Microcontrollers

- **[MicroOsc](https://github.com/thomasfredericks/MicroOsc)** - *Active*  
  Modern, lightweight OSC library for Arduino, ESP8266, ESP32, and Teensy. Supports UDP and serial transport.

- **[OSC (CNMAT)](https://github.com/CNMAT/OSC)** - *Legacy*  
  Classic Arduino library. Still functional but MicroOsc is often easier for beginners.

### Professional Hardware

- **Q-Sys** - Professional audio systems with OSC control
- **RME TotalMix** - Audio interface mixing software with OSC support
- Various professional audio gear with vendor OSC documentation

### Home Automation

- OSC integration discussions in [Home Assistant community](https://community.home-assistant.io/t/integration-request-osc-open-sound-control/895723)

## Example Projects & Templates

- **[Open Stage Control & Max Tutorial](https://cycling74.com/forums/-sharing-open-stage-control-max-tutorial-examples)** - Examples combining Open Stage Control with Max/MSP
- Interactive installation examples (PRs welcome!)
- Performance rig templates (PRs welcome!)

## Maintenance & Contribution Guidelines

- Unmaintained projects are explicitly marked as **Legacy** or with maintenance status notes
- Every entry should include: platform(s), maintenance status, and primary use-case
- PRs adding currently maintained tools are preferred
- Aim to keep the list relevant for 2025 and beyond

## Contributing

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.
