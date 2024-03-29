# 🔎 Reverse-Image-Search🔍

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)[![forthebadge](https://forthebadge.com/images/badges/its-not-a-lie-if-you-believe-it.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/built-by-developers.svg)](https://forthebadge.com)
## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Technical Aspect](#technical-aspect)
  * [Installation](#installation)
  * [To Do](#to-do-in-future-)
  * [Bug / Feature Request](#bug---feature-request)
  * [Technologies Used](#technologies-used)
  * [License](#license)
  * [Contact](#contact-)


## Demo
![](demos.gif)

## Overview

It is a replication of google image search engine for finding similar images in our database using artificial intelligence. It is a project which uses cosine distance or finding the similarity which is an amazing application of cosine similarity.

## Motivation

When we are searching some thing in google there is a option in right of search bar i.e image search. When I noticed it I started thinking of its working and researched and started a project similar to it using deep learning.

## Technical Aspect

1. Firstly I collected images of 6 types of fruits.Dataset contains arount 1157 images.I am providing the link of the dataset [here](https://drive.google.com/drive/folders/1RFnObzTjFsrGVOzpw6q_WYQQJoehglA2?usp=sharing).

2. Now I used pretrained VGG16 model and excluding the last output layer and collected the feature vectors of all the images.

3. Then we need to take a query image and collect the feature vector similarly as said in step 2.

4. Now I calculated the the cosine distance from query features to collected feature vector and sorted it.

5. According to cosine similarity, lesser the distance more the similarity.

6. Then using ajax and flask deployed it to the development server.


## Installation
1. If you like my project do 🌟🌟 my repository.

2. Clone my repository by using following command in terminal/Command Prompt.

```sh
https://github.com/ksdkamesh99/Reverse-Image-Search.git
```

3. Install the Packages: 
```sh
pip install -r requirements.txt
```

4. At last, push in the command:
```sh
python app.py
```

5. Go to ` http://127.0.0.1:5000/` and enjoy the application.

## To Do in future:-
1. UI of website need to be improved.

2. Need to add some more images in the dataset so as to improve the accuracy.

## Bug / Feature Request
If you find a bug (gave undesired results), kindly open an issue [here](https://github.com/ksdkamesh99/Reverse-Image-Search/issues/new/) by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue [here](https://github.com/ksdkamesh99/Reverse-Image-Search/issues/new/). Please include sample queries and their corresponding results.

## Technologies Used


[<img target="_blank" src="https://keras.io/img/logo-small.png" width=200>](https://keras.io/api/applications/) [<img target="_blank" src="https://www.fullstackpython.com/img/logos/scipy.png" width=170>](https://docs.scipy.org/doc/scipy/reference/generated/scipy.spatial.distance.cosine.html)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=200>](https://flask.palletsprojects.com/en/1.1.x/) 



## License

MIT License

Copyright (c) 2020 Kota Sai Durga Kamesh

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


## 📧Contact:-
For any kind of suggesstions/ help in code Please mail me at ksdkamesh99@gmail.com.


