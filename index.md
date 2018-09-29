---
layout: default
---

<iframe width="854" height="480" src="https://www.youtube.com/embed/7vbmOWVxGPU?list=PLN52r1TJ02B6dvtcA9BSRkyvjQmsSwEeU" frameborder="0" allowfullscreen></iframe>

# [](#dataset)Dataset
## Training and Validation Data
* We created the Autonomy Hands and Faces dataset, consisting of 16,883 images, with human-annotated labels for 34,588 hands and 18,838 faces.
* In a semi-supervised manner, we used an initial model trained on the previous dataset
to label more data from third party publically availabe datasets, resulting in 50,365 frames, with 94,854
hand and 58,210 face labels.
```
http://autolab.cmpt.sfu.ca/files/datasets/hands-and-faces/autonomy_hands_and_faces.tar.gz

```
## Test Data
* Data from human-UAV interaction over 2.5, 5.0, 7.5, 10.0, and 20.0 meters. 
```
Test and benchmarking data will be publically available for download soon.
```

# Benchmark

* TBA

# Cite                                                                             
* If you use Autonomy hands and faces in your work please cite our paper!
```
@inproceedings{mohaimenian:iros2018,
  author =       {Sepehr {MohaimenianPour} and Richard Vaughan},
  title =        {Hands and Faces, Fast: Mono-Camera User Detection Robust Enough to Directly Control a UAV in Flight},
  howpublished = {Proceedings of the {IEEE/RSJ} International Conference on Intelligent Robots and Systems ({IROS}'18), Madrid, Spain},
  month =        {October},
  year =         {2018},
}
```
