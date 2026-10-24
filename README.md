<div align="center">

<img src="assets/project_zax_logo.png" alt="Project_Zax Logo" width="230">

# Project_Zax

### Nintendo 3DS Native Recompilation Project

**Windows · Linux · Android**

![Development](https://img.shields.io/badge/Development-Active-FF7900?style=for-the-badge&labelColor=171717)
![Maintainer](https://img.shields.io/badge/Developer-Independent-FFFFFF?style=for-the-badge&labelColor=171717)

**Native Recompilation — Not Emulation**

*An independent project developed in my free time.*

---

![Windows](https://img.shields.io/badge/Windows-Beta-FF7900?style=flat-square&labelColor=171717)
![Linux](https://img.shields.io/badge/Linux-Beta-FF7900?style=flat-square&labelColor=171717)
![Android](https://img.shields.io/badge/Android-Alpha_Testing-FFFFFF?style=flat-square&labelColor=171717)

[![Releases](https://img.shields.io/badge/GitHub-Releases-FF7900?style=for-the-badge&logo=github&logoColor=white&labelColor=171717)](https://github.com/ZaxParra42/Project-ZAX/releases)
[![Reports](https://img.shields.io/badge/GitHub-Report_an_Issue-FFFFFF?style=for-the-badge&logo=github&logoColor=white&labelColor=171717)](https://github.com/ZaxParra42/Project-ZAX/issues)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-Project_Updates-FF7900?style=for-the-badge&logo=whatsapp&logoColor=white&labelColor=171717)](https://whatsapp.com/channel/0029VbDl1fa7T8bOPMjdA60p)

</div>

---

## About Project_Zax

Hey! Welcome to **Project_Zax**.

I'm a programmer who enjoys spending his free time experimenting with software, learning new things, and creating projects for the community.

Project_Zax focuses on bringing Nintendo 3DS games to Windows, Linux, and Android through native code recompilation.

Instead of relying on traditional emulation, the project works on translating game code into native executables and adapting the necessary systems to run on modern platforms.

The main goal is to improve compatibility, stability, graphical rendering, and performance while keeping the original gameplay experience.

### Independent Development

Project_Zax is currently developed and maintained by just one person.

I handle the recompilation work, graphics integration, optimization, debugging, and general development myself.

Since I work on the project during my free time, progress may vary depending on my availability and the technical problems I encounter.

I also have a limited number of devices and testers, so community feedback is especially helpful.

The project is still evolving, and there's plenty of work left to do.

---

## Development Status

### Platforms

| Platform | Status | Current Focus |
|:---|:---|:---|
| **Windows** | Beta | Optimization, compatibility, and bug fixes |
| **Linux** | Beta | Stability and compatibility testing |
| **Android** | Alpha Testing | Mobile adaptation and optimization |

Windows and Linux are currently undergoing Beta refinement.

Android is still in Alpha testing. It requires additional work to adapt rendering, controls, and resource management to mobile devices.

Please note that the development stage does not necessarily indicate that a public build is available.

### Games

| Game | Status | Notes |
|:---|:---|:---|
| **Monster Hunter 4 Ultimate** | Beta | Main development focus |
| **Monster Hunter XX** | Beta | Upcoming release |
| **Monster Hunter 4G** | Testing | Experimental development |

### Monster Hunter 4 Ultimate

![MH4U](https://img.shields.io/badge/MH4U-BETA-FF7900?style=for-the-badge&labelColor=171717)

MH4U is currently the main focus of Project_Zax.

I'm working on improving graphical rendering, correcting lighting and shadow issues, optimizing performance, and fixing problems found during testing.

The goal is to make the Beta more stable across different hardware configurations.

### Monster Hunter XX

![MHXX](https://img.shields.io/badge/MHXX-BETA_COMING_SOON-FF7900?style=for-the-badge&labelColor=171717)

Monster Hunter XX is also in Beta development and is planned as the next release.

Development includes adapting the existing recompilation systems and addressing compatibility issues specific to this game.

More details will be shared as the build approaches release.

### Monster Hunter 4G

![MH4G](https://img.shields.io/badge/MH4G-TESTING-FFFFFF?style=for-the-badge&labelColor=171717)

Monster Hunter 4G is currently undergoing technical testing.

I'm exploring the possibility of supporting MH4G and MH4U within a shared environment, while accounting for the differences between both versions.

This is still experimental and has not been confirmed as a release feature.

---

## Technical Development

Project_Zax includes several systems that I'm continuing to develop and improve.

### Native Recompilation

- Translation of game code for native execution.
- Automatic detection of unresolved function dependencies.
- Alternative processing paths for unresolved references.
- Reference recalculation and validation.
- Handling of duplicate references and false positives.
- Improvements to code organization and recompilation processing.

### Graphics and Rendering

- Independent graphics layer integration.
- Vulkan and OpenGL development.
- Rendering compatibility improvements.
- Lighting and shadow corrections.
- Performance and graphical optimizations.
- In-game graphics configuration.

### Display and Interface

- Dynamic secondary-screen management.
- Automatic screen-format detection.
- Adaptation of Nintendo 3DS dual-screen layouts.
- Interface and control configuration development.

### Android Development

- Adaptation of the recompilation environment.
- Mobile graphics integration.
- Touchscreen control development.
- Rendering workload optimization.
- Background processing and resource management improvements.

Some features are still experimental. Their availability and functionality may differ between platforms and development builds.

---

## Community Testing & Bug Reports

### Your feedback helps improve Project_Zax

One of the biggest challenges of working on this project alone is testing.

I don't have a large testing team or enough hardware to check every possible configuration.

Something that works correctly on my computer might have graphical problems, performance issues, or crashes on another device.

That's why I would really appreciate it if users who test Project_Zax could share their results.

**You don't need to know programming to help.**

If you try a build, I'd like to know how it behaves on your hardware.

I'm particularly interested in reports about:

- Games launching and running correctly.
- Crashes, freezes, or unexpected behavior.
- Graphics, lighting, and shadow problems.
- Performance drops or unstable frame rates.
- Controller and touchscreen issues.
- Problems with the secondary screen.
- Other compatibility issues encountered during gameplay.

### Working correctly? Let me know too!

Bug reports aren't the only useful reports.

If a game works well on your computer or device, that information helps me understand which configurations are compatible.

Knowing what works is just as important as knowing what doesn't.

### How to Submit a Report

You can submit your results through GitHub Issues.

Please include the following information whenever possible:

| Information | Details |
|:---|:---|
| Game | MH4U, MHXX, or MH4G |
| Platform | Windows, Linux, or Android |
| Build | Version being tested |
| CPU | Processor model |
| GPU | Graphics processor |
| RAM | Installed memory |
| Renderer | Vulkan or OpenGL, if applicable |
| Performance | FPS or general performance observations |
| Result | Working, Partially Working, or Not Working |
| Description | What happened during testing |

Screenshots, logs, or short recordings are also useful when reporting problems.

If something crashes or behaves incorrectly, explaining how to reproduce the issue makes it easier for me to investigate.

You don't have to provide everything perfectly. Just share the information you have available.

<div align="center">

### Help Improve the Next Build

[![Report an Issue](https://img.shields.io/badge/SUBMIT_A_TEST_REPORT-FF7900?style=for-the-badge&logo=github&logoColor=white&labelColor=171717)](https://github.com/ZaxParra42/Project-ZAX/issues/new)

*Your reports help me identify problems, prioritize fixes, and improve future releases.*

</div>

---

## Development Roadmap

| Project | Current Stage |
|:---|:---|
| MH4U | Beta refinement |
| MHXX | Upcoming Beta release |
| MH4G | Technical testing |
| MH4G / MH4U shared support | Experimental |
| Windows | Beta optimization |
| Linux | Beta testing |
| Android | Alpha development |

### Progress

- [x] Initial native recompilation framework.
- [x] Reference processing improvements.
- [x] Initial native PC execution.
- [x] Graphics layer integration.
- [x] Dynamic secondary-screen development.
- [x] MH4U Beta development.
- [x] MHXX Beta development.
- [x] Windows and Linux Beta testing.
- [x] Android Alpha testing started.
- [ ] Continue refining MH4U.
- [ ] Prepare the upcoming MHXX Beta release.
- [ ] Expand compatibility testing.
- [ ] Continue Android development.
- [ ] Investigate shared MH4G / MH4U support.
- [ ] Improve documentation and testing resources.

The roadmap may change depending on development progress, testing results, and technical limitations.

---

## Releases & Downloads

Official Project_Zax builds will be published through GitHub Releases when they're ready.

Each release will include relevant information about the supported platforms, installation process, known issues, and changes.

<div align="center">

[![GitHub Releases](https://img.shields.io/badge/VIEW-GITHUB_RELEASES-FF7900?style=for-the-badge&logo=github&logoColor=white&labelColor=171717)](https://github.com/ZaxParra42/Project-ZAX/releases)

</div>

Since the project is still in development, Beta and Alpha builds may contain bugs or incomplete features.

There are no guaranteed release dates.

I'll continue sharing updates as development progresses.

---

## News & Community

You can follow Project_Zax through the official WhatsApp channel.

I use it to share development progress, announcements, screenshots, and information about upcoming builds.

<div align="center">

[![WhatsApp Channel](https://img.shields.io/badge/FOLLOW_PROJECT__ZAX-WHATSAPP-FF7900?style=for-the-badge&logo=whatsapp&logoColor=white&labelColor=171717)](https://whatsapp.com/channel/0029VbDl1fa7T8bOPMjdA60p)

</div>

For technical issues and compatibility reports, please use GitHub Issues.

Keeping reports in one place makes them easier to review, reproduce, and track while I work on corrections.

---

## A Note From the Developer

I understand that most people simply want to download a game and enjoy playing it. That's completely fine.

However, Project_Zax is still in development, and testing is an important part of improving it.

Since I'm working on everything individually, I can't always identify every problem or reproduce issues that only appear on certain devices.

That's why I encourage users who try the builds to share their experiences, even if everything works correctly.

I may not be able to fix every problem immediately or respond to every report, but I do review feedback whenever possible and use it to guide development.

You don't need to contribute code to support the project. Testing a build and sharing the results is already a valuable contribution.

Thanks to everyone who follows the development, shares suggestions, and takes the time to help.

---

## Credits & Acknowledgements

Project_Zax is independently developed, but it also benefits from the research and knowledge shared by the recompilation, reverse-engineering, graphics programming, and open-source communities.

Third-party tools, libraries, and dependencies will receive their corresponding credits in the project documentation.

Thanks as well to everyone contributing testing results, reporting issues, or sharing useful suggestions.

Your participation is appreciated.

---

## Disclaimer

Project_Zax is an independent, unofficial project and is not affiliated with Nintendo, Capcom, or their subsidiaries.

All trademarks, game titles, and copyrighted materials belong to their respective owners.

This repository does not distribute copyrighted game files, proprietary assets, or encryption keys.

Users are responsible for obtaining and using their own game files in accordance with applicable laws.

---

<div align="center">

### Project_Zax

**ONE DEVELOPER. MANY IDEAS.**

![Project Zax](https://img.shields.io/badge/RECOMPILATION-NOT_EMULATION-FF7900?style=for-the-badge&labelColor=171717)

*Built in my free time. Improved with your feedback.*

**Thanks for being part of the project.**

[![WhatsApp](https://img.shields.io/badge/WHATSAPP-UPDATES-FF7900?style=flat-square&logo=whatsapp&logoColor=white&labelColor=171717)](https://whatsapp.com/channel/0029VbDl1fa7T8bOPMjdA60p)
[![GitHub](https://img.shields.io/badge/GITHUB-ISSUES-FFFFFF?style=flat-square&logo=github&logoColor=white&labelColor=171717)](https://github.com/ZaxParra42/Project-ZAX/issues)

</div>
