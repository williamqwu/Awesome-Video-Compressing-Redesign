# Video-Compressing-Redesign
*A collection of interesting papers regarding video analytics.*

- [\#Core Paper](#Core)
- [\#Video Analytic Related](#Video\ Analytic)
- [\#Super Resolution Related](#Super\ Resolution)

## Link
- [Papers collection (Jbox)](https://jbox.sjtu.edu.cn/link/view/7c8a2b91931d49ca8bd9facdd1b464d4)

## Related Paper
### Core
- [Sigcomm'20 (DDS)] Server-Driven Video Streaming for Deep Learning Inference
- [HotCloud'18] Reinventing Video Streaming for Distributed Vision Analytics
- [Sigcomm'20] Interpreting Deep Learning-Based Networking Systems
- [Sigcomm'20 (LiveNAS)] Neural-Enhanced Live Streaming: Improving Live Video Ingest via Online Learning

### Video Analytic
#### Vision Processing / Hardware Support
|  Index | Category | Assessment | Title     | Comment|
| ------ | -------- | ---------- | --------- | ------ |
| DDS-80/MobiCom'15 (Vigil) | camera-side/selected-region/cheap-vision | 9.22/F/none    | The Design and Implementation of a Wireless Video Surveillance System | cheap object detector |
| DDS-30/SenSys'15 (Glimpse) | camera-side/selected-frame/partial-server | 9.15/W/none | Glimpse: Continuous, Real-Time Object Recognition on Mobile Devices | inter-frame pixel changes |
| DDS-48/ (NoScope) | camera-side/selected-frame/cheap-vision | Pending | NoScope: Optimizing Neural Network Queries over Video at Scale |  |
| DDS-54/MobiCom'19 (EAAR) | camera-side/selected-region/cheap-vision/partial-server/RPN/QoE | 9.22/W/none | Edge Assisted Real-time Object Detection for Mobile Augmented Reality |  |
| DDS-31/SysML'19 (Adascale) | cheap-vision |  Pending  | ADASCALE: TOWARDS REAL-TIME VIDEO OBJECT DETECTION USING ADAPTIVE SCALING |  |
| DDS-32/HotNets'18 | cheap-vision |  Pending  | Neural Networks Meet Physical Networks: Distributed Inference Between Edge Devices and the Cloud |  |
| DDS-71/CVPR'17 (WEG) | Cascade | \#2/W/ppt | Fast Video Classification via Adaptive Cascading of Deep Models | short-term class skew reduces latency |
| DDS-79/NSDI'17 | - | \#3/W/ppt | Live Video Analytics at Scale with Approximation and Delay-Tolerance | |
| DDS-45/SigComm'18 (Chameleon) | pipeline configuration | \#4/W/ppt | Chameleon: Scalable Adaptation of Video Analytics | A video analytic controller involving multi-camera collaboration | |
| LiveNAS-38/MMSys'16 (WebRTC) | | Pending | Analysis and Design of the Google Congestion Control for Web Real-Time Communication (WebRTC) | |
| DDS-x/InfoCom'18 (DeepDecision) | | \#4/W/ppt | DeepDecision: A Mobile Deep Learning Framework for Edge Video Analytics | |

#### Video Encoding
|  Index | Category | Assessment | Title     | Comment|
| ------ | -------- | ---------- | --------- | ------ |
| DDS-76/HotCloud'18 (CloudSeg) | analytics-oriented-video-encoding | 9.29/W/none | Bridging the Edge-Cloud Barrier for Real-time Advanced Vision Analytics | same author; re-evaluation needed | |
| DDS-78/SigComm'18 (AWStream) | video-encoding | 9.29/F/none | AWStream: AdaptiveWide-Area Streaming Analytics | re-evaluation needed | |
| 1/     | -        | \#3/F/ppt  | Video Coding for Machines: A Paradigm of Collaborative Compression and Intelligent Analytics | re-evaluation needed |

### Super Resolution
#### Generic Image/Video SR
| Index   | Category                | Assessment | Title                                                        | Comment                                                      |
| ------- | ----------------------- | -------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 1/CVPR'19 (SAN) | Image SR, attention model | 11.3/W/none  | Second-order Attention Network for Single Image Super-Resolution | code not complete |

#### SR + Machine Task
| Index | Assessment  | Category  | Machine Task                       | Title                                                        | Comment    |
| ----- | --------- | --------- | ---------------------------------- | ------------------------------------------------------------ | ---------- |
| 1/ (TDSR)  | \#1/?/ppt    | SR+OD     | Object-detection (preliminary)     | Task-Driven Super Resolution: Object Detection in Low-resolution Images | cited(41)  |
| 2/CVPR'19 (DPSR) | \#2/?/ppt | Image     | Object-detection (preliminary)     | The Effects of Super-Resolution on Object Detection Performance in Satellite Imagery | cited(26)  |
| 3/journal (OD2)   | \#1/?/ppt    | Image     | Pedestrian-detection (preliminary) | JCS-Net: Joint Classification and Super-Resolution Network for Small-Scale Pedestrian Detection in Surveillance Images | weak, not quite helpful   |
| 4/ICCV'19 (OD3)   | \#2/?/ppt | Video     | Action-recognition                 | Two-Stream Action Recognition-Oriented Video Super-Resolution | two-stream |
| 5/ICCV'19 (OD4)   | Pending    | Image     | Object-detection (preliminary?)    | Better to Follow, Follow to Be Better: Towards Precise Supervision of Feature Super-Resolution for Small Object Detection | cited(16)  |
| 6/WACV'18   | Pending      | Benchmark | Visual-recognition                 | UG2: A video benchmark for assessing the impact of image restoration and enhancement on automatic visual recognition |            |
| 7/          | \#2/F/ppt  | Image | Object-detection (preliminary?) | Residual Super-Resolution Single Shot Network for Low-Resolution Object Detection | |

\* Preliminary: analysis of SR without targeting on the (specific) task
