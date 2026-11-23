# DCIT 407 – Motion Detection for Surveillance

## Project Overview

This project focuses on developing an image-processing-based motion detection system for surveillance and traffic monitoring.

The system will process surveillance video frames to identify moving objects, separate foreground regions from stationary backgrounds, and analyze detected motion using fundamental digital image processing techniques.

The project will be implemented using Python, NumPy, OpenCV and Matplotlib.

## Project Objectives

The main objectives are to:

1. Understand and implement fundamental image processing techniques for surveillance applications.
2. Apply image normalization and smoothing to improve frame quality.
3. Investigate ridge enhancement and thinning as part of the assigned image-processing techniques.
4. Extract moving regions from consecutive surveillance frames.
5. Apply thresholding and binarization to generate motion masks.
6. Identify moving objects and perform object counting where feasible.
7. Evaluate detection performance using ground-truth annotations.
8. Compare custom NumPy implementations with equivalent OpenCV functions.

## Project Scope

The project will focus on surveillance and traffic scenarios, particularly moving vehicles and pedestrians.

The implementation will explore:

- Image preprocessing
- Frame differencing and background subtraction
- Motion segmentation
- Binary mask generation
- Morphological processing
- Moving object detection
- Performance evaluation

## Technologies

| Technology | Purpose |
|---|---|
| Python | Primary programming language |
| NumPy | First-principles image processing |
| OpenCV | Image and video processing |
| Matplotlib | Image visualization |
| Pandas | Results and metrics analysis |
| SciPy / scikit-image | Supporting image processing and evaluation |

## Dataset

The project will use publicly available surveillance data from the CDnet 2014 dataset.

Dataset source: https://www.changedetection.net/

Selected video sequences and corresponding ground-truth annotations will be used for testing and evaluation.

## System Architecture

The proposed processing pipeline consists of:

1. Video frame acquisition
2. Grayscale conversion
3. Image normalization
4. Image smoothing
5. Motion extraction
6. Binarization and segmentation
7. Morphological processing and thinning
8. Moving object detection
9. Performance evaluation

## Evaluation Metrics

The system will be evaluated using appropriate quantitative metrics, including:

- Intersection over Union (IoU)
- Precision
- Recall
- F1-score
- Processing time

At least two methods or parameter configurations will be compared.

## Project Structure

```text
src/           - Main implementation
notebooks/     - Experiments and analysis
datasets/      - Dataset documentation
outputs/       - Generated results
docs/          - Project documentation
tests/         - Algorithm tests
presentation/  - Presentation materials
```

## Development Approach

The core image-processing algorithms will be implemented using NumPy or plain Python loops and compared with their equivalent OpenCV functions.

Deep learning and pretrained models will not form the core of this project.

## Project Status

**Current Phase:** Repository setup and system architecture.

## Contributors

Group members will be listed here.

Each member is expected to contribute through their individual GitHub account.

## License and References

Dataset usage will follow the licensing and terms provided by the original dataset source.

Academic papers, documentation and other references used during the project will be acknowledged in the final report.