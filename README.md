## CapraCure - AI-Powered Goat Disease Diagnosis

# Overview
CapraCure is an AI-driven disease diagnosis tool designed specifically for goat health. It leverages computer vision and machine learning to identify diseases based on images and text-based symptoms. The project aims to provide an accessible and efficient solution for farmers, even in low-connectivity areas.

# Features
- **Image-Based Diagnosis:** Farmers can upload a photo of their goat, and a CNN model analyzes it for signs of disease.
- **Text-Based Symptom Analysis:** Users can manually enter symptoms, which are processed using logistic regression for classification.
- **Treatment Recommendations:** AI suggests medications, home remedies, and preventive measures.
- **Veterinary Assistance:** Displays emergency contact numbers for vet support.
- **Offline Support:** Works in rural areas with limited internet access through on-device AI processing.

# Technology Stack
- **Machine Learning:** TensorFlow, Scikit-Learn
- **Image Processing:** OpenCV, CNNs (MobileNetV2)
- **Data Storage:** Firebase, Cloud Storage
- **Application Development:** Flutter, React, Kotlin

# How It Works
1. **User Input:** Farmers upload an image or describe symptoms.
2. **AI Analysis:**
   - CNN model processes the image.
   - Logistic regression classifies text-based symptoms.
3. **Diagnosis & Recommendations:**
   - AI matches input with a disease database.
   - Suggests medications and preventive measures.
   - Provides veterinary contacts.

# Competitive Advantage
- **Specialized Dataset:** Unlike generic models, CapraCure is trained on a curated dataset of 500+ goat disease images.
- **Minimal User Effort:** Only requires an image or short symptom description.
- **Scalability:** Can expand to include more regions and languages.
- **Future Scope:** Potential for integration with medicine sales, insurance, and vet consultations.

# Challenges & Future Enhancements
- **Accessibility:** Ensuring all farmers have access to smartphones capable of capturing images.
- **Data Updates:** Keeping the disease database current with new variants.
- **Scalability:** Expanding the model to support a wider range of livestock diseases.

![image](https://github.com/user-attachments/assets/77e984c7-fd89-4148-b370-d935e1fa2183)
![image](https://github.com/user-attachments/assets/3e148c69-1b46-4a2c-9dfa-03e3e2321010)
![image](https://github.com/user-attachments/assets/5ab8cdff-f9fe-4d62-8910-481da31ae1df)
![image](https://github.com/user-attachments/assets/ae9d94b6-c07a-4067-8621-fcd13be294e4)

