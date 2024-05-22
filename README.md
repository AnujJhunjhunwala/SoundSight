# SoundSight
SoundSight is a cutting-edge software designed to enhance the independence and mobility of visually impaired individuals by verbally informing them about objects in their vicinity. Utilizing advanced machine learning models and natural language processing, SoundSight provides real-time, auditory descriptions of the surrounding environment.

## Features
- **Object Recognition:** Employs the InceptionV3 model by Google to accurately identify objects in the user's vicinity.
- **Natural Language Processing:** Utilizes the GloVe model for sophisticated language processing to generate meaningful and contextually appropriate descriptions.
- **Text-to-Speech Conversion:** Converts generated text descriptions into speech using the gTTS (Google Text-to-Speech) library.

## Getting Started
### Prerequisites
Before running SoundSight, ensure you have the following installed:
- Python 3.6 or higher
- TensorFlow
- Numpy
- gTTS
- Scikit-learn

### Usage
1. Capture images or video frames from a connected camera.
2. Use the InceptionV3 model to recognize objects in the frame.
3. Generate descriptive sentences using the GloVe model.
4. Convert the generated text descriptions to speech using the gTTS library.
5. Verbally inform the user about the objects detected in their vicinity.

### Contributing
We welcome contributions to SoundSight! If you have suggestions for improvements or have found a bug, please open an issue or submit a pull request.

### Acknowledgements
- **InceptionV3 Model:** Developed by Google for high-accuracy image recognition.
- **GloVe Model:** Provided by Stanford University for efficient and powerful word embeddings.
- **gTTS:** Google Text-to-Speech library for converting text to natural sounding speech.
