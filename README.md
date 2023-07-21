# 3D simulated Live match in AR with interaction

![XROS](./readme-img/banner.png)

<div align="center">
<center><img src="./readme-img/readmeGif.gif"></center>
   <h3 align="center">A Demo of our project: 3D Simulated Live Match in AR with Interaction</h3>
</div>

## Table of Contents

1. [Introduction](#1-introduction)
2. [Project Journey](#2-project-journey)

   - [Inception of the Idea](#inception-of-the-idea)
   - [Research and Planning](#research-and-planning)
   - [Technology Stack](#technology-stack)

3. [Setting Up the Project](#3-setting-up-the-project)
   - [System Requirements](#system-requirements)
   - [Dependencies and Libraries Used](#dependencies-and-libraries-used)

4. [Key Features and Functionality](#4-key-features-and-functionality)

   - [Plane Tracking](#plane-tracking)
   - [Fetching Live Cricket Match Data](#fetching-live-cricket-match-data)
   - [Wagon Wheel](#wagon-wheel)
   - [Buttons for Interactions](#buttons-for-interactions)

5. [Current Project Stage and Known Issues](#5-current-project-stage-and-known-issues)
   - [Summary of the Current Project Stage](#summary-of-the-current-project-stage)
   - [Identified Issues and Limitations](#identified-issues-and-limitations)
   - [Proposed Solutions and Future Improvements](#proposed-solutions-and-future-improvements)
6. [Conclusion](#6-conclusion)

---

## 1. Introduction

<!-- ![Fanisko-AR](./readme-img/faniskoAR.png) -->
<div align = "center"><a  href="#"><img width="20%" src="./readme-img/faniskoAR.png" /></a> </div>


3D simulated live match in AR with Interaction - Open Source Project
3D simulated live match in AR with Interaction is an open-source project to create an interactive platform with augmented reality (AR) features such as 3D rendering and Ground Plane Tracking. It provides users with online Web Based Augmented Reality options, including a dynamic 3D WagonWheel as an immersive AR experience. The project leverages web technologies such as HTML, Three.js, WebXR, A-Frame, VanillaJS, etc.

## 2. Project Journey

### Inception of the Idea

This open-source project was developed as a part of the XROS Fellowship under the Fanisko organization. The project aimed to create a live AR experience out of a live data platform with augmented reality (AR) features. By incorporating AR technology, the AR platform aims to provide users with an immersive and interactive viewing experience during live game events.

### Research and Planning

The research and planning phase played a crucial role in shaping the direction and implementation of this AR project. Extensive research was conducted to explore existing AR platforms, plane tracking, data fetching technologies, and DOM Overlaying protocols. This section outlines the key milestones and dates during the research and planning phase.

| Milestone               | Date       |
| ----------------------- | ---------- |
| Research kick-off       | 2023-04-10 |
| AR platform analysis    | 2023-05-08 |
| Fetching tech research  | 2023-05-25 |
| Project Development     | 2023-06-01 |
| Bug Fixing              | 2023-07-01 |
| UI Improvements         | 2023-07-07 |

During the research kick-off, the project team gathered to discuss the objectives and scope of the project. The primary focus was on understanding the capabilities and limitations of existing AR platforms and identifying the most suitable options for integrating AR with live data feeds.

The subsequent milestone involved an in-depth analysis of various AR platforms available in the market. Factors such as ease of integration, performance, and community support were considered during the evaluation process. This research helped the team make an informed decision regarding selecting the WebXR for the project.

Simultaneously, research was conducted on data fetching technologies to identify the best approach for real-time data fetching through live APIs. Different methods, including Axios and Node-based, were studied, and their suitability for live data fetching applications was assessed. This research helped the team gain a deeper understanding of the technical requirements and challenges associated with streaming in the context of the AR project.

Following the research phase, planning and strategy development commenced. The team analyzed the gathered insights, identified project requirements, and formulated a roadmap for the development process. The planning phase involved setting project milestones, allocating resources, and outlining the steps needed to bring the AR project to fruition.

The research and planning phase provided a solid foundation for the subsequent stages of the project, guiding the technology stack selection, development approach, and implementation strategies. The insights gained during this phase successfully integrated augmented reality, data fetching capabilities, and real-time data visualization on the AR platform.

### Technology Stack 

<p align="left">
<a href="https://nodejs.org/en" target="_blank" rel="noreferrer">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=for-the-badge&logo=JavaScript&logoColor=black">
</a>
<!-- <a href="https://immersiveweb.dev/" target="_blank" rel="noreferrer">
<img src="https://img.shields.io/badge/Solidity-363636.svg?style=for-the-badge&logo=Solidity&logoColor=white">
</a> -->
<a href="https://threejs.org/" target="_blank" rel="noreferrer">
<img src="https://img.shields.io/badge/Three.js-000000.svg?style=for-the-badge&logo=threedotjs&logoColor=white">
</a>
<!-- <a href="https://unity.com/" target="_blank" rel="noreferrer">
<img src="https://img.shields.io/badge/Unity-FFFFFF.svg?style=for-the-badge&logo=Unity&logoColor=black">
</a> -->
<a href="https://immersiveweb.dev/ " target="_blank" rel="noreferrer">
<img src="https://earthday.deimosindustries.com/assets/images/webxr-logo.svg" width="8%">
</a>
</p>


## 3. Setting Up the Project

### System Requirements

<a href="https://3d-live-simulated-match-with-interaction.vercel.app/">3D Simulated Live Match in AR with Interaction</a> is a web-based AR experience that can be used through mobile devices. To run the AR experience, ensure that your system meets the following requirements:

- **Operating System:** AndroidOS, iOS(Safari Beta)[Will be accessible to all iOS devices from iOS16]
- **Processor:** Snapdragon 685 or above preferred
- **RAM:** 8GB or higher
- **Storage:** 128GB of available space
- **Browser Compatibility:**
  - Google Chrome (latest version)
  - Mozilla Firefox (latest version)
  - Safari (beta version)
- **Internet Connection:** Stable broadband connection with a minimum speed of 5 Mbps

Please note that these are the recommended system requirements. The project may still work on lower specifications, but performance may be affected.

## Dependencies and Libraries Used

| Dependency/Library | Purpose                                            |
| ------------------ | -------------------------------------------------- |
| HTML, CSS          | For building user interfaces                       |
| Three.js           | JavaScript 3D library for rendering 3D graphics    |
| WebXR              | For AR development on the Web                      |
| A-Frame            | Web framework for building virtual reality (VR)    |
| HitTest API        | JavaScript framework for client-side development   |
| JavaScript         | For fetching live data and integrating UI          |



## 4. Key Features and Functionality

#### Plane Tracking

The plane tracking was incorporated using WebXR and HitTest API.

#### Fetching Live Cricket Match Data

This has been done using past data from a cricket match. To fetch cricket data from a Live API, replace the links in fetchMatchData() and fetchPlayerData() with the API that provides match-wise and player-wise data.

#### Wagon Wheel

The Wagon Wheel has been drawn over the stadium model using Three.js geometries.

#### Buttons for Interactions

DOM Overlay has been used to develop buttons for interaction that provide player-wise and match-wise stats in the application.


## 5. Current Project Stage and Known Issues

### Summary of the Current Project Stage

The project is in an advanced stage, with the core functionalities implemented successfully. However, there are still areas for improvement and fine-tuning to provide a seamless and immersive AR-powered cricketing experience.


### Identified Issues and Limitations

- Finding an Open Source Live Cricket Match Data API that provides coordinates of the position of the balls concerning the cricket stadium.
- WebXR is unstable for 3D models.
- Currently, only compatible with Chrome on Android devices.


### Proposed Solutions and Future Improvements

Proposed solutions and future improvements have been outlined to address the identified issues and limitations. These include:
- Optimizing AR Hit-test performance
- Improving compatibility across different platforms
- Enhancing the stability and scalability of the AR functionality.
<br>
Additionally, continuous testing, user feedback, and iterative development will be key to refining the project further.

## 6. Conclusion

### Creators

The "3D simulated Live match in AR with interaction" project was created by:

- [Ayesha Nasim](https://github.com/n-ay)
- [Vasu Pal](https://github.com/Vasu1712)

### Project Mentor

- [Pugazhenthi Ramakrishan](https://www.linkedin.com/in/pugazhenthi-ramakrishanan/)
- [Harshaanthan Siva](https://www.linkedin.com/in/harshaanthan-sivaraman-9b388b138/)

### Organization

[Fanisko](https://fanisko.com/)

For more information, visit the [XROS Fellowship website](https://xrosfellowship.org/).

### License

This project is open-source and is licensed under the [MIT License](LICENSE).
