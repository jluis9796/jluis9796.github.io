---
layout: post
title:  "Learning from demonstration"
date:   2020-05-24 13:08:36 +0900
---
**Survey**
* Harish Ravichandar, Athanasios S. Polydoros, Sonia Chernova, Aude Billard. Recent Advances in Robot Learning from Demonstration. Annual Review of Control, Robotics, and Autonomous Systems, 2020. <a href="http://rail.gatech.edu/assets/files/2019_LfD_Survey_preprint.pdf"> (link) </a>

```
Surveys LfD => [1,2,3,4,7,9,10,11]
Survey grasping => [12]
Motion planning => [5,6]
LfD Applications => Industry[7], Healthcare[8]
Kinesthetic teaching => [13,14,15,16,17,18,19]
Correspondence problem => [20]
Teleoperation teaching => [21,22,23,24]
Teleoperation interfaces => [25,26,27,28,29]
Crowdsourcing => [30,31,32,33]
Teleoperation applications => [34,28,35]
Passive Observation teaching => [36,37,38]
Pasive Observation Applications => [39,40,42,42,43,31,44]

*Interaction techniques [4]
Active learning => [39,45,46,47,48]
Corrective demonstration =>[49,50]
Importance of human role => [51]
Importance of agent active role => [52,53,54,55,56]

*Learning Methods

Policy learning
GAN[57]+IRL-> GAIL [58]
Policy input (Time) => [13,19,59-65]
Policy input (state) => [15,16,26,66-84]; examples of state including time  [14,85,86]; learning appropriate state-space: unsupervised [87,88,89], supervised[24,90,91]
Policy input (raw observation) => [41,43,92,93,94]
Policy output (Trajectory)=>end-effector position[13,17,64,68,70,81,82,95,96,97]; pose [67,83,98]; force [61,72,74,78]; joint state [62,99]; approaches: dynamical system [70,83,97,98,100,101], prob. inference[13,62,82]
Policy output (low-level actions)=> torques[26,80,84,102,103], stiffness [69,104]; learning stiffness from HRI [63,72,105]; challenge due to external changes [106]
Policy class (deterministic) => theoretical convergence [70,79,83]
Policy class (stochastic) => [62,101,107]; theoretical convergence [101]
Policy class(time-dependent)=> [59,60,62,65][64]
Policy class (time-invariant)=> [70,83][100]

Cost/Reward learning (Trajectory optimization)=> Traditional methods [5,108,109] LfD methods [96,110,111,112]
Cost/Reward learning (Inverse reinforcement learning) => [113]; ≈inverse optimal control [114-117]; linear reward assumption [115-120], non-linear [58,117,121]; maximum-margin based IRL [113,118,122,123], maximum-entropy based IRL [58,119,124,125]; model-based methods [118,120,124,125], model-free methods [119,116,117]; model based vs free[126]

Plans learning => [128-136][150]; components-similarity-based segmentation [137-142], event-occurrence-based [25,143,144]; primitive sequence [132,133,141,145], primitive hierarchy [128,146-149][24]

Simultaneous Multiple learning=> [130,132,136,149,151,152,153,154][156]

*Applications
Manipulator
Manufacturing => [157,158][80,117,159,33,34,160,7,38,39];  kinesthetic teaching and policy learning are common
Assistance and Health care => [161,162,86,163,164,165,166,167,8]; kinesthetic teaching and stable policies are used
Human robot interaction => [14,63,66,75,85,103,134]; state-input policy learning and compliance (torque and stiffness learning [80,104]) are used

Mobile robots
Ground vehicles => [168] IRL [118,122,169], interactive learning [170], active learning [171], adversarial learning [172], end-to-end learning [40,173] teleoperation is common, but also kinesthetic teaching [174]
Aerial vehicles => helicopter maneuvers [21], cluttered environment [175], end-to-end learning [176,177]. Teleoperation is common, and stability is handled by traditional approaches.
Bipedal and quadrupedal robots => walk [178,179], gait optimization [180], quadrupedal locomotion [123,181,182]. Teleoperation and human gait capture are common.
Underwater vehicles => valve turning [184], robot teleoperation [35,185,186], data collection [187]. Teleoperation is common, and stability is handled by traditional approaches.

* Strengths and limitations
Strengths
Non-expert teaching
Data efficiency => LfD + RL [189-196]
Safe learning
Performance guarantee => strong convergence [70,79,81,83,100]
platform Independence => for example, Dynamic Movement Primitive [100] is used in several platforms [153,67,200,201,202]

Limitations
Demonstration
kinesthetic teaching is limited to manipulators.
visual demonstrations suffer from correspondence problem due to motion constraints and dimensionality. Also occlusion, pose estimation, noise.
Teleoperation requires challenging interfaces.

Labeled data
LfD is efficient when enough labeled data is available. If not, LfD requires a considerable amount of data, which implies more time and resources.

Suboptimal or inappropriate demonstrations
When most data is suboptimal, existing solutions limits to filter or identify suboptimal samples [203,204]
LfD alone cannot, so approaches along with other learning methods are required.

*Challenges
Generalization [205,206] => covariate shift or compounding error [207][170]
Intra- and inter-task (skill transfer) generalization => multi-task learning [154,209]
When to extrapolate and when to request user intervention?

Hyper-parameter selection => the need for manual tuning of machine learning models decreases the ability of non-experts.
+End-to-end representation-> neural networks parameters
+Time-based representation-> RBF of DMP-based methods
+State-action representation-> number of components of GMM
+Cost/reward learning-> type of function (etc) of IRL
+High-level task plans-> number of actions, sequences, and states.
=> Automated hyper-parameter selection can be achieved with Gaussian Processes (though they're complex); For GMM, it is more intuitive to use Bayesian Variational Inference [210]; For task plans, clustering methods.

*LfD methods evaluation
Data and computationally efficient (convergence [211])
Smooth outcome
Stability guarantee
Efficient generalization
High repeatability

Appropriate distance metric => Euclidean distance; others [95,111]

Simultaneous low- and high-level learning
Discussed in section 3.4 but research on efficient methods is required.

Multi-modal learning
psychological evidence of learning enhancement [212]
However, limited LfD methods [26,213]
How to identify most relevant modality?
How to collect multi-modal demonstration without burdening the users with sensors?

Multiple demonstrators and cloud robotics
Different demonstrators-> Different priorities of optimal behavior, Different levels of expertise
IRL with different levels of expertise was shown to reach a richer reward function and structure than with single demonstrator or similar expertise demonstrators [214]

```

* Russell C. Toris. Spatial and Temporal Learning in Robotic Pickand-Place Domains via Demonstrations and Observations, Phd thesis, 2016
https://digitalcommons.wpi.edu/cgi/viewcontent.cgi?article=1134&context=etd-dissertations

* David Kent, Carl Saldanha, Sonia Chernova. Leveraging depth data in remote robot teleoperation interfaces for general object manipulation, 2019
http://rail.gatech.edu/assets/files/ijrr2019-kent-saldanha-chernova.pdf



For more ...
http://rail.gatech.edu/
