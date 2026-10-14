# Awesome-Embodied-AI-Environments

# Top Embodied AI Environments Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Photorealistic Simulation, Physics Engines & Interactive Task Environments*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Embodied AI Environments**. These tools provide the simulation infrastructure—physics, rendering, and interaction layers—where embodied agents learn to perceive, navigate, and manipulate before deployment in the physical world.

**Examples** include AI2-THOR, Habitat (Meta), Isaac Sim (NVIDIA), ThreeDWorld, GibsonEnv, SAPIEN, RoboCasa, PyBullet, MuJoCo, and Gazebo (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, GPU-parallelized simulation, and open physics engines—ideal for robotics researchers, embodied AI engineers, and developers seeking transparent, vendor-independent simulation infrastructure.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[NVIDIA Isaac Sim Cloud](https://developer.nvidia.com/isaac/sim)**  
  Cloud-hosted version of Isaac Sim for teams without local GPU infrastructure. Provides photorealistic rendering, PhysX 5 physics, and ROS/ROS 2 bridges. Requires NVIDIA GPU and Omniverse runtime.

- **[AI2-THOR Cloud](https://ai2thor.allenai.org/)**  
  Near-photorealistic indoor scenes with rich object properties and affordances. Cloud-hosted version for teams without local GPU infrastructure. Extensions support large-scale procedural scene generation and embodied manipulation.

- **[UnrealZoo](https://github.com/UnrealZoo/unrealzoo-gym)**  
  Large-scale photo-realistic virtual worlds for embodied AI (ICCV 2025 Highlights). Features MuJoCo robot physics (Go1 and Micro Duck), runtime MCP agent workflows, live 3D scene perception (occupancy and panoramic depth), LiDAR street mapping, vehicle interaction, and diverse controllable agents (drone, robot dog, multi-agent collaboration). Supports dynamic 3DGS environment loading and video data recording pipelines.

## Open-Source GitHub Projects

- **[Habitat-Sim](https://github.com/facebookresearch/habitat-sim)**  
  High-performance 3D simulator for embodied AI research (MIT). Thousands of frames per second—orders of magnitude faster than prior simulators. Features configurable agents, sensor suites (RGB, depth, semantic segmentation, surface normals, optical flow), and scene dataset ingestion API. Supports Habitat 1.0 (navigation), Habitat 2.0 (rearrangement with HAB benchmark), and Habitat 3.0 (co-habitat with humans and avatars).

- **[AI2-THOR](https://ai2thor.allenai.org/)**  
  Near-photorealistic interactive indoor scenes built on Unity. Rich object properties and affordances. Four task suites: iTHOR, RoboTHOR, ProcTHOR-10K, and ArchitecTHOR. Foundation for ALFRED, ALFWorld, and many other benchmarks. Predefined actions (PA) abstract physical interactions—agents modify object states instantaneously (e.g., open a closed cabinet), suitable for high-level task planning.

- **[SAPIEN](https://sapien.ucsd.edu/)**  
  Simulation platform generating realistic 3D scenes with complex physics interactions. ManiSkill built on SAPIEN for manipulation with 3D visual input. Includes tasks with articulated and deformable objects, mobility, and diverse robot embodiments. Large-scale demonstration data with efficient, high-quality simulation.

- **[MuJoCo](https://mujoco.org/)**  
  Multi-joint dynamics with contact physics engine (Apache-2.0, open-sourced 2021). Implicit joint damping implementation enables stable simulation for high damping values—critical for muscle-controlled neuromechanical experiments. Foundation for RoboSuite, RoboCasa, Meta-World, DeepMind Control Suite, and dozens of robot learning benchmarks. Fast, accurate, and widely adopted.

- **[RoboSuite](https://robosuite.ai/)**  
  Modular simulation framework and benchmark for robot learning powered by MuJoCo. Standardized manipulation tasks, procedural environment generation, diverse robot embodiments (including humanoids), composite controllers (joint-space velocity, inverse kinematics, operational space, whole body), teleoperation devices (keyboard, SpaceMouse, DualSense), multi-modal sensors, and photorealistic rendering via NVIDIA Isaac Sim. Part of the ARISE Initiative.

- **[RoboCasa / RoboCasa365](https://robocasa.ai/)**  
  Large-scale simulation framework for training generalist robots in everyday kitchen environments. **RoboCasa365** provides 2,500 realistic kitchen environments, 365 everyday tasks (65 atomic + 300 composite) across 60 daily activities, and over 2,000 hours of robot interaction data. Pre-training scenes strictly non-overlapping with evaluation scenes. Sim-and-Real training achieves **79.8% average success** vs. 61.8% Real Only. Key finding: MimicGen synthetic data scales atomic tasks ~100× but quality varies and can degrade downstream performance.

- **[PyBullet](https://pybullet.org/)**  
  Python module for physics simulation, robotics, and deep learning (zlib license). Ravens benchmark (10 tabletop manipulation tasks), VIMA-BENCH (17 multimodal prompt tasks), CALVIN (34 long-horizon language-conditioned tasks with Franka Panda), and LoHoRavens. Excels in RL scalability alongside MuJoCo. Joint damping implemented explicitly—can cause instabilities for high damping values.

- **[Gazebo Sim](https://gazebosim.org/)**  
  Open-source robotics simulator with strong ROS/ROS 2 integration. Evolution from Gazebo Classic to Ignition to Gazebo Sim. Excel in integration and teaching. Collaborative development with Isaac Sim and O3DE communities for standardized ROS interfaces. Best for teams prioritizing ROS compatibility and educational use.

- **[iGibson](https://github.com/StanfordVL/iGibson)**  
  Simulation environment for interactive navigation and mobile manipulation. Uses Rigid Bodies with Predefined Actions (RBPA) for grasping and Rigid Body Physics (RBP) after release—full physics simulation for all objects continuously with real robot embodiments. Supports LiDAR and PBR rendering. Fifteen high-quality fully interactive scenes. Platform for iGibson Sim2Real Challenge at CVPR20 and iGibson Challenge at CVPR21.

- **[ThreeDWorld (TDW)](https://github.com/threedworld-mit/tdw)**  
  Continuous Rigid Body Physics (RBP) with simplifications facilitating grasping using robot avatars rather than real robot platforms. Supports physics-based interactive tasks.

- **[VirtualHome](http://virtual-home.org/)**  
  Multi-agent household activity simulation platform. Crowdsourced 2,821 ActivityPrograms spanning 75 atomic actions and 308 objects. Scratch-style interface with 77 block types for program authoring. Uses predefined actions (PA) abstracting physical interactions.

### Additional Strong Open-Source Options

- **[Isaac Lab](https://github.com/isaac-sim/IsaacLab)** — Unified framework for robot learning built on NVIDIA Isaac Sim. GPU-accelerated physics and rendering for RL and imitation learning.
- **[ManiSkill3](https://github.com/haosulab/ManiSkill)** — GPU-parallelized robotics simulation and rendering built on SAPIEN. 30,000+ FPS with 4090 GPU. Supports heterogeneous simulation.
- **[RLBench](https://github.com/stepjam/RLBench)** — 100 hand-designed manipulation tasks built on CoppeliaSim (V-REP). First large-scale benchmark for imitation and RL.
- **[LIBERO](https://github.com/Lifelong-Robot-Learning/LIBERO)** — Lifelong robot learning benchmark with four fixed-base manipulation suites (Spatial, Object, Goal, Long).
- **[Meta-World](https://github.com/Farama-Foundation/Metaworld)** — 50 manipulation tasks for meta-RL and multi-task learning built on MuJoCo.
- **[Brax](https://github.com/google/brax)** — Differentiable physics engine for large-scale RL in JAX.
- **[Genesis](https://github.com/Genesis-Embodied-AI/Genesis)** — Universal physics engine for robotics and embodied AI with generative simulation capabilities.

**Frameworks for building custom systems**: Combine **MuJoCo** for fast physics with **Habitat-Sim** for navigation tasks, **SAPIEN/ManiSkill3** for GPU-parallelized manipulation, **RoboCasa365** for kitchen-scale long-horizon training, **AI2-THOR** for photorealistic indoor scenes, and **Isaac Sim** for photorealistic rendering—creating a comprehensive embodied AI simulation stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Embodied AI environments are research tools. Performance in simulation does not guarantee real-world robot success—the sim-to-real gap remains a critical challenge.
- **No simulator dominates across all criteria.** Gazebo Sim and Webots excel in integration and teaching, Isaac Sim and CARLA in realism, and PyBullet or MuJoCo in RL scalability. The field is converging toward standardized ROS interfaces and advanced physics engines.
- **Predefined Actions (PA) vs. Rigid Body Physics (RBP) is a fundamental design choice.** AI2-THOR and VirtualHome use PA—instantaneous state transitions suitable for high-level planning but limiting granularity for robot learning. iGibson, SAPIEN, and MuJoCo use RBP—continuous physics simulation critical for sim-to-real transfer.
- **Synthetic data quality varies.** RoboCasa365 found MimicGen synthetic trajectories scale atomic tasks ~100× but quality varies and can sometimes degrade downstream performance—a key finding for the community.
- Self-hosted open-source solutions require proper GPU provisioning, storage for scene datasets, and ongoing maintenance. Cite specific simulator versions in publications.

---

**Made for robotics researchers, embodied AI engineers, and developers building transparent simulation infrastructure.**  
Let's make Embodied AI Environments more open, data-driven, and physically grounded.
