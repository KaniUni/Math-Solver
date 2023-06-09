# Math Solver
### Abstract

The display of the project starts with a webpage that allows users to write a mathematical expression. The data is collected and sent to a Flask API and then it uses the CNN model which detects the input and convert it into a proper mathematical expression fed to WolframAlpha API to generate solution. This solution is finally displayed on the web page.

![alt text](https://raw.githubusercontent.com/KaniUni/Math-Solver/main/screenshot.png)

### How to Run
First we'll have to run our API. There are two ways to run it.
1. Install all the packages written in `requirements.txt`. We can do it by typing `pip install requirements.txt` in our cmd or terminal. Run the `api.py` file and update the value of `URL` in the `api-url.js` with the localhost url the server is running on and finally open `index.html`.
2. Open `API.ipynb` on Google Colab, also upload the `model.h5` file there. Try to use the GPU runtime, as that will be faster. Then run all the cells. At the last cell we'll get an URL generated by Flask-Ngrok. update the value of `URL` in the `api-url.js` with this url and finally open `index.html`.


### Tech Stack Used:
1. ML Model - Tensorflow

2. API - Flask, WolframAlpha API

3. Webpage - HTML, CSS, JS


