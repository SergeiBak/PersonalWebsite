# Augmented Space Library 2: A Network Infrastructure for Collaborative Cross Reality Applications

## Gregory Smith

The Cross Reality Collaboration Sandbox (CRCS) research group is dedicated to studying issues related to supporting collaborations across geographical distances through different technological reality setups. These different setups can include immersive Virtual Reality (VR), Augmented Reality (AR), and traditional computers. The first version of Augmented Space Library (ASL), a thin network utility for supporting 3D object synchronization, was created to pursue this study. Over time, ASL evolved into an ad hoc collection of undocumented application programming interfaces and turned into a system that struggled to support investigative applications. The lack of an initial overarching architectural structure combined with over three years of non-stop modifications resulted in an unreliable and bloated system. It became evident that for CRCS to continue with its experimentation, a new library system, designed from the ground-up, was required.

The essential lessons learned from the first version of ASL are that the library must ensure straightforward network session establishment, be device-independent, and facilitate the rapid prototyping of simple ideas. These lessons guided the design effort and resulted in a new library, ASL 2.0, that is based on a hybrid of the client-server and peer-to-peer architecture, is integrated with an existing device-agnostic front-end platform, and facilitates the synchronization and communication of distributed collaborative application states. With the design of ASL 2.0, application developers can focus on the fundamental issues of supporting collaboration and be free from the logistics of device-specific issues and the overhead of application state synchronization between remote users. The newly developed library went through two phases of testing to verify its completeness and usability. The initial round of testing explored the support for AR devices and resulted in a custom solution for resolving the different world-origin positions for collaborating AR devices. The second round of testing included four parallel projects. At the time of this thesis writing, all four projects are entering their final testing phase with no major issues encountered. While there is still work to be done, the current ASL 2.0 release is in a healthy and stable state capable of supporting experimentations of remote collaborative applications with heterogeneous devices.

***

[Yusuf Pisan](https://pisanorg.github.io/yusuf/) | [Computing & Software Systems (CSS)](https://www.uwb.edu/css) | [University of Washington Bothell](https://www.uwb.edu/)