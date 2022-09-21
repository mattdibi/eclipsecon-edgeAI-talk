# EclipseCON EdgeAI talk

## Description

In the latest years, Edge AI has gained popularity and opened opportunities to bring AI applications to remote devices. Eclipse Kura, a well established IoT Edge framework, is a good candidate to apply Edge AI concepts to the real world.

In this talk we’ll demonstrate how a machine learning-based application can be easily deployed on an edge device, leveraging the Eclipse Kura features and its interoperability with the NVIDIA Triton™ Server. In particular, we’ll focus on the process of creating a deep learning anomaly detector from scratch: from data collection to training, deployment and inference on the edge.

## Detail

A case-study of the lifecycle of a machine learning-based application within the Eclipse Kura ecosystem: from data collection to training, deployment and inference on the edge.

We'll focus on the process of creating a deep learning anomaly detector from scratch, leveraging the entire Eclipse Kura ecosystem:

- **Data collection**: Kura Wires for collecting diagnostic data from an appliance and upload on the Eclipse Kapua cloud
- **Training**: How can we download the collected data from Eclipse Kapua and develop a model within our preferred ML library (Tensorflow/Keras).
- **Inference**: How can we export the trained model for running on an Inference Server (Nvidia Triton™ Server) which will be our target runtime.
- **Deployment**: How can we deploy this trained model on the edge device leveraging the intuitive Eclipse Kura Wires interface and running the models with Eclipse Kura's inference engine service.

Exciting new and upcoming Eclipse Kura features for Edge AI (AI Model Encryption, New Inference Servers support and more).

## Repository

This repository contains the sources for the presentation and the Jupyter notebook. More information can be found  in their respective folders.
