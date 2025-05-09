## ImageNet-Classifier

![thumbnail_svg](https://github.com/user-attachments/assets/665b2404-a9c0-44c3-98a2-88e29806548b)

A lightweight and user-friendly image classification tool powered by MobileNet pre-trained on ImageNet. This project provides a simple interface to classify images with beautiful result displays.

## 📋 Features

- Pre-trained MobileNet Model: Utilizes the MobileNet architecture pre-trained on ImageNet for efficient image classification
- Beautiful UI: Displays prediction results in an aesthetically pleasing gradient card
- Simple Integration: Easily incorporate into existing Jupyter notebooks or Python applications
- Fast Performance: Optimized for quick predictions on standard hardware

## 🛠️ Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/imagenet-classifier.git
cd imagenet-classifier

# Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## 📊 Dependencies

This project requires the following Python packages:

- TensorFlow
- NumPy
- Matplotlib
- Pillow (PIL)
- IPython
- ipywidgets


## Results

![image](https://github.com/user-attachments/assets/2a6c6bce-9ba1-4742-a662-deda3154e285)

*Fig 1: Cat Image Classification Result*

![image](https://github.com/user-attachments/assets/2d2d7147-368e-4f27-b90a-37c5cb841fe8)

*Fig 2: Sunflower Image Classification Result*

## Full API

- The project provides three main functions:
```bash
preprocess_image(path)
```
- Loads, resizes, and preprocesses an image for MobileNet input.
```bash
predict_image_class(img_array)
```
- Uses MobileNet to classify the preprocessed image and returns a formatted prediction string.
```bash
show_prediction_result(label)
```
- Displays the prediction result in a beautiful gradient card with interactive buttons.


## 🛣️ Roadmap

 1. Add support for image upload via URL
 2. Implement batch processing for multiple images
 3. Create a standalone web application version
 4. Add more visualization options for prediction confidence

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (git checkout -b feature/amazing-feature)
3. Commit your changes (git commit -m 'Add some amazing feature')
4. Push to the branch (git push origin feature/amazing-feature)
5. Open a Pull Request

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgements

- TensorFlow for the amazing deep learning framework
- MobileNet architecture developers
- ImageNet for the dataset used in pre-training


Made with ❤️ by Humaima Anwar
