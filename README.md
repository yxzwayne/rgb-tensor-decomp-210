# RGB Image Compression using Tensor Decomposition Methods

Project Member: Dylan Stockard, Wayne Zhang, Yucheng Zhou


## Tucker Decomposition

The notebook for Tucker decomposition experiment is called `tucker.ipynb` at the base directory of this repo. 

You may need to check if the first two `! pip install` run successfully. Once the `pillow` (PIL) and `tensorly` packages are installed, the notebook should be able to Run All with no further change needed.

This notebook contains our explanation of the Higher-Order Orthogonal Iteration method's time complexity.


## State-of-the-Art: Discrete Cosine Transform

For the SOTA experiment, run `dsc210_final_SOTA_Tuckers.ipynb` at the base directory.
If `pillow` (PIL) package is installed through pip, the notebook should be able to Run All out of the box. Otherwise, please install the `pillow` package first. 

<!-- There are two paths you need to change in the notebook:

- PATH is the path to a large image, which is `data/large_image.jpg`
- PATH2 is the path to a smaller image, which we used `data/stl.jpg`

Once these are specified you can run all and the file should have no errors. -->