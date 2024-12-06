# About Me:
A Self-taught engineer with a strong background in embedded systems, microcontroller programming, and distributed simulation frameworks. Seeking to contribute to cutting-edge hardware/software co-design projects in embedded systems and IoT industries.

# Skills:
- **Languages**: Java - C/C++ - Kotlin - Bash (Shell Scripting) - Dot for architectural diagrams.
- **Embedded Systems**: C/C++ Programming (3+ years) - Java Native Interface (JNI) - AVR Toolhchain - Android NDK - Embedded Systems Design (Decoders, Encoders, Circuit Design) - Microcontroller Programming (GPIO, UART, I2C, SPI, ADC, PWM) - Technical Datasheet Analysis - GNU/Linux Libc - Kernel userspace APIs (IEEE-1284, RS232/Serial-USB) - Realtime signal processing - jMonkeyEngine Framework - Hardware/Software Co-design - Distributed Simulations.
- **Building, Automation and Testing**: CMake - BASH - Git/GitHub VCS - GitHub Actions (CI/CD) - Gradle - Gradle Multi-project Builds - Valgrind - jconsole - GNU Debugger (GDB).
- **Crossplatform API development**: Software Architectural Design - Concurrent Programming - Object-oriented Design - Design Patterns - Game Programming Patterns - Entity-Component-System Design - Procedural Programming (Finite Automata) - Sqlite DB - Data Structures - Algorithms - POSIX - GNU Compiler Collection (GCC) - Android SDK - GLSL - OpenGL - Sonatype/Maven Deployment.
- **Technical Writing**: Documentation - Wikis - GraphViz - Latex.
- **Pure Science**: Scientific Modelling - Scientific Philosophy - Discrete Mathematics - Calculus - Linear Algebra - Medical and Clinical Sciences.

# Experience:
> Essentially, all my contributions are entitled to open-source projects through different routes, either through non-profit open-source organizations (e.g., jMonkeyEngine - Pi4j) or through self-initiated projects on [Electrostat-Lab](https://github.com/Electrostat-Lab) organization, see the [projects section](https://github.com/orgs/Electrostat-Lab/repositories?language=&q=electrostat-lab&sort=&type=all).

## jMonkeyEngine Contributions: 
> Contributor `|` (2020 - Present)

Contributing to jMonkeyEngine, an open-source code-first approach complete 3D game engine suite written primarily in Java with GLSL Java bindings based on the OpenGL pipelines and modular API design, **for 4 years**.

### [Contributions](https://github.com/jMonkeyEngine/jmonkeyengine/commits?author=pavly-gerges) during this period:
- **[JmeSurfaceView](https://github.com/jMonkeyEngine/jmonkeyengine/tree/master/jme3-android/src/main/java/com/jme3/view/surfaceview)**: Proposed and introduced a GL Surface View handler component for embedding jMonkeyEngine Game Contexts into Android Layout Designs. Removing the burden to introduce jMonkeyEngine renderers in Android applications efficiently together with providing the interoperability with the Android Framework, and accelerating the development time by 35-40% approximately which is the time taken to setup custom Android activities and bind them to the native Android components. It has proven comptency in this pilot project [Game-HCI](https://github.com/Electrostat-Lab/Game-HCI), which houses reusable I/O Game GUI components leveraging the power of the MVC architectural patterns in addition to userinput lifecycle linkage through command-state and strategy patterns (i.e., controller interfaces).
  #### Features:
  * Binding of the Android choreographer lifecycle to jMonkeyEngine lifecycle (Game Application Lifecycle Pattern).
  * Splash Screen utility using CPU timeslices using initial frame pacing via Android Handlers.
  * Internal utilities for Android Activity services (e.g., screen manipulation).
  * Utilities for static game states and game resources caching for activity life cycles.
  * Verbose advanced error dialog for exception handling and reporting bugs.
  * Prompt memory handlers bound to the activity life cycle and the static game states utilities.

- **[ContrastAdjustmentFilter](https://github.com/jMonkeyEngine/jmonkeyengine/pull/1665)**: A postprocessor filter GLSL API that controls the 3D-color-gamut contrast of a frame buffer based on a bounded power law applied on the RGBA color vectors, making it easier to adjust scene colors contrast out-of-the-box (e.g., in day-night transition scenes). It was introduced in [jMonkeyEngine v3.5.0-beta4](https://github.com/jMonkeyEngine/jmonkeyengine/releases/tag/v3.5.0-beta4).
  #### Features:
  * 3D-color-gamut normalization to an input range.
  * Sanity guards against negative floating points.
  * Scalable inverse power law on the 3D-color gamut.

- **[Android Audio Bug Fix](https://github.com/jMonkeyEngine/jmonkeyengine/pull/1956)**: Resolved issues related to file resources release and ownership in the Android vorbis audio decoder library. The issue was preventing Android users from playing OGG files on Android systems due to the [Android file descriptor sanitizer](https://android.googlesource.com/platform/bionic/+/master/docs/fdsan.md) which protects the Unix file systems against anti-patterns.
  #### Issues resolved:
  * An anti-pattern introducing a double file closure.
  * Potential memory leaks at the File descriptor wrapper utilized by the vorbis decoder library.
  * Added Java documentation describing the correct pattern for the vorbis decoder.

- **Writing JavaDoc for an Old Animation System (MonkeyAnim)**: I've taken the initiative in writing JavaDocs for a 7-year-old undocumented and vague animation system (MonkeyAnim), and succeeded with the team guidance to [deliver some of it](https://github.com/jMonkeyEngine/jmonkeyengine/pulls?q=is%3Apr+com.jme3.anim+is%3Aclosed+author%3Apavly-gerges) on the currently working release [jMonkeyEngine v3.7.0](https://github.com/jMonkeyEngine/jmonkeyengine/releases/tag/v3.7.0-alpha1). The undocumented animation system was limiting our understanding of some parts implemented on the internals of the system which was hindering the development lifecycle of some games that rely heavily on the animation system.

- **Issues support and Community Management participations**: Issues related to the Android [jme3-android](https://github.com/jMonkeyEngine/jmonkeyengine/commits/master/jme3-android?author=pavly-gerges), and the core modules [jme3-core](https://github.com/jMonkeyEngine/jmonkeyengine/commits/master/jme3-core?author=pavly-gerges).

----------------------------------------------------------------------------------------

## Pi4j Contributions: 
> Technical Writing `|` A Featured Project `|` (2022)

Upon the request of one of the Pi4j community leaders, I published a hybrid project that utilizes both Pi4j-v1 and jMonkeyEngine framework as a [Pi4j-featured project](https://www.pi4j.com/featured-projects/joystick-game/); together with a full tutorial on hooking an Analog-Digital Circuit (MCP3008) onto the Raspberry Pi-4B GPIO through the Serial-Peripheral Interface (SPI) protocol. The tutorial also introduces insights on the conceptual model behind ADCs and DACs circuits. Collectively, the tutorial acts as a demo for I/O controlled Games using the [JoystickModule API](https://github.com/Electrostat-Lab/JoyStickModule).

----------------------------------------------------------------------------------------

## Electrostat-Lab Open-source Contributions: 
> OSS Embedded and Android Projects `|` (2020 - Present)

During the last 2 years, I've started my own open-source projects at [Electrostat-Lab](https://github.com/Electrostat-Lab) organization. 

### The vision of this organization:
The current vision of the Electrostat-Lab organization is to provide [a fully-fledged POSIX-based Open-Source Distributed Simulation Framework](https://github.com/Electrostat-Lab/Electrostatic-Sandbox); and it does this perfectly by dividing the framework into several smaller frameworks and APIs of re-usable code.

# Projects:
[My projects](https://github.com/orgs/Electrostat-Lab/repositories?language=&q=electrostat-lab&sort=&type=all) are located on the [Electrostat-Lab](https://github.com/Electrostat-Lab) GitHub organization. You can find them by typing `electrostat-lab` in the search to search for repositories with this tag. Of which, those are the most coolest projects that I've:

## Electrostatic-Sandbox SDK Suite (WIP)
> [GitHub](https://github.com/Electrostat-Lab/Electrostatic-Sandbox) - [Website](https://electrostat-lab.github.io/Electrostatic-Sandbox/) - [YouTube](https://www.youtube.com/watch?v=tkDjPSjAhhM&list=PLNLJxPHSQiq-WZCZQEpUaAA4zXOUlaIOz&index=1)
>
> **Description**: A work-in-progress open-source code-first complete SDK and development suite for distributed simulation systems based on the IEEE-1516 High-level Architecture Interface, GNU/Linux Kernel userspace APIs, and NASA DSES. The infrastructure of the sytem is subdivided into `Hardware IO Infrastructure (Project: ElectroIO)`, `Software and Networking Infrastructure (Project: ElectroNetSoft)`, and `Simulation Infrastructure (Project: ElectroSim)`.
>
> **Vision**: Build a complete layered framework for [distributed simulation systems](https://en.wikipedia.org/wiki/Distributed_Interactive_Simulation) on the top of the GNU/Linux systems to facilitate building distributed systems for scientific simulation of multiple disciplines including smart homes, smart hospitals, medical, aerospace, and military missions simulations.
>
> **Architecture**: Essentially, the Electrostatic-Sandbox SDK is a software development suite for designing and building distributed simulation systems, and it's decomposed into 3 subprojects: 
> * _Project: ElectroIO_, includes both _ElectroKIO_ and _ElectroMIO_ modules, and encapsulates the I/O channels cores.
>     * **_Project: ElectroKIO_**: entitled to encapsulate linux kernel userspace APIs that interact with the kernel through file system pipelines providing interfaces for the serial ports (RS232 - USB Serial - PS/2), parallel ports (IEEE-1284), ethernet ports (IEEE-803.2), and PCI-e ports.
>     * **_Project: ElectroMIO_**: encapsulates agnostic microcontrollers plain driver APIs featuring the AVR MCUs core communication protocols (GPIO - SPI - UART - ADC - TWI - PWM), together with a strong interface for future implementation of other MCU families.
> * _Project: ElectroNetSoft_, includes the software libraries (e.g., arithmos, di, articular-es,...) and the networking interfaces for some compatible IO cores.
> * _Project: ElectroSim_, encapsulates the _Runtime Infrastructure_ and the interfaces of the [HLA IEEE-1516 Standard](https://standards.ieee.org/ieee/1516/3744/) provided by IEEE for distributed simulation systems.
> 
> **Technical Writing**: The [AvrSandbox](https://github.com/Electrostat-Lab/Electrostatic-Sandbox/tree/master/embedded-system-design/avr-sandbox) blogs for embedded systems providing tutorials for common embedded protocols (e.g., GPIO, SPI, ADC) using the AVR MCUs, and digital design (e.g., Multiplexers, De-multiplexers, Shift Registers).
> 
> **Tools**: C/C++ - Java - Gradle - CMake - Bash - GNU/Linux Libc - Dot (GraphViz) - Tex (Latex) - AVR Toolchains - Android NDK - jMonkeyEngine - SDK programming - Realtime signal processing.
> 

## Serial4j Framework
> [GitHub](https://github.com/Electrostat-Lab/Electrostatic-Sandbox/tree/master/electrostatic-sandbox-framework/electrostatic4j/serial4j) - [TechDemo](https://www.youtube.com/watch?v=ebsMKR3PFVA)
>
> **Description**: A Java terminal IO framework based on the GNU/Linux termios API for communication with peripheral devices using the serial interface (e.g., USB Serial, RS232, and PS/2). Furthermore, it has been migrated to the Electrostatic-Sandbox SDK project!
>
> **Architecture**: The base architecture of Serial4j is based on the Data-Flow Systems, particularly Pipe-and-Filter Architectural design (i.e., the Filesystems and byte streams). The pipe is the plain filesystem and byte streams, while the filters are composed of main stream filters imposed by the operating system; that is the _Terminal_, controlling the byte streams and providing buffered, unbuffered, and line feed/return carriage buffered stream routines. Other filters are mutually exclusive components of the architecture known as _Human-Interface-Device_ APIs and _SerialMonitor APIs_; those provide new routines to manipulate byte streams as _Data Frames_; introducing a new type of buffered streams through accumulating data via modal logic (i.e., boolean algebra).
>
> **Vision**: The framework was designed essentially to provide innovators with custom controllers to bind to jMonkeyEngine Game Lifecycle for Kiosk-based systems, and it's deemed to reduce the development time in this instance by `40-50% of the total time`; the time taken to write the serial interface infrastructure, the HID components, and bind them to the Game Lifecycle.
>
> **Key Features**:
> - Hierarchial modular architecture in structure separating the native libraries from the Java APIs.
> - Cross-platform capabilities on POSIX interfaces.
> - Low-level File I/O APIs with `java.io` APIs specializations integratable with other applications.
> - Full terminal control modes for serial-based file I/O interpreted directly from the GNU/Linux POSIX APIs.
> - Serial Human-Interface-Device (HID) API providing specializations for serial-based devices and providing preprocessing and postprocessing filtering techniques for encoding, decoding, and encryption/decryption algorithms.
> - jMonkeyEngine integration examples with realtime data monitoring.
>
> **Tools**: Java SE Platform - C/C++ - CMake - Gradle - GNU/Linux Libc - Maven central - Realtime signal processing.
> 

## jSnapLoader API
> [GitHub](https://github.com/Electrostat-Lab/jSnapLoader) - [Maven-central](https://central.sonatype.com/artifact/io.github.electrostat-lab/snaploader)
>
> **Description**: A high-performance platform-independent Native Dynamic Library extractor and loader for JVM and Android Applications based on the Data-Flow and the Hierarchial Architectural patterns powered by an incremental extraction system that reduces libraries loading time significantly in subsequent runtimes, and supports building loader instances for new platforms via the platform predicates feature. Futhermore, the library solves the most headache-producing problem in developing cross-platform native applications; which is creating predicates for each system in the form of nested conditional statements, this library solves the problem using formula objects known as _PlatformPredicates_, which are formed of `P(X) = (OS && CPU && ARCH)`.
> 
> **Key Features**:
> -  Platform-specific dynamic libraries building using platform-specific predicates.
> -  File Locator and extractor routines (classpath - external jar).
> -  Retry Criterion with clean extraction.
> -  EventDispatchers: Extraction Listeners, Loading Listeners, and System Detection Listeners.
> -  Anti-failure mechanisms.
> -  Tight handling of memory leaks; as a result of file locator and/or file extractor failures.
> -  Memory logging of the stream providers' handlers using the object hash keys.
> -  Assets extraction through the `Filesystem` API (e.g., gltf files and images).
>
> **Used by**:
> The framework is currently deployed to be used by [Jolt-jni](https://github.com/stephengold/snap-jolt/tree/master), [Serial4j](https://github.com/Electrostat-Lab/Electrostatic-Sandbox/tree/master/electrostatic-sandbox-framework/electrostatic4j/serial4j), and [Electrostatic4j](https://github.com/Electrostat-Lab/Electrostatic-Sandbox/tree/master/electrostatic-sandbox-framework/electrostatic4j).
> 

## Articular-ES Framework
> [GitHub](https://github.com/Electrostat-Lab/Articular-ES) - [TechDemo](https://www.youtube.com/watch?v=CnjUakuqlMI) - [Maven-central](https://central.sonatype.com/artifact/io.github.software-hardware-codesign/articular-es)
>
> **Description**: An entity component system (ECS) framework featuring strong articulations among components from different systems through controller interfaces. The API is powered by a caching system that enables caching data in different configurations. Operational interactions take place within the system manager through the controller objects. The API provides a strong abstraction based on the data-centered architecture with the ability to model complex systems, such as: Human Interface Devices (HID) APIs, and language processing and translational APIs.
>
> **Architecture**: The API provides a strong abstraction based on the data-centered architecture with the ability to model complex systems, such as: Human Interface Devices (HID) APIs, and language processing and translational APIs. The framework is composed structurally of `Systems`, `Entities`, `Modules`, and `Components`, while behaviorly of `SystemControllers` and `DataPipes`.
>
> **Key Features**:
> * Entity-Component-System Data-centered standard architecture.
> * System Modules providing further software modularity.
> * Data pipe components facilitating modelling relations between components.
> * Built on top of abstract Memory Maps providing behavior-agnostic architecture.
> 
> **Tools**: Java SE Platform - Gradle - Entity-Component-System Architecture - jMonkeyEngine Framework - GitHub Actions (CI/CD).
> 

## Automata4j Framework
> [GitHub](https://github.com/Electrostat-Lab/Automata4j) - [TechDemo](https://www.linkedin.com/feed/update/urn:li:activity:7014704404347949056/?updateEntityUrn=urn%3Ali%3Afs_updateV2%3A%28urn%3Ali%3Aactivity%3A7014704404347949056%2CFEED_DETAIL%2CEMPTY%2CDEFAULT%2Cfalse%29&originTrackingId=%2BI05adX4SQKtJ99ZQvk5DQ%3D%3D) - [Maven-central](https://central.sonatype.com/artifact/io.github.software-hardware-codesign/automata4j)
>
> **Description and features**: A classic finite-states-automata (FSA) framework for JVM and Android applications featuring both the `Deterministic Finite Automata (DFA)` and the `Non-deterministic Finite Automata (NDFA)` together with the ability to cache states beforehand in finite-automata aggregates, through the `CascadedTransition` components, a type of finite-states transition path that superimposes cascaded paths through abstract `Queue` data structures.
> 

# My Education:
Graduated from [Faculty of Medicine and Surgery, October 6 University](https://o6u.edu.eg/Faculties.aspx?FactId=2) in 2023 with a Bachelor degree of Medicine and Surgery (M.B.B.Ch.) and GPA-3.15.

# Overview of my Computer Engineering education:
Though I'm a medical candidate, I've got enough wisdom over these years to find the common scientific bases among Software Engineering and Medicine, which are very huge to list them here in this section. Comprehensively, through this genuine way, I've been able to focus on and study both fields. Regarding computer engineering, I'm currently studying _Embedded Systems, and Game Engines Development_ among other pure sciences including, but not limited to, _Calculus, Linear Algebra and Discrete Mathematics_. I'm seeking more knowledge and wisdom in the field of _distributed simulation systems_ that combine all my studies in one place. All my studies run from books, documentation manuals, technical reports, and journals, and rarely workshop webinar tutorials.

