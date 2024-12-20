# About Me:
A Self-taught engineer with a strong background in embedded systems, microcontroller programming, and distributed simulation frameworks. Seeking to contribute to cutting-edge hardware/software co-design projects.

# Skills:
- **Languages**: Java (5+ years), C/C++ (3+ years), Kotlin (2 years), Bash (Shell Scripting) (4 years), Dot for architectural diagrams.
- **Embedded Systems**: C/C++ Programming (3+ years), Java Native Interface (JNI), AVR Toolchain, Android NDK, Embedded Systems Design (Decoders, Encoders, Circuit Design), Microcontroller Programming (Arduino, AVR, PIC).
- **Electronics**: Hardware Prototyping, Soldering for assembly and repair, PCB Design, Kicad, Multimeters, Custom development modules.
- **Building, Automation and Testing**: CMake, BASH, Git, GitHub, GitHub Actions (CI/CD), Gradle, Gradle Multi-project Builds, Valgrind, jconsole, GNU Debugger (GDB).
- **Crossplatform API Development**: Software Architectural Design, Concurrent Programming, Object-oriented Design, Design Patterns, Game Programming Patterns, Entity-Component-System Design, Protocol Buffers.
- **Technical Writing**: Documentation, Wikis, GraphViz, Latex.
- **Pure Science**: Scientific Modelling, Scientific Philosophy, Discrete Mathematics, Calculus, Linear Algebra, Medical and Clinical Sciences.

# Experience:
> Essentially, all my contributions are entitled to open-source projects through different routes, either through non-profit open-source organizations (e.g., jMonkeyEngine, Pi4j) or through self-initiated projects.

## jMonkeyEngine Contributions:
> Contributor `|` (2020 - Present)

Contributing to jMonkeyEngine, an open-source code-first approach complete 3D game engine suite written primarily in Java with GLSL Java bindings based on the OpenGL pipelines and modular API design.

### [Contributions](https://github.com/jMonkeyEngine/jmonkeyengine/commits?author=pavly-gerges) during this period:
- **[JmeSurfaceView](https://github.com/jMonkeyEngine/jmonkeyengine/tree/master/jme3-android/src/main/java/com/jme3/view/surfaceview)**: Proposed and introduced a GL Surface View handler component for Android.
  #### Features:
  * Binding of the Android choreographer lifecycle to jMonkeyEngine lifecycle (Game Application Lifecycle Pattern).
  * Splash Screen utility using CPU timeslices using initial frame pacing via Android Handlers.
  * Internal utilities for Android Activity services (e.g., screen manipulation).
  * Utilities for static game states and game resources caching for activity life cycles.
  * Verbose advanced error dialog for exception handling and reporting bugs.
  * Prompt memory handlers bound to the activity life cycle and the static game states utilities.

- **[ContrastAdjustmentFilter](https://github.com/jMonkeyEngine/jmonkeyengine/pull/1665)**: A postprocessor filter GLSL API that controls the 3D-color-gamut contrast of a frame buffer based on a bound input range.
  #### Features:
  * 3D-color-gamut normalization to an input range.
  * Sanity guards against negative floating points.
  * Scalable inverse power law on the 3D-color gamut.

- **[Android Audio Bug Fix](https://github.com/jMonkeyEngine/jmonkeyengine/pull/1956)**: Resolved issues related to file resources release and ownership in the Android vorbis audio decoder library.
  #### Issues resolved:
  * An anti-pattern introducing a double file closure.
  * Potential memory leaks at the File descriptor wrapper utilized by the vorbis decoder library.
  * Added Java documentation describing the correct pattern for the vorbis decoder.

- **Writing JavaDoc for an Old Animation System (MonkeyAnim)**: I've taken the initiative in writing JavaDocs for a 7-year-old undocumented and vague animation system (MonkeyAnim), and succeeded with comprehensive documentation.

- **Issues support and Community Management participations**: Issues related to the Android [jme3-android](https://github.com/jMonkeyEngine/jmonkeyengine/commits/master/jme3-android?author=pavly-gerges) module and community support.

----------------------------------------------------------------------------------------

## Pi4j Contributions:
> Technical Writing `|` A Featured Project `|` (2022)

Upon the request of one of the Pi4j community leaders, I published a hybrid project that utilizes both Pi4j-v1 and jMonkeyEngine framework as a [Pi4j-featured project](https://www.pi4j.com/featured-projects.html).

----------------------------------------------------------------------------------------

## Electrostat-Lab Open-source Contributions:
> OSS Embedded and Android Projects `|` (2020 - Present)

During the last 2 years, I've started my own open-source projects at [Electrostat-Lab](https://github.com/Electrostat-Lab) organization.

### The vision of this organization:
The current vision of the Electrostat-Lab organization is to provide [a fully-fledged POSIX-based Open-Source Distributed Simulation Framework](https://github.com/Electrostat-Lab/Electrostatic-Sandbox).

# Projects:
[My projects](https://github.com/orgs/Electrostat-Lab/repositories?language=&q=electrostat-lab&sort=&type=all) are located on the [Electrostat-Lab](https://github.com/Electrostat-Lab) GitHub organization.

## Electrostatic-Sandbox SDK Suite
> [GitHub](https://github.com/Electrostat-Lab/Electrostatic-Sandbox) - [Website](https://electrostat-lab.github.io/Electrostatic-Sandbox/) - [YouTube](https://www.youtube.com/watch?v=tkDjPSjAhhM&list=PL0JtL0XKyyP3xB7LqQbWQ9OZ6U8thk3pV)
>
> **Description**: A work-in-progress open-source code-first complete SDK and development suite for distributed simulation systems based on the IEEE-1516 High-level Architecture Interface, GNU/Linux Kernel APIs, and GNU Toolchains.
>
> **Vision**: Build a complete layered framework for [distributed simulation systems](https://en.wikipedia.org/wiki/Distributed_Interactive_Simulation) on the top of the GNU/Linux systems to facilitate the development and deployment of high-fidelity simulations.
>
> **Architecture**: Essentially, the Electrostatic-Sandbox SDK is a software development suite for designing and building distributed simulation systems, and it's decomposed into 3 subprojects: 
> * _Project: ElectroIO_, includes both _ElectroKIO_ and _ElectroMIO_ modules, and encapsulates the I/O channels cores.
>     * **_Project: ElectroKIO_**: entitled to encapsulate linux kernel userspace APIs that interact with the kernel through file system pipelines providing interfaces for the serial ports (RS232 - USB - UART).
>     * **_Project: ElectroMIO_**: encapsulates agnostic microcontrollers plain driver APIs featuring the AVR MCUs core communication protocols (GPIO - SPI - UART - ADC - TWI - PWM), together with a set of custom modules for specific tasks (e.g., motor control, sensor integration).
> * _Project: ElectroNetSoft_, includes the software libraries (e.g., arithmos, di, articular-es,...) and the networking interfaces for some compatible IO cores.
> * _Project: ElectroSim_, encapsulates the _Runtime Infrastructure_ and the interfaces of the [HLA IEEE-1516 Standard](https://standards.ieee.org/ieee/1516/3744/) provided by IEEE for distributed simulation systems.
> 
> **Hardware/PCB design and prototyping**: Designed and assembled a custom development board, the _"ElectroIO"_ development board, for prototyping, wiring, and building projects using the _ElectroMIO_ modules.
> 
> **Technical Writing**: The [AvrSandbox](https://github.com/Electrostat-Lab/Electrostatic-Sandbox/tree/master/embedded-system-design/avr-sandbox) blogs for embedded systems providing tutorials for configuring and programming AVR microcontrollers.
> 
> **Tools**: C/C++, Java, Gradle, Kicad, Multimeters, CMake, Bash, GNU/Linux Libc, Dot (GraphViz), Tex (Latex), AVR Toolchains, Android NDK, jMonkeyEngine, SDK programming, Realtime signal processing.

## Serial4j Framework
> [GitHub](https://github.com/Electrostat-Lab/Electrostatic-Sandbox/tree/master/electrostatic-sandbox-framework/electrostatic4j/serial4j) - [TechDemo](https://www.youtube.com/watch?v=ebsMKR3PFVA)
>
> **Description**: A Java terminal IO framework based on the GNU/Linux termios API for communication with peripheral devices using the serial interface (e.g., USB Serial, RS232, and PS/2). Furthermore, it provides comprehensive APIs for integrating serial communication into Java applications, including jMonkeyEngine-based projects.
>
> **Architecture**: The base architecture of Serial4j is based on the Data-Flow Systems, particularly Pipe-and-Filter Architectural design (i.e., the Filesystems and byte streams). The pipe is the plain data stream that transfers data, whereas the filter is the processing block that transforms the data.
>
> **Vision**: The framework was designed essentially to provide innovators with custom controllers to bind to jMonkeyEngine Game Lifecycle for Kiosk-based systems, and it's deemed to reduce the development and integration time significantly.
>
> **Key Features**:
> - Hierarchical modular architecture in structure separating the native libraries from the Java APIs.
> - Cross-platform capabilities on POSIX interfaces.
> - Low-level File I/O APIs with `java.io` APIs specializations integratable with other applications.
> - Full terminal control modes for serial-based file I/O interpreted directly from the GNU/Linux POSIX APIs.
> - Serial Human-Interface-Device (HID) API providing specializations for serial-based devices and providing preprocessing and postprocessing filtering techniques for encoding, decoding, and encryption.
> - jMonkeyEngine integration examples with realtime data monitoring.
>
> **Tools**: Java SE Platform, C/C++, CMake, Gradle, GNU/Linux Libc, Maven central, Realtime signal processing.

## jSnapLoader API
> [GitHub](https://github.com/Electrostat-Lab/jSnapLoader) - [Maven-central](https://central.sonatype.com/artifact/io.github.electrostat-lab/snaploader)
>
> **Description**: A high-performance platform-independent Native Dynamic Library extractor and loader for JVM and Android Applications based on the Data-Flow and the Hierarchical Architectural pattern.
> 
> **Key Features**:
> - Platform-specific dynamic libraries building using platform-specific predicates.
> - File Locator and extractor routines (classpath - external jar).
> - EventDispatchers: Extraction Listeners, Loading Listeners, and System Detection Listeners.
> - Anti-failure mechanisms with retry criteria.
> - Tight handling of memory leaks; as a result of file locator and/or file extractor failures.
> - Memory logging of the stream providers' handlers using the object hash keys.
> - Assets extraction through the `Filesystem` API (e.g., gltf files and images).
>
> **Used by**:
> Authored a stable deployment on maven-central to be used by [Jolt-jni](https://github.com/stephengold/snap-jolt/tree/master), [Serial4j](https://github.com/Electrostat-Lab/Electrostatic-Sandbox/tree/master/electrostatic-sandbox-framework/electrostatic4j/serial4j), and other projects.

## Articular-ES Framework
> [GitHub](https://github.com/Electrostat-Lab/Articular-ES) - [TechDemo](https://www.youtube.com/watch?v=CnjUakuqlMI) - [Maven-central](https://central.sonatype.com/artifact/io.github.software-hardware-engineering/articular-es)
>
> **Description**: An entity component system (ECS) framework featuring strong articulations among components from different systems through controller interfaces. The API is powered by a caching system to enhance performance.
>
> **Architecture**: The API provides a strong abstraction based on the data-centered architecture with the ability to model complex systems, such as: Human Interface Devices (HID) APIs, and language processing interfaces.
>
> **Key Features**:
> * Entity-Component-System Data-centered standard architecture.
> * System Modules providing further software modularity.
> * Data pipe components facilitating modelling relations between components.
> * Built on top of abstract Memory Maps providing behavior-agnostic architecture.
> 
> **Tools**: Java SE Platform, Gradle, Entity-Component-System Architecture, jMonkeyEngine Framework, GitHub Actions (CI/CD).
>
> **Deployment**: Authored semi-stable pre-releases on maven-central.

## Automata4j Framework
> [GitHub](https://github.com/Electrostat-Lab/Automata4j) - [TechDemo](https://www.linkedin.com/feed/update/urn:li:activity:7014704404347949056/?updateEntityUrn=urn%3Ali%3Afs_updateV2%3A%28urn%3Ali%3Aactivity%3A7014704404347949056%29)
>
> **Description and features**: A classic finite-states-automata (FSA) framework for JVM and Android applications featuring both the `Deterministic Finite Automata (DFA)` and the `Non-deterministic Finite Automata (NFA)`.
>
> **Vision**: It's contemplated that this paradigm will enhance embedded systems development by 2x its speed while keeping the logic close to the formal logic.
> 
> **Deployment**: Authored pre-releases on maven-central as a future application-level paradigm (competing object-oriented and functional paradigms using computational modelling).

# My Education:
Graduated from [Faculty of Medicine and Surgery, October 6 University](https://o6u.edu.eg/Faculties.aspx?FactId=2) in 2023 with a Bachelor degree of Medicine and Surgery (M.B.B.Ch.) and GPA-3.15.

# Overview of my Computer Engineering education:
Equivalent experience of bachelor's degree of computer science tailored for Embedded Systems. (Theory of computation, Discrete Mathematics, Calculus, Digital and Analog Electronics, Computer Organization).
