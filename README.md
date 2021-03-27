# image-denoising-using-deep-learning-with-compressed-model-deployment
Deep learning based Image denoising with model compression using tensorflow lite and final model deployment with streamlit

**Data set preparation

In the case of deep learning-based image denoising, we need a dataset on which we can train our network. Since we are targeting different noises, we need more datasets and for the same, we have combined various datasets to prepare a large dataset. We have combined three different datasets. In the DIV2K_train_HR dataset total of 800 images are there, the shape of each image is 1140x2040x3. In the BSDS500 dataset 200 images are there, size of each image is 481x321x3. We also have 400 images of the Berkeley segmentation data, a shape of 180x180x3.

We have converted all images into .png and resized them to 180x180x3. After collecting all images in a common folder of the same size we have a total of 1700 images from three different datasets as the training datasets. For testing, we have used the Set68 dataset to measure the PSNR and SSIM. For generating the dataset we have added various noises like gaussian, locavore, Poisson, salt &paper, and speckle.
