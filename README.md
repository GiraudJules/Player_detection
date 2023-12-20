# Hockey Player Detection and Tracking

This POC repository contains a Jupyter Notebook demonstrating the use of YOLOv8 for player detection and tracking in sports videos, especially in field hockey video from French Elite Championship.

## Overview

The notebook in this repository illustrates the process of using the YOLOv8 model to detect and track players in field hockey videos. It showcases how to load a pre-trained YOLOv8 model, finetune it, process video frames, and visualize the results.

➡️ ![Player Detection and Tracking notebook](player_detection_and_tracking.ipynb)

## Dataset Creation and Testing with new video

### Building the Dataset

The dataset was created using video footage from one of my field hockey games in the 22/23 season. Key steps in the dataset creation included:
- Extracting frames from the game video.
- Annotating players and other objects of interest in these frames using Roboflow.

### Testing on New Game Footage

The model trained on this dataset was then tested on a video from a 23/24 season game. This test aimed to evaluate the model's generalization and effectiveness in detecting and tracking players in a different setting.

![Detection example from video](/outputs/test_image_from_video.png)

## Collaboration and Feedback

I am always open to collaborations and would love to hear feedback or ideas on how to improve this project from Hockey Coach or Video Analyst. If you have suggestions, questions, or would like to contribute to this project, please feel free to reach out or submit a pull request.

### Connect and Discuss

I am also interested in discussions about sports analytics, computer vision in sports, and other related topics. Let's connect and share ideas! You can find me on:
- LinkedIn: [My LinkedIn](https://www.linkedin.com/in/jules-giraud/)
- Email: jules.giraud@student-cs.fr
