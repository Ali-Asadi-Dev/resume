# Ali Asadi

**Senior iOS Engineer** · Open to relocation

[LinkedIn](https://linkedin.com/in/ali-asadi) · [GitHub](https://github.com/Ali-Asadi-Dev) · [asadi.0241@gmail.com](mailto:asadi.0241@gmail.com) · [**Download PDF**](./Ali-Asadi-Resume.pdf)

---

## Summary

iOS engineer with **9 years** in native Swift, owning **iOS architecture and technical decisions** across the three squads of a **20M+ user** super-app built on **41 Swift packages**. Drives code review while still shipping: **600K+ transactions a day**, **$60M+ a year** in payment volume. Uses AI-assisted development to deliver in days what used to take weeks.

## Engineering Expertise

| Area | Skills |
|---|---|
| **Languages** | Swift, Objective-C |
| **UI Development** | UIKit, SwiftUI, Auto Layout, Storyboards/XIB, Custom UI Components, RTL, Animations (Lottie) |
| **Architecture** | VIPER + Coordinator, Modular Architecture (Swift Package Manager), Clean Architecture, MVVM-C, The Composable Architecture (TCA), Protocol-Oriented Programming |
| **Concurrency** | Swift Concurrency (async/await, Task, actors), Combine |
| **Security** | RSA (SecKey), Keychain, encrypted payloads |
| **Networking** | REST APIs, JSON, URLSession, WebSockets |
| **Data & Storage** | Core Data, Realm, Offline-first sync |
| **Testing & Profiling** | XCTest, XCUITest, Maestro, Instruments |
| **Product Analytics** | Event analytics, A/B testing, experimentation |
| **AI Tooling** | Claude, agent workflows |
| **Delivery** | Git (multi-repo), GitLab CI, Fastlane, App Store releases |
| **Web** | JavaScript, React |

## Professional Experience

### Senior iOS Engineer — Hafhashtad Super App
*Banking and payments* · **Jul 2025 – Present**

- Set iOS architecture and review standards across the **3 squads** of the tech department, in a codebase of **41 Swift packages**.
- Led the V3 bank-card redesign and built the **card module every payment surface now shares**, with no host-specific code: each host passes a config and the server drives card state. Live in balance and transfer, with three more flows migrating onto it.
- Took digital checks from **1% to over 95% success rate** by tracing each failure class back through the client and the clearing system behind it.
- Built the encrypted transfer flow: **RSA public key held in the Keychain**, encrypted CVV2 and one-time-password payloads, with recovery paths for network timeout and invalid key.
- Migrated the shared input components used by **~35 feature packages** in place, keeping the public API and making new behavior opt-in so roughly 30 other screens did not regress.
- Built an **agent workflow** that reads a design from Figma, implements the screen in Xcode, then builds, runs, and drives the app to that screen to check the result against the design.

### Senior iOS Engineer — SolidICT
*Product agency, 5-person iOS team* · **Jan 2022 – Jul 2025** (3 yrs 7 mos)

- Migrated **70% of the codebase from Objective-C to Swift**, modernizing a live app one area at a time.
- Traced UI lag to memory leaks with **Instruments** and fixed them, removing the stutter from the affected screens.
- Split the codebase into independent feature and core packages, removing dependency cycles and unnecessary imports.
- Mentored **4 engineers** through code review and pairing, setting the code quality bar for the iOS team.
- Developed the **Turkcell** mobile operator app from scratch, and MomsCo for the MyBaby brand, each reaching **400K+ installs**.

### iOS Developer — Behin Sayar
*Ride-hailing and university platforms* · **Dec 2017 – Dec 2021** (4 yrs)

- Built **two production iOS apps** from scratch, customer and driver, covering networking, auth, local storage, and maps.
- Built the **real-time location pipeline**: pickup matching, live route drawing, and continuous driver tracking during active rides.
- Wrote **two React PWAs** for students and faculty, used across a national university network.

## Education

**Bachelor's Degree in Computer Engineering** — Sufi University
