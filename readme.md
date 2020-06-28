## Reading List(Object Detection Related)

Here are my <b><a href="http://lovesnowbest.site">notes and thoughts</a></b> for papers.

### Anchor Free
1. CornerNet: Detecting Objects as Paired Keypoints(CornerNet) 👀
2. Bottom-up Object Detection by Grouping Extreme and Center Points(ExtremeNet)👀
3. Feature Selective Anchor-Free Module for Single-Shot Object Detection(FSAF)
4. FCOS: Fully Convolutional One-Stage Object Detection(FCOS)
5. Single-Shot Refinement Neural Network for Object Detection(RefineDet)👀
6. Revisiting Feature Alignment for One-stage Object Detection(AlignDet)
7. RepPoints: Point Set Representation for Object Detection(RepPoints、RPDet)
8. Bridging the Gap Between Anchor-based and Anchor-free Detection via Adaptive Training Sample Selection(ATSS)

### Rescoring for better mAP
1. Acquisition of Localization Confidence for Accurate Object Detection(IoUNet)
2. Mask Scoring RCNN(MS-RCNN)
3. Learning to Rank Proposals for Object Detection(NMS-LTR)

### Better Alignment
1. Cascade R-CNN: Delving into High Quality Object Detection(Cascade R-CNN)
2. Revisiting Feature Alignment for One-stage Object Detection(AlignDet)
3. Cascade RPN: Delving into High-Quality Region Proposal Network with Adaptive Convolution(Cascade RPN)
4. Shape-aware Feature Extraction for Instance Segmentation(Mask Refining R-CNN)
5. Scale-Aware Trident Networks for Object Detection(TridentNet, better anchor align for size?)
6. Region Proposal by Guided Anchoring(GA-RPN, deformable anchor)

### Knowledge Distillation for Object Detection
1. Distilling the knowledge in a Neural Network(start of KD)
2. Mimicking Very Efficient Network for Object Detection(ROI Teaching)
3. Learning Efficient Object Detection Models with Knowledge Distillatio(Hint + Reg + Cls distillation)
4. Distilling Object Detection with Fine-grained Feature Imitation(Hint with Anchor Mask)
5. Consistency-based Semi-supervised Learning for Object Detection(leverage unlabled data, consistency loss)

### Panoptic Segmentation
1. Panoptic Segmentation
2. Panoptic Feature Pyramid Networks
3. Fast Panoptic Segmentation Network👀
4. AdaptIS: Adaptive Instance Selection Network(AdaptIS)
5. SpatialFlow: Bridging All Tasks for Panoptic Segmentation(SpatialFlow)

### Label Assignment
1. Learning from Noisy Anchors for One-stage Object Detection
3. Bridging the Gap Between Anchor-based and Anchor-free Detection via Adaptive Training Sample Selection(ATSS)
4. Libra R-CNN: Towards Balanced Learning for Object Detection(Libra RCNN)
5. IoU-uniform R-CNN- Breaking Through the Limitations of RPN(IoU-Uniform RCNN, deeply water paper)

### NMS Improvement
1. Improving Object Detection With One Line of Code(SoftNMS)
2. Bounding Box Regression with Uncertainty for Accurate Object Detection(Ensemble of Bbox NMS)
3. Relation Networks for Object Detection👀
4. Learning Non-maximum Suppression👀
5. Acquisition of Localization Confidence for Accurate Object Detection(IoUNet, IoU-Guided NMS)
6. NMS by Representative Region: Towards Crowded Pedestrian Detection by Proposal Pairing
7. Detection in Crowded Scenes: One Proposal, Multiple Predictions


### Object Detection
1. RDSNet: A New Deep Architecture for Reciprocal Object Detection and Instance Segmentation(RDSNet)
2. Empirical Upper-bound in Object Detection and More
3. Is Sampling Heuristics Necessary in Training Deep Object Detectors?(Bias Initialization, train RetinaNet w/o focal loss)
4. Deformable Convolutional Networks(self learnt offset for convolution)
5. Side-Aware Boundary Localization for More Precise Object Detection(SABL, slices for localization)
6. Multiple Anchor Learning for Visual Object Detection(iteratively optimize N->1 anchors with MIL)

### Graph
1. DeepGCNs: Can GCNs Go as Deep as CNNs?

### Pedestrian Detection
1. Mask-Guided Attention Network for Occluded Pedestrian Detection
2. Detection in Crowded Scenes: One Proposal, Multiple Predictions
3. NMS by Representative Region: Towards Crowded Pedestrian Detection by Proposal Pairing

## To be read
CVPR2020
1. AugFPN: Improving Multi-scale Feature Learning for Object Detection
2. DR Loss: Improving Object Detection by Distributional Ranking
3. SpineNet: Learning Scale-Permuted Backbone for Recognition and Localization
4. D2Det: Towards High Quality Object Detection and Instance Segmentation
5. Overcoming Classifier Imbalance for Long-tail Object Detection with Balanced Group Softmax
6. Large-Scale Object Detection in the Wild from Imbalanced Multi-Labels
7. Seeing without Looking: Contextual Rescoring of Object Detections for AP Maximization
8. Learning a Unified Sample Weighting Network for Object Detection
9. BlendMask: Top-Down Meets Bottom-Up for Instance Segmentation
10. CenterMask : Real-Time Anchor-Free Instance Segmentation
11. Deep Snake for Real-Time Instance Segmentation
12. Offset Bin Classification Network for Accurate Object Detection




