When using this dataset, the paper adopted the following evaluation methods and metrics:
### Evaluation Method
Comparative Experiments: Performance of Enhance‑YOLOv8 is compared against the YOLOv8 baseline, YOLOv5, YOLOv11, and other mainstream detectors on the same test set.
Ablation Study: Core components (Enhance_AFCA, MANet_PD, WiseIoU) are added incrementally to validate the performance contribution of each module.
Robustness Analysis: Model performance is evaluated under typical agricultural‑scene challenges such as scale variation and target occlusion.
### Assessment Metrics
Standard object‑detection metrics are used, defined as follows:
Precision: Proportion of true positives (TP) among samples predicted as positive, measuring detection accuracy.
Recall: Proportion of actual positive samples correctly detected (TP), reflecting target coverage capability.
Average Precision (AP): Integrates precision across different recall levels, measuring single‑class detection performance.
mean Average Precision (mAP): Average of AP over all classes, serving as the core metric for overall model performance.
Parameters/GFLOPs: Quantify model complexity and computational efficiency.
