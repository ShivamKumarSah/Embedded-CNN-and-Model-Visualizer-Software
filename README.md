# Embedded-CNN-and-Model-Visualizer-Software
This project is a GUI-based application designed to work with various embedded system boards, allowing users to upload custom CNN models in `.h5` format, process images, and visualize the results. The application performs image recognition with bounding boxes and offers 3D visualization of the model’s output.

## Features
- **Embedded System Support**: Select different embedded system boards for processing.
- **Model Upload**: Upload CNN models in `.h5` format.
- **Image Processing**: Upload an image to be processed by the model.
- **Bounding Box**: Visualize image recognition results with bounding boxes around identified objects.
- **3D Model Visualization**: View a 3D visualization of the model's output.

## Workflow
1. **Select Embedded System Board**: Choose the embedded system board (e.g., Raspberry Pi, Orange Pi, etc.).
2. **Upload Model**: Upload your CNN model in `.h5` format.
3. **Upload Image**: Upload an image to be processed by the model.
4. **Output**: The system will display recognized objects with bounding boxes and a 3D visualization of the model's output.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/Embedded-CNN-GUI.git
    ```
2. Install dependencies:
    ```bash
    pip install tensorflow
    ```
    ```bash
    pip install customtkinter
    ```
3. Run the application:
    ```bash
    python My_Software.py
    ```

## Screenshots
![1](https://github.com/user-attachments/assets/63e4dfa8-6e40-4006-870a-eb96fcc4c329)
![2](https://github.com/user-attachments/assets/502748dd-a66d-4d7e-8afc-047cc7e7b5dd)
![3](https://github.com/user-attachments/assets/fea5c014-85c3-4b8c-ae61-409688560741)
![4](https://github.com/user-attachments/assets/c5b353cf-0ee5-4e9b-bb72-c67adc22b897)
![5](https://github.com/user-attachments/assets/3eec7e60-33d5-4e49-b62b-9a4a09362999)
![6](https://github.com/user-attachments/assets/449595be-1faa-44b2-86f2-dcdacaaecf25)


## Tech Stack
- **Programming Language**: Python
- **GUI Framework**: Tkinter / PyQt (update based on your choice)
- **Model Format**: Keras/TensorFlow (.h5)
- **Embedded Systems**: Raspberry Pi, Orange Pi, etc.

## Usage
1. Ensure your embedded system board is set up and connected.
2. Upload your trained CNN model in `.h5` format.
3. Upload the image for processing.
4. View the results with bounding boxes and explore the 3D visualization.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
