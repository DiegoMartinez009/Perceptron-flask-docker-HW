# Perceptron-flask-docker-HW

-Course: Real Time Analytics

-Student: Diego Ronaldo Rodriguez Martinez

-ID: dr110074 

This Repository deploys a perceptron sklearn model using Flask and a Docker container.

### The model is trained on the Iris dataset, we can test the API by queries it for the predicted class with 2 variables:

-*sepal lenght = 5.2*

-*petal length = 2.3*

## In browser 

Paste this URL into your browser bar:

`"http://localhost:3333/api/v1.0/predict?sl=5.2&pl=2.3"`

Result should display like:
```
{"features":[5.2,2.3],"predicted_class":1}
```

As the image below:

<img width="722" src="https://user-images.githubusercontent.com/99198580/171046295-d517a9f0-26c6-4e06-8f1a-caf228ac2bbc.png">






