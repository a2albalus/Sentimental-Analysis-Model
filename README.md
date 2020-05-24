# Sentimental-Analysis-Model

This project was implemented on Amazon SageMaker. It implements a sentimental analysis model: it takes as input a movie review and outputs either 'Positive' if the model thought it was a positive review or 'Negative' if it thought it was a negative review. This model is then deployed as an HTTPS endpoint through which input and output to the model can be sent and recieved.

The files are:

1- SageMaker Project.ipynb: which is a notebook that does the data analysis and training of the model.
2- train.py: includes the training model used for classification into positive or negative reviews.
3- report.html: shows an example of the functioning of the trained model.
4- predict.py: is the function needed by the endpoint to make process the input and make predictions about its sentiment.
5- index.html: is an example of the endpoint URL

