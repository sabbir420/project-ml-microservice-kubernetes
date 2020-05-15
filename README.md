# project-ml-microservice-kubernetes
A project on operationalizing a Machine Learning Microservice API

<h2>Project Overview</h2>

<p>There is a pre-trained, sklearn model that has been trained to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios, and so on. The data, which was initially taken from Kaggle, on the data source site. This project is to operationalize a Python flask app—in a provided file, app.py—that serves out predictions (inference) about housing prices through API calls. This project could be extended to any pre-trained machine learning model, such as those for image recognition and data labeling.
</p>

<h2>Project Tasks</h2>

<p>This project goal is to operationalize this working, machine learning microservice using kubernetes, which is an open-source system for automating the management of containerized applications. The tasks of this project are:
</p>
<ul>
    <li>Test your project code using linting</li>
    <li>Complete a Dockerfile to containerize this application</li>
    <li>Deploy your containerized application using Docker and make a prediction</li>
    <li>Improve the log statements in the source code for this application</li>
    <li>Configure Kubernetes and create a Kubernetes cluster</li>
    <li>Deploy a container using Kubernetes and make a prediction</li>
    <li>Upload a complete Github repo with CircleCI to indicate that your code has been tested</li>
</ul>

***

<h2>Environment Setup</h2>

<ul>
  <li>Create a <code>Makefile</code></li>
  <li>Create a <code>Dockerfile</code></li>
  <li>Run <code>make setup</code> to create a virtual environment and activate it</li>
  <li>Run <code>make install</code> to install necessary dependencies</li>
</ul>

<h2>Linting App</h2>

<ul>
  <li>Run <code>make lint</code> to lint the app</li>
</ul>

<h3>Testing App</h2>

<ul>
  <li>Run <code>make test</code> to test the app</li>
</ul>

<h2>Running App</h2>

<ul>
  <li>Standalone: <code>python app.py</code></li>
  <li>Run in Docker: <code>./run_docker.sh</code></li>
  <li>Run in Kubernetes: <code>./run_kubernetes.sh</code></li>
  <li>Make prediction: <code>./make_prediction.sh</code></li>
</ul>

<h2>Uploading to the Docker Hub</h2>

<ul>
  <li>Run <code>./upload_docker.sh</code> to upload the api to the Docker Hub</li>
</ul>