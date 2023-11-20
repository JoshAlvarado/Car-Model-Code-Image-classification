# Mercedes Vehicle Classification System (MVCS)

## Project Description

### Objective
The Mercedes Vehicle Classification System (MVCS) aims to accurately identify and classify images of Mercedes vehicles by their make, specific model, and associated code model. For example, the system will differentiate between models such as the C300, E350, and S500, and further identify their specific code models like W206 for the C300.

### Scope
- **Initial Focus:** The project will initially focus on Mercedes vehicles due to their distinct model range and available data.
- **Model Range:** We will include a broad range of popular Mercedes models, ensuring a diverse dataset that encompasses various body types (sedans, SUVs, coupes) and model years.
- **Dataset Requirements:** The dataset will consist of labeled images of Mercedes vehicles, categorized by make, model, and code model. It will include images from multiple angles and in various settings to ensure robustness.
- **Classification Categories:** The primary classification categories will be:
  - Make (e.g., Mercedes-Benz)
  - Model (e.g., C300, E350)
  - Code Model (e.g., W206 for the C300 2014-2021, W205 for the C300 20)

### Goals
1. **Develop a Deep Learning Model:** Create a convolutional neural network (CNN) that can classify images of Mercedes vehicles into their respective categories.
2. **Achieve High Accuracy:** Aim for high accuracy in classification to ensure the model is reliable and useful in practical scenarios.
3. **Dataset Creation and Preprocessing:** Collect and preprocess a comprehensive dataset of Mercedes vehicle images. This includes data augmentation to enhance model robustness.
4. **Model Training and Evaluation:** Train the model using the prepared dataset and evaluate its performance using standard metrics like accuracy, precision, and recall.
5. **User Interface for Testing:** Develop a simple user interface where users can upload a vehicle image and receive the classification results.

### Potential Applications
- The MVCS can be used in various applications, such as automotive sales platforms, vehicle inventory management, and enthusiast forums, to automate and enhance vehicle identification processes.

### Technologies to be Used
- Deep Learning Frameworks: TensorFlow or PyTorch.
- Programming Language: Python.
- Image Processing Libraries: OpenCV, PIL.
- Model Training: Utilize GPU acceleration for efficient training.

### Expected Outcomes
- A fully functional deep learning model capable of classifying Mercedes vehicles with high accuracy.
- A dataset that can be further used for research or expanded to include other vehicle makes and models.
- Insights into the challenges and solutions of image classification in the automotive context.

This project not only aims to build a practical AI tool but also serves as a comprehensive learning experience in deep learning, image processing, and the application of AI in the automotive industry.

https://github.com/JoshAlvarado/Car.com-Image-Scraper to automate the dataset process
