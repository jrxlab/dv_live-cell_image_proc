
------------------- Image processing for Cell death analysis -------------------

This pipeline allows the cell death time analysis, using multiple
image processing methods.

The pipeline is splited into multiple scripts.

- run_parameters: input file. It gives the user the possibility to modify the input parameters.

- run_pipeline: this is the file to execute to start the analysis.

- task and types directories contain the segmentation and the tracking scripts.

- analysis directory contains the death time analysis scripts.


Dependencies :

- Scikit-image
- OpenCV
- imageio
- Matplotlib
- networks
- Numpy
- Scipy
