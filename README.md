# Scikit-image
https://scikit-image.org/docs/stable/auto_examples/
## Data
- Datasets with 3 or more spatial dimensions
- Scientific images
- Specific images
- General-purpose images

## Operations on NumPy arrays
- Using simple NumPy operations for manipulating images
- Generate structuring elements
- Block views on images/arrays

## Manipulating exposure and color channels
- RGB to grayscale
- RGB to HSV
- Histogram matching
- Adapting gray-scale filters to RGB images
- Separate colors in immunohistochemical staining
- Filtering regional maxima
- Gamma and log contrast adjustment
- Histogram Equalization
- Tinting gray-scale images
- Local Histogram Equalization
- 3D adaptive histogram equalization

## Edges and lines
- Contour finding
- Convex Hull
- Canny edge detector
- Ridge operators
- Marching Cubes
- Active Contour Model
- Shapes
- Random Shapes
- Approximate and subdivide polygons
- Straight line Hough transform
- Circular and Elliptical Hough Transforms
- Skeletonize
- Edge operators

## Geometrical transformations and registration
- Swirl
- Build image pyramids
- Interpolation: Edge Modes
- Rescale, resize, and downscale
- Piecewise Affine Transformation
- Using geometric transformations
- Structural similarity index
- Types of homographies
- Fundamental matrix estimation
- Robust line model estimation using RANSAC
- Radon transform
- Robust matching using RANSAC

## Image registration
- Image Registration
- Masked Normalized Cross-Correlation
- Registration using optical flow
- Assemble images with simple image stitching
- Using Polar and Log-Polar Transformations for Registration

## Filtering and restoration
- Removing small objects in grayscale images with a top hat filter
- Hysteresis thresholding
- Image Deconvolution
- Using window functions with images
- Unsharp masking
- Mean filters
- Image Deconvolution
- Estimate strength of blur
- Entropy
- Calibrating Denoisers Using J-Invariance
- Inpainting
- Band-pass filtering by Difference of Gaussians
- Denoising a picture
- Shift-invariant wavelet denoising
- Phase Unwrapping
- Non-local means denoising for preserving textures
- Attribute operators
- Wavelet denoising
- Full tutorial on calibrating Denoisers Using J-Invariance

## Detection of features and objectsDense 
- Dense DAISY feature description
- Histogram of Oriented Gradients
- Template Matching
- Filling holes and finding peaks
- Corner detection
- CENSURE feature detector
- Multi-Block Local Binary Pattern for texture classification
- Haar-like feature descriptor
- Blob Detection
- ORB feature detector and binary descriptor
- Gabors / Primary Visual Cortex “Simple Cells” from an Image
- BRIEF binary descriptor
- SIFT feature detector and descriptor extractor
- GLCM Texture Features
- Shape Index
- Sliding window histogram
- Gabor filter banks for texture classification
- Local Binary Pattern for texture classification

## Segmentation of objects
- Region Boundary based RAGs
- RAG Thresholding
- Normalized Cut
- Find Regular Segments Using Compact Watershed
- Thresholding
- Drawing Region Adjacency Graphs (RAGs)
- Chan-Vese Segmentation
- Finding local maxima
- Niblack and Sauvola Thresholding
- Multi-Otsu Thresholding
- Expand segmentation labels without overlap
- Apply maskSLIC vs SLIC
- Random walker segmentation
- Watershed segmentation
- Label image regions
- Markers for watershed transform
- Comparison of segmentation and superpixel algorithms
- Find the intersection of two segmentations
- Region Adjacency Graphs
- Different perimeters
- RAG Merging
- Hierarchical Merging of Region Boundary RAGs
- Extrema
- Explore and visualize region properties with pandas
- Hausdorff Distance
- Measure region properties
- Trainable segmentation using local features and random forests
- Morphological Snakes
- Flood Fill
- Euler number
- Evaluating segmentation metrics
- Use rolling-ball algorithm for estimating background intensity

## Longer examples and demonstrations
- Face detection using a cascade classifier
- Interact with 3D images (of kidney tissue)
- Use pixel graphs to find an object’s geodesic center
- Visual image comparison
- Morphological Filtering
- Estimate anisotropy in a 3D microscopy image
- Comparing edge-based and region-based segmentation
- Segment human cells (in mitosis)
- Thresholding
- Measure fluorescence intensity at the nuclear envelope
- Face classification using Haar-like feature descriptor
- Explore 3D images (of cells)
- Rank filters

# Contour Detection using OpenCV
https://learnopencv.com/contour-detection-using-opencv-python-c/  
Using contour detection, we can detect the borders of objects, and localize them easily in an image. It is often the first step for many interesting applications, such as image-foreground extraction, simple-image segmentation, detection and recognition. 
