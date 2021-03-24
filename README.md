[![#yourfirstpr](https://img.shields.io/badge/first--timers--only-friendly-blue.svg)](https://github.com/nanoframework/Home/blob/master/CONTRIBUTING.md) 
[![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/nanoframework/home.svg)](http://isitmaintained.com/project/nanoframework/home "Average time to resolve an issue") [![Percentage of issues still open](http://isitmaintained.com/badge/open/nanoframework/home.svg)](http://isitmaintained.com/project/nanoframework/home "Percentage of issues still open") [![](https://badgen.net/opencollective/backers/nanoframework?label=Open%20Collective%20backers)](https://opencollective.com/nanoframework) [![Discord](https://img.shields.io/discord/478725473862549535.svg?logo=discord&logoColor=white&label=Discord&color=7289DA)](https://discord.gg/gCyBu8T)

![nanoFramework logo](resources/logo/nanoFramework-repo-logo.png)

-----
Document Language: [English](README.md) | [简体中文](README.zh-cn.md)

# .NET **nanoFramework** Home

[<img align="right" width="100px" src="https://dotnetfoundation.org/img/logo_big.svg" />](https://dotnetfoundation.org/)

This _Home_ repository is the starting point for developers that want to learn about .NET **nanoFramework**, contribute to it or opening issues.
It contains links to the various GitHub repositories used by .NET **nanoFramework**.

.NET **nanoFramework** goal is to be a platform that enables the writing of managed code applications for constrained embedded devices.
Developers can harness the familiar IDE Visual Studio and their .NET (C#) knowledge to quickly write applications without having to worry about the low level hardware intricacies of a micro-controller.

It is part of the [.NET Foundation](https://www.dotnetfoundation.org/).

Being a developer you'll probably will fit in one (or maybe both :wink:) of the following _profiles_:

- Developer: if your goal is to develop C# applications for micro-controllers.
- Contributor: if you are interested in actively contributing by coding (native, managed, C, C++, CMake), writing documentation or participating in the overall project organization.

# Sponsoring .NET **nanoFramework**

Most of the core team members and contributors are embedded systems enthusiasts, passionate about coding and people that like challenges. The work on .NET **nanoFramework** is done mostly on their free time. Some of the core members happen to work on companies that sponsor heavily **nanoFramework** and offer their work hours to the project. If you use .NET **nanoFramework** for serious work or want to support it, please donate. This allow for paying the infrastructure cost and more time to be invested on the project. Besides monetary contributions, there are several other ways to contribute. Please read the documentation about this [here](http://docs.nanoframework.net/content/contributing/index.html).

This is how we use the donations:

- Pay for infrastructure costs.
- Develop public relation actions to get the project known.
- Support maintainers and contributors that invest a large amount of time in the project.
- Support projects that .NET **nanoFramework** depends on.
- Produce documentation, tutorials and other content to support developers using .NET **nanoFramework**.
- Organize events to demo .NET **nanoFramework**.

## Sponsors

Sponsors will get their logo and link to a website on our GitHub readme and also on our home page.

<a href="https://opencollective.com/nanoframework#support"><img src="https://opencollective.com/nanoframework/tiers/sponsor.svg?avatarHeight=80"></a>

### Bronze Sponsors

<a href="https://opencollective.com/nanoframework/tiers/bronze-sponsor/0/website" target="_blank" rel="noopener noreferrer"><img src="https://opencollective.com/nanoframework/tiers/bronze-sponsor/0/avatar.svg"></a>
<a href="https://www.orgpal.com"><img src="https://www.orgpal.com/orgpallogo.png" height="50" width="114"/></a>

## Backers

Backers are individuals who contribute with money to help support nanoFramework. Every little bit helps and we appreciate all contributions, even the smallest ones.

<a href="https://opencollective.com/nanoframework#support"><img src="https://opencollective.com/nanoframework/tiers/backer.svg?avatarHeight=80"></a>

## Other backers and sponsors

There are other people and organizations that have contributed to .NET **nanoFramework** along the time in several ways: sponsoring the coding of a feature that was missing or needed improvement, paying for an expense, coding a feature or... We would like to acknowledge these sponsors.

<table>
 <tr>
  <td><a href="http://www.eclo.solutions"><img src="http://www.eclo.solutions/images/eclo-solutions-logo-tall.svg" height="100" width="151"></a></td>
  <td><a href="http://www.chibios.org"><img src="https://upload.wikimedia.org/wikipedia/commons/c/cd/ChibiOS_Embeddedware_Official_Logo.jpg" height="100" width="100" alt="ChibiOS RTOS"/></a></td>
 </tr>
</table>

## Firmware for reference boards

Each of the following ZIP files contains the image files for nanoBooter and nanoCLR in various formats (HEX, BIN and DFU). They should be flashed in the target boards using an appropriate software utility.

The **stable** versions are RTM builds with the smallest possible size. They include the latest stable version. The debugging feature is disabled and only minimal (or none) error messages.

The **preview** versions are continuous builds of the reference targets. They include the latest version of all features and bug corrections. They also have the debugging feature enabled along with detailed error messages.

| Target | Stable | Preview |
|:-|---|---|
| ESP32_WROOM_32 | [ ![Download](https://api.bintray.com/packages/nfbot/nanoframework-images/ESP32_WROOM_32/images/download.svg) ](https://bintray.com/nfbot/nanoframework-images/ESP32_WROOM_32/_latestVersion) | [![Latest Version @ Cloudsmith](https://api-prd.cloudsmith.io/v1/badges/version/net-nanoframework/nanoframework-images-dev/raw/ESP32_WROOM_32.zip/latest/x/?render=true&badge_token=gAAAAABgWxsQ0EOQ1_NxwC74J7T4CPbdGB3unrMqV-ALAnO7NmQeLcrlPWAehyXUQ3_4EsiE30fOp-boZmAADZwTcQBKv8-gJTmJhUP0DeZJCMsdWf4lBP4%3D)](https://cloudsmith.io/~net-nanoframework/repos/nanoframework-images-dev/packages/detail/raw/ESP32_WROOM_32.zip/latest/) |
| ESP_WROVER_KIT | [ ![Download](https://api.bintray.com/packages/nfbot/nanoframework-images/ESP_WROVER_KIT/images/download.svg) ](https://bintray.com/nfbot/nanoframework-images/ESP_WROVER_KIT/_latestVersion) | [![Latest Version @ Cloudsmith](https://api-prd.cloudsmith.io/v1/badges/version/net-nanoframework/nanoframework-images-dev/raw/ESP_WROVER_KIT.zip/latest/x/?render=true&badge_token=gAAAAABgWxs0sy_Z0SJKVtabJLFxB-wercZM99WqrRSZZVSfcOeW2EjIhyu3MPq36A2-St-aqhmoVxICvlJM0Fg2JXx46vLcuM1vpL2AnKbEaPbpFd2tY64%3D)](https://cloudsmith.io/~net-nanoframework/repos/nanoframework-images-dev/packages/detail/raw/ESP_WROVER_KIT.zip/latest/) |
| ESP32_PICO | [ ![Download](https://api.bintray.com/packages/nfbot/nanoframework-images/ESP32_PICO/images/download.svg) ](https://bintray.com/nfbot/nanoframework-images/ESP32_PICO/_latestVersion) | [![Latest Version @ Cloudsmith](https://api-prd.cloudsmith.io/v1/badges/version/net-nanoframework/nanoframework-images-dev/raw/ESP32_PICO.zip/latest/x/?render=true&badge_token=gAAAAABgWxtNdQxouHYolWQFagVq8taYLJzrxmbrP-_3yisFna9pGplAkfsCxyc-JhjD9c6KvIPjPKRId6E6-X9RswLd9vKx3pf4dX1TIcPF26YJG9uCTc4%3D)](https://cloudsmith.io/~net-nanoframework/repos/nanoframework-images-dev/packages/detail/raw/ESP32_PICO.zip/latest/) |
| ST_STM32F429I_DISCOVERY | [ ![Download](https://api.bintray.com/packages/nfbot/nanoframework-images/ST_STM32F429I_DISCOVERY/images/download.svg) ](https://bintray.com/nfbot/nanoframework-images/ST_STM32F429I_DISCOVERY/_latestVersion) | [![Latest Version @ Cloudsmith](https://api-prd.cloudsmith.io/v1/badges/version/net-nanoframework/nanoframework-images-dev/raw/ST_STM32F429I_DISCOVERY.zip/latest/x/?render=true&badge_token=gAAAAABgWxtgAxHQjTJGznPOINUoT_Ej3tdlloXGP3tyipuu1bigH-NFmKsDiJqOFZhkYzo0HuekIdfn_af2KBfO-IrHuHd-9FrqP7nFVvuIpriyBU29jKM%3D)](https://cloudsmith.io/~net-nanoframework/repos/nanoframework-images-dev/packages/detail/raw/ST_STM32F429I_DISCOVERY.zip/latest/) |
| ST_NUCLEO64_F091RC | [ ![Download](https://api.bintray.com/packages/nfbot/nanoframework-images/ST_NUCLEO64_F091RC/images/download.svg) ](https://bintray.com/nfbot/nanoframework-images/ST_NUCLEO64_F091RC/_latestVersion) | [![Latest Version @ Cloudsmith](https://api-prd.cloudsmith.io/v1/badges/version/net-nanoframework/nanoframework-images-dev/raw/ST_NUCLEO64_F091RC.zip/latest/x/?render=true&badge_token=gAAAAABgWxuEsfOKMwTQ4p8tNlgFltGI-TQyh6hS-c4m2fn3cOiiCoH2Zs_A9blCjwIA_ldqDk7OdlvCONxjn7si9t-xqPyHyAT8j-1cnAuwtKpY9iV1-_o%3D)](https://cloudsmith.io/~net-nanoframework/repos/nanoframework-images-dev/packages/detail/raw/ST_NUCLEO64_F091RC.zip/latest/) |
| ST_STM32F769I_DISCOVERY | [ ![Download](https://api.bintray.com/packages/nfbot/nanoframework-images/ST_STM32F769I_DISCOVERY/images/download.svg) ](https://bintray.com/nfbot/nanoframework-images/ST_STM32F769I_DISCOVERY/_latestVersion) | [![Latest Version @ Cloudsmith](https://api-prd.cloudsmith.io/v1/badges/version/net-nanoframework/nanoframework-images-dev/raw/ST_STM32F769I_DISCOVERY.zip/latest/x/?render=true&badge_token=gAAAAABgWxuSyThy9rWl2BFzOgy1r4LRv1KYZe_vU3VicNMvPjsbwg3ps-x_V1aC8yiSoIXwIP8aPw3Ph6-wCpJZqUJduVtpp2s_UR6P2ccwtoOMJGjlvJ8%3D)](https://cloudsmith.io/~net-nanoframework/repos/nanoframework-images-dev/packages/detail/raw/ST_STM32F769I_DISCOVERY.zip/latest/) |
| ORGPAL_PALTHREE | [ ![Download](https://api.bintray.com/packages/nfbot/nanoframework-images/ORGPAL_PALTHREE/images/download.svg) ](https://bintray.com/nfbot/nanoframework-images/ORGPAL_PALTHREE/_latestVersion) | [![Latest Version @ Cloudsmith](https://api-prd.cloudsmith.io/v1/badges/version/net-nanoframework/nanoframework-images-dev/raw/ORGPAL_PALTHREE.zip/latest/x/?render=true&badge_token=gAAAAABgWxuvhPup6KikfsjlSNopnl1YJj6kwaw3ZKb4ePHYbU-kp3YcyQ5fggVV_eyGSa9Gh53-TIJ5RIbFMV8gvKnvDCTczJW8CpelDLyMgP373Ey10hw%3D)](https://cloudsmith.io/~net-nanoframework/repos/nanoframework-images-dev/packages/detail/raw/ORGPAL_PALTHREE.zip/latest/) |
| NETDUINO3_WIFI | [ ![Download](https://api.bintray.com/packages/nfbot/nanoframework-images/NETDUINO3_WIFI/images/download.svg) ](https://bintray.com/nfbot/nanoframework-images/NETDUINO3_WIFI/_latestVersion) | [![Latest Version @ Cloudsmith](https://api-prd.cloudsmith.io/v1/badges/version/net-nanoframework/nanoframework-images-dev/raw/NETDUINO3_WIFI.zip/latest/x/?render=true&badge_token=gAAAAABgWxvAxFISErASMvjPfBiilCIOBObv-i9TAxVYbL0_kXOsLOGv_5CFTD9sQ_NHjSB4TNhTB4AnA0aed7VG-Vu9koWwHxMQs-1Bo_LlB9tufBhubGE%3D)](https://cloudsmith.io/~net-nanoframework/repos/nanoframework-images-dev/packages/detail/raw/NETDUINO3_WIFI.zip/latest/) |
| TI_CC1352R1_LAUNCHXL_868 | [ ![Download](https://api.bintray.com/packages/nfbot/nanoframework-images/TI_CC1352R1_LAUNCHXL_868/images/download.svg) ](https://bintray.com/nfbot/nanoframework-images/TI_CC1352R1_LAUNCHXL_868/_latestVersion) | [![Latest Version @ Cloudsmith](https://api-prd.cloudsmith.io/v1/badges/version/net-nanoframework/nanoframework-images-dev/raw/TI_CC1352R1_LAUNCHXL_868.zip/latest/x/?render=true&badge_token=gAAAAABgWxvs4c8caJtRfrxQMUln4iKcBPy3j_L6K3BNZRBKFt5YjIhU9qSFzoPqyM0s4RGTFrUUTg1VN6YID7MkrGf3PeZT_2dW9mR5VdFkIGnrnVW9vtA%3D)](https://cloudsmith.io/~net-nanoframework/repos/nanoframework-images-dev/packages/detail/raw/TI_CC1352R1_LAUNCHXL_868.zip/latest/) |
| TI_CC1352R1_LAUNCHXL_915 | [ ![Download](https://api.bintray.com/packages/nfbot/nanoframework-images/TI_CC1352R1_LAUNCHXL_915/images/download.svg) ](https://bintray.com/nfbot/nanoframework-images/TI_CC1352R1_LAUNCHXL_915/_latestVersion) | [![Latest Version @ Cloudsmith](https://api-prd.cloudsmith.io/v1/badges/version/net-nanoframework/nanoframework-images-dev/raw/TI_CC1352R1_LAUNCHXL_915.zip/latest/x/?render=true&badge_token=gAAAAABgWxv9FGSgTGts-1jHwH4R9rCD74Ry-HDqgamGyMxcIFB4w0ByEzLiVXRFvTwpromS_Zi2uMRnXHLPP4XEO9lJmGJbHEDrexyss9tSU9jHx_C2ybc%3D)](https://cloudsmith.io/~net-nanoframework/repos/nanoframework-images-dev/packages/detail/raw/TI_CC1352R1_LAUNCHXL_915.zip/latest/) |
| TI_CC3220SF_LAUNCHXL | [ ![Download](https://api.bintray.com/packages/nfbot/nanoframework-images/TI_CC3220SF_LAUNCHXL/images/download.svg) ](https://bintray.com/nfbot/nanoframework-images/TI_CC3220SF_LAUNCHXL/_latestVersion) | [ ![Download](https://api.bintray.com/packages/nfbot/nanoframework-images-dev/TI_CC3220SF_LAUNCHXL/images/download.svg) ](https://bintray.com/nfbot/nanoframework-images-dev/TI_CC3220SF_LAUNCHXL/_latestVersion) |
| NXP_MIMXRT1060_EVK | [ ![Download](https://api.bintray.com/packages/nfbot/nanoframework-images/NXP_MIMXRT1060_EVK/images/download.svg) ](https://bintray.com/nfbot/nanoframework-images/NXP_MIMXRT1060_EVK/_latestVersion) | [![Latest Version @ Cloudsmith](https://api-prd.cloudsmith.io/v1/badges/version/net-nanoframework/nanoframework-images-dev/raw/NXP_MIMXRT1060_EVK.zip/latest/x/?render=true&badge_token=gAAAAABgWxwUlaLK-cw0e71em0ksycYwgy8Xxc44JLI3_ZwxxrszUOEzLud2mKaWr6GUuPjaw84h9BoKzf_1ksd5eZ1n1IpeYOmpGmMWbEYrYrQCAeZNFCw%3D)](https://cloudsmith.io/~net-nanoframework/repos/nanoframework-images-dev/packages/detail/raw/NXP_MIMXRT1060_EVK.zip/latest/) |

The above firmware builds include support for the class libraries and features marked bellow.

<details>
  <summary>Click to expand!</summary>

  | Target                  | Gpio               | Spi                | I2c                | Pwm                | Adc                | Dac                | Serial             | OneWire            | Events             | SWO                | Networking         | Large Heap         | UI         |
  |:-:                      |:-:                 |:-:                 |:-:                 |:-:                 |:-:                 |:-:                 |:-:                 |:-:                 |:-:                 |:-:                 |:-:                 |:-:                 |:-:                 |
  | ESP32_WROOM_32          | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |                    | :heavy_check_mark: | :heavy_check_mark: |                    |
  | ESP_WROVER_KIT          | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |                    | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
  | ESP32_PICO          | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |                    | :heavy_check_mark: | :heavy_check_mark: |                    |
  | ST_STM32F429I_DISCOVERY | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |                    | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |                    | :heavy_check_mark: |                    |
  | ST_NUCLEO64_F091RC      | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |                    |                    | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |                    |                    |                    |
  | ST_STM32F769I_DISCOVERY | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
  | ORGPAL_PALTHREE | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |                    |
  | MBN_QUAIL               | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |                    |                    | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |                    |                    |                    |                    |
  | NETDUINO3_WIFI          | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |                    | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |                    |                    |                    |                    |
  | TI_CC1352R1_LAUNCHXL    | :heavy_check_mark: |  |  |  |  |                    |                    |                    |  |                    |  |                    |                    |
  | TI_CC3220SF_LAUNCHXL    | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |                    |                    |                    | :heavy_check_mark: |                    | :heavy_check_mark: |                    |                    |
  | NXP_MIMXRT1060_EVK           | :heavy_check_mark: |  |  |  |  |  | :heavy_check_mark:  |                    | :heavy_check_mark: |                    | :heavy_check_mark: | :heavy_check_mark: |                    |
</details>

## Firmware for community target boards

Besides the above firmware images, you can find several others for community provided target boards. Check the available ones and download links on the [Community Targets repo](https://github.com/nanoframework/nf-Community-Targets).

## Repositories

Our GitHub organization holds the various repositories for firmware, class libraries, documentation and tools.
You can find [here](docs/organization/README.md) a list and a description of each of them.

## How to Engage, Contribute and Provide Feedback

Some of the best ways to contribute are to try things out, file bugs, and join in design conversations.

If you have a question, need clarification on something, need help on a particular situation or want to start a discussion, do not open an issue here. It is best to ask the question on [Stack Overflow](https://stackoverflow.com/questions/tagged/nanoframework) using the `nanoframework` tag or to start a conversation on one of our [Discord channels](https://discordapp.com/invite/gCyBu8T). Make sure to select the channel that's most appropriate to the context so subject matter experts are most likely to answer promptly.

If you've find a bug or can't use Discord, please open an issue at [Issues](https://github.com/nanoframework/Home/issues).
We ask you to open an issue only when you have a real and confirmed one. Don't open an issue for support requests or to start a discussion. For that you'll get a better (and quicker!) support/feedback in one of the [Discord](https://discord.gg/gCyBu8T) channels.

You can also ask questions on Stack Overflow and tag them with [#nanoframework](https://stackoverflow.com/tags/nanoframework).

Looking for something to work on? Check the list of [up-for-grabs issues](https://github.com/nanoframework/Home/issues?q=is%3Aissue+is%3Aopen+label%3Aup-for-grabs) on the Home repo, that's a great place to start.

See some of our guides for more details:

- [Contributing Guide](https://github.com/nanoframework/.github/blob/master/CONTRIBUTING.md)
- [Contributing workflow](https://docs.nanoframework.net/content/contributing/contributing-workflow.html)

## License

.NET **nanoFramework** libraries, firmware images, tools and samples are licensed under the [MIT license](LICENSE.md).

## Documentation

### [Docs](https://docs.nanoframework.net)

The project documentation is a great place to find information about .NET **nanoFramework**, no matter if you are newcomer or a veteran. It's organized in the following categories:

- [API reference](http://docs.nanoframework.net/api) documentation for the various class libraries.
- [Developing C# applications](https://docs.nanoframework.net/content/getting-started-guides/getting-started-managed.html#coding-a-hello-world-application) using .NET **nanoFramework**.
- [Building an image](https://docs.nanoframework.net/content/building/index.html) to load on a target board.
- [.NET **nanoFramework** architecture](https://docs.nanoframework.net/content/architecture/index.html) and how the different pieces fit together.
- [Contributing to .NET **nanoFramework**](https://docs.nanoframework.net/content/contributing/index.html) includes an overview on how you can contribute to the project.

### [Blog](https://www.nanoframework.net/blog)

There is a blog where we try to post detailed updates about the development status, technical posts about a particular feature ou a design option.

### [YouTube channel](https://www.youtube.com/c/nanoFramework)

We also have a YouTube channel where with video tutorials along with feature demos and teasers about new ideas that we are experimenting with.

## Code of Conduct

This project has adopted the code of conduct defined by the Contributor Covenant to clarify expected behavior in our community.
For more information see the [.NET Foundation Code of Conduct](https://dotnetfoundation.org/code-of-conduct). 
