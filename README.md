<!--
Profile design system
- Section hierarchy: H2 section > code tag > H3 title > status/achievement > two bullets > links
- Project cards: 52% visual / 48% description, vertically centered
- Link order: Repository first, Video second
- Preserve source-image aspect ratios; do not stretch research figures or demos
-->

<div align="center">
  <img src="./banner.svg" alt="Subin Park — Robotics Engineer and AI Developer" width="100%">
</div>

I work on ROS 2 autonomous driving and warehouse multi-robot systems, with research experience in LLM-based Korean hate speech detection.

## Experience & Focus

<table>
  <tr>
    <td width="50%" valign="top">
      <code>RESEARCH EXPERIENCE</code>
      <h3><a href="https://ssu-humane.github.io/">HUMANE Lab</a></h3>
      <strong>Undergraduate Researcher · 8 months</strong>
      <ul>
        <li>Conducted Korean hate-speech detection research using KOLD.</li>
        <li>Ran ICCD/CD and self-refinement experiments for few-shot classification.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <code>CURRENT FOCUS</code>
      <h3>ARCo WES · Warehouse Multi-Robot Simulation</h3>
      <strong>In progress</strong>
      <ul>
        <li>Developing a Webots simulator for warehouse multi-robot operations.</li>
        <li>Studying task verification and dynamic replanning when inventory or task records diverge from the physical state.</li>
      </ul>
    </td>
  </tr>
</table>

## Connect & Core Stack

<div align="center">
  <sub><strong>CONNECT</strong></sub>
  <br>
  <a href="https://velog.io/@psubin05/posts"><img src="https://img.shields.io/badge/Velog-20C997?style=for-the-badge&amp;logo=velog&amp;logoColor=white" alt="Velog"></a>
  <a href="mailto:psubin0512@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&amp;logo=gmail&amp;logoColor=white" alt="Email"></a>
  <br><br>
  <sub><strong>CORE STACK</strong></sub>
  <br>
  <img src="https://img.shields.io/badge/ROS_2-22314E?style=flat-square&amp;logo=ros&amp;logoColor=white" alt="ROS 2">
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&amp;logo=cplusplus&amp;logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&amp;logo=python&amp;logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/NVIDIA_Jetson-76B900?style=flat-square&amp;logo=nvidia&amp;logoColor=white" alt="NVIDIA Jetson">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&amp;logo=pytorch&amp;logoColor=white" alt="PyTorch">
</div>

## Selected Projects

<table>
  <tr>
    <td width="52%" valign="middle">
      <a href="https://github.com/psubin05/F1TENTH-Adaptive-Racing-Control">
        <img src="./racing-pipeline.svg" alt="F1TENTH adaptive racing control pipeline" width="100%">
      </a>
    </td>
    <td width="48%" valign="middle">
      <code>AUTONOMOUS DRIVING · COMPETITION</code>
      <h3>F1TENTH Adaptive Racing Control</h3>
      <strong>🏅 8th Place · Encouragement Award</strong><br>
      <sub>2025 The 4th F1TENTH Korea Championship · ICCAS 2025</sub>
      <ul>
        <li>Runs TinyLidarNet inference in a ROS 2 racing stack on NVIDIA Jetson.</li>
        <li>Adds LiDAR-aware speed limits and speed-dependent steering constraints.</li>
      </ul>
      <a href="https://github.com/psubin05/F1TENTH-Adaptive-Racing-Control"><strong>Repository →</strong></a>
      &nbsp;·&nbsp;
      <a href="https://github.com/psubin05/F1TENTH-Adaptive-Racing-Control/blob/main/assets/competition-run.mp4"><strong>Video →</strong></a>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="52%" valign="middle">
      <a href="https://github.com/psubin05/f1tenth-collision-recovery">
        <img src="./recovery-demo.gif" alt="F1TENTH collision detection and reverse recovery demo" width="100%">
      </a>
    </td>
    <td width="48%" valign="middle">
      <code>ROBOT CONTROL · TEAM PROJECT</code>
      <h3>F1TENTH Collision Detection &amp; Reverse Recovery</h3>
      <ul>
        <li>Detects collision states using LiDAR, IMU, and odometry.</li>
        <li>Integrates ROS 2 state transitions for reverse recovery and return to autonomous driving after localization stabilizes.</li>
      </ul>
      <a href="https://github.com/psubin05/f1tenth-collision-recovery"><strong>Repository →</strong></a>
      &nbsp;·&nbsp;
      <a href="https://github.com/psubin05/f1tenth-collision-recovery/blob/main/%EC%8B%9C%EC%97%B0%20%EC%98%81%EC%83%81.mov"><strong>Video →</strong></a>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="52%" valign="middle">
      <a href="https://github.com/graviny/capstone">
        <img src="./warehouse.svg" alt="ARCo WES · Warehouse Multi-Robot Simulation" width="100%">
      </a>
    </td>
    <td width="48%" valign="middle">
      <code>MULTI-ROBOT · IN PROGRESS</code>
      <h3>ARCo WES · Warehouse Multi-Robot Simulation</h3>
      <ul>
        <li>Simulates a 24 × 14 m warehouse in Webots with patrol and transport robots.</li>
        <li>Uses real order data to model inventory and task-state mismatches for task verification and dynamic replanning.</li>
      </ul>
      <a href="https://github.com/graviny/capstone"><strong>Repository →</strong></a>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="52%" valign="middle">
      <a href="https://github.com/psubin05/hate_self_refine">
        <img src="./hate-speech-method.png" alt="Self-refined negative demonstrations for Korean hate speech classification" width="100%">
      </a>
    </td>
    <td width="48%" valign="middle">
      <code>HUMANE LAB · UNDERGRADUATE RESEARCH</code>
      <h3>LLM-Based Korean Hate Speech Detection</h3>
      <ul>
        <li>Evaluates KOLD few-shot classification using ICCD/CD experiments.</li>
        <li>Improves macro-F1 from <strong>0.4039</strong> to <strong>0.4636</strong> through self-refinement.</li>
      </ul>
      <a href="https://github.com/psubin05/hate_self_refine"><strong>Repository →</strong></a>
    </td>
  </tr>
</table>
