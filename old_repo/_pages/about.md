---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I'm a Ph.D. student in School of [Electrical and Computer Engineering](https://www.ece.gatech.edu/), Georgia Tech, specializing in Robotics. I'm advised by Dr. [Ye Zhao](https://www.me.gatech.edu/faculty/zhao) at the [Laboratory for Intelligent Decision and Autonomous Robots (LIDAR)](https://lab-idar.gatech.edu/).

Prior to that, I received an M.S. also in [Electrical and Computer Engineering](https://www.ece.gatech.edu/) from Georgia Tech in 2020 and a B.Eng. in Automation from [Northeastern University (China)](http://english.neu.edu.cn/) in 2018.

My research interests center around optimization-based planning, control, and estimation for contact-rich manipulation and legged locomotion, especially in: 

1) Computationally efficient trajectory optimization and model predictive control;

2) Agile locomotion leveraging whole-body dynamics;

3) Safety guaranteed footstep planning in challenging terrains;

4) Reinforcement learning for contact-rich loco-manipulation.

I also collaborated closely with [SkyMul](https://www.linkedin.com/company/skymul/) to automate the rebar tying process using quadrupedal robots. Check out some of the cool things we showcased at WOC 2024!

<div style="display: flex; align-items: center; margin-bottom: 20px; gap: 20px;">
    <div style="flex: 0 0 auto;">
        <img src="../images/rebar_1.gif" alt="Rebar Tying Animation 1" style="width: 300px; height: auto;">
    </div>
    <div style="flex: 0 0 auto;">
        <img src="../images/rebar_2.gif" alt="Rebar Tying Animation 2" style="width: 300px; height: auto;">
    </div>
</div>

News:
======
- Jun 2025: Our work on combining mixed-integer programming and reactive synthesis has been accepted to IROS 2025.
- Jan 2025: My work with MERL on proprioceptive contact state and force estimation has been accepted by ICRA 2025. See you in Atlanta!
- Jan 2024: I start my internship at MERL!
- May 2023: Our work on soft contact manipulation is finally accepted by TRO! 
- Jan 2023: One paper on vision-based navigation has been accepted by ICRA 2024.
- June 2022: Our momentum-aware trajectory optimization and MPC paper has been accepted by RA-L. [[pdf]](https://arxiv.org/pdf/2203.01548.pdf)
- May 2022: Our multi-robot task allocation and planning work has been accepted by CASE 2022! The extended version is attached. [[pdf]](https://arxiv.org/pdf/2110.08436.pdf)

Selected Publications:
======
Please check out my [Google Scholar](https://scholar.google.com/citations?user=cnitUIAAAAAJ&hl=en) page for the full list of my publications.

<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <div style="flex: 0 0 250px;">
        <img src="..\images\micp-ltl.gif" alt="LTL-MICP" style="width: 250px; height: auto;">
    </div>
    <div style="flex: 1; padding-left: 20px;">
        <h3>Physically-Feasible Reactive Synthesis for Terrain-Adaptive Locomotion via Trajectory Optimization and Symbolic Repair</h3>
        <p>
            <strong>Ziyi Zhou*</strong>, Qian Meng*, Hadas Kress-Gazit, Ye Zhao<br>
            <em>IEEE/RSJ International Conference on Intelligent Robots, Systems (IROS), 2025</em>
        </p>
        <p>
            <a href="https://arxiv.org/pdf/2503.03071">Paper</a> |
            <a href="https://www.youtube.com/watch?v=i2rw1nVTxxY">Video</a>
            <!-- | <a href="link-to-bibtex">BibTeX</a> -->
        </p>
    </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <div style="flex: 0 0 250px;">
        <img src="..\images\ICRA2025_IMMKF.gif" alt="IMM-MBKO" style="width: 250px; height: auto;">
    </div>
    <div style="flex: 1; padding-left: 20px;">
        <h3>Simultaneous Collision Detection and Force Estimation for Dynamic Quadrupedal Locomotion</h3>
        <p>
            <strong>Ziyi Zhou</strong>, Stefano Di Cairano, Yebin Wang, Karl Berntorp<br>
            <em>IEEE International Conference on Robotics and Automation (ICRA), 2025</em>
        </p>
        <p>
            <a href="https://arxiv.org/pdf/2504.17201">Paper</a>
        </p>
    </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <div style="flex: 0 0 250px;">
        <img src="..\images\opt2skill.gif" alt="Opt2Skill" style="width: 250px; height: auto;">
    </div>
    <div style="flex: 1; padding-left: 20px;">
        <h3>Opt2Skill: Imitating Dynamically-feasible Whole-Body Trajectories for Versatile Humanoid Loco-Manipulation</h3>
        <p>
            Fukang Liu, Zhaoyuan Gu, Yilin Cai, <strong>Ziyi Zhou</strong>, Shijie Zhao, Hyunyoung Jung, Sehoon Ha, Yue Chen, Danfei Xu, Ye Zhao<br>
            <em>arXiv preprint</em>
        </p>
        <p>
            <a href="https://arxiv.org/pdf/2409.20514">Paper</a> |
            <a href="https://www.youtube.com/watch?v=DRHfpCYXJfU">Video</a> |
            <a href="https://opt2skill.github.io/">Website</a>
            <!-- | <a href="link-to-bibtex">BibTeX</a> -->
        </p>
    </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <div style="flex: 0 0 250px;">
        <img src="..\images\mmp.png" alt="MMP" style="width: 250px; height: auto;">
    </div>
    <div style="flex: 1; padding-left: 20px;">
        <h3>Hierarchical Experience-informed Navigation for Multi-modal Quadrupedal Rebar Grid Traversal</h3>
        <p>
            Max Asselmeier,
            Jane Ivanova,
            <strong>Ziyi Zhou</strong>,
            Patricio A. Vela,
            Ye Zhao<br>
            <em>IEEE International Conference on Robotics and Automation (ICRA), 2024</em>
        </p>
        <p>
            <a href="https://lab-idar.gatech.edu/wp-content/uploads/2023/09/ICRA2024_MMP_Navigation_Asselmeier.pdf">Paper</a> |
            <a href="https://youtu.be/NHK-VPDyDm0">Video</a>
            <!-- | <a href="link-to-bibtex">BibTeX</a> -->
        </p>
    </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <div style="flex: 0 0 250px;">
        <img src="..\images\tro_soft.gif" alt="Soft Manipulation" style="width: 250px; height: auto;">
    </div>
    <div style="flex: 1; padding-left: 20px;">
        <h3>Real-Time Deformable-Contact-Aware Model Predictive Control for Force-Modulated Manipulation</h3>
        <p>
            Lasitha Wijayarathne*,
            <strong>Ziyi Zhou*</strong>,
            Ye Zhao,
            Frank L. Hammond III<br>
            <em>IEEE Transactions in Robotics (TRO), 2023</em>
        </p>
        <p>
            <a href="https://arxiv.org/pdf/2212.09234">Paper</a> | 
            <a href="https://github.com/lasithagt/admm">Code</a> |
            <a href="https://www.youtube.com/watch?v=wuC0Zyr-ZKU">Video</a>
            <!-- | <a href="link-to-bibtex">BibTeX</a> -->
        </p>
    </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <div style="flex: 0 0 250px;">
        <img src="..\images\momentum_aware_2.gif" alt="Momentum-aware TO" style="width: 250px; height: auto;">
    </div>
    <div style="flex: 1; padding-left: 20px;">
        <h3>Momentum-Aware Trajectory Optimization and Control for Agile Quadrupedal Locomotion</h3>
        <p>
            <strong>Ziyi Zhou*</strong>, Bruce Wingo*, Nathan Boyd, Seth Hutchinson, Ye Zhao<br>
            <em>IEEE Robotics and Automation Letters (RA-L), 2022</em>
        </p>
        <p>
            <a href="http://lab-idar.gatech.edu/wp-content/uploads/Publications/RAL_dynamics_consensus_2022.pdf">Paper</a> | 
            <a href="https://www.youtube.com/watch?v=6M78cM0cgCM">Video</a>
            <!-- | <a href="link-to-bibtex">BibTeX</a> -->
        </p>
    </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <div style="flex: 0 0 250px;">
        <img src="..\images\gpf.png" alt="GPF navigation" style="width: 250px; height: auto;">
    </div>
    <div style="flex: 1; padding-left: 20px;">
        <h3>GPF-BG: A Hierarchical Vision-Based Planning Framework for Safe Quadrupedal Navigation</h3>
        <p>
            Shiyu Feng,
            <strong>Ziyi Zhou</strong>,
            Justin S. Smith,
            Max Asselmeier,
            Ye Zhao,
            Patricio A. Vela<br>
            <em>IEEE International Conference on Robotics and Automation (ICRA), 2023</em>
        </p>
        <p>
            <a href="http://lab-idar.gatech.edu/wp-content/uploads/2023/02/pubQuadNav-ICRA-2023.pdf">Paper</a> | 
            <a href="https://youtu.be/avUnefrbhY8">Video</a>
            <!-- | <a href="link-to-bibtex">BibTeX</a> -->
        </p>
    </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <div style="flex: 0 0 250px;">
        <img src="..\images\ltl_multi_robot.png" alt="LTL multi robot" style="width: 250px; height: auto;">
    </div>
    <div style="flex: 1; padding-left: 20px;">
        <h3>Reactive Task Allocation and Planning for Quadrupedal and Wheeled Robot Teaming</h3>
        <p>
            <strong>Ziyi Zhou</strong>, Dong Jae Lee, Yuki Yoshinaga, Dejun Guo, Ye Zhao<br>
            <em>IEEE International Conference on Automation Science and Engineering (CASE), 2022</em>
        </p>
        <p>
            <a href="https://arxiv.org/pdf/2110.08436.pdf">Paper</a> | 
            <a href="https://github.com/GTLIDAR/ltl_multi_agent">Code</a> |
            <a href="https://www.youtube.com/watch?v=xtjLYctN03Y">Video</a>
            <!-- | <a href="link-to-bibtex">BibTeX</a> -->
        </p>
    </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <div style="flex: 0 0 250px;">
        <img src="..\images\sydebo.png" alt="TAMP" style="width: 250px; height: auto;">
    </div>
    <div style="flex: 1; padding-left: 20px;">
        <h3>SyDeBO: Symbolic-Decision-Embedded Bilevel Optimization for Long-Horizon Manipulation in Dynamic Environments</h3>
        <p>
            Zhigen Zhao*, <strong>Ziyi Zhou*</strong>, Michael Park, Ye Zhao<br>
            <em>IEEE Access, 2021</em>
        </p>
        <p>
            <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9537786">Paper</a> | 
            <a href="https://github.com/GTLIDAR/tamp-manipulation/tree/manipulation-tamp-RAL">Code</a> |
            <a href="https://www.youtube.com/watch?v=lkhr3UiiDuw">Video</a>
            <!-- | <a href="link-to-bibtex">BibTeX</a> -->
        </p>
    </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <div style="flex: 0 0 250px;">
        <img src="..\images\admm.png" alt="Accelerated ADMM" style="width: 250px; height: auto;">
    </div>
    <div style="flex: 1; padding-left: 20px;">
        <h3>Accelerated ADMM based Trajectory Optimization for Legged Locomotion with Coupled Rigid Body Dynamics</h3>
        <p>
            <strong>Ziyi Zhou</strong>, Ye Zhao<br>
            <em>American Control Conference (ACC), 2020</em>
        </p>
        <p>
            <a href="http://lab-idar.gatech.edu/wp-content/uploads/Publications/ACC2020_ADMM.pdf">Paper</a> | 
            <a href="https://www.youtube.com/watch?v=BP3YILbidN0&t">Video</a>
            <!-- | <a href="link-to-bibtex">BibTeX</a> -->
        </p>
    </div>
</div>


<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=300&t=tt&d=BWCxL0v9h2hgv3PCfXlKMcKj-1BieloY3GIobxnMTsQ'></script>