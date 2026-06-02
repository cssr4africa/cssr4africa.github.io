# Software

Software developed by the CSSR4Africa consortium for the Pepper robot can be accessed by cloning the [CSSR4Africa repository on GitHub](https://github.com/cssr4africa/cssr4africa).

Some modules used machine learning. These models are available on   [CSSR4Africa repository on HuggingFace](https://huggingface.co/cssr4africa/cssr4africa_models/tree/main).

Some modules have very large unit test data sets. These data sets are also available on   [CSSR4Africa repository on HuggingFace](https://huggingface.co/cssr4africa/cssr4africa_unit_tests_data_files/tree/main).

Instructions on how to install the software can be found in [Deliverable D3.3](https://cssr4africa.github.io/deliverables/CSSR4Africa_Deliverable_D3.3.pdf).  

 In addition to Pepper sensor and actuator tests, demonstrating how to access sensor data and control actuators on the robot, the following software modules are available.

- Attention Subsystem
- Animate Behaviour Subsystem
- Environment Map Generation
- Face & Mutual Gaze Detection and Localization
- Gesture Execution
- Person Detection and Localization
- Sound Detection and Localization
- Speech Event

These modules are documented in the associated [deliverables](https://cssr4africa.github.io/deliverables).

More modules will be added as the integration process proceeds.

---

## Pepper4DEC

The CSSR4Africa software has been forked and re-implemented in ROS2 (Humble) to give autonomous tours of the Digital Experience Centre (DEC) of the Upanzi Network at Carnegie Mellon University Africa. The Pepper4DEC software repository is planned to be made publicly available.

In addition to porting all existing CSSR4Africa modules from ROS1 to ROS2, the Pepper4DEC fork provides the following additional functionality:

- A BehaviorTree.CPP v4 **Behavior Controller** that orchestrates the full DEC tour, managing transitions between tour stops, visitor interactions, and recovery behaviours
- A **RAG-based Conversation Manager** that enables context-aware natural language interaction with visitors at each DEC booth
- **SLAM-based autonomous navigation** using Nav2, allowing the robot to navigate independently between tour stops
- **VAD-aware speech recognition** with an action-server interface, replacing the ROS service interface used in CSSR4Africa to better support long-running speech interactions
- An updated **overt attention controller** with saliency-driven scanning that prioritises detected faces

It is planned to merge the DEC branch with the master CSSR4Africa branch at some point, if time allows, thereby making the ROS2 migration and additional functionality available to the wider CSSR4Africa project. This intent is reflected in the CSSR4Africa work plan and deliverables.