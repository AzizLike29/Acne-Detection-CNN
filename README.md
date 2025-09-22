<h1>Detecting acne on the face using a CNN (Convolutional Neural Network)</h1>

<h2>- Training and Validation Accuracy</h2>

<img width="826" height="498" alt="download (1)" src="https://github.com/user-attachments/assets/595de1d8-9863-49da-8ab2-3751c5acf4e3" />

<span>The curve shows that training and validation accuracy rose steadily until the end, at around 0.90 and ~0.88–0.89, respectively, while both losses fell consistently and remained close to each other. This pattern indicates good model generalization without signs of overfitting.</span>

<h2>- Confusion Matrix</h2>

<img width="785" height="624" alt="download (2)" src="https://github.com/user-attachments/assets/3a654fdd-3ce2-499e-aa12-e603040d1cf8" />

<span>The model has performed well with the majority of predictions correct in all classes (diagonally dominant), especially for blackheads, cysts, pustules, and whiteheads; however, there is still a major weakness in distinguishing papules from pustules (the largest misclassification is papules→pustules). This means that generalization is solid, but decisions on two similar classes are still vulnerable.</span>
