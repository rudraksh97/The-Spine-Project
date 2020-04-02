## Spinal Cord Segmentation and Classification
1. [U-net](https://arxiv.org/abs/1505.04597) based CNN for generating binary segmentation masks for different parts in the spinal cord.
2. Dual Input CNN was built to classify between Damaged and Normal Spinal cords.

## Training Data
The dataset consisted of radiological images, X rays, from over 1000 thousand patients who
visited some medical centre seeking for their treatment. The X-ray images of the patients
highlighted the thoracic and lumbar regions of the vertebral column. For each
patient in the dataset, two X-Ray images highlighting two different views namely AP
and Lateral were available. So total 2000 X-ray images, equally divided among the two views were available.

## Data preprocessing and Dataset generation

```
The Spine Project/
├── generate_patches.ipynb
├── README.md
├── research_model.ipynb
├── run_tests.ipynb
```

## Model

## Tests and Vessel Removal

## Some snippets
