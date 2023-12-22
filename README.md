# ML
The content-based filtering method recommends several objects based on the similarity of the recommended objects with the selected object. Content based filtering uses two user vectors which in this case are the user preference and pet datasets, but recognizes that there may be other information available about the user and/or pet that can improve prediction. The additional information is fed to a neural network which then generates user and pet vectors.

## Dataset
Source: Reliable Animal Information Websites on the Internet Like Whiskas and Rolay Canin.

## Model
2 sequential neural network models are made which will be connected to the dot product. the benchmark for the model built is the loss value. where the loss value obtained reaches 0.006.

## Deploy Model
**Convert Model info H5 format
**Make API Endpoint Using Flask
**Create Container Using Docker and push to Cloud Run
