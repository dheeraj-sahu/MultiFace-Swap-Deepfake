# MultiFace Swap Deepfake

## Description
This project automates the process of swapping multiple faces in images using deep learning techniques. It leverages advanced neural networks and computer vision libraries to achieve realistic face swapping results. The project includes a user-friendly web interface built with Flask, allowing users to easily upload images and perform face swaps.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation Instructions](#installation-instructions)
- [Usage](#usage)
- [Contributing](#contributing)
- [Documentation](#documentation)
- [Demo](#demo)
- [License](#license)
- [Contact Information](#contact-information)

## Features
- **Multiple Face Swapping**: Swap multiple faces in a single image.
- **High-Quality Results**: Uses deep learning models to ensure realistic and high-quality face swaps.
- **Batch Processing**: Supports batch processing of images for efficient face swapping.
- **User-Friendly Interface**: Provides an easy-to-use web interface built with Flask.
- **Configurable Parameters**: Allows users to fine-tune the face swap process with various parameters.

## Technologies Used
- **Python**: The primary programming language for this project.
- **Flask**: A micro web framework used to create the web application.
- **OpenCV**: An open-source computer vision library used for image processing.
- **face_recognition**: A library for recognizing and manipulating faces in Python.
- **NumPy**: A library for numerical operations in Python.

## Installation Instructions
Follow these steps to set up and run the project on your local machine:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/YOUR-USERNAME/MultiFace-Swap-Deepfake.git
    cd MultiFace-Swap-Deepfake
    ```

2. **Create a Virtual Environment** (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Set the Secret Key**:
    - Create a `.env` file in the root directory of the project.
    - Add the following line to the `.env` file:
      ```env
      SECRET_KEY=your_secret_key_here
      ```

5. **Run the Flask App**:
    ```bash
    export FLASK_APP=app.py  # On Windows use `set FLASK_APP=app.py`
    flask run
    ```

6. **Access the Web Interface**:
    Open your web browser and go to `http://127.0.0.1:5000/`.

## Usage
1. **Upload Image**: Use the web interface to upload an image in which you want to swap faces.
2. **Upload New Face**: Upload an image containing the new face to be swapped into the original image.
3. **Download Result**: After processing, download the image with the swapped faces.

## Contributing
Contributions are welcome! Please follow these steps to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## Documentation
- **Project Report**: A detailed project report including the methodology, implementation details, results, and challenges faced is available [here](DOCUMENTATION_LINK).

## Demo
- **Video Demonstration**: Watch a video demonstration of the project [here](DEMO_LINK).

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact Information
For any inquiries or issues, please create an issue on this repository or contact the project maintainer at [your-email@example.com](mailto:your-email@example.com).
