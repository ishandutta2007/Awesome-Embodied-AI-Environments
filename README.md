# Awesome Embodied AI Environments [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated collection of top SaaS platforms, cloud simulators, and open-source GitHub projects for **Embodied AI Environments**, photorealistic world simulation, physics engines, and robot learning benchmarks.

[![Tracked Projects](https://img.shields.io/badge/Tracked%20Projects-25%2B-blue.svg)](#table-of-contents)
[![Embodied AI](https://img.shields.io/badge/Embodied%20AI-Robotics%20Simulation-success.svg)](#sector-overview--market-dynamics)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

---

## Top Embodied AI Environments Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Photorealistic Simulation, Physics Engines, Sim-to-Real Transfer & Interactive Task Environments*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Embodied AI Environments**. These tools provide the simulation infrastructure—physics, rendering, and interaction layers—where embodied agents learn to perceive, navigate, and manipulate before deployment in the physical world.

**Open-source emphasis**: Every major active project for self-hosting, GPU-parallelized simulation, and open physics engines—ideal for robotics researchers, embodied AI engineers, and developers seeking transparent, vendor-independent simulation infrastructure.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

---

## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS & Cloud-Hosted Platforms](#saas--cloud-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

---

## Sector Overview & Market Dynamics

The global Embodied AI and robotics simulation software sector is estimated at **$3.2B–$4.7B in 2025** and projected to grow beyond **$6.5B in 2026** (reaching **$23B+ by 2030** at an estimated CAGR of ~30–38%). 

The sector exhibits **moderate fragmentation with a bifurcated, tier-concentrated market structure**: foundational compute, cloud runtime, and accelerated physics engines are concentrated among tech giants like NVIDIA (Omniverse) and hyperscalers, whereas task environments, benchmarks, and multi-modal synthetic world platforms remain highly fragmented across specialized research labs, academic spin-offs, and open-source ecosystems.

---

## SaaS & Cloud-Hosted Platforms

| Platform | Company / Org | Company Size (Valuation / Revenue) | Starting Price (Specific Tier) | Free Tier Limit | Primary Capabilities & Focus |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[NVIDIA Isaac Sim Cloud](https://developer.nvidia.com/isaac/sim)** | NVIDIA Corporation | **~$5.4T** market cap (~$130B+ annual revenue) | **$1.00 / hour / GPU** consumption on cloud marketplaces; or **$4,500 / GPU / year** under Omniverse Enterprise | **Free for non-commercial individual development** via NVIDIA Developer Program (requires self-managed workstation / cloud GPU compute instance) | Photorealistic rendering (RTX), PhysX 5 dynamics, ROS/ROS 2 integration, and parallel synthetic sensor simulation. |
| **[Unity Industry / Unity Robotics](https://unity.com/solutions/automotive-transportation-manufacturing)** | Unity Software Inc. | **~$19.5B** market cap (~$2.1B annual revenue) | **$210 / seat / month** (or $2,310 / seat / year prepaid) for Unity Pro baseline | **Free forever on Unity Personal** for individuals/studios with **< $200,000 USD** in trailing 12-month revenue and funding | Real-time 3D simulation engine, CAD/URDF ingestion via Pixyz, ROS-TCP connector, and synthetic sensor data generation. |
| **[Viam](https://www.viam.com/)** | Viam Robotics, Inc. | **~$150M–$250M** est. valuation ($117M total venture funding) | **$0.25 / GB / month** data storage beyond threshold; cloud compute billed at **$0.000018 / vCPU-second** | **$5.00 / month of free cloud services credits forever** (no credit card required; covers entry fleet data sync & control) | Cloud-managed robotics data pipeline, sensor streaming, fleet management, and cloud-to-edge agent execution. |
| **[Foxglove](https://foxglove.dev/)** | Foxglove Technologies Inc. | **~$100M+** est. valuation ($40M Series B raised) | **$20.00 / month** base plan (Foxglove Pro, includes 3 developer seats and 1 TB storage) | **Free forever plan** with hard cap of **1 TB cloud storage**, **1 TB bandwidth**, **10 connected devices**, and **3 projects** with unlimited basic seats | Robotics visualization, live telemetry streaming, MCAP/ROS log playback, and collaborative agent observability. |
| **[AI2-THOR Cloud](https://ai2thor.allenai.org/)** | Allen Institute for AI (Ai2) | **~$205.8M** annual revenue / budget (~$138.9M net assets) | **$0.00 / month** (Philanthropic research platform; compute hosted via public AWS/GCP Docker templates at ~$0.50–$1.20/GPU-hr) | **Free forever without usage fees** under Apache-2.0 license; cloud benchmarks run via community credits or user-supplied cloud instances | Interactive photorealistic indoor scenes, rich object affordances, ProcTHOR procedural generation, and manipulation benchmarks. |
| **[UnrealZoo](https://github.com/UnrealZoo/unrealzoo-gym)** | Academic Research Team (HKUST / Tsinghua / ICCV 2025) | Academic research consortium (non-profit open research project) | **$0.00 / month** (Research simulator; headless deployment on cloud GPU instances e.g. AWS EC2 g4dn/g5 from ~$0.526/hr) | **Free and open-source forever** under MIT/Apache license; prebuilt gym binaries freely downloadable | Large-scale photo-realistic virtual worlds, MuJoCo robot physics integration, 3DGS rendering, LiDAR mapping, and MCP agent workflows. |

---

## Open-Source GitHub Projects

All repositories are sorted descending by their GitHub stargazers count:

- **[openai/gym](https://github.com/openai/gym)** [![GitHub stars](https://img.shields.io/github/stars/openai/gym?style=social&color=white)](https://github.com/openai/gym/stargazers)  
  The classic standard interface for reinforcement learning environments and robotics benchmarks (maintained for legacy compatibility; succeeded by Gymnasium).

- **[Genesis](https://github.com/Genesis-Embodied-AI/Genesis)** [![GitHub stars](https://img.shields.io/github/stars/Genesis-Embodied-AI/Genesis?style=social&color=white)](https://github.com/Genesis-Embodied-AI/Genesis/stargazers)  
  Universal physics engine designed for robotics and embodied AI with unified support for rigid bodies, soft bodies, cloth, fluids, and generative simulation.

- **[MuJoCo](https://github.com/google-deepmind/mujoco)** [![GitHub stars](https://img.shields.io/github/stars/google-deepmind/mujoco?style=social&color=white)](https://github.com/google-deepmind/mujoco/stargazers)  
  Multi-Joint dynamics with Contact physics engine by Google DeepMind (Apache-2.0). Stable implicit damping for robotics, biomechanics, and scalable reinforcement learning.

- **[PyBullet (bullet3)](https://github.com/bulletphysics/bullet3)** [![GitHub stars](https://img.shields.io/github/stars/bulletphysics/bullet3?style=social&color=white)](https://github.com/bulletphysics/bullet3/stargazers)  
  High-performance real-time multiphysics simulation for robotics, VR, and machine learning (Zlib license). Widely used in Ravens, VIMA-BENCH, and CALVIN.

- **[CARLA](https://github.com/carla-simulator/carla)** [![GitHub stars](https://img.shields.io/github/stars/carla-simulator/carla?style=social&color=white)](https://github.com/carla-simulator/carla/stargazers)  
  Open-source autonomous driving simulator built on Unreal Engine with urban environments, sensor suites (GNSS, LiDAR, cameras), and flexible traffic simulation.

- **[Gymnasium](https://github.com/Farama-Foundation/Gymnasium)** [![GitHub stars](https://img.shields.io/github/stars/Farama-Foundation/Gymnasium?style=social&color=white)](https://github.com/Farama-Foundation/Gymnasium/stargazers)  
  The official community-maintained standard API for reinforcement learning environments by Farama Foundation, providing seamless transitions from classic Gym.

- **[Isaac Lab](https://github.com/isaac-sim/IsaacLab)** [![GitHub stars](https://img.shields.io/github/stars/isaac-sim/IsaacLab?style=social&color=white)](https://github.com/isaac-sim/IsaacLab/stargazers)  
  Unified, modular framework for robot learning built on NVIDIA Isaac Sim. Delivers GPU-accelerated physics, photorealistic sensor rendering, and massive parallelism for RL and imitation learning.

- **[Webots](https://github.com/cyberbotics/webots)** [![GitHub stars](https://img.shields.io/github/stars/cyberbotics/webots?style=social&color=white)](https://github.com/cyberbotics/webots/stargazers)  
  Complete development environment and open-source robot simulator (Apache-2.0) with an extensive library of robots, sensors, actuators, and cross-platform ROS 2 support.

- **[Habitat-Sim](https://github.com/facebookresearch/habitat-sim)** [![GitHub stars](https://img.shields.io/github/stars/facebookresearch/habitat-sim?style=social&color=white)](https://github.com/facebookresearch/habitat-sim/stargazers)  
  High-performance 3D simulator for embodied AI research by Meta (MIT). Capable of thousands of FPS for point-goal navigation, social rearrangement, and human-avatar interaction (Habitat 1.0–3.0).

- **[ManiSkill](https://github.com/haosulab/ManiSkill)** [![GitHub stars](https://img.shields.io/github/stars/haosulab/ManiSkill?style=social&color=white)](https://github.com/haosulab/ManiSkill/stargazers)  
  GPU-parallelized robotics simulation benchmark powered by SAPIEN. Achieves 30,000+ FPS on consumer GPUs with heterogeneous sensor rendering and mobile manipulation tasks.

- **[Brax](https://github.com/google/brax)** [![GitHub stars](https://img.shields.io/github/stars/google/brax?style=social&color=white)](https://github.com/google/brax/stargazers)  
  Differentiable physics engine written in JAX by Google Research, enabling massively parallel reinforcement learning and trajectory optimization directly on GPU/TPU accelerators.

- **[RoboSuite](https://github.com/ARISE-Initiative/robosuite)** [![GitHub stars](https://img.shields.io/github/stars/ARISE-Initiative/robosuite?style=social&color=white)](https://github.com/ARISE-Initiative/robosuite/stargazers)  
  Modular simulation framework and benchmark for robot learning powered by MuJoCo. Includes standardized manipulation environments, multi-controller abstractions, and photorealistic rendering.

- **[LIBERO](https://github.com/Lifelong-Robot-Learning/LIBERO)** [![GitHub stars](https://img.shields.io/github/stars/Lifelong-Robot-Learning/LIBERO)](https://github.com/Lifelong-Robot-Learning/LIBERO/stargazers)  
  Lifelong robot learning benchmark with standardized suites (Spatial, Object, Goal, Long Horizon) built on MuJoCo and RoboSuite to evaluate transfer and continual skill acquisition.

- **[Gymnasium-Robotics](https://github.com/Farama-Foundation/Gymnasium-Robotics)** [![GitHub stars](https://img.shields.io/github/stars/Farama-Foundation/Gymnasium-Robotics?style=social&color=white)](https://github.com/Farama-Foundation/Gymnasium-Robotics/stargazers)  
  Official Farama Foundation robotics environments including Fetch, Shadow Hand dexterous manipulation, and Franka Emika Panda arms built on MuJoCo.

- **[Meta-World](https://github.com/Farama-Foundation/Metaworld)** [![GitHub stars](https://img.shields.io/github/stars/Farama-Foundation/Metaworld?style=social&color=white)](https://github.com/Farama-Foundation/Metaworld/stargazers)  
  Open-source benchmark for meta-reinforcement learning and multi-task learning consisting of 50 distinct robotic manipulation tasks sharing a unified action space.

- **[RLBench](https://github.com/stepjam/RLBench)** [![GitHub stars](https://img.shields.io/github/stars/stepjam/RLBench?style=social&color=white)](https://github.com/stepjam/RLBench/stargazers)  
  Robot learning benchmark with 100+ manipulation tasks built on CoppeliaSim (V-REP) and PyRep, designed for vision-guided reinforcement learning and imitation learning.

- **[AI2-THOR](https://github.com/allenai/ai2thor)** [![GitHub stars](https://img.shields.io/github/stars/allenai/ai2thor?style=social&color=white)](https://github.com/allenai/ai2thor/stargazers)  
  Near-photorealistic interactive indoor simulator on Unity by the Allen Institute for AI. Supports iTHOR, RoboTHOR, and ProcTHOR-10K with rich physical object affordances.

- **[RoboCasa](https://github.com/robocasa/robocasa)** [![GitHub stars](https://img.shields.io/github/stars/robocasa/robocasa?style=social&color=white)](https://github.com/robocasa/robocasa/stargazers)  
  Large-scale simulation framework for generalist robots in everyday kitchens. Provides 2,500+ kitchen layouts, 365 daily tasks, and thousands of hours of demonstration data with sim-to-real transfer validation.

- **[D4RL](https://github.com/Farama-Foundation/D4RL)** [![GitHub stars](https://img.shields.io/github/stars/Farama-Foundation/D4RL?style=social&color=white)](https://github.com/Farama-Foundation/D4RL/stargazers)  
  Datasets for Deep Data-Driven Reinforcement Learning providing standardized benchmarks for offline reinforcement learning in robotics and control.

- **[Gazebo Sim (gz-sim)](https://github.com/gazebosim/gz-sim)** [![GitHub stars](https://img.shields.io/github/stars/gazebosim/gz-sim?style=social&color=white)](https://github.com/gazebosim/gz-sim/stargazers)  
  The flagship open-source robotics simulator from Open Robotics with first-class ROS / ROS 2 integration, modular physics engines, and distributed network architecture.

- **[Facebook FAIR AI Habitat / Fairo](https://github.com/facebookresearch/fairo)** [![GitHub stars](https://img.shields.io/github/stars/facebookresearch/fairo?style=social&color=white)](https://github.com/facebookresearch/fairo/stargazers)  
  Meta FAIR robotics framework providing modular abstractions, real robot controllers, sensor interfaces, and simulation connectors.

- **[SAPIEN](https://github.com/haosulab/SAPIEN)** [![GitHub stars](https://img.shields.io/github/stars/haosulab/SAPIEN?style=social&color=white)](https://github.com/haosulab/SAPIEN/stargazers)  
  Realistic and physics-rich simulation platform designed for embodied AI and articulated object manipulation with ray-tracing visual rendering.

- **[iGibson](https://github.com/StanfordVL/iGibson)** [![GitHub stars](https://img.shields.io/github/stars/StanfordVL/iGibson?style=social&color=white)](https://github.com/StanfordVL/iGibson/stargazers)  
  Simulation environment developed by Stanford VL for interactive navigation and mobile manipulation in photorealistic homes with continuous rigid body physics.

- **[VirtualHome](https://github.com/xavierpuigf/virtualhome)** [![GitHub stars](https://img.shields.io/github/stars/xavierpuigf/virtualhome?style=social&color=white)](https://github.com/xavierpuigf/virtualhome/stargazers)  
  Multi-agent household activity simulation platform featuring 2,800+ activity programs for high-level language planning, video synthesis, and task execution.

- **[ThreeDWorld (TDW)](https://github.com/threedworld-mit/tdw)** [![GitHub stars](https://img.shields.io/github/stars/threedworld-mit/tdw?style=social&color=white)](https://github.com/threedworld-mit/tdw/stargazers)  
  General-purpose virtual world simulation platform by MIT utilizing Unity for photo-real rendering, rigid body mechanics, cloth/soft-body physics, and audio generation.

- **[ProcTHOR](https://github.com/allenai/procthor)** [![GitHub stars](https://img.shields.io/github/stars/allenai/procthor?style=social&color=white)](https://github.com/allenai/procthor/stargazers)  
  Large-scale procedural generation framework by Ai2 for generating infinite interactive 3D embodied AI environments across thousands of realistic household scenes.

- **[UnrealZoo Gym](https://github.com/UnrealZoo/unrealzoo-gym)** [![GitHub stars](https://img.shields.io/github/stars/UnrealZoo/unrealzoo-gym?style=social&color=white)](https://github.com/UnrealZoo/unrealzoo-gym/stargazers)  
  Large-scale photo-realistic virtual worlds built on Unreal Engine 5 with MuJoCo physics, 3DGS rendering, LiDAR street mapping, and multi-agent MCP runtime workflows.

---

## How to Contribute

1. Fork the repository.
2. Add or update entries in [README.md](file:///C:/Users/ishan/Documents/Projects/Awesome-Embodied-AI-Environments/README.md).
3. Ensure all table entries include specific tier pricing, clear free tier limits, and company size/market valuation data.
4. For open-source additions, ensure the star badge uses `style=social&color=white` and links to the repository's `stargazers` page, with entries sorted descending by star count.
5. Submit a pull request with a concise description of the addition or revision.

---

## Disclaimer

- This is a community-curated list for research and educational purposes; inclusion does not constitute an endorsement.
- Performance in simulation environments does not guarantee real-world robotic deployment success due to the persistent reality of the sim-to-real gap.
- No single simulation environment dominates across every performance metric: Gazebo and Webots excel in ROS integration and hardware validation, Isaac Sim and CARLA lead in graphical fidelity and synthetic sensor generation, and MuJoCo and Brax excel in physics throughput and reinforcement learning scalability.

---

**Built for robotics researchers, embodied AI engineers, and developers building the future of physical intelligence.**
