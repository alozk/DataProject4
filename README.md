# Classification of X-Ray images
The challenge is to face a Kaggle competition where you will compete for the highest score. In this case, we are going to decide that your technical ability will be the one to evaluate you in a completely objective way. In order to perform this challenge, you must download the attached dataset and make the prediction of the images cataloged in the test dataset.

These files are radiological images so your job will be to train a predictive model capable of determining which part of the body has been X-rayed. Classifying a body part from an X-ray image may seem trivial, but having it automated can be key to the whole field of deep learning in medical imaging. In many hospitals, when a physician requests multiple image acquisitions, an accession number is created for each body part (e.g., knee, ankle, and leg), but the registration of the corresponding images is often incorrect within each accession number.

The incorrect registration of body parts in radiographs is a relevant problem, because if, for example, you want to extract a knee dataset using PACS filtering (database where medical images are stored in a hospital) using the study description, you will often extract images with several body parts. Moreover, if a model is created to classify diseases in some specific body part, the implementation of the model in clinical practice will be almost impossible. On the one hand, imagine that a model is created to detect pneumonia on chest radiographs. To implement that model, we must be sure to obtain only chest radiographs. Otherwise, we may end up trying to diagnose pneumonia from a skull X-ray, which makes no sense.

# Steps:

 1. Get the images from Kaggle competition 👉 kaggle_get_images.ipynb
 2. Analyze the images (get the img size) 👉 image_size.ipynb
 3. Train the cnn model (classify them) 👉 cnn_model.ipynb
