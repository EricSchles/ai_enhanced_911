# AI Enhanced 911

The goal of this project is to make use of ML to make it easier to call for help in an emergency:

## Major features

General datasets:

* https://gengo.ai/datasets/the-best-25-datasets-for-natural-language-processing/ 
* http://deeplearning.net/datasets/

* audio processing 
	* [a set of audio processing tools](https://github.com/faroit/awesome-python-scientific-audio)
	* [Think Digital Signal Processing](http://greenteapress.com/thinkdsp/html/index.html)
	* [blog post intro](https://www.pythonforengineers.com/audio-and-digital-signal-processingdsp-in-python/)
	* [A collection of Audio Files](https://github.com/rosuH/YSL)
* natural language processing
	* [an introduction to nlp](https://www.nltk.org/book/)
	* [a list of libraries](https://github.com/keon/awesome-nlp#user-content-python)
	* [raw text](https://www.gutenberg.org/)
	* [nlp datasets](https://github.com/niderhoff/nlp-datasets)
* web interface
	* [an introduction to flask](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world)
* geo positioning
* mutli channel call for help
* facial recognition
	* [a great set of tutorials on image processing](https://www.pyimagesearch.com/)
	* [opencv docs](https://docs.opencv.org/3.0-beta/doc/py_tutorials/py_tutorials.html)
	* [image dataset](https://gengo.ai/datasets/20-best-image-datasets-for-computer-vision/)

## Engineering Best Practice

* git tutorials
* coding best practices
* testing
* CI
* CD
* containers
* file storage
* documentation

## Understanding the phases of a machine learning engineering project

* Defining the system
* Designing the functionality
* Researching the current AI solutions in the space
* Learning (or relearning) the necessary technology
* Classical Statistics Goes Here
	* Exploratory Data Analysis
	* Hypothesis validation / rejection
	* Modeling and feature engineering
	* Model visualization and performance tuning
* Classical Software Engineering Goes Here With Support For the ML
	* Building connections from your model to your application, typically via HTTP or some other protocol
	* building out the rest of the system to support the machine learning portion
	* establishing the infrastructure to ensure latency requirements for the model are met
	* establishing model dashboards to ensure the models results are clear and make sense
	* establishing what qualifies as model drift, and therefore necessitates retraining of the model, or selecting a new model

