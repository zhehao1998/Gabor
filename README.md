# Gabor
Gabor filters are band-pass filters and can be overlayed on an image to further highlight edges. Notebook includes visualization of individual filters with chosen parameters.

# Idea
- Multiple filters are passed over the image and this isolates edge patterns
- Output of these filters are cumulatively overlayed onto the original image
- When the overlayed image is parsed into an edge detection algorithm such as Canny or Sobel, edges are made more apparent and this also reduces noise identified incorrectly as edges

It is possible to further improve edges extraction by first applying preprocessing to the image (such as CLAHE). CLAHE is included in the notebook, but other methods can be additionally investigated.
