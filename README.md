# Video-Compress-Redesign
## Link
- [Jbox Papers](https://jbox.sjtu.edu.cn/link/view/7c8a2b91931d49ca8bd9facdd1b464d4)
- [Overview on Video Analytics -- DKT](https://kuntaidu.github.io/2020/07/23/Video-analytics-overview.html)

## Related Paper
- [Sigcomm'20 (DDS)] Server-Driven Video Streaming for Deep Learning Inference

### DDS-related

|  Index | Category | assessed | Title     | Comment|
| ---- | ---- | ---- | ---- | ---- |
| 80 ["Vigil"] | camera-side/selected-region/cheap-vision | 9.22F    | The Design and Implementation of a Wireless Video Surveillance System | cheap object detector |
| 30 ["Glimpse"] | camera-side/selected-frame/partial-server | 9.15W | Glimpse: Continuous, Real-Time Object Recognition on Mobile Devices | inter-frame pixel changes |
| 48 | camera-side/selected-frame/cheap-vision |                 | NoScope: Optimizing Neural Network Queries over Video at Scale |  |
| 54 ["EAAR"] | camera-side/selected-region/cheap-vision/partial-server/RPN/QoE | 9.22W | Edge Assisted Real-time Object Detection for Mobile Augmented Reality |  |
| 76 ["CloudSeg"] | analytics-oriented-video-encoding | 9.29W | Bridging the Edge-Cloud Barrier for Real-time Advanced Vision Analytics | same author(J. Jiang) |
| 78 ["AWStream"] | video-encoding | 9.29F | AWStream: AdaptiveWide-Area Streaming Analytics |  |
| 31 ["Adascale"] | cheap-vision |                 | ADASCALE: TOWARDS REAL-TIME VIDEO OBJECT DETECTION USING ADAPTIVE SCALING |  |
| 32 | cheap-vision |                 | Neural Networks Meet Physical Networks: Distributed Inference Between Edge Devices and the Cloud |  |

*Camera-side vision processing or hardware support*


### Super Resolution
#### Generic image/video SR

| Index   | Category                | Assessed | Title                                                        | Comment                                                      |
| ------- | ----------------------- | -------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 1 "SAN" | CVPR'19, Image SR, attention model | 11.3W    | Second-order Attention Network for Single Image Super-Resolution (WebRTC) | code not complete, Memory Exceed |

#### SR + Machine Task


| Index | Assessed  | Category  | Machine Task                       | Title                                                        | Comment    |
| ----- | --------- | --------- | ---------------------------------- | ------------------------------------------------------------ | ---------- |
| 1 "TDSR"  | Week12    | SR+OD     | Object-detection (preliminary)     | Task-Driven Super Resolution: Object Detection in Low-resolution Images | cited(41)  |
| 2 "DPSR"  | Week12/13 | Image     | Object-detection (preliminary)     | [CVPR'19] The Effects of Super-Resolution on Object Detection Performance in Satellite Imagery | cited(26)  |
| 3 "OD2"   | Week12    | Image     | Pedestrian-detection (preliminary) | [IEEE trans(19)] JCS-Net: Joint Classification and Super-Resolution Network for Small-Scale Pedestrian Detection in Surveillance Images | weak       |
| 4 "OD3"   | Week12/13 | Video     | Action-recognition                 | [ICCV'19] Two-Stream Action Recognition-Oriented Video Super-Resolution | two-stream |
| 5 "OD4"   | TODO      | Image     | Object-detection (preliminary?)    | [ICCV'19] Better to Follow, Follow to Be Better: Towards Precise Supervision of Feature Super-Resolution for Small Object Detection | cited(16)  |
| 6   | TODO      | Benchmark | Visual-recognition                 | [WACV'18] UG2: A video benchmark for assessing the impact of image restoration and enhancement on automatic visual recognition |            |

\* Preliminary: analysis of SR without targeting on the (specific) task
