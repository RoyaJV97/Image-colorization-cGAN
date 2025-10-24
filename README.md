# 🎨 Image Colorization with Conditional GANs

This project explores image-to-image translation using **Conditional Generative Adversarial Networks (cGANs)** to colorize grayscale images. The model is trained to generate colorized versions of black-and-white images, guided by paired training data.

## 🧠 What I Did

- Implemented a **cGAN architecture** using **PyTorch**
- Trained on paired grayscale/color image datasets
- Designed a **U-Net-based generator** and **PatchGAN discriminator**
- Benchmarked performance against a **pretrained ResNet18** baseline
- Achieved improved color fidelity and better structural consistency
- Visualized output vs ground truth side-by-side in the notebook

## 🧪 Key Tools & Libraries

- Python
- PyTorch
- torchvision
- NumPy, Matplotlib

## 📁 Files

- `FINAL_DNN.ipynb`: Full notebook including training loop, loss curves, visual outputs, and comparison with baseline model

## 🖼️ Sample Output

The Images below are the personal Images which we tested with our trained model, the first raw are the gray-scale Images, the second are the generated ones, and the lst raw are the original pictures  

<img width="631" height="362" alt="image" src="https://github.com/user-attachments/assets/532eca0f-4b14-4b3f-8554-102fa796ddb7" />


## 🔍 Why This Matters

Image colorization is a meaningful application of deep learning in areas like:
- Restoration of historical photographs
- Medical imaging
- Satellite data visualization

This project also serves as a hands-on example of working with **generative models**, adversarial training, and evaluating with pretrained classifiers.

## 📌 Author

[Roya Joulaei Vijouyeh](https://github.com/RoyaJV97)
[Mojtaba Roshana](https://github.com/mojee13)
[Asal Rangrazi]

---

👩‍🔬 *Interested in how this connects to Physics-Informed Machine Learning or scientific data? Reach out! I'm currently applying to PhD programs in AI and scientific ML.*

