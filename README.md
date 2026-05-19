# Football Player Detection with YOLOv5

This project focuses on football player and ball detection using YOLOv5 in a Jupyter Notebook environment.

The work was developed as part of an Artificial Intelligence laboratory assignment focused on computer vision, object detection models, and Docker/Jupyter environment configuration.

The laboratory topic was open-ended, and I decided to focus the project on soccer because of my personal interest in sports analytics.

The project was based on open-source YOLOv5 resources and Kaggle examples used for educational purposes.

---

## Laboratory Objectives

- Configure a local environment using Docker and Jupyter Notebook.
- Understand the use of `.pt` models in computer vision.
- Run object detection tests on football match images.
- Test player detection, ball detection, and basic team classification.
- Analyze outputs, metrics, and detection results generated during notebook execution.

---

## Technologies Used

- Python
- YOLOv5
- PyTorch
- OpenCV
- Jupyter Notebook
- Docker

---

## Features

- Football player detection
- Ball detection
- Basic team classification (`Team1` and `Team2`)
- Testing with football match images from different scenarios
- Execution using pretrained `.pt`

---

## Training Configuration

Different execution and training parameters were configured and tested during the laboratory work, including:

- Number of epochs
- Batch size
- Image resolution
- Dataset configuration through `.yaml` files
- Usage of pretrained weights (`yolov5s.pt`)

The notebook also included training metrics and performance graphs originally provided in the Kaggle reference notebook. These graphs were analyzed as part of the learning process to better understand model behavior and inference results.

---

## Results

Several tests were performed using football images from different matches and scenarios.

The obtained results allowed:

- Detection of multiple players on the field
- Ball detection in different situations
- Basic differentiation between teams based on jersey colors
- Analysis of model limitations caused by lighting conditions, distance, and similar uniform colors

Final detection examples and Jupyter Notebook execution screenshots are included in this repository as evidence of the laboratory workflow and obtained results.

---

## References

- YOLOv5 Open Source Implementation
- Kaggle Dataset: Football (Image and Annotated) Data  
  https://www.kaggle.com/datasets/venkatkumar001/football-analysis/data

- Kaggle Notebook: Soccer's Team Prediction Count | YOLOv5  
  https://www.kaggle.com/code/venkatkumar001/soccer-s-team-prediction-count-yolov5
