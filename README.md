## Spinal Cord Segmentation and Classification
1. [U-net](https://arxiv.org/abs/1505.04597) based CNN for generating binary segmentation masks for different parts in the Spinal cord.
2. Dual Input CNN to classify between Damaged and Normal Spinal cords.

## Dataset
The dataset consisted of radiological images, X rays, from over 1000 thousand patients who
visited some medical centre seeking for their treatment. The X-ray images of the patients
highlighted the thoracic and lumbar regions of the vertebral column. For each
patient in the dataset, two X-Ray images highlighting two different views namely AP
and Lateral were available. So total 2000 X-ray images were there, equally divided among the two views.

## Images
This images are for a normal Spinal cord
### AP and Lateral Views
<img src="https://github.com/rudraksh97/The-Spine-Project/blob/master/Examples/Github/APLAT.jpg?raw=True">

### AP Binary Masks
<img src="https://github.com/rudraksh97/The-Spine-Project/blob/master/Examples/Github/AP.jpg?raw=True">

### LAT Binary Masks
<img src="https://github.com/rudraksh97/The-Spine-Project/blob/master/Examples/Github/LAT.jpg?raw=True">

```
The-Spine-Project/
├── Examples
│   ├── Normal
│   └── Damaged
|   └── Github
├── generate_patches.ipynb
├── README.md
├── research_model.ipynb
├── run_tests.ipynb
```

## Model

## Tests
