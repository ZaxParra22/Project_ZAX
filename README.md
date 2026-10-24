<div align="center">

<img src="./project_zax.png" alt="Official Logo" width="195">

# Project_Zax

### NATIVE RECOMPILATION PROJECT

**Nintendo 3DS → Windows · Linux · Android**

![Development](https://img.shields.io/badge/DEVELOPMENT-ACTIVE-FF7900?style=for-the-badge&labelColor=111111)
![Developer](https://img.shields.io/badge/INDEPENDENT-SOLO_DEVELOPER-FFFFFF?style=for-the-badge&labelColor=111111)

**Recompilation, not emulation.**

*One developer. Many ideas. Built for the community.*

---

![Windows](https://img.shields.io/badge/WINDOWS-BETA-FF7900?style=flat-square&labelColor=111111)
![Linux](https://img.shields.io/badge/LINUX-BETA-FF7900?style=flat-square&labelColor=111111)
![Android](https://img.shields.io/badge/ANDROID-ALPHA-FFFFFF?style=flat-square&labelColor=111111)

[![Releases](https://img.shields.io/badge/RELEASES-FF7900?style=for-the-badge&logo=github&logoColor=white&labelColor=111111)](https://github.com/ZaxParra22/Project_ZAX/releases)
[![Reports](https://img.shields.io/badge/BUG_REPORTS-FFFFFF?style=for-the-badge&logo=github&logoColor=white&labelColor=111111)](https://github.com/ZaxParra22/Project_ZAX/issues)
[![Community](https://img.shields.io/badge/COMMUNITY-FF7900?style=for-the-badge&logo=whatsapp&logoColor=white&labelColor=111111)](https://whatsapp.com/channel/0029VbDl1fa7T8bOPMjdA60p)

</div>

---

## 01 / Overview

Hey! Welcome to my little corner of game development.

I'm an independent programmer who enjoys spending his free time experimenting with software, learning new things, and building projects for the community.

This project explores bringing Nintendo 3DS games to modern platforms through **native code recompilation**, translating game code into native executables rather than relying on traditional emulation.

The goal is simple: improve compatibility, performance, and graphical flexibility while preserving the original gaming experience.

### Built independently

Everything is currently developed and maintained by one person.

From recompilation and graphics integration to optimization, debugging, and testing, I handle the development myself.

There's no large team behind this work, and progress depends on my available time. Some challenges take longer than expected, but that's part of experimenting and learning.

**The project is developed individually, but community feedback helps make it better.**

---

## 02 / Development Status

### Platforms

| Platform | Status | Current Focus |
|:---|:---:|:---|
| **Windows** | `BETA` | Performance and compatibility |
| **Linux** | `BETA` | Stability and testing |
| **Android** | `ALPHA` | Mobile adaptation and optimization |

Windows and Linux are undergoing Beta refinement.

Android is still in Alpha testing, with ongoing work on rendering efficiency, controls, and hardware adaptation.

> **Note:** Development status does not necessarily mean a public build is available. Features and compatibility may change between versions.

---

## 03 / Games

### Monster Hunter 4 Ultimate

![MH4U](https://img.shields.io/badge/MH4U-BETA-FF7900?style=for-the-badge&labelColor=111111)

**CURRENT FOCUS**

The main development target, currently undergoing Beta refinement.

Work focuses on improving rendering accuracy, correcting lighting and shadow issues, optimizing performance, and addressing stability problems.

Compatibility across different hardware configurations remains an important priority.

### Monster Hunter XX

![MHXX](https://img.shields.io/badge/MHXX-UPCOMING_BETA-FF7900?style=for-the-badge&labelColor=111111)

**NEXT RELEASE**

Currently in Beta development, with an upcoming release planned.

The existing recompilation infrastructure is being adapted and tested to handle the game's specific requirements.

Additional details will be shared as the build gets closer to release.

### Monster Hunter 4G

![MH4G](https://img.shields.io/badge/MH4G-TESTING-FFFFFF?style=for-the-badge&labelColor=111111)

**EXPERIMENTAL**

Currently undergoing technical testing.

I'm exploring the possibility of supporting MH4G and MH4U within a shared environment while accounting for differences between both versions.

This remains an experimental goal rather than a confirmed feature.

### Current Lineup

| Title | Stage | Priority |
|:---|:---|:---|
| Monster Hunter 4 Ultimate | Beta | Main focus |
| Monster Hunter XX | Beta | Upcoming release |
| Monster Hunter 4G | Testing | Experimental |

---

## 04 / Under the Hood

The work goes beyond simply getting games to launch. A large part of development involves adapting the original code and improving how it runs on modern systems.

### Native Recompilation

- Translation of game code into native executable code.
- Automatic detection of unresolved function dependencies.
- Alternative processing paths for unresolved references.
- Reference recalculation and validation.
- Duplicate and false-positive handling.
- Improvements to the recompilation workflow.

### Graphics & Rendering

- Independent graphics layer integration.
- Vulkan and OpenGL development.
- Lighting and shadow corrections.
- Rendering compatibility improvements.
- In-game graphical settings.
- Performance-oriented optimizations.

### Display & Controls

- Dynamic secondary-screen management.
- Automatic screen-format detection.
- Dual-screen layout adaptation.
- Platform-specific interface and input development.

### Android

Mobile development introduces additional challenges related to rendering workloads, memory usage, and hardware differences.

Current experiments focus on optimizing screen updates, improving background processing, and adapting the interface for touchscreen devices.

*Some systems remain experimental and may not be available in every build.*

---

## 05 / Testing Matters

### A little help goes a long way

One of the biggest challenges of developing alone is testing.

I don't have a large testing team or enough hardware to verify how everything behaves across different computers and devices.

Something that works perfectly on my setup might have issues on yours.

**If you try a build, I'd really appreciate it if you could share your results.**

You don't need programming experience to contribute.

Even a short report can help identify problems and improve future versions.

### What can you report?

- Does the game launch correctly?
- How does it perform on your hardware?
- Are there graphical glitches or missing effects?
- Do lighting and shadows look correct?
- Are there crashes, freezes, or unexpected behaviors?
- Do controls and the secondary screen work properly?

**Everything working fine? That's useful too.**

Knowing which hardware configurations work correctly is just as valuable as finding bugs.

### Reporting an Issue

Please include as much information as possible:

| Information | Details |
|:---|:---|
| Game | MH4U / MHXX / MH4G |
| Platform | Windows / Linux / Android |
| Build | Version tested |
| CPU / GPU | Hardware models |
| RAM | Installed memory |
| Renderer | Vulkan / OpenGL, if applicable |
| Performance | FPS and stability |
| Result | Working / Partial / Failed |
| Details | Problems or testing observations |

Screenshots, logs, and recordings are welcome.

For bugs, reproduction steps are especially helpful. Please avoid sharing copyrighted game files or personal information.

<div align="center">

### FOUND SOMETHING? LET ME KNOW.

[![Submit Report](https://img.shields.io/badge/OPEN_A_TEST_REPORT-FF7900?style=for-the-badge&logo=github&logoColor=white&labelColor=111111)](https://github.com/ZaxParra22/Project_ZAX/issues/new)

*Your feedback helps turn today's problems into tomorrow's fixes.*

</div>

---

## 06 / Roadmap

There's still plenty to improve, and priorities may change as testing continues.

| Area | Current Direction |
|:---|:---|
| MH4U | Beta refinement and bug fixing |
| MHXX | Preparing the upcoming Beta |
| MH4G | Testing and compatibility research |
| Windows / Linux | Optimization and stability |
| Android | Alpha development |
| Community | Expanding testing and compatibility reports |

### Milestones

- [x] Initial native recompilation framework.
- [x] Reference processing improvements.
- [x] Initial native PC execution.
- [x] Graphics layer integration.
- [x] Dynamic secondary-screen development.
- [x] MH4U and MHXX Beta development.
- [x] Windows and Linux Beta testing started.
- [x] Android Alpha testing started.
- [ ] Continue refining MH4U.
- [ ] Prepare the MHXX public Beta.
- [ ] Expand hardware compatibility testing.
- [ ] Continue Android optimization.
- [ ] Investigate MH4G / MH4U shared support.
- [ ] Improve documentation and reporting resources.

No fixed release dates are guaranteed.

---

## 07 / Releases

Official builds will be published through GitHub Releases when ready.

Release notes will include supported platforms, installation instructions, known limitations, compatibility information, and relevant improvements.

<div align="center">

[![View Releases](https://img.shields.io/badge/VIEW_RELEASES-FF7900?style=for-the-badge&logo=github&logoColor=white&labelColor=111111)](https://github.com/ZaxParra22/Project_ZAX/releases)

</div>

Beta and Alpha builds may contain bugs, incomplete features, or unexpected behavior.

I'd rather spend more time fixing important issues than rush an unfinished release.

---

## 08 / Community

Want to follow development progress?

I share updates, announcements, screenshots, and upcoming release information through the official WhatsApp channel.

<div align="center">

[![WhatsApp Channel](https://img.shields.io/badge/FOLLOW_DEVELOPMENT-WHATSAPP-FF7900?style=for-the-badge&logo=whatsapp&logoColor=white&labelColor=111111)](https://whatsapp.com/channel/0029VbDl1fa7T8bOPMjdA60p)

</div>

For technical problems and compatibility reports, please use GitHub Issues.

Keeping reports organized makes it easier to reproduce problems and track fixes.

---

## 09 / A Note From the Developer

I know most people simply want to download a game and enjoy playing it. That's completely understandable.

But while these ports are still being developed, testing is one of the most helpful things the community can do.

I can't test every device or fix every issue immediately, especially while handling development on my own.

If you have a chance to try a build, sharing what worked and what didn't would mean a lot.

You don't need to contribute code or understand recompilation to help. Your experience alone can provide valuable information.

I'll keep experimenting, learning, and improving things whenever I can.

**Thanks for following along and being part of the process.**

---

## 10 / Credits

This work builds on research, tools, and knowledge shared by the recompilation, reverse-engineering, graphics programming, and open-source communities.

Third-party tools and dependencies will receive their corresponding credits and license notices in the documentation.

Thanks to everyone who contributes useful feedback, tests builds, or shares suggestions.

---

## Legal Disclaimer

This is an independent, unofficial development project and is not affiliated with Nintendo, Capcom, or their subsidiaries.

All trademarks, game titles, and copyrighted materials belong to their respective owners.

No copyrighted game files, proprietary assets, or encryption keys are distributed through this repository.

Users are responsible for obtaining and using their own game files in accordance with applicable laws.

---

<div align="center">

<img src="./project_zax.png" alt="Logo" width="85">

### ONE DEVELOPER. MANY IDEAS.

**Made in my free time. Improved with your feedback.**

![Recompilation](https://img.shields.io/badge/RECOMPILATION-NOT_EMULATION-FF7900?style=for-the-badge&labelColor=111111)

*Thanks for being part of the journey.*

[![WhatsApp](https://img.shields.io/badge/WHATSAPP-UPDATES-FF7900?style=flat-square&logo=whatsapp&logoColor=white&labelColor=111111)](https://whatsapp.com/channel/0029VbDl1fa7T8bOPMjdA60p)
[![GitHub](https://img.shields.io/badge/GITHUB-ISSUES-FFFFFF?style=flat-square&logo=github&logoColor=white&labelColor=111111)](https://github.com/ZaxParra22/Project_ZAX/issues)

</div>
