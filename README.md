# fashion-recommendations-system-
Project Name: Fasion Recommendation System for Ecommerce A Deep learning based streamlit web app which can recommened you various types of fasion products with respect to your choices.
Recommender systems are the systems that are designed to recommend things to the user based on many different factors. These systems predict the most likely product that the users are most likely to purchase and are of interest to. Companies like Netflix, Amazon, etc. use recommender systems to help their users to identify the correct product or movies for them.


DATA SETS:
![WhatsApp Image 2024-01-17 at 16 30 42_d4148c57](https://github.com/aashish1malik/fashion-recommendations-system-/assets/144604675/03555b36-414c-43aa-afc7-6ee9abdc17e5)
https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset/code

Once the data is pre-processed, the neural networks are trained, utilizing transfer learning from ResNet50. More additional layers are added in the last layers that replace the architecture and weights from ResNet50 in order to fine-tune the network model to serve the current issue. The figure shows the ResNet50 architecture
![WhatsApp Image 2024-01-17 at 16 44 36_dfe76e3c](https://github.com/aashish1malik/fashion-recommendations-system-/assets/144604675/4f72dfad-e0b6-42e0-9cdf-918c1f95ed78)

BUILT WITH
**OpenCV** - Open Source Computer Vision and Machine Learning software library
**Tensorflow** - TensorFlow is an end-to-end open source platform for machine learning.
**Tqdm** - tqdm is a Python library that allows you to output a smart progress bar by wrapping around any iterable.
**streamlit** - Streamlit is an open-source app framework for Machine Learning and Data Science teams. Create beautiful data apps in hours, not weeks.
**pandas** - pandas is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool, built on top of the Python programming language.
**Pillow** - PIL is the Python Imaging Library by Fredrik Lundh and Contributors.
**scikit-learn** - Scikit-learn is a free software machine learning library for the Python programming language.
**opencv-python** - OpenCV is a huge open-source library for computer vision, machine learning, and image processing. - Scikit-learn is a free software machine learning library for the Python programming language.
**opencv-python** - OpenCV is a huge open-source library for computer vision, machine learning, and image processing.
**css** -Cascading Style Sheets (CSS) is a stylesheet language used to describe the presentation of a document written in HTML or XML (including XML dialects such as SVG, MathML or XHTML). CSS describes how elements should be rendered on screen, on paper, in speech, or on other media
**Html**-HTML stands for Hyper Text Markup Language. HTML is the standard markup language for creating Web pages. HTML describes the structure of a Web page. HTML consists of a series of elements.
**bootstrap**- Bootstrap is a free, open source front-end development framework for the creation of websites and web apps. Designed to enable responsive development of mobile-first websites.
**javascript**-JavaScript (JS) is a cross-platform, object-oriented programming language used by developers to make web pages interactive. 




PLAN OF ACTION

1 ) Import Model: Import model resnet50 using keras with preprocessing_input to just process the image.

2)Extract Features: Pass  images to restnet50 model and extract features and then flatten the features to convert into 1d vector. Extracted features and images has to be stored into pickle files so that while recommendation we pass index of resultant features will get images in return.

3)3. Load Extracted features: To get recommendation for given query point using distance metrics


4)4. Save Images: We use streamlit to make this system. Create one upload button, that will provide browse option then click on upload image will bed saved it into uploads folder in your local.


5)5. Generate Recommendation: Now features got stored and will pass new query image to resnet50 model, it will generate features which will flatten further. Here we use Euclidean distance metrics to find out recommended 5 Nearest Neighbors or look similar images.




images:
![WhatsApp Image 2024-01-17 at 16 09 28_a368ae12](https://github.com/aashish1malik/fashion-recommendations-system-/assets/144604675/24c830c3-0748-4f53-a543-e2b7978436b1)
![WhatsApp Image 2024-01-17 at 16 09 28_daa73781](https://github.com/aashish1malik/fashion-recommendations-system-/assets/144604675/14e031de-b74f-4e77-81ec-b4c6909e4e31)


RESULT VEDIO:
[streamlit-main-2024-01-17-19-01-52.webm](https://github.com/aashish1malik/fashion-recommendations-system-/assets/144604675/72b61e31-1f25-4518-8b6d-6e1b7ae016ef)



CONCLUSION:
In this project, we have presented a novel framework for fashion recommendation that is driven by data, visually related and simple effective recommendation systems for generating fashion product images. The proposed approach uses a two-stage phase. Initially, our proposed approach extracts the features of the image using CNN classifier ie., for instance allowing the customers to upload any random fashion image from any E-commerce website and later generating similar images to the uploaded image based on the features and texture of the input image. It is imperative that such research goes forward to facilitate greater recommendation accuracy and improve the overall experience of fashion exploration for direct and indirect consumers alike.




