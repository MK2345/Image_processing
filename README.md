## Testing some image enhancement techniques

This repository is a work in progress and will continue to be expanded and enhanced. It is primarily
intended for practice purposes.

### Color correction
Adjustment of color balance, saturation and hue to achieve natural or desired colors.

<img src="images/dog_color_corrected.png">


### Rectification
Correction of geometric distortions that can be caused by camera lenses or perspective.

<img src="images/dog_rect.png">


### Deconvolution
Mathematical technique for sharpening images by reversing the blur function

<img src="images/doc_deconv.png">

### Super-Resolution
Techniques for increasing the image resolution beyond the original recording resolution.

<img src="images/dog_super_resolution.png">


### Image segmentation
Separation of foreground and background or objects in the image for further processing steps

<img src="images/dog_watersheed.png">


### Histogram equalization

<img src="images/histo_equ.png">



### Global histogram equalization
This is the classic method in which the histogram of the entire image is evenly distributed. It improves the global contrast, but can lead to excessive contrast enhancement in some cases.

<img src="images/global_hist_equ.png">

### Adaptive Histogram Equalization (AHE):
This method divides the image into smaller areas (tiles) and applies the histogram equalization to each tile separately. This results in better local contrast enhancement, especially for images with different lighting conditions.

<img src="images/adap_hist_equ.png">



### Contrast Limited Adaptive Histogram Equalization (CLAHE):
An enhancement of AHE that introduces a limit on contrast to reduce over-enhancement and noise amplification

<img src="images/clahe.png">


### Histogram stretching:
This technique stretches the histogram over the entire available gray value range. A certain percentage of the darkest and lightest pixels are often mapped to the extreme values.

<img src="images/hist_stretching.png">



### Histogram shrinking:
This transforms the gray values into a narrower range of values. This can be useful to emphasize certain areas of the image.

<img src="images/hist_shrinking.png">



### Piecewise linear histogram transformation:
With this method, different sections of the histogram can be spread or compressed to different degrees.

<img src="images/piecewise_hist_transform.png">


### Histogram limitation:
Here, gray values outside a certain range are mapped to black or white, followed by contrast enhancement in the remaining range.

<img src="images/hist_limit.png">
