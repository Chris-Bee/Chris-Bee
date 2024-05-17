[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-0e76a8?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/christianbrommer) [![Twitter Badge](https://img.shields.io/badge/-Twitter-00acee?style=flat-square&logo=Twitter&logoColor=white)](https://twitter.com/chrbrommer) [![Google Scholar](https://img.shields.io/badge/Google%20Scholar-blue?style=flat-square&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?hl=en&user=Vxdg150AAAAJ)


## My Projects

### The MaRS Framework

MaRS (Modular and Robust Multi-Sensor Fusion) is a robot localization framework that was developed as a direct outcome of the research during my Ph.D. studies. The main C++ library, listed below, can be used to process sensor data in CSV files directly. MaRS also has a ROS1 wrapper that implements the C++ API and allows a real-time and closed-loop capable integration of MaRS for your vehicle.

- MaRS [C++ Library](https://github.com/aau-cns/mars_lib)
- MaRS [ROS1 Wrapper](https://github.com/aau-cns/mars_ros)
- MaRS [ROS2 Wrapper](https://github.com/aau-cns/mars_ros2) (Coming soon)

#### Projects and Research in Conjunction with the MaRS Framework

MaRS was used together with other projects such as:

- [PeET](https://github.com/aau-cns/poet): Pose Estimation Transformer for Single-View, Multi-Object 6D Pose Estimation soon.
- The AMADEE20 Mars analog mission
- The [CNS Flight-Stack](https://github.com/aau-cns/flight_stack) for UAV autonomy

### The INSANE Dataset Tools

The [AMADEE20](http://amadee20.oewf.org/) Mars analog mission led to the development of the AMAZE helicopter (Analog MArs Zone Exploration), which was designed with 18 sensors to create a sophisticated multi-sensor UAV dataset. We called this the INSANE dataset (Increased Number of Sensors for developing Advanced and Novel Estimators), which was published [open-access](https://journals.sagepub.com/doi/full/10.1177/02783649241227245) in the A+ International Journal of Robotics Research (IJRR).

A repository with additional tools for the generation of the dataset can be found here:
- [INSANE Dataset Tools](https://github.com/aau-cns/insane_dataset_tools)

### CNS Flight Stack

The development of the AMAZE helicopter, mentioned above, also led to the development of the full autonomy CNS Flight Stack. The main repository of the flight stack can be found here:
- [CNS Flight-Stack](https://github.com/aau-cns/flight_stack)