🖼️ Image Captioning AI Project
This project demonstrates how Artificial Intelligence can describe the content of an image using natural language. It uses a pre-trained BLIP (Bootstrapping Language-Image Pre-training) model from Hugging Face to generate image captions. The model can analyze an image and produce a descriptive caption, bridging the gap between visual content and textual understanding.
🚀 Technologies Used
Python
Google Colab
Hugging Face Transformers
PyTorch
Pillow (for image processing)
requests (to fetch images from the web)
⚙️ How It Works
Model: BLIP model is used for caption generation, pre-trained and loaded from Hugging Face.
Input: An image is provided using a URL.
Output: The model generates a human-like caption describing the image.
📌 Usage (Google Colab)
Open the Google Colab notebook:
Image-Captioning-AI-Project.ipynb
Run the notebook cells step by step.
Provide an image URL as input.
The model will return a caption describing the image.
✅ Example
image_url = "https://www.caninecampus.us/wp-content/uploads/2020/08/extra-blog-image-EXERCISE.jpg"
print(generate_caption(image_url))
🔍 Output 
Processing image from URL: https://www.caninecampus.us/wp-content/uploads/2020/08/extra-blog-image-EXERCISE.jpg
two dogs playing with a ball in the grass


