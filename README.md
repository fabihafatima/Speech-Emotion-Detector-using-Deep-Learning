
# ![Logo]("static\spede3.jpg") **Sp**eech **E**motion **De**tector

Bringing you upto speed with emotions depicted in any speech, this a ML/DL based tool which helps in detecting a total of eight emotions namely: happy, sad, neutral, anger, disgust, calm, surprised and fearful.

You can upload a wav file in order to detect the emotion in that 
speech or song.

# Overview
This Python-based application leverages deep learning techniques to analyze uploaded speech recordings, providing insights into the detected emotions and transcribing the spoken words. The project incorporates a simple and intuitive user interface created using vanilla JavaScript, CSS, and HTML.




# Purpose and Applications

This project aims to personalize various aspects of interactions for individuals based on their emotions. By accurately detecting emotions in speech, the system can cater to specific interests and preferences, enhancing the overall user experience.

#### Support for Autistic Individuals
For individuals with autism spectrum disorders who may face challenges in accurately gauging emotions, this application provides a valuable tool. The emotion detection capability assists in understanding and interpreting emotions, fostering better social interactions.

#### Accessibility for Deaf Individuals
The application serves as a vital tool for the deaf community, enabling them to understand not only the words spoken but also the emotions conveyed during live online calls or phone conversations. This contributes to more inclusive communication.

#### Smart Automotive Safety
The technology extends beyond personal interactions. For instance, in smart car systems, the application could be utilized to detect the emotional state of the driver. In scenarios where the driver is identified as angry or fearful, the smart car could adapt its behavior, such as slowing down or providing additional assistance, enhancing safety on the road.

#### Potential Impact on Industries
The application's diverse applications hold significant potential for companies and industries. From personalized user experiences in entertainment to improved customer service interactions, the integration of speech emotion detection can revolutionize various sectors.
# Data used
The model has been trained on a dataset comprising 5252 samples from the following sources:

### Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS) Dataset
- Speech Files: 1440
- Song Files: 1012
- Actors: 24 professional actors (12 female, 12 male)
- Expressions in Speech: Calm, happy, sad, angry, fearful, - surprise, and disgust
- Expressions in Song: Calm, happy, sad, angry, and fearful
- Ratings: Each file was rated 10 times on emotional validity, - intensity, and genuineness by 247 individuals.
- Validation Data: Open-access and can be downloaded along with the paper from PLoS ONE.
### Toronto Emotional Speech Set (TESS) Dataset
- Files: 2800
- Actresses: Two actresses (aged 26 and 64 years)
- Emotions: Anger, disgust, fear, happiness, pleasant surprise, sadness, and neutral
- Audiometric Testing: Speeches have thresholds within the normal range
# Features

1. **Speech Upload**: Users can easily upload speech recordings through the user-friendly interface.
2. **Emotion Classification**: The system employs Convolutional Neural Networks (CNN) and Decision Tree algorithms to accurately classify emotions present in the speech signals. The deep learning model has been trained on a diverse dataset to recognize a wide range of emotions, including happy, sad, neutral, anger, disgust calm, surprised and fearful.
3. **Speech-to-Word Translation**: The application includes a speech-to-word translator, utilizing advanced algorithms to convert spoken language into written text. This feature enhances the user experience by providing a textual representation of the spoken words.
4. **Interactive UI**: The vanilla JavaScript, CSS, and HTML-based user interface ensure a seamless and visually appealing interaction. Users are guided through the process of uploading speech recordings and receive clear, comprehensible results.

### Speech Emotion Recognition (SER) System
The SER system operates through four main steps:

- **Voice Sample Collection:** Users upload speech recordings, providing the system with the data necessary for emotion analysis.

- **Feature Vector Extraction:** A features vector is formed by extracting relevant features from the voice samples. These features play a crucial role in differentiating between various emotions.

- **Feature Relevance Determination:** The system determines which features are most relevant for accurately differentiating each emotion. This step enhances the precision of emotion classification.

- **Deep Learning and Machine Learning Classification:** The selected features are introduced to both deep learning and machine learning classifiers for recognition. This dual approach ensures robust emotion detection and classification.



![App Screenshot](static\screenshots\spede1.jpg)
![App Screenshot](static\screenshots\spede2.jpg)

## Dependencies

Before running the project locally, make sure you have the following dependencies installed:

- **Python 3.x**: The core programming language for the backend.
- **TensorFlow**: An open-source machine learning framework for building and training deep learning models.
- **Scikit-learn**: A machine learning library that provides simple and efficient tools for data analysis and modeling.
- **Flask**: A micro web framework for building the backend server.
- **HTML5, CSS3, JavaScript**: Required for the frontend user interface.

Install Python dependencies using the following command:

```bash
pip install tensorflow scikit-learn Flask
```

## Getting Started

#### 1.  Clone the repository to your local machine :

```bash
git clone https://github.com/fabihafatima/Speech-Emotion-Detector-using-Deep-Learning.git
```
#### 2. Navigate to the project directory:

```bash
cd speech-emotion-detection
```
#### 3. Run the Flask app:
```bash
python3 app.py
```

#### 4. Open your web browser and go to 'http://127.0.0.1:5000/' to access the application.

## Usage

1. Upload a speech recording using the provided interface.
2. Wait for the system to process the speech and analyze emotions.
3. View the emotion classification and the transcribed words on the results page.

## Contributing
Contributions to this project are welcome! Feel free to open issues or submit pull requests.
