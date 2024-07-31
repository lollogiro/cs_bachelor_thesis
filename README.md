# My Computer Science Bachelor Thesis project
## Pose estimation to classify and evaluate static bodyweight exercises

This project aims to classify and evaluate static bodyweight exercises using pose estimation. After extracting keypoints from an athlete's pose, these keypoints are used to recognize and classify the exercise into one of four categories: Front Lever, Back Lever, Planche, and Handstand.

Following the classification task, the project evaluates the execution of the exercises by identifying common errors according to FIG (Fédération Internationale de Gymnastique) rules.

The notebooks `notebook_tesi_cnn_training.ipynb` and `notebook_tesi_dense_training.ipynb` detail the architecture and training process of two different models. These models are compared to determine the better one for skill classification.

Both models have been trained using 280 self-selected images, with each class containing approximately the same number of examples.

The notebook `notebook_tesi_skill_eval.ipynb` uses the better-performing model (CNN in this case) to recognize the exercise and evaluate its execution.
