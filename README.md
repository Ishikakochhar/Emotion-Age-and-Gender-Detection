###Emotion, Age, and Gender Detection with Mood-Based Recommendations

This project is a Deep Learning-based Image Processing (DIP) system that detects emotion, age, and gender from facial images and recommends mood-appropriate music and content. It combines computer vision, data analysis, and generative AI for a personalized user experience.

---

## Features

- **Emotion Detection:** Classifies facial expressions (Surprise, Fear, Disgust, Happy, Sad, Angry, Neutral) using a custom CNN trained on RAF-DB.
- **Age & Gender Prediction:** Predicts age (regression) and gender (classification) from face images using a multi-output neural network trained on UTKFace.
- **Mood-Based Music Recommendation:** Suggests songs from a labeled dataset based on detected emotion.
- **Generative AI Content Suggestions:** Uses Google Gemini Pro to recommend articles, videos, or books tailored to the user's mood, age, and gender.
- **Data Visualization:** Visualizes dataset distributions and model performance.

---

## Workflow

1. **Image Input:** User provides a facial image.
2. **Preprocessing:** Image is resized and normalized for model input.
3. **Prediction:** Models output emotion, age, and gender.
4. **Recommendation:** 
    - Music is recommended based on emotion.
    - Additional content is suggested using generative AI.
5. **Visualization:** Results and recommendations are displayed.

---

## Technologies

- Python, TensorFlow, Keras, OpenCV, Pandas, Matplotlib, Seaborn, Plotly
- Google Generative AI (Gemini Pro)
- Jupyter Notebook

---

## Getting Started

1. Clone the repository.
2. Install dependencies from `requirements.txt`.
3. Download and organize datasets (RAF-DB, UTKFace, mood music CSV).
4. Run the Jupyter notebook:
   ```
   jupyter notebook "Emotion, Age, and Gender Detection.ipynb"
   ```
5. (Optional) Set up your Google Generative AI API key in a `.env` file.

---

## Example Output

- **Emotion:** Happy
- **Age:** 23
- **Gender:** Female
- **Music Recommendations:** 5 mood-matched songs
- **Content Recommendations:** 5 AI-generated articles/videos/books

---

## License

For educational and research use only.

---

For details, see `Emotion, Age, and Gender Detection.ipynb`.
