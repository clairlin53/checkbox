- 0.0.16
  - Removed url image loading
  - Removed scipy dependency
  - Changed image reading from skimage to opencv
  - Fixed ordered dict creation to work in older versions of python
  - Images resized to 640p width for processing
  - Using original model
- 0.0.15
  - #9
    - Removed direct image loading instead made it more generic using NdArray
    - Moved the loading of the model to init method for faster score processing
- 0.0.14
  - PyTest and Doc Update