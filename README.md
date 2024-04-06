# Semantic Segmentation of High-Resolution Aerial Images

This project is conducted by **Maher Thakkar** and **Jaineet Shah**, under the guidance of **Anitha Modi**, Assistant Professor at the Department of Computer Science and Engineering, Institute of Technology, Nirma University, Ahmedabad.

## Introduction

Semantic image segmentation is a cornerstone in the field of computer vision, aiming at understanding images at the pixel level. Our project delves into building segmentation from high-resolution aerial images, facilitated by the advancements in Convolutional Neural Networks (CNN). We tackle the challenge of processing very high-quality images by employing techniques that adapt them to be processed on standard-spec computers efficiently.

## Objectives

The primary goal is to evaluate different models for the classification of aerial images within the Aerial Semantic Segmentation Drone Dataset collected by Graz University of Technology, and to identify the most efficient model for high-resolution image segmentation.

## Literature Review

Our research was inspired by significant strides in neural networks, particularly CNNs, which have shown exceptional performance in visual learning tasks, including semantic segmentation. We explored various architectural models and applied semantic image segmentation across different domains, such as medical imaging and intelligent transportation systems.

## Methodology

### Dataset

We utilized the Aerial Semantic Segmentation Drone Dataset, which focuses on the semantic understanding of urban scenes to enhance the safety of autonomous drone flight and landing procedures. This dataset includes over 20 houses captured from a nadir view, with images acquired at an altitude of 5 to 30 meters above ground, having a resolution of 6000x4000 pixels.

### Models Developed

1. **VGG-16 Encoder and FCN8 Decoder**:
    - Architecture: Pre-trained VGG-16, FCN-8 decoder.
    - Performance: Analyzed based on train, validation, and test scores including accuracy, IOU, and Dice score.

2. **U-Net**:
    - Architecture: Symmetric design with contracting and expansive paths.
    - Performance: Evaluated through loss, accuracy, IOU, and f1 scores.

3. **SegNet**:
    - Architecture: Encoder-decoder architecture with a focus on efficient memory usage.
    - Performance: Assessed using the same metrics as above.

## Results

Our evaluation indicated that the **VGG-16 Encoder & FCN-8 Decoder** model outperformed others in terms of accuracy and IOU score, showcasing its efficiency in segmenting high-resolution images.

## Conclusion

The comparative analysis of the three proposed models revealed that the VGG-16 Encoder & FCN-8 Decoder is the most suitable for segmenting high-resolution aerial images, providing a promising direction for future research in enhancing semantic segmentation accuracy.

## Acknowledgements

We extend our gratitude to Prof. Anitha Modi for her invaluable guidance, and Prof. Tejal Upadhyay for insightful feedback on implementation and presentation aspects. Our appreciation also goes to the Institute of Technology, Nirma University, for providing the platform and resources to carry out this project.

## References

A comprehensive list of references is provided in our project report, highlighting seminal works in semantic segmentation, CNNs, and applications of image segmentation in various domains.

