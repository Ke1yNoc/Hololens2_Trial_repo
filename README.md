<h1 align="center"> ASK ME ON TEAMS IF ANYTHING UNSURE ABOUT THIS </h1>

---

## Requirements
1. Download and Install Windows Software Development Kit 10.0.22621.3233 (https://developer.microsoft.com/en-us/windows/downloads/windows-sdk/), you can also install the version 10.0.19041.685 (though it does not compatiable with MRTK-2.8.3, it only support MRTK-2.6.1)
2. Download and Install Visual Studio 2022 (https://visualstudio.microsoft.com/). *Remember to select Desktop development with C++ & Universal Windows Platform development (Tick USB Device Connectivity & C++(v142/v143) Universal Windows Platform tools)*
3. Download and Install Unity 2021.3.37f1, it is the latest LTS version supported by the MRTK-2.8.3.

## MRFT Warning
1. DO NOT TRUST MRFT(Mixed Reality Feature Tool) (https://learn.microsoft.com/en-us/windows/mixed-reality/develop/unity/welcome-to-mr-feature-tool), it can no longer download and import the MRTK to Unity projects.
2. It will crash whenever you try to import any MRTK to any Unity project, and the crash reason in the log showed Microsoft has removed those pacakges from the dedicated Azure download platform and causes 404 issue.
3. However, it can still be used for importing Mixed Reality OpenXR Plugin which is mandatory for configuring project.
