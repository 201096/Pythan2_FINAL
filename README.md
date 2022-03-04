# ImgClassService
https://mukhtar-py.herokuapp.com/

This group project includes Farabi Samalyk and Daniyar Issenov SE-2014

Requirements
Django server should receive as an input an image
there should be a functionality of uploading the image
Once image is uploaded there should be a functionality of running a CNN based image classifier
Store path to an image and image classifier result in DB
Use as DB MySQL or Postgresql
Deploy the project into Heroku
Tutorial on deploying the Django project in Heroku
https://realpython.com/django-hosting-on-heroku/
<img width="987" alt="image" src="https://user-images.githubusercontent.com/79573421/156716486-b2f6e0a2-1b29-4208-99c0-a59a72db4648.png">

Algorithm for building a CNN image classifier<img width="841" alt="image" src="https://user-images.githubusercontent.com/79573421/156716522-ed333c61-a99e-4374-a3d2-9045575d3559.png">
Build a CNN based image classifier using this guide
https://www.tensorflow.org/tutorials/images/cnn
Train the model using CIFAR10 dataset
Save into the file the model after completion of training using keras
https://www.tensorflow.org/guide/keras/save_and_serialize
Host with Django only trained keras model
Check how to load already trained keras model
https://machinelearningmastery.com/save-load-keras-deep-learning-models/
https://www.educative.io/edpresso/keras-load-save-model


<img width="815" alt="image" src="https://user-images.githubusercontent.com/79573421/156716541-18d4facb-ad63-4860-82d4-fd6916682f97.png">


# Installation
python manage.py makemigrations
python manage.py migrate

#  Usage
python manage.py runserver

# Examples
![image](https://user-images.githubusercontent.com/68743608/156688012-43dc9f79-f51f-4818-95b7-519996910955.png)
![image](https://user-images.githubusercontent.com/68743608/156688033-e225b6f2-0856-4497-8a2c-f343b84f4a8f.png)
![image](https://user-images.githubusercontent.com/68743608/156687978-67125132-1133-466c-8858-5d0c1f5bddb2.png)
