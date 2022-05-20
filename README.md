# Custom-Object-Detection-YOLOv4
Building a custom object detection model to recognize potholes with the YOLOv4 object detection model file.

# Steps
Gather the images for training the model

Annotate your image dataset with any annotation tool like LabelBox or LabelImg

Convert your annotated image to tfrecord format (I used roboflow for this conversion)

Split the dataset into training and test (typically in 80:20 ratio)

Add your new dataset to the code in the Prepare Tensorflow 2 Object Detection Training Data section

Run the code in the notebook and run inference on your test data
