# Machine Learning Projects Repository

This repository contains multiple machine learning projects ranging from image processing to demand forecasting in the cab booking industry. Each project is self-contained with its Jupyter notebooks, datasets, and documentation.

## Projects Overview

### 1. Handwritten Character Recognition

- **Description**: This project focuses on recognizing handwritten characters using machine learning techniques.
- **Notebook**: [Handwritten Character Recognition Notebook](Handwritten_character_recognition/handwritten_character_recognition.ipynb)

### 2. Image Stitching GAN (Generative Adversarial Network)

- **Description**: This project demonstrates the use of GANs for stitching images to create panoramas.
- **Components**:
  - **Notebook**: [Image-Stitching-GAN Notebook](Image-Stitching-GAN/Image-Stitching-GAN.ipynb)
  - **Documentation**: [Project Report](Image-Stitching-GAN/Image_Stitching_GAN.pdf)
  - **Sample Outputs and Inputs**:
    - High-Resolution Output: ![HR Image](Image-Stitching-GAN/hr/014.jpg)
    - Input 1: ![LR1 Image](Image-Stitching-GAN/lr1/014.jpg)
    - Input 2: ![LR2 Image](Image-Stitching-GAN/lr2/014.jpg)
    - Generated Panorama: ![Generated Image](Image-Stitching-GAN/test_generated_image_14.png)
  - **Read More**: [Additional Info](Image-Stitching-GAN/README.md)

### 3. ML Forecast Cab Booking Demand

- **Description**: Analyze and predict the demand for cabs using historical booking data.
- **Components**:
  - **Notebook**: [Forecast Cab Booking Demand Notebook](ML_Forecast_Cab_Booking_Demand/forecast_cab_booking_demand.ipynb)
  - **Documentation**: [Demand Forecasting Report](ML_Forecast_Cab_Booking_Demand/Forecast%20Cab%20Booking%20Demand.pdf)

### 4. ML Model for Auto Insurance Industry

- **Description**: Develop a model to assist in risk assessment and premium calculation for auto insurance.
- **Notebook**: [ML Model for Auto Insurance Industry Notebook](ML_model_for_Auto_Insurance_Industry/ml-model-for-auto-insurance-industry.ipynb)

### 5. Super-Resolution and Low-Light Image Enhancement

- **Description**: This repository focuses on two advanced image processing techniques. The first project enhances the resolution of images through super-resolution techniques, aiming to reconstruct a high-resolution image from its low-resolution counterpart. The second project improves the visibility and quality of images taken in low-light conditions using various enhancement algorithms. Both projects are designed to demonstrate the practical applications of these techniques in improving image quality for better analysis and visualization.
- **Notebooks**:
  - **Super-Resolution**: [Super-Resolution Notebook](SupRes_LowLightEnhance.SupRes.ipynb) showcases the method to enhance image resolution.
  - **Low-Light Enhancement**: [Low-Light Enhancement Notebook](SupRes_LowLightEnhance/OutputLowLE.ipynb) demonstrates techniques to enhance images captured in poorly lit environments.
- **Outputs and Figures**:
  - **Super-Resolution Output**: Demonstrated in `SupRes_LowLightEnhance/output-super-res/SupRes-out.JPG`.
  - **Low-Light Enhancement Outputs**: Available in the `SupRes_LowLightEnhance/output-low-light` directory with multiple enhanced examples.
  - **Figures**: Visual results can be found in the `SupRes_LowLightEnhance/fig` directory illustrating the enhancements.
- **Presentation**: Detailed insights and methodologies are discussed in [LowLight_SuperRes.pdf](SupRes_LowLightEnhance/LowLight_SuperRes.pdf), which includes a comprehensive presentation of the projects.

## Getting Started

To get started with any of these projects, clone the repository, navigate to the project's directory, and open the Jupyter notebooks in a Jupyter environment:

```bash
git clone https://github.com/your-repo/ML.git
cd ML/<project_directory>
jupyter notebook <notebook_name>.ipynb
```

## Contribution

Contributions to improve the projects or add new features are welcome. Please fork the repository and submit a pull request with your changes.

<!-- ## License

The contents of this repository are covered under [MIT License](LICENSE). -->
