## Machine Learning - Model Research

### Describe how Teachable Machine uses machine learning to come up with solutions to an arbitrary problem.

Teachable Machine is a web-based tool developed by Google that allows users to create machine learning models without needing to write code. It uses a process called transfer learning to make machine learning accessible and easy to use for a wide range of problems. Here’s how it applies machine learning to solve problems:

**1. Problem Definition**

- The user defines the problem they want to solve, such as image classification, sound recognition, or pose detection.

**2. Data Collection**

- The user gathers and uploads training data directly into the tool. This data is specific to the problem they want to solve.

- For image classification, the user uploads labeled images. For sound recognition, they record or upload audio samples. For pose detection, they provide examples of body poses.

- These examples serve as labeled data for the machine learning model.

**3. Model Training**

- Teachable Machine uses pre-trained models as a starting point. These models have already been trained on large datasets and have learned general features

- The tool fine-tunes these pre-trained models using the user's specific dataset. This process is called transfer learning.

- During training, the model learns to associate the user's input data (e.g., images, sounds, or poses) with the corresponding labels.

**4. Inference & Predictionn**

- After training, users can test the model to see if it correctly classifies new samples(e.g., new images, sounds, or poses).

- This step helps in fine-tuning the model by adding more examples or adjusting the training parameters if needed.

- The model makes predictions based on what it has learned, and the user can evaluate its accuracy.

**5. Exporting the Model**

- Once the model performs well, the user can export it in various formats, such as TensorFlow.js, TensorFlow Lite, or a hosted cloud API.

- The exported model can be integrated into websites, apps, or other projects.

#### What application did you choose to create using Teachable Machine?

I am building a model which can differentiate between a green vs orange sketchpen using the image model functionality provided by teachable machines. For this I will take the image samples of both sketchpens and train the model so that it can differentiate the colors.


#### What problem is it intended to solve?

This image model is designed to make machine learning more accessible and user-friendly, particularly for individuals without extensive programming or technical expertise. It makes use of webcam to identify the color of the sketchpen to predict if it is green or orange. 

#### Why did you choose to create this application?
This is a simple application that will help you identify the color of the sketchpens and may be we might be able to add more colors to the model and train it so that can detect that various colors of sketchpens and that will help people in identifying the colors. This was very easy to build the model and train it using images captured from webcam.

#### Provide the URL to your application or exported model created using Teachable Machine


**Orange Sketchpen prediction by the model**
![image](https://github.com/user-attachments/assets/62dd8f5b-b405-4be1-a74b-4e1eb40951bc)

**Green Sketchpen prediction by the model**
![image](https://github.com/user-attachments/assets/ba30da99-bd8e-455a-9e2a-19af9c5f457a)

Below is the URL for the model that is generated using Teachable machines
[Teachable Image Model](https://teachablemachine.withgoogle.com/models/U2GVT21w4/)




