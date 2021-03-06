# Phoronix Test Suite Release History

Phoronix Test Suite 7.4
======
#### Release Date: 19 September 2017 | Codename: Tynset
* `phoronix-test-suite unload-module` and `phoronix-test-suite auto-load-module` and `phoronix-test-suite network-info` sub-commands
* Inline showing of test results when benchmarking against an existing result file from the CLI
* New `perf_tips` module for reporting various performance tips to users
* New `ob_auto_compare` module to provide inline seamless OpenBenchmarking.org result references to tests currently running from CLI
* Dropped `graphics_event_checker`
* Improved screensaver handling
* Various Phodevi improvements

Phoronix Test Suite 7.2
======
#### Release Date: 8 June 2017 | Codename: Trysil
* Result parser improvements
* `phoronix-test-suite dump-file-info`, `phoronix-test-suite dump-tests-to-git`, `phoronix-test-suite dump-suites-to-git` sub-commands
* Phoromatic support for setting run priorities on test schedules

Phoronix Test Suite 7.0
======
#### Release Date: 6 March 2017 | Codename: Ringsaker
* New `phoronix-test-suite estimate-run-time` and `phoronix-test-suite winners-and-losers` sub-commands
* Phoromatic database improvements
* New system software/hardware display formatting
* Support for having one test run generate multiple test result outputs
* `phoronix-test-suite stress-run` improvements

Phoronix Test Suite 6.8
======
#### Release Date: 28 November 2016 | Codename: Tana
* BSD support improvements.
* New `phoronix-test-suite list-not-installed-tests` and `phoronix-test-suite php-conf` sub-commands
* New `flamegrapher` module
* New `results_custom_export` module
* Phodevi hardware/software detection improvements

Phoronix Test Suite 6.6
======
#### Release Date: 6 September 2016 | Codename: Loppa
* Graphing improvements
* Phoromatic web UI tweaks
* Improved disk detail reporting

Phoronix Test Suite 6.4
======
#### Release Date: 2 June 2016 | Codename: Hasvik
* `phoronix-test-suite stress-run` improvements
- Phoromatic support for stress testing
- Phoromatic support for email notifications and other features
- Watchdog module for suspending/stopping temperatures if sensor thresholds reached

Phoronix Test Suite 6.2
======
#### Release Date: 16 February 2016 | Codename: Gamvik
* Dynamic dependency handler infrastructure
* Windows support improvements
* LimitNetworkCommunication option
* Reworked generation of PDF test results
* Continued Phoromatic plumbing improvements
* Initial Vulkan detection/support

Phoronix Test Suite 6.0
======
#### Release Date: 16 November 2015 | Codename: Hammerfest
* Rework of the Phoromatic web interface
* New local results viewer using HTML+JS
* Result parsing improvements
* Rework of low-level infrastructure / underlying improvements / faster merging
* Improved SVG graph generation
* New graph rendering interface for pts_Graph

Phoronix Test Suite 5.8
======
#### Release Date: 5 June 2015 | Codename: Belev
* MIPS support improvements
* Faster rendering of result files and other data processing improvements
* Stress-run improvements
* System sensor monitoring via the Phoromatic UI
* Addition of the Phoromatic Results Export Viewer
* Various Linux hardware & software detection improvements
* Allow Phoronix Test Suite clients to be self-updated via update script passed from the Phoromatic Server
* Mongoose web server support for the Phoromatic Server's HTTP instance
* Support viewing system client logs via the Phoromatic Server UI
* Numerous other improvements to Phoromatic

Phoronix Test Suite 5.6
======
#### Release Date: 24 March 2015 | Codename: Dedilovo
* Many Phoromatic Improvements
* Phoromatic Server Search Support
* Phoromatic Server Stress-Run Controls
* Support For Commenting/Annotating Result Files
* Support For Custom System Variables To Be Used By Result File Strings
* Rootadmin additions & Controls
* Support For Results Via RSS
* Allow One-Time Benchmark Runs & Issuing Of Benchmark Tickets
* Allow Uploading Of Results To OpenBenchmarking.org Via Viewer Page
* Allow Forming Of Custom Test Suites Via Build Suite Page
* Add stress-run Sub Command To Phoronix Test Suite Client
* OS X Support Improvements

Phoronix Test Suite 5.4
======
#### Release Date: 9 December 2014 | Codename: Lipki
* Major overhaul to the built-in Phoromatic Server
* Avahi zero-conf networking support
* Improved download cache handling
* IBM POWER8 hardware detection improvements
* Various code refactoring & other improvements

Phoronix Test Suite 5.2
======
#### Release Date: 5 June 2014 | Codename: Khanino
* Tech Preview / Experimental Built-In Phoromatic Server
* Result graphing improvements, including new box plot graphs
* Phodevi software & hardware detection improvements
* Phodevi Radeon GPU usage reporting via RadeonTOP
* New Phoronix Test Suite sub-command options
* Bug-fixes and other minor enhancements

Phoronix Test Suite 5.0
======
#### Release Date: 12 March 2014 | Codename: Plavsk
* Tech Preview / Experimental HTML5 GUI
* Run-random-tests command
* Phodevi Hardware/Software Detection Improvements
* Start-up Speed Enhancements
* Numerous bug-fixes
* Assorted minor improvements

Phoronix Test Suite 4.8
======
#### Release Date: 13 August 2013 | Codename: Sokndal
* Minimum / maximum result reporting
* Frame latency / jitter testing support
* Improved hardware/software detection support
* NVIDIA/AMD AIB GPU board detection support
* Facebook HHVM (HipHop Virtual Machine) 2.1 support
* Graph coloring improvements
* System detail reporting improvements
* Phodevi hardware sensor improvements
* Phoromatic.com support improvements

Phoronix Test Suite 4.6
======
#### Release Date: 21 May 2013 | Codename: Utsira
* Compiler masking/flag improvements
* Phodevi enhancements
* DragonFlyBSD support improvements
* Support for running under Facebook HHVM HipHop Virtual Machine
* New internal-run sub-command
* Phodevi hardware/software improvements

Phoronix Test Suite 4.4
======
#### Release Date: 20 February 2013 | Codename: Forsand
* Phodevi Hardware/Software Detection Improvements
* OpenBenchmarking.org Integration Enhancements
* Improved Reporting Of Test Installation Errors
* Improved Reporting Of Test Run-Time Errors
* Improved BSD Operating System Support
* Rewritten PTS External Dependencies Handling
* Improved Compiler/User Flag Reporting On Test Results

Phoronix Test Suite 4.2
======
#### Release Date: 20 December 2012 | Codename: Randaberg
* Desktop Support Improvements
* Phodevi Support For IMPI Detection
* New auto-compare Option For Facilitating Fully Automated Comparisons
* Add list-recommended-tests Option
* Various Minor Enhancements

Phoronix Test Suite 4.0
======
#### Release Date: 23 July 2012 | Codename: Suldal
* New Result Viewer Interface
* Performance-per-Watt / Energy Monitoring Improvements
* Hardware/Software Detection Improvements
* Greater Documentation
* New Result Analytical Features

Phoronix Test Suite 3.8
======
#### Release Date: 19 March 2012 | Codename: Bygland
* Improved Disk Reporting
* Improved Compiler Option/Configuration Reporting
* New Graph Renderer
* Improved ARM / Mobile Device Support
* Download Caching Enhancements
* Re-written Graphics Event Checker
* Support For Apple Mac OS X 10.8

Phoronix Test Suite 3.6
======
#### Release Date: 13 December 2011 | Codename: Arendal
* Enhanced Support For BSD, Solaris Operating Systems
* Various Graphing Improvements
* Expanded Phodevi Library Coverage
* Greater OpenBenchmarking.org Integration
* Various Bug Fixes

Phoronix Test Suite 3.4
======
#### Release Date: 8 September 2011 | Codename: Lillesand
* MATISK Benchmarking Module
* Improved Phodevi Device Recognition
* Graphing Improvements
* Third-Party Test/Suite Uploading From The Phoronix Test Suite Client
* Continued OpenBenchmarking.org Integration Enhancements
* GNU Hurd Operating System Support

Phoronix Test Suite 3.2
======
#### Release Date: 15 June 2011 | Codename: Grimstad
* Facebook HipHop Compiler Support
* Improved Software Detection
* Improved Hardware Detection
* Support For New System Sensors
* Improved Wine Compatibility
* Interactive Text Mode Support

Phoronix Test Suite 3.0
======
#### Release Date: 26 February 2011 | Codename: Iveland
* OpenBenchmarking.org Integration
* Enhanced Multi-OS, Multi-Architecture Capabilities
* Internal Architectural Enhancements
* Improved Graph Rendering

Phoronix Test Suite 2.8
======
#### Release Date: 31 August 2010 | Codename: Torsken
* 134 Test Profiles
* 56 Test Suites + PCQS
* New Analytics Capabilities
* New Installation & External Dependency Management Support
* Improved Windows 7 x64 Support

Phoronix Test Suite 2.6
======
#### Release Date: 24 May 2010 | Codename: Lyngen
* 134 Test Profiles
* 56 Test Suites + PCQS
* New Test Results Parsing Mechanism
* New PTS Results Viewer Interface
* Phoromatic / Phoromatic Tracker Improvements
* Functional Windows 7 x64 Support

Phoronix Test Suite 2.4
======
#### Release Date: 24 February 2010 | Codename: Lenvik
* 131 Test Profiles
* 54 Test Suites + PCQS
* Palm webOS / Optware Support
* Improved *BSD OS Support
* Image Quality Comparison Support
* Improved Sensor Monitoring
* GTK2 User Interface Enhancements
* New Network Engine
* Initial Phodevi / pts-core Support On Windows

Phoronix Test Suite 2.2
======
#### Release Date: 16 November 2009 | Codename: Bardu
* 120 Test Profiles
* 50 Test Suites + PCQS
* Automated Regression Tracking Module (Autonomous Git Bisecting)
* Test Recovery Support
* Statistical Significance Support
* Anonymous Usage Reporting
* Display Mode Support
* Network Proxy Support
* Overhauled GTK2 GUI

Phoronix Test Suite 2.0
======
#### Release Date: 4 August 2009 | Codename: Sandtorg
* 109 Test Profiles
* 47 Test Suites + PCQS
* Expanded Reference System Comparisons
* Many New Test Options
* Introduction Of Phodevi Library
* Overhaul To GTK2 User Interface
* New Test Profile Options
* Initial Release Of PTS Desktop Live

Phoronix Test Suite 1.8
======
#### Release Date: 6 April 2009 | Codename: Selbu
* 90 Test Profiles
* 39 Test Suites + PCQS
* GTK2 Graphical User Interface
* Enhanced *BSD Support
* Support For Reference System Comparisons
* Image Renderer Optimizations
* Updated Test Options
<a href="?k=changes_18">Complete Change-Log</a>

Phoronix Test Suite 1.6
======
#### Release Date: 20 January 2009 | Codename: Tydal
* 89 Test Profiles
* 36 Test Suites + PCQS
* Options To Build Your Own Suite
* An Adobe PDF Generator For Test Results
* Support Multiple Arguments When Installing/Running Tests
* Introduce bilde_renderer, Add Support For Rendering Adobe Flash / SWF Graphs
* Support For Virtual Suites
* New Features In pts-core
* Numerous New Options

Phoronix Test Suite 1.4
======
#### Release Date: 3 November 2008 | Codename: Orkdal
* 84 Test Profiles
* 34 Test Suites + PCQS
* Mac OS X Support
* Cascading Test Profiles
* Self-Contained Test Profiles
* More Modules
* WINE-based Tests
* OpenSolaris 2008.11 Support
* SVG Graph Rendering Option
<a href="?k=changes_14">Complete Change-Log</a>

Phoronix Test Suite 1.2
======
#### Release Date: 3 September 2008 | Codename: Malvik
* 76 Test Profiles
* 38 Test Suites
* Improved Hardware Detection
- Multi-Monitor Support
- Multi-GPU Support
* Modular Plug-in Framework
- System Monitoring Module
- E-Mail Results Module
- Graphics Override Module
- Screensaver Control Module
* OpenSolaris 2008.05 Support
* FreeBSD / *BSD Support
* Improved Graph Rendering
* Result Analysis Option
* Improved Documentation

Phoronix Test Suite 1.0
======
#### Release Date: 5 June 2008 | Codename: Trondheim
Initial Stable Release
* 57 Test Profiles
* 23 Test Suites
* Download Caching Support
* XML-based Test / Suite System
* Support For Managing External Dependencies
* Basic Hardware, Software Detection Support
* Automated Test Installation
* Integrated Results Viewer
* Line, Bar, Boolean Graphing Support
* Batch Mode Support
* Global Test Upload Capability
* Support Across All Major Linux Distributions
