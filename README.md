# PIAIC-AI-Q2

Course content for PIAIC AI Quarter 2

## Reference Books

> #### **Python for Data Analysis: Data Wrangling with Pandas, NumPy, and IPython**
>
> **Author**: Wes McKinney
>
> <hr style='border: none; border-top: dashed 2px'/>
>
> **Description**: Get complete instructions for manipulating, processing, cleaning, and crunching datasets in Python. Updated for Python 3.6, the second edition of this hands-on guide is packed with practical case studies that show you how to solve a broad set of data analysis problems effectively. You’ll learn the latest versions of pandas, NumPy, IPython, and Jupyter in the process.
>
> **_Written by Wes McKinney, the creator of the Python pandas project_**, this book is a practical, modern introduction to data science tools in Python. It’s ideal for analysts new to Python and for Python programmers new to data science and scientific computing. Data files and related material are available on GitHub.
>
> - Use the IPython shell and Jupyter notebook for exploratory computing
> - Learn basic and advanced features in NumPy (Numerical Python)
> - Get started with data analysis tools in the pandas library
> - Use flexible tools to load, clean, transform, merge, and reshape data
> - Create informative visualizations with matplotlib
> - Apply the pandas groupby facility to slice, dice, and summarize datasets
> - Analyze and manipulate regular and irregular time series data
> - Learn how to solve real-world data analysis problems with thorough, detailed examples

> #### **Learning Pandas: High performance data manipulation and analysis using Python**
>
> **Author**: Michael Heydt
>
> <hr style='border: none; border-top: dashed 2px'/>
>
> **Description**: You will learn how to use pandas to perform data analysis in Python. You will start with an overview of data analysis and iteratively progress from modeling data, to accessing data from remote sources, performing numeric and statistical analysis, through indexing and performing aggregate analysis, and finally to visualizing statistical data and applying pandas to finance.
>
> With the knowledge you gain from this book, you will quickly learn pandas and how it can empower you in the exciting world of data manipulation, analysis and science.
>
> What you will learn
>
> - Understand how data analysts and scientists think about of the processes of gathering and understanding data
> - Learn how pandas can be used to support the end-to-end process of data analysis
> - Use pandas Series and DataFrame objects to represent single and multivariate data
> - Slicing and dicing data with pandas, as well as combining, grouping, and aggregating data from multiple sources
> - How to access data from external sources such as files, databases, and web services
> - Represent and manipulate time-series data and the many of the intricacies involved with this type of data
> - How to visualize statistical information
> - How to use pandas to solve several common data

## Week 1

**Topics Covered**

- Intro to `Numpy`
- Benefits Contiguous Memory Allocation &amp; Vectorization
- `Numpy` Arrays
- Array Creation Functions
  - `np.array`
  - `np.asarray`
  - `np.arange`
  - `np.ones`, `np.ones_like`
  - `np.zeros`, `np.zeros_like`
  - `np.empty`, `np.empty_like`
  - `np.full`, `np.full_like`
  - `np.eye`, `np.Identity`
- `ndarray` (n-dimensional array) type and explicit casting/conversion
- Arithematic with `Numpy`
- Indexing and Slicing `1-D` array
- `2-D` arrays
- Indexing `2-D` arrays
- Indexing vs Slicing in higher dimensional arrays

**Assignment**

Download the assignment notebook from [here](<https://github.com/nasir-hussain1/piaic_q2_Assignments/blob/master/Assignment%231(Numpy%20Fundamentals).ipynb>)

Submit the assignment [here](https://forms.gle/GFnM5iS9Qc1G168R7) using google forms

## Week 2

**Topics Covered**

- Stacking
  - Horizontal Stacking: `np.hstack`
  - Vertical Stacking: `np.vstack`
  - Dept-Wise Stacking: `np.dstack`
- Creating `numpy` arrays using `tuples`
- Splitting Arrays
  - Horizontal Splitting: `np.hsplit`
  - Vertical Splitting: `np.vsplit`
  - Depth splitting: `np.dsplit`
- Numerical Methods of `numpy` arrays
  - `axis` values of `numpy.ndarray` and thier usage
  - `ndarray.max`
  - `ndarray.min`
  - `ndarray.argmin`
  - `ndarray.argmax`
- Statistical Methods of `numpy` arrays
  - `ndarray.mean`
  - `ndarray.std`
  - `ndarray.average`
  - `ndarray.prod`
  - `ndarray.sum`
  - `ndarray.cumprod`
  - `ndarray.cumsum`
- Applying Logical operators on `numpy` arrays
- Fancy indexing
- Transposing Arrays and Swapping Axes
- Element-wise array functions
  - `np.sqrt`
  - `np.exp`
  - `np.maximum`
  - `np.minimum`
  - `np.modf`
- Unary Functions (requires single array as an argument)
  - `np.abs`, `np.fabs`
  - `np.sqrt`
  - `np.square`
  - `np.exp`
  - `np.log`, `np.log10`
  - `np.log2`, `np.log1p`
  - `np.sign`
  - `np.ceil`
  - `np.floor`
  - `np.rint`
  - `np.modf`
  - `np.isnan`
  - `np.isfinite`, `np.isinf`
  - `np.cos`, `np.cosh`, `np.sin`, `np.sinh`, `np.tan`, `np.tanh`, `np.arccos`, `np.arccosh`, `np.arcsin`, `np.arcsinh`, `np.arctan`, `np.arctanh`
  - `np.logical_not`
- Binary Functions (requires two arrays as argument)
  - `np.add`
  - `np.subtract`
  - `np.multiply`
  - `np.divide`, `np.floor_divide`
  - `np.power`
  - `np.maximum`, `np.fmax`
  - `np.minimum`, `np.fmin`
  - `np.mod`
  - `np.copysign`
- Linear Algebra with `numpy`
  - Element-wise multiplication or Hadamard Product (using simple `*` operator or `np.multiply`)
  - Dot product (using `np.dot`)
  - Matrix Multiplication (using `np.matmul` or `a @ b`)
    - NOTE: When the arrays are 2D, `np.dot` is equivalent to `np.matmul`
    - Columns of 1st matrix MUST be equal to Rows of 2nd Matrix
  - `np.linalg` library and its functions
    - `diag`
    - `dot`
    - `trace`
    - `det`
    - `eig`
    - `inv`
    - `pinv`
    - `qr`
    - `svd`
    - `solve`
    - `lstsq`
- Handling Image data in `numpy`
  - `PIL` library (Pillow library)
    - `Image` class from `PIL`
    - Initialize an image object using `Image.open(./path/to/image)` or `Image.fromarray(an_image_array)`
    - Image object methods:
      - `format`
      - `size`
      - `mode`
      - `convert`
      - `save`
  - Converting image object to `numpy` array
  - Shape of an image array, i.e. `(width, height, channels)`
  - Loading and displaying image with `matplotlib`
    - `imread` - to parse the image into numpy array
    - `imshow` - to plot an image using numpy array of the image

**Assignment**

Download the assignment 2 notebook from <a href='https://github.com/nasir-hussain1/piaic_q2_Assignments/blob/master/Assignment%232(Numpy%20Fundamentals.ipynb'>here</a>

Submit the assignment [here](https://forms.gle/GFnM5iS9Qc1G168R7) using google forms

Additionally, following tasks are also required to be completed

1. [Recipe Origanizer](https://github.com/nasir-hussain1/piaic_q2_Assignments/tree/master/NumpyTask1)
2. [Cereal Market Analysis](https://github.com/nasir-hussain1/piaic_q2_Assignments/tree/master/NumpyTask2)
3. [Election Analysis](https://github.com/nasir-hussain1/piaic_q2_Assignments/tree/master/NumpyTask3)
