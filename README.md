# anime-face-generator
This project showcases an Anime Face Generator built using Generative Adversarial Networks (GANs). The goal was to generate realistic anime faces by training a GAN on an anime face dataset from Kaggle. The project includes custom implementations of both the generator and discriminator networks, training loops, and visualizations of the model's performance over time.

## Key Features
Anime Face Dataset: Utilized a publicly available anime face dataset from Kaggle to train the model.
Generator and Discriminator Networks: Designed custom architectures for both networks with careful attention to stability during training.
Training Process: Defined the training loop with adaptive learning to optimize both networks simultaneously.
Image Saving: Captured generated images after each training epoch to monitor progress.
Visualization with OpenCV: Created a video compilation using OpenCV to illustrate the evolution of generated images across epochs.
Metrics and Analysis: Plotted training metrics, such as loss curves and generator/discriminator scores, to track model performance and convergence.
Highlights
Epoch-by-Epoch Visualization: The project outputs a video that showcases how the generated anime faces improve over time, providing an intuitive grasp of the GAN's learning process.
Comprehensive Metric Tracking: Loss curves for both generator and discriminator are plotted to give insights into model stability and effectiveness during training.
Reproducible Code: Code is organized for easy reproduction and understanding, making it accessible for further development or educational purposes.
