### Overview

This project provides a Python implementation for Image Inpainting, specifically designed to hide defects or remove unwanted objects from images. The inpainting process is achieved using both the Fast Marching Method and the Navier Stokes Method, resulting in optimal and visually appealing results. The project utilizes OpenCV 2.X or higher and is compatible with Python 3.

### Features

1. **Fast Marching Method**: This method efficiently fills in the missing or damaged regions in an image by propagating information from the known areas to the unknown areas. It is particularly effective for inpainting large regions.

2. **Navier Stokes Method**: The Navier Stokes Method is employed for fine details and textures. It enhances the inpainting results by considering local structures and patterns in the image.

3. **OpenCV**: The project leverages the capabilities of OpenCV for image processing tasks, ensuring high-performance and reliability.

4. **User-friendly Interface**: The implementation includes a simple and user-friendly interface, allowing users to inpaint images with minimal effort.

### Requirements

- Python 3
- OpenCV 2.X or higher
- Numpy
- sys module

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Aditya5052/Image_Inpainting.git
   cd image-inpainting
   ```

2. Install the required dependencies:

   ```bash
   pip install opencv-python numpy
   ```

### Usage

1. Run the inpainting script with the desired image file:

   ```bash
   python inpainting.py --image_path=path/to/your/image.jpg
   ```

   Replace `path/to/your/image.jpg` with the path to the image you want to inpaint.

2. View the inpainted image and compare it with the original.

### Results

![Screenshot 2022-08-22 at 9 16 25 AM](https://user-images.githubusercontent.com/72243114/189874683-40d9a1eb-6f16-468b-81a7-9dd985905368.png)
![Screenshot 2022-08-23 at 8 49 55 PM](https://user-images.githubusercontent.com/72243114/189874712-a442ed7c-23a0-473d-afcb-af9c9c5537fa.png)


### Contribution

Contributions are welcome! If you have ideas for improvements or new features, please open an issue or submit a pull request.
