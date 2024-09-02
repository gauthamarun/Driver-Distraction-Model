# Keeping Drivers Focused: A Deep Learning Model for Driver Distraction Detection

## Description
This project presents an advanced Driver Monitoring System (DMS) aimed at enhancing road safety by detecting driver distractions. Leveraging deep learning techniques, the model integrates multiple views to accurately identify distractions such as drowsiness, mobile phone usage, and more, even in challenging conditions like occlusions. The system utilizes a novel augmentation method based on Neural Style Transfer (NST) to improve robustness, especially when dealing with limited or artificial datasets.

### Key Features:
- **nstAugment Function**: A customizable Neural Style Transfer-based image augmentation technique that enhances model performance by creating varied training data.
- **Meta-Learner Layer**: An innovative approach that combines predictions from multiple views (front and side cameras) to achieve state-of-the-art accuracy in distraction detection.
- **Movinet Backbone**: A lightweight and efficient model that ensures low latency, making the system suitable for real-time applications.

The model achieves an accuracy of 87.44% on the 3MDAD dataset, outperforming existing methods by incorporating multi-view integration and NST-based augmentation, making it a robust solution for real-world driver monitoring systems.

## Technologies Used:
- Python
- TensorFlow/PyTorch
- Neural Style Transfer (NST)
- Movinet Architecture
- Kaggle GPU Environment

## How to Run:
1. Clone the repository.
2. Ensure you have the necessary dependencies installed.
3. Run the notebook on a suitable GPU environment to train the model.
4. Test the model using the provided dataset or your custom dataset.

## Acknowledgments:
This project was developed by a team of students from the School of Computer Science and Engineering at Vellore Institute of Technology, and was recently accepted at Bennett University Global AI Summit.

##Dataset References

Imen Jegham, Anouar Ben Khalifa, Ihsen Alouani, Mohamed Ali Mahjoub, A novel public dataset for multimodal multiview and multispectral driver distraction analysis: 3MDAD, Signal Processing: Image Communication, Volume 88, October 2020, 115966, DOI: https://doi.org/10.1016/j.image.2020.115960.

Imen Jegham, Anouar Ben Khalifa, Ihsen ALOUANI, Mohamed Ali MAHJOUB, MDAD : A Multimodal and Multiview in-Vehicle Driver Action Dataset, In: Vento M., Percannella G. (eds) Computer Analysis of Images and Patterns. CAIP 2019. Lecture Notes in Computer Science, vol 11679. Springer, Cham, pp. 518-529.
