<h1>Dataset Augmentation and Standardization</h1>

<h4>This Jupyter Notebook file contains code to standardize and augment JPG files for use in AI and ML models.
Purpose</h4>

The purpose of this code is to create a larger and more diverse dataset for training AI and ML models. Augmenting the dataset with variations of the same image (e.g., rotated, cropped, flipped, etc.) can improve the model's ability to recognize objects under different conditions. Standardizing the images to a common format (e.g., same size, color space, etc.) can also improve model accuracy and reduce training time.

<h4>Usage</h4>
  <ul>
    <li>Ensure all dependencies are installed.</li>
    <li>Place the JPG files you wish to augment and standardize in a folder called "input_images" within the same directory as the Jupyter Notebook file.</li>
Run the cells in the Jupyter Notebook file.
    <li>The output images will be saved in a folder called "output_images" within the same directory.</li>
  </ul>

<h4>Parameters</h4>
  <ul>
    <li>rotation_range: Range of degrees for random rotations. Default is 0 to 360.</li>
    <li>width_shift_range and height_shift_range: Range of fractions for random horizontal and vertical shifts, respectively. Default is 0.1.</li>
    <li>shear_range: Range of degrees for random shearing. Default is 0 to 20.</li>
    <li>zoom_range: Range for random zoom. Default is 0.2.</li>
    <li>horizontal_flip: Boolean to randomly flip images horizontally. Default is True.</li>
    <li>vertical_flip: Boolean to randomly flip images vertically. Default is False.</li>
    <li>target_size: Tuple of integers representing the desired output size of the images. Default is (224, 224)./<li>
    <li>color_mode: String representing the color space of the images. Default is "rgb".</li>
   </ul>
