**FoodSynthNet: Generative AI Framework for Class-Balanced Food Image Datasets and Intelligent Food Recognition for Nutrition Monitoring**

FoodSynthNet is a web-based food recognition and nutrition monitoring project. It is designed to use Conditional Generative Adversarial Networks (cGANs) to generate synthetic food images for underrepresented classes, helping improve dataset balance. Users upload a food image through the web interface and view the predicted food category with associated nutrition information and health suggestions.

**Features**
- User sign-up and sign-in
- Upload a food image for analysis
- Image preprocessing before recognition
- Food-category prediction
- Nutrition details such as calories, nutrients, vitamins, and minerals, where available
- Health-related suggestions associated with the predicted food
- cGAN-based synthetic image generation to support class-balanced datasets
  
**Workflow**
1. The user signs in.
2. The user uploads a food image.
3. The image is preprocessed.
4. The classifier predicts a food category.
5. The system retrieves nutrition information associated with that category.
6. The application displays the prediction and available nutrition details.
7. During dataset preparation, cGAN can generate label-conditioned synthetic images for underrepresented classes.

**Technologies**
- Language: Python
- Web framework: Flask
- Generative AI: Conditional GAN (cGAN)
- Frontend: HTML and CSS

**Food Categories**
Example categories include:
- Biryani
- Chapati
- Corn
- Fried rice
- Jalebi
- Mango
- Watermelon

**Limitations**
- Recognition quality depends on training data, model weights, and supported food categories.
- Dietary suggestions are general information, not a substitute for professional medical advice.
  
**Future Enhancements**
- Add more regional and international food categories
- Improve synthetic image quality and evaluate dataset balance
- Add camera-based, real-time food detection
