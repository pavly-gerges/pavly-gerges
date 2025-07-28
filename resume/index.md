# About Me:

A self-taught embedded software engineer with a demonstrated background in embedded systems, microcontroller programming, and distributed simulation theory seeking to contribute to open-source and proprietary software in _Embedded Microcontroller Programming_, _Embedded Linux_, and _safety-critical systems engineering_ domains. 

I essentially architect, implement, and maintain open-source embedded software products for **4+ years** taking ideas from observation and theory to real life fully-fledged deployable software to solve low-level devastating problems in Embedded Systems industry (e.g., building distributed simulations, loading native libraries, re-programming bad fuse bits).

My goal is to build an SDK Suite to bootstrap distributed simulation systems integrating both software systems and hardware switch and controls.

# Skills:
- **Programming and scripting**: Java - C/C++ - Kotlin - Bash (Shell Scripting) - Dot for architectural diagrams.
- **Embedded Systems**: C/C++ Programming (3+ years) - Java Native Interface (JNI) - AVR Toolhchain - Android NDK - Embedded Systems Design (Decoders, Encoders, Circuit Design) - Microcontroller Programming (GPIO, UART, I2C, SPI, ADC, PWM) - Technical Datasheet Analysis - GNU/Linux Libc - Kernel userspace APIs - Realtime signal processing - jMonkeyEngine Framework - Hardware/Software Co-design - Distributed Simulations.
- **Electronics**: Hardware Prototyping - Soldering for assembly and repair - PCB Design - Kicad - Multimeters - Custom development modules.
- **Building, Automation and Testing**: CMake - BASH - Git/GitHub VCS - GitHub Actions (CI/CD) - Gradle - Gradle Multi-project Builds - Valgrind - jconsole - GNU Debugger (GDB).
- **Crossplatform API development**: Software Architectural Design - Concurrent Programming - Object-oriented Design - Design Patterns - Game Programming Patterns - Entity-Component-System Design - Procedural Programming (Finite Automata) - Sqlite DB - Data Structures - Algorithms - POSIX - GNU Compiler Collection (GCC) - Android SDK - GLSL - OpenGL - Sonatype/Maven Deployment.
- **Technical Writing**: Documentation - Wikis - GraphViz - Latex.
- **Pure Science**: Scientific Modelling - Scientific Philosophy - Discrete Mathematics - Calculus - Linear Algebra - Medical and Clinical Sciences.

# Experience:
> Contributed to open-source projects through non-profit open-source organizations (e.g., jMonkeyEngine - Pi4j) and projects on the [Electrostat-Lab](https://github.com/Electrostat-Lab) organization.

## Electrostat-Lab Open-source Contributions: 
> Embedded Software Engineer `|` (2020 - Present) <br/>
> Led the design, development and deployment of open-source projects solving various real-life problems; see the [projects section](https://github.com/orgs/Electrostat-Lab/repositories?language=&q=electrostat-lab&sort=&type=all).

* Initiated and leading the active development lifecycle of the [Electrostatic-Sandbox SDK Suite](https://github.com/Electrostat-Lab/Electrostatic-Sandbox) to solve the devastating problem of bootstrapping distributed simulation systems by integration of software and hardware (e.g., Rocket Launching Simulations, Flight Simulations, and Switch and Control Military Simulations).
* Led the design philosophy, engineering, testing, and maintenance of [Serial4j](https://github.com/Electrostat-Lab/Serial4j), a Java terminal I/O library for character devices control on GNU/Linux systems, solving problems of integrating custom hardware control systems with the already-existing graphics and physics simulations bearing in mind system quality and integrity through the good use of concurrency and multi-threading.
* Engineered and deployed multiple releases for [jSnapLoader](https://github.com/Electrostat-Lab/jSnapLoader), a high-performance cross-platform native dynamic libraries loader (DLL) for JVM and Android applications powered by an incremental loading system, stable release on maven-central reducing time porting the native Java frameworks to other platforms by approx. **30%** by its unique design philosophy that utilizes `Platform Predicates` instead of the legacy nested conditional statements.
* Led the design philosophy, development, testing, and deployment of [Jector](https://github.com/Electrostat-Lab/Jector), a concurrency model API featuring the dependency injection and lazy execution patterns solving the [Multithreading in AssetManager](https://github.com/jMonkeyEngine/jmonkeyengine/issues/5) issues, on [maven-central](https://central.sonatype.com/artifact/io.github.software-hardware-codesign/jector/overview) reducing the frame rendering latency and the frame drops for the OpenGL-based Java Game Engines by approx. **70%** of frames per a single second while doing CPU-extensive tasks (e.g., Asset Loading, Building procedural worlds).
* Engineered and deployed [Automata4j](https://github.com/Electrostat-Lab/Automata4j), a classic finite-state-automaton framework for JVM and Android applications, as a proof-of-concept (POF) for _the applied computational theory_ with an approx. **80%** compliancy on the formal logic of **_the Automata Theory_** minimizing the effort of implementing scientific prototypes and projects that are based on the Automata Theory (e.g., research projects based on the formal languages).
* Led the design philosophy and development of [ffplay-ip-cam](https://github.com/Electrostat-Lab/ffplay-ip-cam), a complete structured script toolset for IP Cameras AV streaming, solving the issue of realtime streaming and recording video and audio on GNU/Linux systems using Smart IP Cameras over the RTSP Protocol.
* Leading the active analysis, recovery of data, and simulation of a selected curated list of complex systems that had led to devastating catastrophic accidents in the past on the [Embedded-Cybernetics](https://github.com/Electrostat-Lab/Embedded-Cybernetics/); in addition to suggesting and re-iterating on some maneuvers that could be introduced to enhance the safety of the industry significantly by **95%** on the selected systems.

## Pi4j Contributions: 
> Project Technical Writer `|` A Featured Project `|` (2022)

Upon the request of one of the Pi4j community leaders, I published an article about a hybrid project that utilizes both Pi4j-v1 and jMonkeyEngine framework as a [Pi4j-featured project](https://www.pi4j.com/featured-projects/joystick-game/); together with a full tutorial on hooking an Analog-Digital Circuit (MCP3008) onto the Raspberry Pi-4B GPIO through the Serial-Peripheral Interface (SPI) protocol. The tutorial also introduces insights on the conceptual model behind ADCs and DACs circuits. Collectively, the tutorial acts as a demo for I/O controlled Games using the [JoystickModule API](https://github.com/Electrostat-Lab/JoyStickModule).

## jMonkeyEngine Contributions: 
> OSS Contributor `|` (2020 - Present) <br/>
> [Contributed to jMonkeyEngine](https://github.com/jMonkeyEngine/jmonkeyengine/commits?author=pavly-gerges), an open-source code-first approach complete 3D game engine suite written primarily in Java with GLSL Java bindings based on the OpenGL pipelines and modular API design.

- **[JmeSurfaceView](https://github.com/jMonkeyEngine/jmonkeyengine/tree/master/jme3-android/src/main/java/com/jme3/view/surfaceview)**: Designed, developed, tested, and actively maintaining a GL Surface View handler component for embedding jMonkeyEngine Game Contexts into Android Layout Designs. Removing the burden to introduce jMonkeyEngine renderers in Android applications efficiently together with providing the interoperability with the Android Framework, and **accelerating the development time by 50% approx. when it comes to integrating OGLES renderers in the already-existing Android Apps**.
  #### Brief list of features:
  * Binding of the Android choreographer lifecycle to jMonkeyEngine lifecycle (Game Application Lifecycle Pattern).
  * Splash Screen utility using CPU timeslices by initial frame pacing via Android Handlers.
  * Utilities for static game states and game resources caching for activity life cycles.
  * Verbose advanced error dialog for exception handling and reporting bugs.
  * Prompt memory handlers bound to the activity life cycle and the static game states utilities.

- **[ContrastAdjustmentFilter](https://github.com/jMonkeyEngine/jmonkeyengine/pull/1665)**: Designed, developed, tested and actively maintaining a postprocessor filter GLSL API that controls the 3D-color-gamut contrast of a frame buffer based on a power law with clamp values applied on the RGBA color vectors, making it easier to adjust scene colors contrast out-of-the-box (e.g., in day-night transition scenes). The feature was integrated in [jMonkeyEngine v3.5.0-beta4](https://github.com/jMonkeyEngine/jmonkeyengine/releases/tag/v3.5.0-beta4).
  #### Brief list of features:
  * 3D-color-gamut normalization to an input range.
  * Sanity guards against negative floating points.
  * Scalable inverse power law on the 3D-color gamut.

- **[Android Audio Bug Fix](https://github.com/jMonkeyEngine/jmonkeyengine/pull/1956)**: Reproduced and resolved issues of file resources release and ownership in the Android vorbis audio decoder library. The issue was preventing Android users from playing OGG files on Android systems due to the [Android file descriptor sanitizer](https://android.googlesource.com/platform/bionic/+/master/docs/fdsan.md) which protects the Unix file systems against anti-patterns.
  #### Issues resolved:
  * An anti-pattern forcing a double file closure on the native NDK/JNI-side.
  * Potential memory leaks at the File descriptor wrapper utilized by the vorbis decoder library.
  * Added Java documentation describing the correct pattern for the vorbis decoder.

- **Writing JavaDoc for an Old Animation System (MonkeyAnim)**: Writing JavaDocs for a 7-year-old undocumented and vague animation system (MonkeyAnim), and shipping [some](https://github.com/jMonkeyEngine/jmonkeyengine/pulls?q=is%3Apr+com.jme3.anim+is%3Aclosed+author%3Apavly-gerges) with the team guidance on the release [jMonkeyEngine v3.7.0](https://github.com/jMonkeyEngine/jmonkeyengine/releases/tag/v3.7.0-alpha1).

- **Issues support and Community Management participations**: Issues of the Android Platform [jme3-android](https://github.com/jMonkeyEngine/jmonkeyengine/commits/master/jme3-android?author=pavly-gerges), and the core modules [jme3-core](https://github.com/jMonkeyEngine/jmonkeyengine/commits/master/jme3-core?author=pavly-gerges).

## Neurosurgery Internship: 
> Internship `|` (2023 - 2025) <br/>
> Neurosurgery Assistant surgeon 

Assisted in surgical planning and in-surgery techniques in intricate neurospinal surgeries (e.g., Open spinal canal decompression, Lumbar Laminectomy and Diskectomy via a posterior lumbosacral approach), neurocranial surgeries (e.g., Open craniotomies for acute epidural hematomas via pterional approaches) and peripheral nerve entrapment surgeries (e.g., Open Carpal Tunnel Decompressions), in addition to basic history analysis, physical examination, patient monitoring techniques, and participating in the interpretation of the various diagnostic studies.

# Projects:
## Electrostatic-Sandbox SDK Suite
> [GitHub](https://github.com/Electrostat-Lab/Electrostatic-Sandbox) - [Website](https://electrostat-lab.github.io/Electrostatic-Sandbox/) - [YouTube](https://www.youtube.com/watch?v=tkDjPSjAhhM&list=PLNLJxPHSQiq-WZCZQEpUaAA4zXOUlaIOz&index=1)
>
> **Description**: A work-in-progress open-source code-first complete SDK and development suite for distributed simulation systems based on the IEEE-1516 High-level Architecture Interface, GNU/Linux Kernel userspace APIs, and NASA DSES. The infrastructure of the system is subdivided into `Hardware IO Infrastructure (Project: ElectroIO)`, `Software and Networking Infrastructure (Project: ElectroNetSoft)`, and `Simulation Infrastructure (Project: ElectroSim)`.
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
> **Hardware/PCB design and prototyping**: Designed and assembled a custom development board, the _"ElectroIO"_ development board, for prototyping, wiring, and building projects using the _ElectroMIO_ IO API. The board is a modular multiple PCB boards featuring a _CPU Module_, a _Power Module_, and a _Comm Module_ enabling hardware durability and adaptability for newly designed CPU Modules, in addition to decreasing the design and implementation time of the novel boards by more than 50% of the time; as hardware modules are adaptable and reusable across almost all microcontrollers.
> 
> **Technical Writing**: The [AvrSandbox](https://github.com/Electrostat-Lab/Electrostatic-Sandbox/tree/master/embedded-system-design/avr-sandbox) blogs for embedded systems providing tutorials for common embedded protocols (e.g., GPIO, SPI, ADC) using the AVR MCUs, and digital design (e.g., Multiplexers, De-multiplexers, Shift Registers).
> 
> **Tools**: C/C++ - Java - Gradle - Kicad - Multimeters - CMake - Bash - GNU/Linux Libc - Dot (GraphViz) - Tex (Latex) - AVR Toolchains - Android NDK - jMonkeyEngine - SDK programming - Realtime signal processing.
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
> **Description**: A high-performance platform-independent Native Dynamic Library extractor and loader for JVM and Android Applications based on the Data-Flow and the Hierarchial Architectural patterns powered by an incremental extraction system that reduces libraries loading time significantly in subsequent runtimes. Furthermore, the library solves the most headache-producing problem in developing cross-platform native applications; which is creating predicates for each system in the form of nested conditional statements, this library solves the problem using formula objects known as _PlatformPredicates_, which are formed of `P(X) = (OS && CPU && ARCH)`.
> 
> **Used by**:
> Authored a stable deployment on maven-central to be used by [Jolt-jni](https://github.com/stephengold/snap-jolt/tree/master), [Serial4j](https://github.com/Electrostat-Lab/Electrostatic-Sandbox/tree/master/electrostatic-sandbox-framework/electrostatic4j/serial4j), and [Electrostatic4j](https://github.com/Electrostat-Lab/Electrostatic-Sandbox/tree/master/electrostatic-sandbox-framework/electrostatic4j).
> 

## Articular-ES Framework
> [GitHub](https://github.com/Electrostat-Lab/Articular-ES) - [TechDemo](https://www.youtube.com/watch?v=CnjUakuqlMI) - [Maven-central](https://central.sonatype.com/artifact/io.github.software-hardware-codesign/articular-es)
>
> **Description**: An entity component system (ECS) framework featuring strong articulations among components from different systems through controller interfaces. The API is powered by a caching system that enables caching data in different configurations. Operational interactions take place within the system manager through the controller objects. The API provides a strong abstraction based on the data-centered architecture with the ability to model complex systems, such as: Human Interface Devices (HID) APIs, and language processing and translational APIs.
>
> **Deployment**: Authored semi-stable pre-releases on maven-central.

## Automata4j Framework
> [GitHub](https://github.com/Electrostat-Lab/Automata4j) - [TechDemo](https://www.linkedin.com/feed/update/urn:li:activity:7014704404347949056/?updateEntityUrn=urn%3Ali%3Afs_updateV2%3A%28urn%3Ali%3Aactivity%3A7014704404347949056%2CFEED_DETAIL%2CEMPTY%2CDEFAULT%2Cfalse%29&originTrackingId=%2BI05adX4SQKtJ99ZQvk5DQ%3D%3D) - [Maven-central](https://central.sonatype.com/artifact/io.github.software-hardware-codesign/automata4j)
>
> **Description and features**: A classic finite-states-automata (FSA) framework for JVM and Android applications featuring both the `Deterministic Finite Automata (DFA)` and the `Non-deterministic Finite Automata (NDFA)` together with the ability to cache states beforehand in finite-automata aggregates, through the `CascadedTransition` components, a type of finite-states transition path that superimposes cascaded paths through abstract `Queue` data structures.
>
> **Vision**: It's contemplated that this paradigm will enhance embedded systems development by 2x its speed while keeping the logic close to the formal logic.
> 
> **Deployment**: Authored pre-releases on maven-central as a future application-level paradigm (competing object-oriented and functional paradigms using computational modelling).

# My Education:
Graduated from [Faculty of Medicine and Surgery, October 6 University](https://o6u.edu.eg/Faculties.aspx?FactId=2) in 2023 with a Bachelor degree of Medicine and Surgery (M.B.B.Ch.) and GPA-3.15.

# Overview of my Computer Engineering education:
Equivalent experience of bachelor's degree of computer science tailored for Embedded Systems. (Theory of computation - Discrete Mathematics - Calculus - Digital and Analog Electronics - Computer Organization - Software Design - Data structure and algorithms design - Programming languages).

