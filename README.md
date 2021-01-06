DEPRECATED: Use [Onboard-SDK-ROS](https://github.com/AutoModality/Onboard-SDK-ROS)

# DJI Onboard SDK (OSDK) 3.4

[![Join the chat at https://gitter.im/dji-sdk/Onboard-SDK](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/dji-sdk/Onboard-SDK?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## What is the DJI Onboard SDK?

The DJI Onboard SDK allows you to connect your own Onboard Computer to a [supported](https://developer.dji.com/onboard-sdk/documentation/introduction/osdk-hardware-introduction.html#supported-products) DJI vehicle or flight controller using a serial port (TTL UART). For full documentation, please visit the [DJI Developer Site](https://developer.dji.com/onboard-sdk/documentation/). Documentation regarding the code can be found in the [OSDK API Reference](https://developer.dji.com/onboard-api-reference/index.html) section of the developer website.

## Latest Release
OSDK 3.4.1 was released on 06 Dec 2017. This is a bugfix release fixing build issues for STM32, Qt, and resolving issues #212 and #221. Additionally, MIT license verbiage has been added to the open source components of OSDK. Links to DJI EULA have been added for headers accompanying closed-source binaries.

## Last Major Release

OSDK 3.4 was released on 22 Nov 2017. This release introduces support for Matrice 210 and 210 RTK. Developers will now have access to previously unavailable data such as front-facing and downward-facing stereo camera feeds through USB. Please see the [release notes](https://developer.dji.com/onboard-sdk/documentation/appendix/releaseNotes.html) for more information.

## Firmware Compatibility

| Aircraft/FC       | Firmware Package Version | Flight Controller Version | OSDK Branch            | Notes                                                                 |
|-------------------|--------------------------|---------------------------|------------------------|-----------------------------------------------------------------------|
| **M210/M210 RTK** | **1.1.0410**             | **3.2.39.12**             | **OSDK 3.4 (Current)** | Requires DJI Assistant 2 version 1.1.8                                |
|                   |                          |                           |                        |                                                                       |
| **M600/M600 Pro** | **1.0.1.65**             | **3.2.41.9**              | **OSDK 3.4 (Current)** |                                                                       |
|                   | *1.0.1.65*               | *3.2.41.9*                | OSDK 3.3               | Firmware released 10/24/17                                            |
|                   | *1.0.1.60*               | *3.2.41.5*                | *Not Supported*        | Firmware pulled due to instability                                    |
|                   | **1.0.1.20**             | **3.2.15.62**             | **OSDK 3.3 (Current)** | 3.3 backward compatiblity released 10/18                              |
|                   | 1.0.0.80                 | 3.2.15.00                 | OSDK 3.2               |                                                                       |
|                   |                          |                           |                        |                                                                       |
| **A3/A3 Pro**     | **1.7.1.5**              | **3.2.36.8**              | **OSDK 3.4 (Current)** |                                                                       |
|                   | 1.7.1.5                  | 3.2.36.8                  | OSDK 3.3               |                                                                       |
|                   | 1.7.0.5                  | 3.2.15.50                 | OSDK 3.2               |                                                                       |
|                   | 1.7.0.0                  | 3.2.15.37                 | OSDK 3.2               |                                                                       |
|                   |                          |                           |                        |                                                                       |
| **N3**            | **1.7.1.5**              | **3.2.36.8**              | **OSDK 3.4 (Current)** |                                                                       |
|                   | 1.7.1.5                  | 3.2.36.8                  | OSDK 3.3               |                                                                       |
|                   | 1.7.0.0                  | 3.2.15.37                 | OSDK 3.2               |                                                                       |
|                   |                          |                           |                        |                                                                       |
| **M100**          | 1.3.1.0                  | 3.1.10.0                  | **OSDK 3.4 (Current)** |                                                                       |



## Support

You can get support from DJI and the community with the following methods:

- Github Issues or [gitter.im](https://gitter.im/dji-sdk/Onboard-SDK)
- Send email to dev@dji.com describing your problem and a clear description of your setup
- Post questions on [**Stackoverflow**](http://stackoverflow.com) using [**dji-sdk**](http://stackoverflow.com/questions/tagged/dji-sdk) tag
- [**DJI Forum**](http://forum.dev.dji.com/en)
