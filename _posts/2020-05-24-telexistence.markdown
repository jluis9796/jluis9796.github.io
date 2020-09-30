---
layout: post
title:  "Telexistence"
date:   2020-05-24 13:34:36 +0900
---

# Teleoperation Toolkits
<table>
  <thead>
    <tr>
      <th>Title</th>
      <th>25%</th>
      <th>50%</th>
      <th>75%</th>
      <th>99%</th>
      <th>Tags</th>
      <th>Summary</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>Susumu Tachi. Recent Development of Telexistence, 2018</td>
    <td>●●●●</td>
    <td></td>
    <td></td>
    <td></td>
    <td>#Survey</td>
    <td>Summary</td>
    </tr>
    <tr>
    <tr>
    <td>Takahiro Nozaki, Satoshi Hangai. Telexistence and Real Haptics - Fusion of humans and machines opens a new avenue, 2018</td>
    <td>●●●●</td>
    <td></td>
    <td></td>
    <td></td>
    <td>#Haptics</td>
    <td>Summary</td>
    </tr>
    <tr>
    <td>Masahiro Furukawa. Scale conversion on telexistence, 2018</td>
    <td>●●●●</td>
    <td></td>
    <td></td>
    <td></td>
    <td>#Scale conversion</td>
    <td>Summary</td>
    </tr>
    <tr>
    <td>David Kent, Carl Saldanha, Sonia Chernova. Leveraging depth data in remote robot teleoperation interfaces for general object manipulation, 2019. (David Kent, Carl Saldanha, Sonia Chernova. A comparison of remote robot teleoperation interfaces for General object manipulation, 2017)</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td>#Grasping interfaces for teleoperation #(Free-positioning, Constrained-positioning,point-and-click)</td>
    <td>Description: In contrast to contemporary robot manipulation using a Free Positioning pose specification, here two novel interfaces, Constrained Positioning and Point-and-Click, are presented, which incorporate scene information from depth data into the grasp pose to reduce the number of 3D transformations the user must input. Also, the interactions are designed for 2D image streams, rather than traditional 3D virtual scenes, further reducing mental transformations. The findings: The study showed that Point-and-Click outperforms both Free Positioning and Constrained Positioning by significantly increasing the number of tasks completed and significantly reducing task
failures and grasping errors, while significantly reducing the number of user interactions. Why? Constraining the interaction to a physical surface significantly reduces the number of missed grasps, resulting in more efficient use of the arm. Also, the 2D visualization mode resulted in significantly better performance than the 3D visualization mode, with significant reductions in task failures, grasping errors, task completion time, number of interactions, and user workload, all while reducing bandwidth requirements imposed by streaming depth data. We recommend using 2D image views over 3D depth views for teleoperation manipulation interfaces and switch between multiple camera views to get a better depth sense. For difficult to detect objects, such as specular objects, transparent objects or occluded objects, it will not be able to calculate a good set of grasps.
</td>
    </tr>
    <tr>
    <td>Akira Fukabori, Kevin Kajitani. Ana Avatar, 2018</td>
    <td>●●●●</td>
    <td></td>
    <td></td>
    <td></td>
    <td>#Toolkits</td>
    <td>Summary</td>
    </tr>
    <tr>
    <td>MHD Yamen Saraiji. Beyond Presence - A telexistence toolkit for augmenting body and re-engineering presence, 2018</td>
    <td>●</td>
    <td></td>
    <td></td>
    <td></td>
    <td>#Toolkits</td>
    <td>Summary</td>
    </tr>
    <tr>
    <td>MHD Charith Fernando, Genki Sano. Future of telexistence technology and its impact to the society, 2018</td>
    <td>●</td>
    <td></td>
    <td></td>
    <td></td>
    <td>#Toolkits</td>
    <td>Summary</td>
    </tr>
    <tr>
    <td>Daisuke Kondo. Visual display system for teleoperation of construction machinery, 2018</td>
    <td>●</td>
    <td></td>
    <td></td>
    <td></td>
    <td>#Toolkits</td>
    <td>Summary</td>
    </tr>
    <tr>
    <td>Russell C. Toris. Spatial and Temporal Learning in Robotic Pickand-Place Domains via Demonstrations and Observations, Phd thesis, 2016 <a href= "https://digitalcommons.wpi.edu/cgi/viewcontent.cgi?article=1134&context=etd-dissertations" > (Link) </a></td>
    <td>●</td>
    <td></td>
    <td></td>
    <td></td>
    <td>#Cloud crowdsourcing</td>
    <td> Description: A system asks crowdsourced users to place a series of items in a simulated world inside of a web browser (three JavaScript libraries were developed to facilitate web-based humanrobot interaction: the roslibjs client library and ros2djs and ros3djs visualization libraries). This raw data is used to generate a multi-hypothesis models in an unsupervised manner via Expectation Maximization clustering and a novel ranking heuristic. In addition, when ordering constraints are needed, the solution proposed is weighting the heuristic by a ratio of coarsely available temporal data. Finally a Temporal Persistence Modeling algorithm (probabilistic exponential distributions augmented with a Gaussian component to represent probable object locations and search suggestions) is presented for probabilistic prediction of the time that an object is expected to remain at a given location given sparse prior observations. The findings: The resulting hypotheses from the proposed
methodology matched the human expectation of the task description 94% of the time when no temporal constraints are required.  Also, a CARL robot (consists of
a Segway RMP base with a 6 degree-of-freedom JACO arm)  successfully queried the system for what a table setting template is, found the necessary objects on the kitchen
counter, and set the table appropriately. For unknown ordering constraints, the system was able to reconstruct a tower adhering to both spatial and temporal constraints in both the "Consistent Ordering, Consistent Placement" and "Random Ordering, Consistent Placement" conditions. Also, in the household crowdsourced domain showed the ability to overcome noisy environments from untrained users in order to set a table in the appropriate order. TP models based on sparse temporal observations showed a reasonable prediction method for single-item tracking and also enabled a robot for multi-item location prediction.</td>
    </tr>
    <tr>
    <td>Ajay Mandlekar et al. RoboTurk: A crowdsourcing platform for robotic skill learning through imitation, 2018</td>
    <td>●</td>
    <td></td>
    <td></td>
    <td></td>
    <td>#Toolkits #Mobile phone endpoing #Transpacific teleoperation (China - California) #Learning from teleoperation demonstration </td>
    <td>Description: A crowd-sourced platform that collects large set of data from concurrent users for (simulated Sawyer) robot manipulation through a video-streaming website, a smartphone as a VR motion controller and a haptic feedback. Assumption: While RL requires reward function, large-state-space exploration, large interaction, and self-supervised learning has large noise, Imitation learning improves efficiency and performance. While kinesthestic teaching is intuitive but limited, teleoperation has been for decades. While video-game controllers lacks natural variations in motion, free-space positioning interfaces as VR enables fine-grained dexterous control. The goal: They conducted a user study comparing the performance of smartphone-based controller, keyboard, 3D Mouse and VR controller. The findings: A dataset with over 2200 task demonstrations (137 hours of data collected in 20 hours of usage by contracted workers). What about user interface evaluation? Keyboard and 3D mouse completion time was slower than VR and phone, which were similar. What about network capacity and delays? Three troublesome (low-capacity, high-delay, or both) networks produced roughly the same distributions of completion time as the baseline. What about far remote teleoperation? Users were able to complete the tasks despite high network delays between California and China, but the completion time was around 20 seconds slower. Using data center in China introduced a constant delay in comparison to a data center in Oregon. Can the collected data improve policy learning? Demonstration-guided reinforcement learning comparison using (none, 1, 10, 100, 1000) demonstrations of the two tasks showed that a large and diverse dataset of demonstrations can encourage agents to explore and learn more effectively. However, only 10 demonstrations were able to achieve comparable performance to 100 demonstrations maybe due to the fact the data collected in 48 hours is large enough. Nonetheless, even though 1000 demonstrations is higher in terms of variety, this could be pausibly mirrored by using 10 demonstrations and giving agents time to explore from demonstration states.</td>
    </tr>
    <tr>
    <td>Jaeyong Sung, Seok Hyun Jin, Ashutosh Saxena. Robobarista: Object part based transfer of manipulation trajectories from crowd-sourcing in 3d pointclouds, 2015</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td>#Learning generalization #Deep learning #Multimodal integration</td>
    <td>Description: A simulated and real PR2 robot are trained by non-experts through a crowd-sourcing web-based 3d-viewer-controller to manipulate objects, and a deep learning model is trained to learn this multimodal data (point cloud, language, trajectory). The hypothesis: Many differently-shaped objects share similarly-operated object parts. The assumption: the target object parts were pre-labeled from scene voxels by experts, so the target part at each trial is highlighted to non-experts from the start. The goal: thus, the goal is to evaluate if the manipulation trajectory of an object can be transferred to a completely different object if they share similarly-operated parts (116 RGB-D point-clouds, 1225 trajectories, 250 language instructions by 71 non-experts). The findings: Were trajectories completely transferred? Yes for 60%. Were the object manipulation the actual correct one? No guarantee, but the results showed it was achieved for a large fraction of objects which the robot has never seen before. Is crowd-sourcing teaching possible? Yes, crowd-sourced non-experts performed at 60%, compared to 53.1% by experts. Is segmentation required? Yes. Even though target parts were prelabel by experts, they were still extremely noisy. Is intermediate object part labeling necessary to find a manipulation trajectory? NOT sufficient (as expected by hypothesis). The object part classifier performed badly at 23.3% even though the part label finder achieved 70%. Can features be hand-coded? NOT easily. While features methods achieved 40.8% or even 53.7% with full-data (heavy computation), the deep learning method (not hand-designing of features) achieved equal or better performance even with simple concatenation or noise</td>
    </tr>
    <tr>
    <td>Eric Rosen, Elizabeth Phillips, David Whitney, Daniel Ullman, Stefanie Tellex .Testing robot teleoperation using a virtual reality interface with ROS reality, 2018</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td>#Learning generalization #Deep learning #Multimodal integration</td>
    <td> Description: A Baxter robot is teleoperated and controlled through ROS reality and Unity-based HTC-vive reality system. The human and robot share a virtual space, but are not superimposed (The humans is around the robot). The goal: This work evaluated twelve complex tasks and measured whether they were succesfully achieved with this robot and software, and whether they could be teleoperated. Found issues: more precision for block stacking through VR, robot force or end-effector deficiencies, not knowing robot posses limitations through ROS reality. Benefits: They argue that teleoperation could be a solution to the problem of gathering data for learning from demonstration.</td>
    </tr>
    <tr>
    <td> Tianhao zhang, et al. Deep imitiation learning for complex manipulation tasks from virtual reality teleoperation, 2018</td>
    <td>●</td>
    <td></td>
    <td></td>
    <td></td>
    <td>#Object Manipulation #Deep learning #Multimodal integration #Learning from teleoperation demonstration </td>
    <td>Description: A consumer-grade VR device (headset and motion-tracked controller) is used to teleoperate a PR2 robot (with a RGBD-camera for color and depth images). The data (RGB image, depth image and hand position) from conducting ten manipulation tasks with the robot was collected and used to train deep visuomotor policies (pixels-to-action mapping). The goals: Can we build an inexpensive and intuitive teleoperation system for robotic manipulation? can imitation learning learn to solve manipulation tasks using these data? Assumption: To avoid sickness due to time lag between displayed scene and humans' head motion, we render a 3D point cloud from RGBD images as object in the virtual environment and update instantaneously the human view to reflect head movement. The result: less than 30 minutes of data was sufficient to learn a successful policy (High success rate and good generalization) even in long running tasks. Although successful, the learned policies were often suboptimal compared to humans (e.g., not following the shortest path). For initial states beyond the training ones, the robot succeded in the experiments. </td>
    </tr>
        <tr>
    <td>Ioannis Havouties, Sylvain Calinon. Learning from demonstration for semi-autonomous teleoperation, 2018</td>
    <td>●●</td>
    <td></td>
    <td></td>
    <td></td>
    <td>#Underwater teleoperation #Mixed teleoperation #TP-HSMM (Markov Model) #LQT (Linear Quadratic Tracking)</td>
    <td>Description: A teleoperation strategy that decouple the operator's and the robot's spaces in the statistical representation is proposed. This proposed approach intends to replace the conventional user of video streams with a minimal exchange of activation weights as communication overhead.</td>
    </tr>
  </tbody>
</table>

