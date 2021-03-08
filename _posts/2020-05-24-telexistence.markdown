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
    <td>Description: In hand motion of teleoperated robots, not only motion conversion but also other physical quantities are related to the scale conversion, and the device dimensions and the control are accurately designed. In most cases, geometrical relations are used. Endoscope tips have two cameras, and the distance between them is designed to be one scale smaller than the display for the surgeon. The tip of the robots is also one scale smaller than the surgeon's hand. This is the geometrical scale relation. Now, let's talk of the motion scale relation. While the distance, velocity and acceleration for straight motion respect to the operator has [scale factor > 1], the rotation motion has a [scale factor = 1]. Therefore, in order to create a sense and motion loop between the robot and the operator without loosing operator skills, the targets for conversion control are chosen wisely. From the perspective of telexistence, it is of interest what clue the operator uses to get the relation (scale factor) between self and the world when the body size changed. Geometrical Scale Conversion: Here, the factors to control are the binocular distance, vergence angle and the interpupillary distance. Also, the geometrical structure of the eye (camera) location, the observer's surface position and the target object. When one eye is closed and the observer height is changed, the height of the target object was reported to be felt different. When looking down, it feels larger, and when looking up, it feels shorter. This may be due to the change of the perceived gradient of the floor pattern extending toward the back depending on the observing height. The effect of changing binocular distance and observing height was reported to achieve a transition from adult perspective to kid perspective. The user first uses own body size as reference, but once surrounded by more people they become the reference. Also, elements as sofa and table limits this interpretation. When a box is put on top of a table, the  binocular distance become predominant. Motion Scale Conversion: Impedance control makes possible to transform the softness of a target, which could facilitate surgery via robots. In telexistence, sending to the robot an increased motion speed of the operator reduces the task time.</td>
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
    <td>Description: AVATAR refers to the technology that makes possible to experience senses through remote control in real time of robot synchronized to the user by using haptics, VR, telecommunications, sensors and robotics. Also it refers to the robot itself. It differs from remote communication in the fact that it makes possible to transmit the presence feeling, conciousness and skills. ANA decided to focus on this new technology to accomplish their goal: contributing to the dreamed future by connecting the world. ANA avatar XPRIZE: In association with XPRIZE foundation, ANA decided to conduct a 4 year competition on building a general purpose AVATAR, accounting for a 10 million dollars investment (429 tesms by 2018/8). AVATAR X: A program aiming to start a space business employing AVATAR. It is expected that AVATAR innovation helps to solve current distance and time limitations of space access. AVATAR X Consortium: Starts-ups and companies, both space-related ones and unrelated ones, were called to participate. The plan is to start createing the roadmap and business plan , and then start each project by 2020 fiscal year. AVATAR X Lab@OITA: Here, experiments on remote building construction will be conducted. Also, experiments on basic activities (searching, entertainment, building, living, eating, health, etc) in space in collaboration with humans on earth. AVARATIN: This refers to the services employing AVATAR technology.  The main goal is to spread AVATAR around the world. This includes business as robot sales but also data sales, skills usage, advertisement sales, among others. BtoB business is focused on public places (aquarium,museums) and big events (olimpics). BtoC business is focused on remote lessons, remote families. In the future the plan is to make possible everyone can register through their smartphone and connect easily to any robot. This requires increases AVATAR in cooperation with companies, and also to connect robots developed by research centers and startups. So far experiments have been conducted in Okinawa's aquarium and Hiroshima's museum. </td>
    </tr>
    <tr>
    <td>MHD Yamen Saraiji. Beyond Presence - A telexistence toolkit for augmenting body and re-engineering presence, 2018</td>
    <td>●</td>
    <td></td>
    <td></td>
    <td></td>
    <td>#Toolkits</td>
    <td>Description: In contrast with traditional telepresence systems, the design of telexistence robots (such as Telesar V) is mainly inhereted from the human body, thus the mapping between operator and the robot is consistent, and the sensory modalities and feedback are coherent. One advantage is the ability to redesign specific factors of human body. For example, modulate specific sensory modalities and augment parts of the body. Here, a telexistence toolkit (TxToolkit) used in augmentative, assistive, and collaboration apps is shown. The body modalities were the stereo vision, binaural audio and speech output. The head design was aimed to maintain minimal size and low-cost design. A visual programming interface was designed to facilitate the use of the toolkit. This interface was implemented under Unity3D. Using this interface makes possible to alter how the user's body is mapped with the robot. Therefore, we can also alter our body schema. We can refer to this form of body alteration as Body Morphology. There are three forms of morphological transformation: one-to-one body morphology (one human, one robot), one-to-many body morphology (one human, many robots), many-to-one body morphology (many humans, one robot).
      </td>
    </tr>
    <tr>
    <td>MHD Charith Fernando, Genki Sano. Future of telexistence technology and its impact to the society, 2018</td>
    <td>●</td>
    <td></td>
    <td></td>
    <td></td>
    <td>#Toolkits #gloves #HMD #Robot #Latency</td>
    <td>Description: A system teleoperation composed of three components was implemented: Cockpit control, Surrogate robot, Cloud infraestructure. The cockpit was light and small enough to be carried in a suitcase. The surrogate robot was cost-efficient and aimed for mass-production, which consists of 6DoF Torso, 3 DoF head, 7 DoF arms, 13 DoF hands, weight 75kg and 350W consumption. The camera resolution is 2160x1020 px, and 3 fingers are equipped with haptic sensors to detect 3DoF force, 3DoF vibration, and temperature. The cloud infraestructure prioritizes the data so that we can get the lowest latency while keeping the guaranteed data delivery as of traditional streaming servers. Typical upload+download latency within Japan is 25ms with optical fiber. The processing delay plus latency is around 125ms. the   Results: The system was implemented for visiting a remote island "Ogawasara" located several hundred kms away from Tokyo. 90 participants had visual, auditory, voice, haptic and motor experiences for approx. 10 minutes each person. </td>
    </tr>
    <tr>
    <td>Daisuke Kondo. Visual display system for teleoperation of construction machinery, 2018</td>
    <td>●</td>
    <td></td>
    <td></td>
    <td></td>
    <td>#Toolkits</td>
    <td>The problem: It has been reported a wide decrease of efficiency of remote manipulation of construction machines in comparison to direct manipulation. While rescue tasks do not require as much efficiency as security, mine tasks demand profitability and therefore require efficiency.The main cause for efficiency decrease is due to lack of visual information, auditory information and sense of acceleration, delay in communication among others. However there are reports indicating that the lack of visual information have the biggest influence. Therefore, it can be expected that replicating the world view by improving the presentation of the visual information will cause an increased efficiency. This work introduces two research examples: 1) Wide Visual Field Cilinder Screen, 2) Replication of Motion Stereostopic. Key idea 1): A monitor wide enough to replicate the size of objects and the actual field size as in the actual environment. Also, the monitor should be enough far away (1 ~ 1.5m) to avoid tiredness and undesired stereoscopic effects, and should be portable. Head mount display was not considered because users get tired. Key idea 2): The sense of motion parallax is twice the sense of binocular parallax (disparity). Then, a system that replicates the motion stereoscopic (i.e., the perception of three-dimensionality based on the visual change caused by own movement or target object movement) could increase task efficiency. Therefore, it is needed a special structure to correct video depending on perspective movement. However, the delay between viewer motion and corrected video display should be small to avoid not only innacuracy but also feeling of dizziness. The solution proposed here did not telecontrol a remote camera system due to the high delay and that the maintenance of a remote camera system is unpractical. Here the data is acquired by the distance sensor and cameras and sent to a PC. Then, a video is generated for a required perspective by 3DCG of the data. The system consists of a a sensor component (camera, distance sensor, posture sensor) and a display component (motion tracker, 3DCG PC, display). The findings: An experiment with a system scaled to 1/12 achieved 66ms of delay between user position change and video change. </td>
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
    <td>Description: A teleoperation strategy that decouples the operator's and the robot's spaces in the statistical representation is proposed (Namely, mixed teleoperation). This approach intends to replace the conventional use of video streams with a minimal exchange of activation weights as communication overhead. The problems: The variability of the robot operating environment. Communication bandwidth in long range teleoperation (e.g., space, deepsea) imposes a hard constraint on the efficiency of the system. Assumption: Most variability comes from the change of the pose of the manipulators and the pose of the items to be manipulated. Hypothesis: We use a task-parametrized Hidden semi-Markov model (TP-HSMM) to learn task representations (why? because task-parametrized mixture model encoding is flexible and HSMM captures motion duration and generate novel trajectories), and generate motions by sampling in combination with linear quadratic tracking (LQT). Previous models in Robotics: DMPs (Ijspeert, 2013. Palomeras, 2016). Extended DMP (Gams+, 2014. Ude+, 2014. Pastor+, 2011). GMM+GMR (Calinon+, 2012. Calinon, 2016). TP-GMM (Zeestraten+, 2017). HMM + GMR to improve HMMs poor state duration modeling (Lee & Ott, 2010. Lee+, 2010. Chan+, 2013). HMM + motion planner (Bowen & Alterovitz, 2014). HMM + HMM-space-distance-based clustering (Kulic+, 2008). Previous models in speech synthesis: HSMM (Yu & Kobayashi, 2006). HSMM in robotics models the state transition and duration (Calinon+, 2011. Tanwani & Calinon, 2016. Havoutis+, 2016. Havoutis & Calinon, 2016, 2017) . The result: The users employing local feedback required less time to achieve the task and their movements were smoother than the users getting remote feedback. The system could predict the task and generate motions from intermediate states. </td>
    </tr>
    <tr>
    <td>Lawrence R. Rabiner. A tutorial on Hidden Markov Models and selected applications in speech recognition, 1989</td>
    <td>●</td>
    <td></td>
    <td></td>
    <td></td>
    <td>#HMM #SpeechRecognition #ViterbiSearch</td>
    <td>● Introduction.<br>● Discrete Markov Processes<br>Extension to Hidden Markov Models<br>Elements of an HMM<br>The three basic problems of HMMs<br>● Solutions to the basic problems of HMMs<br>● Types of HMMs<br>Continuous observation densities in HMMs<br>Autoregressive HMMs<br>Variants on HMM structures-Null transitions and tied states<br>Inclusion of explicit state duration density in HMMs<br>Optimization criterion - ML, MMI, MDI<br>Comparison of HMMs<br>● Implementation issues for HMMs<br>Scaling<br>Multiple observation sequences<br>Initial estimates of HMM parameters<br>Effects of insufficient training data<br>Choice of model<br>● Implementation of Speech recognizers using HMMs.<br> ● Connected word recognition using HMMs. <br>● HMMs for large vocabulary speech recognition. </td>
    </tr>
    
  </tbody>
</table>

