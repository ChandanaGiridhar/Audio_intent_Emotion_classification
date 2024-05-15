# Audio_intent_Emotion_classification
Audio Intent Classification and Emotion Classification

## Initial Proposal and Motivation

Audio intent Classification is much needed in interactive voice response (IVR), understanding the intent and sentiment behind customer inquiries is crucial for enhancing service quality and satisfaction. This project proposes the development of a voice intent classification and sentiment analysis system tailored to process customer voice interactions. By leveraging state-of-the-art audio computing and natural language processing (NLP) technologies, this system aims to accurately interpret the customer's intent and sentiment from audio interactions, providing actionable insights to improve response strategies and customer experience.

As of now, my plan is to achieve Audio Intent classification using data like Skit-S2I Dataset which is a dataset for Intent classification from the Banking domain as part of query understanding process. Then as second part of the project I would like to add sentiment analysis to the voice to understand the customer’s mood and take the informed decision this can be a useful feature in the IVR process.

## Methodology 
![Methodology](https://github.com/ChandanaGiridhar/Audio_intent_Emotion_classification/blob/main/Methodology.png)

As the project, intends to work on two different aspects i.e. Audio Intent classification and Emotion Classifier/Voice Sentiment Analysis. Hence, there are 2 seperate flows in methodology. For further explaination, Please refer to the Python Notebook. 

## Conclusion
While for audio intent classification, the model works extremely well. However, for the emotion classifier, the model is run on various batch size and epochs settings

run1 -> batch = 5, epochs = 30, accuracy=32.22%

run2 -> batch = 15, epochs = 50, accuracy = 43.19%

run3 -> batch = 40, epoch = 45, accuracy = 56.65%

run4 -> batch = 70, epoch = 50, accuracy =48.50%

run5 -> batch = 64, epoch = 64, accuracy = 71.39%

From this i have achieved audio intent classification but emotion classifier could have been better as several more runs and hyperparameter tuning is required to achieve best results.
