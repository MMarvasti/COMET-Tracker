# COMET: Context-aware iOu-guided network for sMall objEct Tracking
Tracking an unknown target captured from medium- or high-aerial view is challenging, especially in scenarios of small objects, large viewpoint change, drastic camera motion, and high density. This paper introduces a context-aware IoU-guided tracker that exploits an offline reference proposal generation strategy and a multitask two-stream network. The proposed strategy introduces an efficient sampling strategy to generalize the network on the target and its parts without imposing extra computational complexity during online tracking. It considerably helps the proposed tracker, COMET, to handle occlusion and view-point change, where only some parts of the target are visible. Also, the proposed network fully exploits small object information by effective components and a multitask loss function. 
Extensive experimental evaluations on broad range of tracking benchmarks (UAVDT, VisDrone-2019, Small-90, UAV-123, and OTB-2015) demonstrate the effectiveness of our approach for small object tracking.
