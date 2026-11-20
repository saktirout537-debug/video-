# SHIFT: detailed website research and product inventory

Research date: 20 November 2026  
Primary website: https://shiftspc.com/  
Advertised version at review: 2.7.1

## Scope and evidence

This document consolidates information extracted earlier in this chat from the SHIFT homepage, About page, complete feature directory, FAQ, ten topic guides, setup instructions, pricing, downloads, support, privacy notice, terms, refund policy, and linked Gumroad listing.

It records published product descriptions, not an independent software test, security audit, or hardware benchmark. Website statements about functionality and privacy are attributed to SHIFT. Prices, packaging, policies, and product versions reflect the pages observed on the research date. This is a detailed paraphrased research inventory, not a verbatim archive of every page or asset.

The app screen recording and the separate motion-design reference are outside this website inventory.

## 1. Product identity

| Field | Extracted information |
|---|---|
| Product name | SHIFT; linked purchase listing uses SHIFT PC |
| Category | Portable Windows PC monitoring and diagnostics software |
| Advertised version | 2.7.1 |
| Devices | Windows laptops and desktops |
| Operating systems | Windows 10 and Windows 11, subject to build compatibility |
| Architectures | x64, x86, ARM64 |
| Core functions | Live monitoring, hardware inventory, Windows diagnostics, local Deep Check, optional repair assistance, saved reports and comparisons |
| Processing model | Monitoring and Deep Check run locally and offline |
| Payment model | One-time digital software purchase |
| Advertised base price | ₹759 |
| Delivery platform | Gumroad |
| Support and privacy email | shiftscpc@gmail.com |

### Positioning and brand language

The site positions SHIFT around understanding PC behavior, investigating warning signs, and choosing the next check using available evidence. Its homepage combines early-warning language with an explicit qualification that diagnostics cannot guarantee hardware safety.

Brand phrases visible during review included:

- “Don’t wait for your PC to fail.”
- “A clearer PC experience.”
- “Hardware, drivers, system health.”
- “Get the complete picture.”
- “Your PC. Decoded.” on the Gumroad listing.

### How the site describes AI

The homepage calls SHIFT a portable monitoring and diagnostics app with a local AI agent. The more precise operational description on the feature pages, guides, and FAQ is that Deep Check applies diagnostic rules to Windows evidence locally. The site states that this does not send evidence to a cloud AI model.

The About page describes version 2.7.1 as an early version of its AI and acknowledges that it may make mistakes or miss hardware details, particularly deeper component-level issues. The reviewed pages do not establish a particular language model, model architecture, training method, or general-purpose conversational AI capability.

Sources: [Homepage](https://shiftspc.com/), [About](https://shiftspc.com/about.html), [Features](https://shiftspc.com/features.html), [Gumroad](https://shiftscape.gumroad.com/l/whynjw).

## 2. Problems addressed and practical benefits

The following maps documented features to the user questions they help investigate. Benefits describe supported workflows, not guaranteed outcomes.

| User problem or question | Relevant SHIFT capabilities | Practical benefit and boundary |
|---|---|---|
| Why is my PC slow? | Resource dashboard, per-app usage, disk activity, resource pressure, performance analysis | Observe which activity coincides with a slowdown and choose a focused next check; a busy resource alone does not prove a fault. |
| Why does a game or editing application stutter? | CPU/GPU/RAM/VRAM readings, adapter selection, graphs, latency diagnostics | Compare readings during a repeatable workload rather than guessing from idle readings. |
| Is one application using too much memory? | Per-app private memory, available RAM, paging, compression, memory-growth observation | Record a memory-use pattern; short observations do not establish a memory leak. |
| Is my PC overheating? | Supported temperatures, sensor diagnostics, advisory thresholds, thermal alerts | Understand available sensor readings in workload context and compare with manufacturer limits. |
| Can I respond to persistent high temperatures? | Selected-app closing and optional force-close | Configure optional actions after review; these cannot guarantee hardware safety. |
| Why did Windows restart or show a blue screen? | Crash records, frequency, stop codes, dump headers, event logs | Build a record around an incident and identify evidence for further investigation. |
| Could a driver or device be involved? | Driver versions, dates, signatures, related errors, device codes | Gather specific details for targeted troubleshooting. |
| Why is startup slow? | Boot timing, degradation events, startup apps/tasks/services/extensions | Review startup evidence and candidates for further investigation. |
| Is storage nearly full or showing warnings? | Free-space checks, available SMART data, wear and reliability counters | Review available warning information and capacity; coverage depends on providers and drives. |
| Why is a drive slow? | Activity, response time, queues, short read/write tests, supported HDD fragmentation analysis | Collect storage-performance observations without assuming every busy disk is failing. |
| Why does the laptop battery last less time? | Reported full-charge/design capacities, runtime, charge and power status | Separate reported capacity reduction from workload-related power use. |
| What hardware and Windows version do I have? | Hardware inventory and CPU/GPU details | Gather configuration context for requirements, troubleshooting, or support. |
| What does a diagnostic finding mean? | Explained findings, evidence browser, check status | Inspect evidence, scope, suggested action, and recheck guidance before acting. |
| Are relevant Windows protections enabled? | Security checks, Defender status, update and restart indicators | Review available Windows security information; no independent antivirus-engine claim is established. |
| Can I keep diagnostics local? | Offline checks, local processing, local reports, protected scan storage | Run checks without automatic diagnostic uploads to SHIFT servers, according to the privacy notice. |
| How can I share useful evidence? | PDF, HTML, text, JSON, CSV, scan history and comparison | Prepare an appropriate support handoff and inspect identifiers before sharing. |
| How can I watch readings while working? | Mini mode, pinning, transparency, tray mode | Keep supported readings accessible in a compact view. |

Sources: [FAQ](https://shiftspc.com/faq.html), [Guides](https://shiftspc.com/guides.html), [Features](https://shiftspc.com/features.html).

## 3. Complete inventory of all 81 features

The directory groups its features into eight categories. Counts: 11 + 7 + 18 + 8 + 11 + 7 + 9 + 10 = 81.

Source for all entries in this section: [SHIFT feature directory](https://shiftspc.com/features.html). Category labels below follow the directory's grouping; descriptions are paraphrased.

### 3.1 Live monitoring — 11 features

| # | Feature | Published capability |
|---|---|---|
| 1 | Live dashboard | Bring CPU, GPU, RAM, VRAM, battery, and available temperature readings together. |
| 2 | CPU monitoring | Track processor utilization to observe demanding workloads. |
| 3 | GPU monitoring | Read graphics utilization from supported driver providers or Windows counters. |
| 4 | VRAM monitoring | Separate dedicated graphics-memory use, dedicated capacity, and shared RAM. |
| 5 | GPU selection | Select the adapter used for graphics-load and memory readings. |
| 6 | RAM & reserved memory | Show physical-memory usage and memory Windows reserves for applications. |
| 7 | Disk monitoring | Follow storage activity, transfer speed, response time, and queued requests. |
| 8 | Performance graphs | Review resource patterns over time, including advanced counters for driver interruptions, page faults, threads, and open system objects. |
| 9 | Per-app usage | Inspect CPU, supported GPU activity, and private-memory use for running software. |
| 10 | Resource pressure | Combine readings to show sustained pressure across CPU, graphics, memory, or storage. |
| 11 | Network latency | Measure a test message's round-trip time to a host in milliseconds. |

GPU readings use providers available through the graphics driver and Windows. Different adapters and counters need like-for-like comparison.

### 3.2 Temperature and hardware readings — 7 features

| # | Feature | Published capability |
|---|---|---|
| 12 | Temperature monitoring | Read supported CPU, GPU, and graphics-memory temperature sensors. |
| 13 | Hardware readings | Show available clock speeds, voltages, and fan readings. |
| 14 | Temperature limits | Set component advisory levels and highlight elevated readings. |
| 15 | Thermal alerts | Notify about temperatures and sustained resource pressure. |
| 16 | Protective app closing | Ask selected applications to close when high temperatures persist. |
| 17 | Optional force-close | End selected apps remaining open after a grace period; disabled by default. |
| 18 | Sensor diagnostics | Inspect the source, recency, and availability of sensor readings. |

Sensor coverage depends on hardware, drivers, and permissions. The site directs users to Temperatures & Sensors for detected readings. Protective closing requires selecting eligible applications and does not guarantee safety. Force-close can discard unsaved work.

### 3.3 PC hardware and Windows diagnostics — 18 features

| # | Feature | Published capability |
|---|---|---|
| 19 | Diagnostic scans | Run all diagnostic areas or individual checks. |
| 20 | Hardware inventory | Review processor, motherboard, firmware, RAM, storage, graphics, network, and Windows information. |
| 21 | CPU details | Inspect processor specifications and supported current readings. |
| 22 | GPU details | Review adapter properties, driver information, and supported graphics readings. |
| 23 | Crash analysis | Inspect blue-screen codes, dump headers, crash records, and hard resets. |
| 24 | Crash history | Review recorded crash frequency and recurring instability. |
| 25 | Event log analysis | Group repeated System/Application warnings, errors, and critical events. |
| 26 | Driver analysis | Inspect versions, dates, signatures, and related error evidence. |
| 27 | Device errors | Review Windows device status and reported device error codes. |
| 28 | Boot analysis | Examine recorded startup timings and boot-degradation events. |
| 29 | Startup review | Review apps, sign-in tasks, services, and Windows extensions affecting startup. |
| 30 | Service analysis | Check service states, startup modes, errors, and process-memory use. |
| 31 | Memory analysis | Inspect available RAM, reserved memory, disk-backed memory, compression, and Windows system memory. |
| 32 | Memory growth | Observe an app briefly to see whether its memory use grows. |
| 33 | Performance analysis | Take a focused sample of Windows performance readings to investigate slowdown. |
| 34 | Latency diagnostics | Inspect driver-related delays, processor interruptions, timer precision, and scheduling variation. |
| 35 | Power configuration | Review the active Windows power plan and settings that permit processor cores to idle. |
| 36 | Registry checks | Look for missing references in startup settings, services, file associations, and sampled component registrations. |

The site distinguishes ongoing monitoring from a focused performance sample. Its registry description establishes reference checks, not a blanket registry-cleaning promise.

### 3.4 Storage and battery — 8 features

| # | Feature | Published capability |
|---|---|---|
| 37 | Disk health | Read available storage-health status and SMART failure-prediction flags. |
| 38 | Drive self-check details | Inspect supported SMART attributes and reported problem sectors. |
| 39 | SSD wear | Show available wear estimates, power-on hours, and reliability counters. |
| 40 | Free-space checks | Flag volumes with limited remaining capacity. |
| 41 | Storage benchmarks | Measure drive read/write performance through short temporary-file tests. |
| 42 | HDD fragmentation | Analyze fragmentation on a supported rotational system drive. |
| 43 | Battery health | Compare reported full-charge capacity with matched design-capacity records. |
| 44 | Power status | Show charge, reported runtime, AC connection, and battery-saver state. |

Drive health uses information the device reports. Battery health uses reported capacity values; neither establishes the physical safety or complete condition of a component.

### 3.5 Local Windows Deep Check — 11 features

| # | Feature | Published capability |
|---|---|---|
| 45 | Security checks | Review Windows protection, administrator prompts, secure startup, drive encryption, and restart indicators. |
| 46 | Deep Check | Assess broader Windows evidence using local diagnostic rules. |
| 47 | Explained findings | Show the condition, evidence, source, suggested action, and recheck guidance. |
| 48 | Evidence browser | Search collected information and inspect underlying records. |
| 49 | Defender status | Review available protection settings, signatures, and detection history. |
| 50 | Network inspection | Review adapters, addresses, name-resolution settings, gateways, and active connections. |
| 51 | Hardware error history | Review recorded hardware, display, filesystem, and storage-controller warnings. |
| 52 | Update inventory | Review installed-update records and pending-restart signs. |
| 53 | Windows integrity check | Inspect Windows components and protected system files using Windows diagnostic tools. |
| 54 | Defender full scan | Optionally request a full scan through active Microsoft Defender. |
| 55 | File inventory | Collect a limited list of file names and sizes without reading personal file contents. |

The integrity-check description points users to the separate system-file repair action if they choose repair after reviewing results. Defender scanning uses Microsoft Defender and requires it to be active.

### 3.6 Optional repair assistance — 7 features

| # | Feature | Published capability |
|---|---|---|
| 56 | Repair assistance | Open relevant Windows tools and show next steps linked to findings. |
| 57 | System file repair | Launch Windows component and system-file repair tools for review. |
| 58 | Disk repair check | Open Windows disk checking for a selected drive, subject to scheduling, repair, and restart prompts. |
| 59 | Service controls | Start, enable, or delay selected services through supported actions. |
| 60 | Power adjustments | Apply supported power-plan and processor-idle changes while plugged in. |
| 61 | Device rescan | Ask Windows to scan for hardware changes and open Optional Updates. |
| 62 | Restore checkpoints | Verify a Windows restore point before actions configured to require one. |

The site advises saving work and reviewing scope, permissions, and prompts before changes. Some repair tools need administrator approval. The restore-checkpoint feature is conditional; it is not a published promise that every action automatically creates a restore point.

### 3.7 Reports and history — 9 features

| # | Feature | Published capability |
|---|---|---|
| 63 | Diagnostic scores | Display scores alongside coverage and check results. |
| 64 | Scan history | Save structured scan snapshots for later review. |
| 65 | Scan comparison | Compare an earlier scan with current findings and supported readings. |
| 66 | PDF reports | Export standard findings or graphical scan-history reports. |
| 67 | Deep Check reports | Save findings as a web page, plain text, or JSON. |
| 68 | Report management | Preview, print, and delete selected reports with matching saved scan data. |
| 69 | Monitoring logs | Save alerts, action results, and optional five-second monitoring samples. |
| 70 | Spreadsheet export | Export monitoring history as CSV. |
| 71 | Log retention | Rotate monitoring logs and optionally remove older dated files. |

Scores summarize available diagnostic checks rather than measuring physical hardware damage. Exports serve different purposes; the guides do not promise that every live graph appears in every PDF.

### 3.8 Privacy and everyday use — 10 features

| # | Feature | Published capability |
|---|---|---|
| 72 | Local processing | Run Deep Check locally without sending evidence to a cloud AI model. |
| 73 | Protected storage | Protect structured scan data with Windows encryption tied to the current user account. |
| 74 | Report privacy | Redact common identifying details from supported exports. |
| 75 | Mini version | Use a small monitoring window with pinning and adjustable transparency. |
| 76 | Tray mode | Optionally keep SHIFT running in the Windows system tray. |
| 77 | Appearance settings | Choose design, light/dark appearance, colors, fonts, and text size. |
| 78 | Animated companion | Choose an animated character and the SHIFT Run mini-game. |
| 79 | Portable app | Select an architecture-specific build, extract the archive, and run SHIFT. |
| 80 | Permission handling | Use administrator approval for deeper system readings and checks. |
| 81 | Clear check status | Distinguish completed, partial, unavailable, canceled, and unrequested checks. |

Report redaction still requires user review before sharing. The reviewed text does not specify the precise Windows encryption API or algorithm.

## 4. Interface, visual identity, and demonstrated workflows

### Product views featured on the homepage

- Live monitoring with CPU, memory, graphics, and temperature readings.
- Diagnostics showing scores, coverage, and findings.
- Performance overview.
- Black-theme overview.
- Mini version showing compact CPU/GPU, battery, temperatures, graphics-memory, and workload readings.
- System findings.
- Reports and report comparison.

The homepage provides image enlargement/gallery controls. Guide images are labeled as illustrative interface readings rather than benchmark results.

### Feature-tour demonstrations

The live-dashboard walkthrough introduces resource observation and Quick Check as a starting point when a PC feels slow. The report-library walkthrough explains reopening saved scans, reviewing what was checked, and exporting a PDF for records or support.

### Appearance and interaction

The site names Signal and Black themes. Users can choose light/dark appearance, colors, fonts, and text sizes. Mini mode can stay above other windows and supports transparency. Tray mode is optional. An orange animated companion is part of the product presentation; character selection and SHIFT Run are listed features.

Source: [Homepage](https://shiftspc.com/), [Getting started](https://shiftspc.com/getting-started.html), [Features](https://shiftspc.com/features.html).

## 5. Compatibility, download contents, and setup

### Architecture compatibility

| Build | Specific Gumroad description |
|---|---|
| x64 | Windows 10 or 11 on Intel/AMD 64-bit PCs |
| x86 | Windows 10 on 32-bit PCs |
| ARM64 | Windows 10 or 11 on ARM64 PCs |

The main site broadly groups Windows 10/11 with all three builds. The purchase listing gives the more specific x86 limitation above, so the broad site wording should not be interpreted as 32-bit Windows 11 support.

### Package contents

The Gumroad listing describes one ZIP of approximately 177 MB containing:

- x64, x86, and ARM64 Windows builds.
- `START-SHIFT.cmd`.
- `INSTRUCTIONS.txt`.
- `LICENSE`.
- `LibreHardwareMonitor-LICENSE.txt`.

This records the published listing; the archive itself was not downloaded or independently inspected during website research. The presence of a licence-notice filename does not establish all bundled versions or implementation details.

### Starting the application

The purchase listing says to extract all files, keep the folders together, and run `START-SHIFT.cmd` to select the appropriate build automatically. The website setup instructions also describe extracting the archive and running `SHIFT.exe`.

### Documented first-session workflow

1. Choose the correct Windows build and extract the archive.
2. Open SHIFT.
3. Review CPU, RAM, GPU, VRAM, battery, and detected temperatures.
4. Choose Signal, Black, or Mini view as appropriate.
5. Run a scan, individual check, or Deep Check.
6. Inspect completed, partial, and unavailable modules before interpreting results.
7. Review optional repairs and app-closing settings before enabling them.
8. Save or export evidence when needed.
9. Inspect names, paths, and device information before sharing a report.

### Permissions and internet

Monitoring and Deep Check work offline. Deeper Windows checks and some supported sensors may need administrator approval. Checkout and email support require internet access. Portable operation does not mean every check is available without permission.

Sources: [Getting started](https://shiftspc.com/getting-started.html), [Portable diagnostics guide](https://shiftspc.com/portable-pc-diagnostics.html), [Gumroad](https://shiftscape.gumroad.com/l/whynjw).

## 6. Reports, exports, history, and support handoff

| Output or record | Documented role |
|---|---|
| Standard PDF | Save diagnostic findings |
| Graphical scan-history PDF | Preserve visual history summaries |
| Deep Check web page | Save findings in a browser-readable format |
| Deep Check plain text | Keep text findings |
| Deep Check JSON | Keep structured findings |
| Monitoring CSV | Open monitoring history in a spreadsheet |
| Structured scan snapshots | Revisit and compare scans |
| Monitoring logs | Keep alerts, action results, and optional five-second samples |

Report management includes preview, printing, and selected deletion. Monitoring logs can rotate, with optional removal of older dated logs. Exact retention defaults and export schemas are not established by the reviewed pages.

The report guide recommends including the symptom, expected versus actual behavior, approximate incident time, repeatability, Windows/SHIFT versions, relevant hardware, readings, and check status. A current CPU reading does not explain a previous crash by itself. Choose an export relevant to the incident and inspect the saved file before sharing.

Sources: [Features](https://shiftspc.com/features.html), [PC health report guide](https://shiftspc.com/pc-health-report.html).

## 7. Pricing, checkout, delivery, and licence

### Pricing and payment

The site advertises ₹759 as a one-time fee for the toolkit. The listed inclusion is live monitoring, hardware/driver information, diagnostics, local Deep Check, report exports, history, and comparison. The refund policy states that there is no recurring subscription.

The homepage offers a currency selector displaying: INR, USD, GBP, EUR, JPY, AUD, CAD, HKD, SGD, NZD, BRL, ZAR, CHF, ILS, PHP, PLN, CZK, SEK, NOK, DKK, MXN, KRW, TWD, SAR, AED, TRY, COP, RON, THB, MYR, IDR, and VND. Only the displayed INR price was recorded; this is not a verified table of prices in every currency.

### Observed checkout amount

The linked checkout view with India selected showed:

- Subtotal: ₹759.00.
- GST: ₹137.07.
- Total: ₹896.07.
- An optional tip control, with no tip selected.

This was a single observed checkout state, not a universal final price. The session also showed a creator test-purchase notice. No payment was made, and these figures do not establish the tax calculation or price for every customer, country, or future purchase. Marketing should distinguish the advertised base price from the final checkout total.

### Delivery and later access

Gumroad provides access after checkout. Existing purchasers can use their receipt email or, if they used a Gumroad account, their Gumroad library. The download page advises checking the purchase email address and spam folder, then contacting support with an order reference if necessary.

### Published licence conditions

- Use SHIFT only on devices the user owns or is authorized to manage.
- Do not redistribute paid copies.
- Do not use SHIFT without authorization.
- Keep the receipt for access and support.
- Included licence notices apply.

The reviewed terms do not clearly specify a device-count allowance, technician/commercial licence tier, transfer policy, or duration of update entitlement.

Sources: [Pricing](https://shiftspc.com/pricing.html), [Downloads](https://shiftspc.com/downloads.html), [Terms](https://shiftspc.com/terms.html), [Refunds](https://shiftspc.com/refund-policy.html), [Gumroad](https://shiftscape.gumroad.com/l/whynjw).

## 8. Refund and cancellation information

The policy says change-of-mind purchases are non-refundable, subject to refunds or other remedies required by applicable law. It advises reviewing features, compatibility, and purchase details before paying.

For access problems, delivery issues, material product issues, or duplicate charges, users are directed to support with the order reference and relevant details. The reviewed page does not provide a blanket refund guarantee or a specific refund-processing timeline.

Source: [Refund policy](https://shiftspc.com/refund-policy.html).

## 9. Support process

Contact: **shiftscpc@gmail.com**.

The support page covers installation, access, diagnostic findings, downloads/delivery, payments/duplicate charges, privacy requests, and other issues.

### Information requested

- SHIFT version.
- Windows version/build.
- Architecture or processor type.
- Concise problem description and exact error, where relevant.
- What the user already tried.
- Order reference for purchase questions.
- Relevant report or readings, if useful and reviewed for privacy.

### Support form behavior

The page lets the user choose a topic, describe an issue, and save a text request draft. The user then emails that file to support. The page says nothing is sent automatically. Unsaved text stays in the browser tab's session storage and is cleared when saved; the privacy notice adds that browser session restoration may retain unsaved drafts.

The site asks users to exclude passwords and payment credentials. It does not state a guaranteed response time, support hours, phone number, or live-chat service on the reviewed pages.

Source: [Support](https://shiftspc.com/support.html).

## 10. Privacy and data handling

### Application

According to the published notice, SHIFT operates offline and does not transmit system information, telemetry, crash reports, or diagnostic data to SHIFT servers. Saved reports remain on the device unless the user shares them.

The feature directory separately states that structured scan data is protected using Windows encryption associated with the current user. Supported exports can remove common identifying details. Users still need to inspect reports, screenshots, paths, names, and device details before sharing.

### Website

The privacy notice states:

- Google Analytics 4 measures visits and website use.
- Analytics cookies measure visits, page views, and engagement.
- Google processes that information for analytics reports.
- Advertising personalization and Google Signals are disabled in the site's tag configuration.
- Page addresses sent by that configuration omit query strings and fragments.
- Search runs in the browser.
- Support drafts use tab session storage and are not submitted automatically.
- Hosting providers may process connection logs.
- External checkout and download services have their own privacy notices.

The notice links to Google's privacy policy and analytics opt-out information.

### Information voluntarily sent to support

Support information is used to answer the enquiry, resolve the issue, and maintain necessary records. Users are asked to provide only necessary information. Access, correction, deletion, and other privacy enquiries go to the support email; identity verification may be required before records are changed or deleted.

### Distinction to preserve

The app's offline operation and lack of automatic diagnostic transmission are separate from website analytics and from a user's decision to email a report. Local diagnostic work does not make an exported report anonymous once shared.

Source: [Privacy notice](https://shiftspc.com/privacy.html), [Features](https://shiftspc.com/features.html).

## 11. Detailed guide-library inventory

The library contains ten topic guides plus the setup guide. The observed topic guides carry publication or update dates of 20 November 2026. They explain both what evidence can show and what it cannot prove.

### 11.1 CPU, GPU, and RAM monitoring

The guide recommends watching resource readings during the actual slowdown, recording the affected app and workload, and keeping tasks/settings comparable between observations. Task Manager is offered as a built-in starting point.

It explains that high CPU does not prove CPU damage; high RAM use does not prove faulty memory; a busy disk is not automatically failing; and missing GPU or temperature data is not zero activity. GPU selection matters on multi-adapter systems. Performance graphs distinguish spikes from sustained patterns, while per-app usage provides application context.

The memory-growth check is a short observation rather than proof of a leak. Save the task, time, versions, relevant readings, and appropriate report before making changes. Mini mode can help during gaming. Screenshots are illustrative rather than benchmarks.

Source: https://shiftspc.com/pc-monitoring.html

### 11.2 CPU and GPU temperatures

Identify the component, selected adapter, sensor label, and whether the reading is current. CPU, GPU, and graphics-memory temperatures are separate measurements. Compare the same task and conditions over time, including plugged-in versus battery operation.

Missing readings can reflect hardware, provider, driver, or permission limits. Sensor diagnostics provide source, recency, and availability. Use the exact component/system manufacturer's thermal specifications instead of a universal threshold. User-configured advisory limits and protective actions do not replace built-in hardware protections or guarantee safety.

Source: https://shiftspc.com/cpu-temperature-monitor.html

### 11.3 VRAM and GPU memory

The guide distinguishes dedicated graphics memory from shared system RAM. Integrated graphics need different interpretation from discrete graphics. Do not add a shared-memory limit to dedicated capacity and call the result physical VRAM.

Choose the correct adapter, measure the actual game or application, record resolution and quality settings, and change one variable at a time. Compare hardware with the software developer's requirements. There is no universal VRAM quantity for every workload. SHIFT reports readings; it does not add physical memory or guarantee performance.

Source: https://shiftspc.com/vram-usage.html

### 11.4 Slow-PC investigation

Possible contributors include limited free storage, background apps, storage waits, or demanding work. Record whether the slowdown affects startup, one app, a game, or the whole desktop. Review CPU, memory, and disk while reproducing the task under ordinary conditions.

Close unused apps normally, compare the same task, and review optional startup apps with care. Use Windows settings for pending updates. Monitoring informs a next step; it does not guarantee acceleration. For restarts and blue screens, prioritize crash evidence instead.

Source: https://shiftspc.com/why-is-my-pc-slow.html

### 11.5 Windows crash history

Record the incident time, task, visible stop code, and whether the symptom was a freeze, restart, power loss, or blue screen. Review relevant crash and event checks and their completion status. Look for recurring patterns around the same incident.

The guide explains that Kernel-Power Event ID 41 indicates an unclean shutdown/restart rather than establishing its root cause. Missing records or dumps do not prove no crash occurred. Driver dates near an incident do not prove causation.

SHIFT's published capability includes dump-header inspection. Full symbol-based debugging through WinDbg is described as a separate workflow that may require a specialist. Avoid publicly sharing dump files without considering privacy. Include timestamps, exact codes, check status, versions, and a reviewed report in support requests.

Source: https://shiftspc.com/windows-crash-history.html

### 11.6 Laptop battery health

The guide explains generating a Windows battery report with `powercfg /batteryreport`. Compare full-charge capacity and design capacity for the same battery using matching units.

Illustrative formula: full-charge capacity ÷ design capacity × 100. The example 40,000 mWh ÷ 50,000 mWh gives 80%; this is educational, not a measured SHIFT outcome or a universal replacement threshold.

Current charge percentage differs from retained capacity. Cycle count may be missing or zero when unsupported; it should not be assumed to mean a new battery. SHIFT's published battery features cover matched capacity comparisons, charge, reported runtime, AC, and battery-saver state. The guide directs users to the Windows battery report for cycle count where hardware supplies it.

Separate capacity reduction from demanding power use. Capacity readings do not establish physical safety or restore capacity. The guide advises stopping use of a swollen device and following manufacturer service guidance.

Source: https://shiftspc.com/laptop-battery-health.html

### 11.7 System information

The guide describes Windows Settings → System → About for basics and `msinfo32` for a fuller overview. Record exact processor, model, Windows, and system-type information relevant to the task.

A PC's device name, model, serial number, and Windows product key are different identifiers. The guide provides a PowerShell firmware serial-number query but explicitly states that SHIFT's feature list does not promise a serial-number lookup. Blank or placeholder firmware values require manufacturer verification.

Hardware inventory does not establish upgrade compatibility by itself. Protect serial numbers and other identifiers in public screenshots.

Source: https://shiftspc.com/system-information.html

### 11.8 Portable and offline diagnostics

Portable operation avoids a traditional installation workflow. Choose the correct build, extract the archive, and inspect only a computer the user is authorized to manage. Some checks and sensors need administrator permission.

Offline checks use evidence available on that computer and cannot guarantee every crash explanation or missing sensor. Portable format alone does not establish better accuracy, privacy, or speed. Purchasing and support still need internet. Inspect exports before sharing.

Source: https://shiftspc.com/portable-pc-diagnostics.html

### 11.9 PC health reports

A useful report combines the actual findings with the symptom, expected versus actual result, time, repeatability, versions, hardware, and check status. Choose standard or graphical-history PDF as appropriate and open the saved output to verify its contents.

Not every live graph is guaranteed in every PDF. Privacy options help with supported exports, but users must review identifiers. A score is a summary of available checks, not a certificate of perfect hardware. Send a short, concrete symptom description with the report.

Source: https://shiftspc.com/pc-health-report.html

### 11.10 Choosing PC monitoring software

The comparison describes Task Manager as a built-in starting point for app/resource activity; HWiNFO as hardware information, monitoring, and reporting; HWMonitor as hardware sensor monitoring; and SHIFT as local monitoring plus Windows findings and reports.

It explicitly identifies itself as a comparison from SHIFT's own website, not an independent benchmark. It does not claim SHIFT duplicates every competitor feature or is best for all hardware. Users should compare exact sensors, permissions, per-app activity, logs, reports, workflows, and current terms.

Source: https://shiftspc.com/pc-monitoring-software.html

## 12. FAQ topics and extracted answers

| Topic | Answer in substance |
|---|---|
| Problems solved | Bring readings, temperatures, and diagnostic findings into one view to investigate symptoms and choose a next check. |
| Information shown | CPU/GPU, RAM/VRAM, storage, battery, supported temperatures, drivers, and Windows findings. |
| Safety | Processing is local; findings can be incomplete; optional repairs and closing actions need review. |
| Internet requirement | Monitoring/Deep Check work offline; checkout and email need internet. |
| Supported devices | Windows laptops/desktops with architecture-specific builds. |
| Administrator approval | Needed for deeper readings and checks. |
| Deep Check | Local rules applied to Windows evidence, with findings for user review. |
| Support/refunds | Separate support and policy pages provide details. |
| Slow PC | Observe relevant resource use while the symptom occurs and compare a similar task after a small change. |
| CPU temperature | Check available sensors and the exact processor's thermal specifications. |
| Crash logs | Start with time, event records, and stop code; one error may not identify a cause. |
| VRAM | Keep dedicated and shared memory distinct and inspect the correct adapter. |
| Battery health | Compare matching reported capacities; use cycle count only where reported. |
| Portable offline check | Extract and run; some checks still need permission. |
| Sharing a PDF | Choose a suitable export, review identifiers, and add symptom context. |
| Alternative to HWiNFO/HWMonitor | Compare the required sensors, workflows, and terms rather than assuming full equivalence. |

Source: [FAQ](https://shiftspc.com/faq.html).

## 13. Claim boundaries to preserve

1. Hardware, sensors, counters, and diagnostics depend on components, drivers, providers, permissions, and available records.
2. Unavailable readings are not zero, and partial checks are not fully completed checks.
3. Diagnostic scores summarize available evidence rather than physical damage.
4. Monitoring alone does not automatically improve speed.
5. A high usage or temperature reading alone does not establish a failed part.
6. Temperature interpretation requires the exact component/system specifications.
7. Protective closing cannot guarantee hardware safety; force-close can lose unsaved work.
8. A short memory-growth observation cannot prove a leak.
9. Restart events and nearby driver records do not establish root cause by themselves.
10. Dump-header inspection is not a claim of full symbol-based memory-dump debugging.
11. SMART and wear data are reported information, not a guarantee that a drive will not fail.
12. Battery capacity and cycle count do not establish physical safety or guaranteed runtime.
13. Defender scan support relies on Microsoft Defender rather than establishing a separate antivirus engine.
14. Optional repair assistance uses supported actions and Windows tools; it is not a guarantee of automatic repair.
15. Report privacy applies to supported formats and common identifiers; final review is still necessary.
16. Offline app processing is distinct from website analytics, external checkout, and voluntary report sharing.
17. ₹759 is the advertised base price; the final total is determined at checkout.
18. No subscription is advertised, but a one-time payment does not by itself establish lifetime updates or unlimited-device use.

Sources: [Features](https://shiftspc.com/features.html), [About](https://shiftspc.com/about.html), [Guides](https://shiftspc.com/guides.html), [Terms](https://shiftspc.com/terms.html).

## 14. Unspecified or unverified information

The reviewed pages did not clearly establish the following. Their absence from this inventory does not prove the product lacks them.

- Device-count allowance per purchase.
- Commercial, repair-shop, or technician licence rules beyond authorized-device use.
- Licence transfer terms or a licence-expiry period.
- Lifetime-update entitlement or a defined update-support duration.
- Free-trial or demo terms.
- Minimum RAM, free-space requirement, or supported Windows build numbers.
- Exhaustive device/sensor compatibility matrix.
- Code-signing status, checksums, independent malware review, or security certification.
- Independent accuracy, speed, overhead, or competitive benchmark results.
- Specific AI model, training, inference architecture, or model size.
- Exact structured-storage encryption mechanism.
- Full report schemas and default log-retention periods.
- Guaranteed support hours, response times, or service-level agreement.
- Complete cancellation procedure beyond the published digital-purchase refund information.
- Legal business identity or address, customer counts, independently validated testimonials, and market-share figures in the reviewed content.
- A verified price list for every currency offered by the homepage selector.

## 15. Interpretation of the product's value

The following is a synthesis of the reviewed material rather than a separate published guarantee:

SHIFT's strongest proposition is bringing live resource readings, hardware context, Windows diagnostic evidence, explanations, and saved reports into one portable, local workflow. It helps a user move from a vague symptom to a documented observation and a more informed next check.

The workflows described are relevant to everyday Windows owners, gamers, creators, and people preparing evidence for technical support. These are inferred use cases from the guides; they do not establish a formal customer segment or commercial licence entitlement.

## 16. Complete source index

### Main product and help pages

1. Homepage — https://shiftspc.com/
2. About — https://shiftspc.com/about.html
3. All 81 features — https://shiftspc.com/features.html
4. Guides directory — https://shiftspc.com/guides.html
5. FAQ — https://shiftspc.com/faq.html
6. Pricing — https://shiftspc.com/pricing.html
7. Downloads — https://shiftspc.com/downloads.html
8. Getting started — https://shiftspc.com/getting-started.html
9. Support — https://shiftspc.com/support.html

### Policies

10. Privacy — https://shiftspc.com/privacy.html
11. Terms and licence — https://shiftspc.com/terms.html
12. Refund policy — https://shiftspc.com/refund-policy.html

### Topic guides

13. CPU/GPU/RAM monitoring — https://shiftspc.com/pc-monitoring.html
14. CPU/GPU temperature — https://shiftspc.com/cpu-temperature-monitor.html
15. VRAM — https://shiftspc.com/vram-usage.html
16. Slow PC — https://shiftspc.com/why-is-my-pc-slow.html
17. Crash history — https://shiftspc.com/windows-crash-history.html
18. Battery health — https://shiftspc.com/laptop-battery-health.html
19. System information — https://shiftspc.com/system-information.html
20. Portable diagnostics — https://shiftspc.com/portable-pc-diagnostics.html
21. Health reports — https://shiftspc.com/pc-health-report.html
22. Monitoring software comparison — https://shiftspc.com/pc-monitoring-software.html

### External purchase and access links

23. Linked product listing — https://shiftscape.gumroad.com/l/whynjw
24. Linked checkout — https://shiftscape.gumroad.com/l/whynjw?wanted=true
25. Customer library destination — https://gumroad.com/library

The library destination is an access route linked by the download page; this research did not inspect customers' private libraries or purchase files.
