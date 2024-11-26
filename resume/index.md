# About Me:
> [GitHub](https://github.com/pavly-gerges) - [YouTube](https://www.youtube.com/@pavlg3944) - [LinkedIn](https://www.linkedin.com/in/pavly-gerges-420b81228/) - [Gmail](https://mail.google.com/mail/u/0/?fs=1&to=pepogerges33@gmail.com&su=SUBJECT&body=BODY&bcc=&tf=cm) - [WhatsApp](https://wa.me/201011912807)

 A self-taught OSS Engineer from the medical profession with a strong professional background in open-science and open-source Hardware/Software Engineering.

# Skills:
- **Languages**: Java - C/C++ - Kotlin - Bash (Shell Scripting) - Dot for architectural diagrams.
- **Java Platform**: Java Reflection API - Java Native Interface (JNI) - JNI Invocation API - Java Command-line tools.
- **Crossplatform API Design and development**: Software Architectural Design - Concurrent Programming - Object-oriented Design - Design Patterns - Game Programming Patterns - Entity-Component-System Design - Procedural Programming (Finite Automata) - Sqlite DB - Data Structures - Algorithms - POSIX - GNU Compiler Collection (GCC) - Android Core SDK - Android NDK - GLSL - OpenGL - Sonatype/Maven Deployment.
- **Technical Writing**: Documentation - Wikis - GraphViz - Latex.
- **Building, Automation and Testing**: CMake - BASH - JUnit - Git/GitHub VCS - GitHub Actions (CI/CD) - Windows-Subsystem For Linux (WSL) - Gradle - Gradle Plugins - Gradle Multi-project Builds - Valgrind - jconsole - GNU Debugger (GDB) - Valgrind.
- **Embedded Systems**: C/C++ Programming - Java Native Interface (JNI) - Microcontroller Programming - GNU/Linux Libc - jMonkeyEngine Framework - Hardware/Software Co-design - Distributed Simulations.
- **Pure Science**: Scientific Modelling - Scientific Philosophy - Discrete Mathematics - Calculus - Linear Algebra - Medical and Clinical Sciences.

# Experience:
> Essentially, all my contributions are entitled to open-source projects through different routes, either through non-profit open-source organizations (e.g., jMonkeyEngine - Pi4j) or through self-initiated projects on [Electrostat-Lab](https://github.com/Electrostat-Lab) organization, see the [projects section](https://github.com/orgs/Electrostat-Lab/repositories?language=&q=electrostat-lab&sort=&type=all).

## jMonkeyEngine Contributions: 
> Contributor `|` (2020 - Present)

Contributing to jMonkeyEngine, an open-source code-first approach complete 3D game engine suite written primarily in Java with GLSL Java bindings based on the OpenGL pipelines and modular API design, **for 4 years**.

### [Contributions](https://github.com/jMonkeyEngine/jmonkeyengine/commits?author=pavly-gerges) during this period:
- **[JmeSurfaceView](https://github.com/jMonkeyEngine/jmonkeyengine/tree/master/jme3-android/src/main/java/com/jme3/view/surfaceview)**: Proposed and introduced a GL Surface View handler component for embedding jMonkeyEngine Game Contexts into Android Layout Designs. Removing the burden to introduce jMonkeyEngine renderers in Android user applications efficiently together with interoperability with the Android Framework, and accelerating the development time by 35-40% approximately which is the time taken to setup custom Android activities and bind it to the native Android components. It has proven comptency in this pilot project [Game-HCI](https://github.com/Electrostat-Lab/Game-HCI), which houses reusable I/O Game GUI components leveraging the power of the MVC architectural patterns together with userinput lifecycle linkage through command-state and strategy patterns (i.e., controller interfaces).
  #### Features:
  * Binding of the Android choregrapher lifecycle to jMonkeyEngine lifecycle (Game Application Lifecycle Pattern).
  * Splash Screen utility using CPU timeslices.
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

- **Beginnings of the Serial4j framework**: Designed [Serial4j](https://github.com/Electrostat-Lab/Serial4j) back in 2021, a Java Terminal I/O framework for serial interfaces (e.g., Serial USB and RS232) based on the Data-Flow and the Data-centered architectural designs blending a lot of the previously learned skills, including, developing APIs using C/C++, building dynamic native libraries, using Gradle and CMake to build JNI applications, testing memory leaks, designing and implementing modal logic algorithms and byte-flow patterns, hardware/software co-design, plus introducing [a vision for distributed simulation systems](https://www.youtube.com/watch?v=4GFGsH4eyJs&t=235s). Serial4j solves the issue of effectively using serial devices on GNU/Linux machines for Java applications without the added complexities of the concurrency and multi-threading layers, and furthermore introducing the serial Human-Interface-Devices pattern to build comptent hardware for Embedded Game Development.

----------------------------------------------------------------------------------------

## Pi4j Contributions: 
> Technical Writing `|` (2022)

Upon the request of one of the Pi4j community leader, I've published a hybrid project that utilizes both Pi4j-v1 and jMonkeyEngine framework as a [Pi4j-featured project](https://www.pi4j.com/featured-projects/joystick-game/); in which I presented a full tutorial on hooking an Analog-Digital Circuit (MCP3008) onto the RPI GPIO through the Serial-Peripheral Interface (SPI) protocol. The tutorial also adds insights on the generic circuits and the conceptual model behind ADCs and DACs circuits.

----------------------------------------------------------------------------------------

## Electrostat-Lab Open-source Contributions: 
> OSS Embedded and Android Projects `|` (2020 - Present)

During the last 2 years, I've started my own open-source projects at [Electrostat-Lab](https://github.com/Electrostat-Lab) organization. 

### Development at Electrostat-Lab:
Electrostat-Lab projects tend to solve problems arising within different domains, mainly jMonkeyEngine community, and my unfinished game [JPluto Arcade Game](https://www.youtube.com/watch?v=HcerZ-8IWSo); which should utilize a wide aspect of Hardware/Software Co-design, so typically the rendering and physics pipelines are managed using jMonkeyEngine interfaces, while the controller interfaces are built using custom peripherals and interfaced over serial and networks. 

### The vision of this organization:
The current vision of the Electrostat-Lab organization is to provide [a fully-fledged POSIX-based Open-Source Distributed Simulation Framework](https://github.com/Electrostat-Lab/Electrostatic-Sandbox); and it does this perfectly by dividing the framework into several smaller frameworks and APIs of re-usable code.

# Projects:
[My projects](https://github.com/orgs/Electrostat-Lab/repositories?language=&q=electrostat-lab&sort=&type=all) are located on the [Electrostat-Lab](https://github.com/Electrostat-Lab) GitHub organization. You can find them by typing `electrostat-lab` in the search to search for repositories with this tag. Of which, those are the most coolest projects that I've:

## Gradle-At-A-Glance
> [GitHub](https://github.com/Electrostat-Lab/Gradle-At-A-Glance) - [Overview Video](https://www.youtube.com/watch?v=vUyPf0jyFxQ)
>
> **Description**: A critique project for the current Gradle Framework on the [gradle/gradle](https://github.com/gradle/gradle) repository featuring the Gradle platform modules and infrastructure, in addition to a fair comparison to a design of a home-made similar project using [the System-Entity-Structure/Model-Base Framework (SES/MB) for Modelling and Simulation](https://link.springer.com/chapter/10.1007/978-3-031-11085-6_1#Fig6), and [the Tricotyledon Theory of System Design (T3SD)](https://link.springer.com/chapter/10.1007/BFb0025045), known as "Ccoffee". Ccoffee is a provisional conceptual design for a virtual project written purely in the C programming language even providing services for hardware compatibility (i.e., Microcontrollers). The project is subdivided into multiple modules; where each module represents a collective solution for a sub-problem in the problems domain with a strong abstractive layer featuring the Hierarchial patterns, such that, the solution range involves `filesystem` module, `connection-handler` module, and `infrastructure` module.
>
> **Features**:
> - _Agnostic Build_: The most headache-producing part in Native project development is the building stage which is platform-specific, and it could be eliminated by using the `POSIX` interfaces and providing a clear way to pilot-building the project by itself using a wrapper API; which compiles, builds, and caches the project binaries for a faster second run.
> - _Robust Discrete Architecture_: According to the software ontology involved, the `filesystem` module deals with the primitive filesystems operations and is subdivided internally to a couple of API; `FileGenerator` component, `FileLocator` component, `FileEditor` component, `FileExtractor` component, and `FileUtils` component for extra manipulation, while the `connection-handler` module is devoted to provide the basis for the RESTful APIs, and is basically composed of `ConnectionEstablishmentHandler` component, `ConnectionMonitorHandler` component, `ConnectionInputStreamHandler` component, `ConnectionOutputStreamHandler` component, and `ConnectionListeners` component, and part of this might be categorized as a specialization of the `filesystem` APIs (i.e., depends-on/assembly relationship).
> - _Port to Embedded Systems and superiority over the Gradle Binaries_: Essentially, the beneficence of using the C programming langauge and the GNU C Collection is that it provides the ability to ship the project or at least the most relevant parts of it to run on bare-metal RISC MCUs (e.g., the AVR ATMega32) which is superior to the current Gradle and other building tools like CMake, but a clear usage for this feature is not fully studied, yet.
> 
> **Tools**: Java SE Platform - Gradle Plugin API - Plant UML Component Diagraphs - Intellij IDEA - Sonatype Maven Central.
> 

## GDude Gradle Plugin
WIP

## GMake Gradle Plugin
WIP

## jSnapLoader API
> [GitHub](https://github.com/Electrostat-Lab/jSnapLoader) - [Maven-central](https://central.sonatype.com/artifact/io.github.electrostat-lab/snaploader)
>
> **Description**: A high-performance platform-independent Native Dynamic Library extractor and loader for JVM and Android Applications based on the Data-Flow and the Hierarchial Architectural patterns.
> 
> **Features**:
> -  Platform-specific dynamic libraries' registration.
> -  Platform-specific dynamic libraries building using platform-specific predicates.
> -  Locate and load external dynamic libraries directly.
> -  File Locator and extractor routines (classpath - external jar).
> -  Extract native libraries from the stock jar library (classpath).
> -  Locate external jars and extract native libraries from them.
> -  Define an extract directory path.
> -  Retry Criterion with clean extraction.
> -  EventDispatchers: Extraction Listeners, Loading Listeners, and System Detection Listeners.
> -  Filesystem Failure Throwable Exceptions: binds the user API to the jSnapLoader lifecycle.
> -  Tight handling of memory leaks; as a result of file locator and/or file extractor failures.
> -  Memory logging of the stream providers' handlers using the object hash keys.
> -  Assets extraction through the `Filesystem` API (e.g., gltf files and images).
>  
> **Robust Discrete Architecture**: The architecture basically divides the library into subsets of APIs; each of them solves a subset problem of the major problem. The library solves the most headache-producing problem in developing cross-platform native applications; which is creating predicates for each system in the form of nested conditional statements, this library solves the problem using formula objects known as _PlatformPredicates_, which are formed of `P(X) = (OS && CPU && ARCH)`, and thus new _PlatformPredicates_ could be built on the user application side and not primarily hard-coded into the main API leading to a robust design with simple ideas picked from Discrete Mathematics and Modal Logic. Additionally, the framework offers a stock onloading anti-failure mechanism, and a stepwise command-state pattern to handle failures from the user application side enabling the implementation of several anti-failure routines from the user side. Furthermore, memory logging and tight handling of stream resources are attained on both the normal program flow and the exceptional cases (i.e., failure cases). The framework is open-ended for user-based specializations and wrappers APIs.
>
> **Used by**:
> The framework is currently deployed to be used by [Jolt-jni](https://github.com/stephengold/snap-jolt/tree/master), [Serial4j](https://github.com/Electrostat-Lab/Electrostatic-Sandbox/tree/master/electrostatic-sandbox-framework/electrostatic4j/serial4j), and [Electrostatic4j](https://github.com/Electrostat-Lab/Electrostatic-Sandbox/tree/master/electrostatic-sandbox-framework/electrostatic4j).
> 

## Serial4j Framework
> [GitHub](https://github.com/Electrostat-Lab/Serial4j) - [TechDemo](https://www.youtube.com/watch?v=ebsMKR3PFVA)
>
> **Description**: A Java terminal IO framework based on the GNU/Linux termios API for communication with peripheral devices using the serial interface (e.g., USB Serial, RS232, and PS/2).
>
> **Architecture**: The base architecture of Serial4j is based on the Data-Flow Systems, particularly Pipe-and-Filter Architectural design, so from a low-level perspective, the Filesystems and byte streams, which is very analogus conceptually to serialization and deserialization, but on wire. The pipe is the plain filesystem and byte streams, while the filters are composed of main stream filters imposed by the operating system; that is the Terminal, that controls the byte streams providing buffered, unbuffered, and line feed/return carriage buffered stream routines. Other filters are mutually exclusive parts of the architecture known as _Human-Interface-Device_ APIs and _SerialMonitor APIs_; those provide new routines to manipulate byte streams as _Data Frames_; so essentially introducing a new type of buffered streams through accumulating data via modal logic (or boolean algebra aka. bitwise operations). The framework was designed essentially to provide innovators with custom controllers to bind to jMonkeyEngine Game Lifecycle for Kiosk-based systems.
>
> **Features**:
> - Hierarchial modular architecture in structure separating the native libraries from the Java APIs.
> - Cross-platform capabilities on POSIX interfaces.
> - Low-level File I/O APIs with `java.io` APIs specializations integratable with other applications.
> - Full terminal control modes for serial-based file I/O interpreted directly from the GNU/Linux POSIX APIs.
> - Serial Human-Interface-Device (HID) API providing specializations for serial-based devices signifying the `read()` and `write()` operations and providing preprocessing and postprocessing filtering techniques for encoding, decoding, and encryption/decryption algorithms.
> - jMonkeyEngine integration examples with realtime data monitoring.
>
> **Tools**: Java SE Platform - C/C++ - CMake - Gradle - GNU/Linux Libc - [ShiftAvr](https://github.com/Electrostat-Lab/ShiftAvr/) - WSL - Maven central.
> 

## GMonitor Gradle Plugin
> [GitHub]() - [TechDemo]() - [Maven-central]()
>
> **Description**: Creates a portable _Serial Monitor_ plugin to be used beside embedded systems applications on embedded linux machines and the raspberry pi through integrating the Serial4j framework into the Gradle Framework via a Gradle Plugin that distributes the jobs of the Serial4j _Serial Monitor_ into Gradle tasks.
>
> **Features**:
> - Starts a continous serial monitor session on a port of user selection.
> - Supports jMonkeyEngine application integration controls out-of-the-box.
> - Dynamically changeable baud rate, file modes, and terminal modes.
> - Anti-failure detection and anti-failure routines through the legacy exception handling.
> - Layered architecture separating the concurrency and thread-dependent APIs from the terminal, low-level I/O, serial monitor, and HID APIs.
> - Deployed for x86, x86-64, arm32, and arm64 systems as distributed dependencies on maven-central.
>
> **Tools**: Java SE Platform - Gradle Plugins API - [Serial4j Framework](https://github.com/Electrostat-Lab/Electrostatic-Sandbox/tree/master/electrostatic-sandbox-framework/electrostatic4j/serial4j) - Maven Central - Intellij IDEA

## Jector Framework
> [GitHub](https://github.com/Electrostat-Lab/Jector) - [TechDemo](https://www.youtube.com/watch?v=CjjXpxce37w) - [Maven-central](https://central.sonatype.com/artifact/io.github.software-hardware-codesign/jector)
>
> **Description**: An advanced DI framework for JVM and Android applications based on the Java Reflection API with a specialized implementation for jMonkeyEngine Applications.
>
> **Features**: Jector provides a programming concurrent (order-parallelism/sync) model for best practices by injecting functions' stacks into schedulable tasks, and in turn into their designated threads. Threads can be activated and controlled to achieve either parallelism or synchronicity. Its threading model could be used for assets asynchronous loading, async tasks execution, and mutual multithreading (threading using mutual events).
>
> **Tools**: Java SE Platform - Gradle - jMonkeyEngine Framework.

## Articular-ES Framework
> [GitHub](https://github.com/Electrostat-Lab/Articular-ES) - [TechDemo](https://www.youtube.com/watch?v=CnjUakuqlMI) - [Maven-central](https://central.sonatype.com/artifact/io.github.software-hardware-codesign/articular-es)
>
> **Description**: An entity component system (ECS) framework featuring strong articulations among components from different systems through controller interfaces. The API is powered by a caching system that enables caching data in different configurations. Operational interactions take place within the system manager through the controller objects.
>
> **Architecture**: The API provides a strong abstraction based on the data-centered architecture with the ability to model complex systems, such as: Human Interface Devices (HID) APIs, and language processing and translational APIs. The framework is composed structurally of `Systems`, `Entities`, `Modules`, and `Components`, while behaviorly of `SystemControllers` and `DataPipes`.
>
> **Features**:
> 
> **Tools**: Java SE Platform - Gradle - Entity-Component-System Architecture - jMonkeyEngine Framework - GitHub Actions (CI/CD).
> 

## Automata4j Framework
> [GitHub](https://github.com/Electrostat-Lab/Automata4j) - [TechDemo](https://www.linkedin.com/feed/update/urn:li:activity:7014704404347949056/?updateEntityUrn=urn%3Ali%3Afs_updateV2%3A%28urn%3Ali%3Aactivity%3A7014704404347949056%2CFEED_DETAIL%2CEMPTY%2CDEFAULT%2Cfalse%29&originTrackingId=%2BI05adX4SQKtJ99ZQvk5DQ%3D%3D) - [Maven-central](https://central.sonatype.com/artifact/io.github.software-hardware-codesign/automata4j)
>
> **Description and features**: A classic finite-states-automata (FSA) framework for JVM and Android applications featuring both the `Deterministic Finite Automata (DFA)` and the `Non-deterministic Finite Automata (NDFA)` together with the ability to cache states beforehand in finite-automata aggregates, through the `CascadedTransition` components, a type of finite-states transition path that superimposes cascaded paths through abstract `Queue` data structures.
> 

## Game-HCI
> [GitHub](https://github.com/Electrostat-Lab/Game-HCI) - [TechDemo1](https://www.youtube.com/watch?v=Gp2JJ-PCI8c) - [TechDemo2](https://www.youtube.com/watch?v=Jog8FdHDeOU) - [Jitpack-io](https://jitpack.io/#Electrostat-lab/Game-HCI)
>
> **Description**: An Android API housing useful re-usbable Human-computer Interfaces (HCI) in the form of in-game android views with an integration API for jMonkeyEngine featuring the Model-View-Controller (MVC) Architecture for designing GUI components and providing a binding API to the jMonkeyEngine Lifecycle.
>
> **Features**: The API has a couple of ready-to-use components, including but not limited to, a `GameStickView` component and a `ControllerButtonsView` component, a `DrivingWheelView` component, a `GullWing` component for spacecrafts, a `Tachometer` and a `UTurnView` generically for vehicles, plus other Android Menustate items. The API is available on `Jitpack-io` for public use.
> 
>

## Electrostatic-Sandbox SDK Suite (WIP)
> [GitHub](https://github.com/Electrostat-Lab/Electrostatic-Sandbox) - [Website](https://electrostat-lab.github.io/Electrostatic-Sandbox/)
>
> **Description**: A work-in-progress open-source code-first complete SDK and development suite for distributed simulation systems based on the IEEE-1516 High-level Architecture Interface, GNU/Linux Kernel userspace APIs, and NASA DSES. The infrastructure of the sytem is subdivided into `Networking Infrastructure`, `Software Infrastructure`, and `Simulation Infrastructure`.
>
> **Architecture**: Essentially, the `Networking Infrastructure` is composed of a common communication protocol API abstracting off the different serial and parallel communication cores (e.g., TCP/IP, Serial Interfaces RS232 Standard and USB Standard, Parallel Standard IEEE-1284 or Centronics, Ethernet Standard IEEE-802.3), the `Software Infrastructure` is composed mainly of the firewall APIs, the database APIs, and the rest of operating system resources handler APIs (e.g., MemoryManagers and WindowManagers) in addition to the `Runtime Infrastructure (RTI)` and the `RTI Interfaces` defined by the [HLA IEEE-1516 Standard](https://standards.ieee.org/ieee/1516/3744/) for Distributed Simulation Systems.
> 

# My Education:
I graduated from [Faculty of Medicine and Surgery, October 6 University](https://o6u.edu.eg/Faculties.aspx?FactId=2) in 2023 with GPA-3.15, and currently taking my medical internship. I am currently holding a Bachelor degree of Medicine and Surgery (M.B.B.Ch.), however, not entitled yet to practice medicine. 

# Overview of my Computer Engineering education:
Though I'm a medical candidate, I've got enough wisdom over these years to find the common scientific bases among Software Engineering and Medicine, which are very huge to list them here in this section. Comprehensively, through this genuine way, I've been able to focus on and study both fields. Regarding computer engineering, I'm currently studying Embedded Systems, and Game Engines Development among other pure sciences including, but not limited to, Calculus, Linear Algebra and Discrete Mathematics. I'm seeking more knowledge and wisdom in the field of distributed simulation systems that combine all my studies in one place. All my studies run from books, documentation manuals, technical reports, and journals, and rarely workshop webinar tutorials.
> 
