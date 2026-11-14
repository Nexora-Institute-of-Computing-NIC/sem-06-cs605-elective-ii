# CS605 — Elective II: Computer Vision — PLAN

**Semester:** 6 · **Credits:** 3 · **Level:** Advanced
**Theory:** 45 hrs · **Lab:** 15 hrs · **Tools:** Python, OpenCV, PyTorch, torchvision, matplotlib

## Syllabus

### Unit 1 — Image Foundations (9 lectures)
1. What computer vision is — tasks and applications
2. Digital images — pixels, channels, colour spaces
3. Image representation — tensors, shapes, dtypes
4. Point operations — brightness, contrast, gamma
5. Filters — convolution, Gaussian blur, sharpening
6. Edge detection — Sobel, Canny
7. Histograms and equalisation
8. Geometric transforms — scaling, rotation, affine
9. Interpolation — nearest, bilinear, bicubic

### Unit 2 — Features and Classical Vision (9 lectures)
1. Corner detection — Harris and Shi-Tomasi
2. Feature descriptors — SIFT, SURF, ORB
3. Feature matching and homography
4. Image stitching and panorama construction
5. Optical flow — Lucas-Kanade
6. Motion tracking
7. Stereo vision and depth from disparity
8. Camera calibration
9. Classical object detection — HOG + SVM

### Unit 3 — Convolutional Neural Networks for Vision (9 lectures)
1. CNN building blocks — conv, pool, batch norm
2. Classic architectures — LeNet, AlexNet, VGG
3. ResNet and skip connections
4. Efficient models — MobileNet, EfficientNet
5. Transfer learning for vision
6. Data augmentation for vision
7. Fine-tuning pre-trained models
8. Training strategies — augmentation, schedules, mixup
9. Common failure modes — distribution shift, spurious correlations

### Unit 4 — Detection, Segmentation, and Beyond (9 lectures)
1. Object detection — two-stage (R-CNN, Faster R-CNN)
2. Object detection — one-stage (YOLO, SSD)
3. Evaluation — IoU, mAP, precision-recall
4. Semantic segmentation — FCN, U-Net
5. Instance segmentation — Mask R-CNN
6. Pose estimation — keypoints (overview)
7. Vision Transformers (ViT)
8. Self-supervised vision — SimCLR, DINO (overview)
9. Multimodal models — CLIP and vision-language

### Unit 5 — Applied Vision and Ethics (9 lectures)
1. Face recognition — embeddings, verification, identification
2. OCR — text detection and recognition
3. Medical imaging — classification and segmentation
4. Autonomous driving — perception stack
5. Video understanding — action recognition
6. Deployment — optimising models for edge
7. Model interpretability — saliency, Grad-CAM
8. Bias and fairness — datasets, evaluation
9. Privacy and surveillance — the ethical questions

## Practical Labs (15)

1. Set up OpenCV and PyTorch; load and display an image
2. Implement convolution from scratch and compare with OpenCV
3. Edge detection — Sobel vs Canny on the same image
4. Histogram equalisation for contrast enhancement
5. Feature matching with ORB — find one image inside another
6. Build a panorama from two overlapping photos
7. Optical flow — visualise motion in a video
8. Fine-tune ResNet for a custom image classification dataset
9. Data augmentation pipeline — measure accuracy gain
10. Train YOLO on a small custom dataset (5–10 classes)
11. Evaluate detection with IoU and mAP
12. Fine-tune U-Net for semantic segmentation on a small dataset
13. Use CLIP for zero-shot image classification
14. Grad-CAM visualisation — interpret a CNN's decision
15. Final project — an end-to-end vision application with report

## Assignments

1. Image processing pipeline writeup
2. Classical features — implement and analyse SIFT/ORB on real images
3. CNN training report — ResNet fine-tune on a custom dataset
4. Detection / segmentation report — results, failures, analysis
5. Final project — a complete vision application with ethical considerations
