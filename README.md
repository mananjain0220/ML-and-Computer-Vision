# Assessing the Feasibility of Damage Prediction and Detection through Multi-Modal Machine Learning in Digital Freight Forwarding Operations

1. **Project Background**: Master's thesis project for Cargoboard GmbH, in collaboration with Fraunhofer IEM.
2. **Goal**: Develop a machine learning framework to detect and predict shipment damage in digital freight forwarding.
3. **Framework Design**: This method combines tabular data and image analysis to efficiently and accurately identify damaged shipments.
4. **Efficiency Considerations**: Focuses on reducing the high computational costs of image processing.
5. **Validation Approach**: Tested models on an imbalanced dataset that combines tabular data with limited images of damaged shipments.
6. **Technologies Used**:
   - **Tabular Analysis**: Random Forest Classifier, showing effective damage prediction.
   - **Image Analysis**: A Vision Transformer (ViT) is used for damage classification, and a YOLO detector is used for damage segmentation. Image diversity limits these methods.
7. **Challenges**: Addressed data imbalance and a scarcity of image data while demonstrating the framework's potential to improve damage detection in logistics.

