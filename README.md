# Dogs vs Cats

Classification model to distinguishing images of dogs vs cats vs pandas.

Dog             |  Cat             |  Panda
:-------------------------:|:-------------------------:|:-------------------------:
![](docs/dog.jpg)  | ![](docs/cat.jpg)  | ![](docs/panda.jpg)

## Dataset

Images of dogs, cats and pandas

| Dogs | Cats | Pandas |
| :-------------: | :-------------:| :-------------:|
| 1,000 | 1,000 | 1,000 |

Sources:
* Dogs and Cats from: [Kaggle's dogs vs cats](https://www.kaggle.com/c/dogs-vs-cats/data)
* Pandas from: [ImageNet](http://www.image-net.org/) and downloading them manually from URLs
```
(env) $ python src/download_images_from_url.py -a panda
```

## Technologies

* [numpy](http://www.numpy.org)
* [pandas](https://pandas.pydata.org/)
* [matplotlib](https://matplotlib.org/)
* [scikit-learn](https://scikit-learn.org/)
* [pillow](https://pillow.readthedocs.io/)
* [keras](https://keras.io)
* [tensorflow](https://www.tensorflow.org/)
* [jupyter](https://jupyter.org/)

## Deployment

### Virtual Environment using Bash

1. Creation of a virtual environments done by executing the command venv
2. Command to activate virtual environment
3. Install dependencies
4. List the libraries installed on your environment
5. Do your work!
6. When you are done, the command to deactivate virtual environment
```
$ python3 -m venv env/
$ source env/bin/activate
(env) $ pip install -r requirements.txt
(env) $ pip freeze
(env) $ ...
(env) $ deactivate
```

## Resources

* Deep Learning for Computer Vision with Python by Dr. Adrian Rosebrock: https://www.pyimagesearch.com/deep-learning-computer-vision-python-book/