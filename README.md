# RGB Image Compression using Tensor Decomposition Methods

### Course: DSC 210 - Numerical Linear Algebra for Data Science

### Instructor: Dr. Tsui-wei Weng

### Project Member: Dylan Stockard, Wayne Zhang, Yucheng Zhou

## Instructions

1. Ensure that the following libraries are installed in your Python 3 environment:
  - pillow
  - tensorly
  - matplotlib
2. Open `tucker.ipynb` at the base directory of this repo and run all the cells;
3. Open `dsc210_final_SOTA_Tuckers.ipynb` at the base directory and run all the cells.

## Results

### Tucker Decomposition

The notebook contains our explanation of the Higher-Order Orthogonal Iteration method's time complexity.


*Scratch Tucker Decomposition results*

<img width="297" alt="scratch" src="https://user-images.githubusercontent.com/39586897/206063993-88cff0dc-fa6b-4945-9c21-34010e06fc86.png">

*Tensorly's Tucker Decomposition results*

Note that the results of the plot are with resepct to rank of decomposition.

![geisel](https://user-images.githubusercontent.com/39586897/206064372-309d3e49-e7ed-424b-9b0d-a7de094268e8.png)
![placidusax](https://user-images.githubusercontent.com/39586897/206064374-95b96707-ed5a-476f-b05d-f13b55a6a711.png)
![niet](https://user-images.githubusercontent.com/39586897/206064373-100ee985-9d24-44e5-8172-ec1874938fcc.png)
![sat](https://user-images.githubusercontent.com/39586897/206064376-251ee96f-a012-4411-af0a-1363ec69264b.png)
![chicken](https://user-images.githubusercontent.com/39586897/206064371-fac50c51-2da0-4dd0-a17e-d94512e05173.png)


### DCT Method

Using DCT on large image:

<img width="848" alt="dct-large" src="https://user-images.githubusercontent.com/39586897/206064725-3e2d8c62-91c5-4d0a-add4-5c6a0720066e.png">

Using DCT on smaller images with different block sizes:

<img width="395" alt="dct_smaller" src="https://user-images.githubusercontent.com/39586897/206064833-215b9ebd-4fc8-404a-bfd7-90513c435233.png">

Metrics:

<img width="386" alt="dct_metric" src="https://user-images.githubusercontent.com/39586897/206064941-df884b89-fd02-4da8-8ba2-092dfb997b36.png">



