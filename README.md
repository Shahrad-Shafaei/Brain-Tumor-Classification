# Brain-Tumor-Classification

### Data and code: 
- https://www.kaggle.com/code/nirmalgaud/brain-tumor-classification/input
- https://www.linkedin.com/posts/nirmal-gaud-210408174_tumor-activity-7258763822935539712-dDH6


### Models Used:
Tested several pre-trained architectures, including VGG16, VGG19, MobileNet, Xception, and InceptionV3. Each model was fine-tuned and enhanced with techniques such as multi-head attention, Gaussian noise regularization, batch normalization, and dropout layers for improved performance and robustness.

### Results:
To evaluate model performance, focused on key metrics: precision, recall, F1-score, and accuracy. Here’s how the models stacked up:
- MobileNet led with impressive scores, achieving an accuracy of 97%.
- VGG16 and VGG19 performed competitively with accuracies around 91-92%.
- Other models like Xception and InceptionV3 showed unique strengths in recall and precision across certain classes.

### Visualization and Analysis:
The results were visualized with annotated bar plots, clearly showing how each model performed across metrics. This helped in identifying the best model for this task and provided insights into where further optimization might be needed.

### Takeaways:
- Pre-trained models can significantly speed up the development process while achieving high accuracy.
- Adding attention mechanisms, dropout, and normalization layers further improved the models' robustness against overfitting.
- Visualizing comparative performance helped in selecting the most effective model based on both class-wise and overall metrics.
