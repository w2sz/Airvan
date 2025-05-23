# Airvan Project - Home

[Home](.) \| [Documentation](doc) \| [Calendar](https://calendar.google.com/calendar/u/0/embed?src=7d6ff641efe0e885fa858d34da6e10fd99e1d2fd7c405e6accf23027cc922db0@group.calendar.google.com&ctz=America/New_York) \| [Meeting Minutes](https://drive.google.com/drive/folders/1w6okqB9U94YdA9lP_eaBHEua9bieqaRl) \| [Slides](https://docs.google.com/presentation/d/1Ww7tBK9KSm9yHedZIFGHmEW860MVFOorjmqm3pCkUfE) \| [Discord](https://discord.gg/8mKERb27Zd)

Airvan is a cost-effective, scalable open-source aerial platform featuring open hardware architecture designed for general autonomous applications. This accessible aeronautical system enables widespread adoption and operation by individuals with minimal technical expertise, democratizing access to autonomous aerial technology.

With modular payloads, this platform may be used for different purposes, such as:

- Radio communication relay
- Aerial photography
- Surveying
- Cargo delivery
- etc.

Example use case:

1. AirRepeater (Airvan + Radio Repeater) can be used to establish long range radio communications in the aftermath of environmental and human caused disaster.
2. AirLens (Airvan + Camera + Computer Vision) can perform search and rescue with computer vision technology to spot creatures/objects in motion at a distance.
3. AirSurveyor (Airvan + Camera + Photogrammetry) scan the landscape and generate orthomosaic maps or 3D textured mesh for civil engineering use.

![AirRepeater System](https://i.imgur.com/OfHRdmn.png)

See videos of [test flight aerial view](https://youtu.be/CvpGYRIj5Zo) and [example mission simulation](https://youtu.be/J7g-IRBaNW4).

## Specification

The project is in the active early design stage now. Specifications are subject to change.

### General

- Maximum flight time: 120 minutes
- Maximum payload weight: 2.5 kg (5-1/2 lbs)
- Maximum dimension when folded: 1.3 m (4-1/4 ft)

### AirRepeater

- Repeater coverage: 80 km (50 mi) in radius, open space
- Transmitting power: 5 watts

## Technical Approach

- Foam boards for main body with carbon fiber for structural strength.
- Computer modeling and analysis with OpenVSP
- ArduPilot + Pixhawk + Mission Planner for autonomous feature.

## Progress

- 04/27/2025 Prototype #2 Test flight, [Aerial View of Troy, NY](https://youtu.be/CvpGYRIj5Zo)
- 04/22/2025 #2 fuselage done, upgrading electronics.
- 03/01/2025 Prototype #2 wing built with custom wire cutting machine.
- 01/01/2025 Jingxi Zhu takes the project lead
- 04/10/2023 Crash report and design improvement.
- 04/03/2023 Test flight at 86' Field. Prototype #1 crashed.
- 03/13/2023 Test flight location investigation.
- 02/18/2023 Flight controller, sensors and software testing.
- 02/08/2023 [User interface](https://discord.com/channels/1026653079749275659/1029134535348211732/1072938576863563876) concept design (Manual, Automatic, Mixed, Remote)
- 02/07/2023 A [MVP model](https://discord.com/channels/1026653079749275659/1029134443992076419/1072562378744533024) built for further analysis.
- 01/30/2023 [Financial data](https://drive.google.com/drive/folders/138rb2HcaUgs6OqswoUpuqhm_u9hDs0dA) publicly available.
- 01/29/2023 Material purchase.
- 01/18/2023 Computer modeling started.
- 11/16/2022 Electronic parts list created. The first batch electronics suffice the need for ground testing.
- 11/04/2022 Aircraft [frame draft](https://drive.google.com/drive/folders/1w6okqB9U94YdA9lP_eaBHEua9bieqaRl?usp=share_link) started.
- 10/12/2022 Team recruitment, cost analysis and fundraising planning.
- 10/03/2022 Project specification and technical approach under discussion.
- 09/29/2022 Project started.

## Timeline

### Fall 2022

- By mid October [On time]
  - Project outline
  - Team formation
  - Budget estimation
- By mid November [On time]
  - Funding acquisition
  - System design
  - Purchase order

### Spring 2023

- By mid February [In Progress]
  - Modeling - *Simulation & Analysis*
  - Lab testing - *wind tunnel*
  - System integration
- By mid April
  - Assemble
  - Field testing - *parameter Tuning*
  - Prototype delivery

## Fundraising

Please contact Zhemin 'Hisen' Zhang via `zhangz29 at rpi dot edu` if you are interested in sponsoring or donating to the project.

Financial information release available [here](https://drive.google.com/drive/folders/138rb2HcaUgs6OqswoUpuqhm_u9hDs0dA).

- 11/14/2022 $2,000 budget from Rensselaer Union. Effective since June 2023. Expire on May 2024.
- 11/07/2022 $1,000 from Mr. Bob Cummings '69 and Mr. David Walker '71 via School of Engineering, Rensselaer Polytechnic Institute.
- 11/06/2022 $100 endowment from Gregory Kotlyarsky.
- 11/06/2022 $100 endowment from Zhemin Zhang.

## Contributors

### Organizations

This project is a collaborative outcome of three clubs at Rensselaer Polytechnic Institute.

- [W2SZ Amateur Radio Club](https://w2sz.union.rpi.edu) - Radio solution;
- [RPI Drone Club](https://rpidrone.club/) - Aircraft design and construction;
- [Design Build Fly](https://rpidbf.tumblr.com/) - Aircraft design and construction;
- [Embedded Hardware Club](http://www.rpiehc.org/) - Avionics.

### Individuals

- **Jingxi Zhu** <[GitHub](https://github.com/Zhujingxi)> - Aircraft section lead since Spring 2025
- **Zhemin Zhang** *a.k.a. Hisen* < [GitHub](https://github.com/HisenZhang) \| [QRZ](https://www.qrz.com/db/KD2TAI) \| [CV](https://drive.google.com/drive/folders/1yjGs06L5jsOb7V4cnr0k2sHhIgjTP67z) > - Project initiator, fundraiser. Chief engineer of radio system. President of W2SZ Amateur Radio Club, KD2TAI.
- **Gregory Kotlyarsky** *a.k.a. Greg* - Chief engineer of electromechanical system. Treasurer of RPI Drone Club.
- **Fuller Hayden** - Chief engineer of avionic system. Operation officer of RPI Embedded Hardware Club.

## Legal Information

### FAA Regulation

This project is [Title 14 CFR Part 107](https://www.ecfr.gov/current/title-14/chapter-I/subchapter-F/part-107) compliant, referred to as the Small UAS Rule.

### License

This project adopts MIT License.
