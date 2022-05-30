# Perceptron-flask-docker-HW

-Course: Real Time Analytics

-Student: Diego Ronaldo Rodriguez Martinez

-ID: dr110074 

This Repository deploys a perceptron sklearn model using Flask and a Docker container.

### The model is trained on the Iris dataset, we can test the API by queries it for the predicted class with 2 variables:

-*sepal lenght = 3.5*

-*petal length = 1.2*

## In browser 

Paste this URL into your browser bar:

`http://localhost:3333/api/v1.0/predict?sl=3.5&pl=1.2`

Result should display like:
```
{"features":[3.5,1.2],"predicted_class":-1}
```

As the image below:

<img width="722" src="https://user-images.githubusercontent.com/99198580/171046875-643e3021-8695-4672-ab29-7098d075d6df.png">

Where predicted_class: -1 the predicted class is Iris setosa.



