# pneumonia_recognition
Creating a CNN model to recognize x-ray images of lungs with pneumonia.

<center><h1>Motivation</h1></center>

<p>
    In this project, we are going to create a Convolutional Neural Network (CNN) model that can predict if a patient has or not pneumonia based on X-ray images (the dataset could be found in <a href = "https://www.kaggle.com/datasets/vivek468/beginner-chest-xray-image-classification" target = "_blank">Chest X-Ray Image Classification</a>. Our main motivation is to facilitate pneumonia recognition by increasing speed and also by increasing the accuracy. With that, we will create diagnosis more precisely. Therefore, we will split this project in these parts:
</p>

<ol>
    <li>Importing libraries;</li>
    <li>Reading the dataset:
        <ol>
            <li>Understanding the dataset;</li>
            <li>Preprocessing the training set;</li>
            <li>Preprocessing the test set;</li>
        </ol>
    </li>
    <li>Creating the CNN model;</li>
    <li>Training the CNN model:
        <ol>
            <li>Training;</li>
            <li>About the results;</li>
        </ol>
    </li>
    <li>Making predictions:
        <ol>
            <li>predict_image;</li>
            <li>For healthy lungs;</li>
            <li>For unhealthy lungs;</li>
            <li>Analising the whole test set.</li>
        </ol>
    </li>
    <li>Exporting the model;</li>
</ol>
