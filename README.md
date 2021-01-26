# have-a-nice-day
An application recognising emotions from your face and matching the best quote to motivate you! 💪💪

## NN vs. SVM
The first part of the project is inspired by the article [Comparative Analysis of Image Classification Algorithms Based on Traditional Machine Learning and Deep Learning](https://www.researchgate.net/publication/343374467_Comparative_Analysis_of_Image_Classification_Algorithms_Based_on_Traditional_Machine_Learning_and_Deep_Learning).
The assumption of this part is to achieve values approaching to those mentioned in the article and on the base of observations, attempt to compare NN and SVM models recognizing emotions from a picture.


## to-do list
- [x] build tensorflow model to recognize emotions 🙂🙃
- [x] build SVM model to recognize emotions 🙃🙂
- [ ] compare NN and SVM classification model ⚖️
- [ ] use larger and higher quality dataset - AffectNet 📖
- [ ] try to write algorithm without tensorflow/keras 🧠
- [ ] move computing from local env to the cloud ☁️
- [ ] consider how to match a quote with an emotion ✍️
- [ ] design UI for the app 🖼
- [ ] create frontend application 📱

## run
1. Download data from Kaggle  [Dataset](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data?select=fer2013.tar.gz)
2. Download scripts from the /scripts directory
3. Using Jupyter Notebooks or Google Colab run `data-preprocessing.ipynb`
4. Run `*-emotion-classification.ipynb`


## sources
#### [Facial Emotion Recogition Dataset](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data?select=fer2013.tar.gz)

#### [Quotes-500K Dataset](https://github.com/ShivaliGoel/Quotes-500K)
