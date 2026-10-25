# Atichat Kangsamut

## Featured Projects

### [Travel Style Segmentation & Drift Monitoring](https://github.com/DewPerawis/ITCS355-Final-PJ-6688012-6688121-6688193)

**MLOps · Monitoring & Reliability · Team Project**

Collaborated with Perawis Buranasing and Supitsara Tanasarnsukstid on a three-person ITCS355 project for segmenting travel preferences.

- The team built a K-Means inference service that accepts 24 travel-category ratings and returns one of five segments, distance from the cluster center, an uncertainty flag, and the model version; Gaussian Mixture Models were evaluated as a comparison.
- The project combines DVC and MLflow for reproducible training and model tracking with FastAPI, Docker, Azure, and GitHub Actions for deployment and CI/CD.
- Monitoring and validation include offline input-drift checks, a recorded Azure Monitor alert, and a semantic canary used to detect a deliberate segment-mapping failure and verify recovery.

**My team responsibilities:** Dashboards, drift checks, alerts, failure and recovery demonstration, cost reporting, and the model card, as documented in the project proposal.

**Project stack:** Python, scikit-learn, FastAPI, Docker, DVC, MLflow, Azure, GitHub Actions.

[View repository and saved demo evidence](https://github.com/DewPerawis/ITCS355-Final-PJ-6688012-6688121-6688193)

### [Road Damage Detection](https://github.com/atichatz/road-damage-detection)

**Computer Vision · Deep Learning · Team Project**

Collaborated with Perawis Buranasing on a two-person project for **ITCS352 Introduction to Deep Learning**, detecting four road-damage categories in the RDD2022 Japan subset: longitudinal cracks, transverse cracks, alligator cracks, and potholes.

- The team compared SSD MobileNetV3, Faster R-CNN ResNet-50 FPN, and YOLOv8s across four training runs, including a comparison of 640 px and 832 px input resolutions.
- The selected YOLOv8s model achieved **mAP@0.5 = 0.562** and **mAP@0.5:0.95 = 0.265**, with reported inference time of approximately **11 ms per image** on an RTX 4060 Laptop GPU.
- The project includes dataset preparation, exploratory analysis, saved evaluation results, and a Gradio application supporting image, video, and webcam inference, with a Docker demo.

**Project stack:** Python, PyTorch, torchvision, Ultralytics YOLOv8, OpenCV, Gradio, Docker, TensorBoard.

[View repository](https://github.com/atichatz/road-damage-detection) · [Report](https://github.com/atichatz/road-damage-detection/blob/main/docs/report-gr6.pdf) · [Presentation](https://github.com/atichatz/road-damage-detection/blob/main/docs/presentation-slide-gr6.pdf)

### [National Cuisine Classification](https://github.com/nithit-cypherX/cuisine-classification)

**Applied NLP · LLM Prompt Engineering · Team Project**

Collaborated with [Nithit Teeraworawit](https://github.com/nithit-cypherX) on a Python project that classifies recipes into six cuisine categories using ingredient lists.

- Contributed to the implementation of an experimental pipeline comparing zero-shot prompting with dynamic few-shot prompting using examples retrieved from ChromaDB.
- The team implementation compares three text representations (bag-of-words, sparse, and dense) and four example counts (0, 4, 8, and 16), covering 12 experimental conditions on the same 90-recipe test set.
- The project includes prediction logging and evaluation with accuracy, macro F1, per-class F1, and confusion matrices.

**Project stack:** Python, OpenAI API, ChromaDB, Sentence Transformers, pandas, scikit-learn, Matplotlib, Seaborn.

**My role:** Implementation contributor in a two-person academic project.

[View repository](https://github.com/nithit-cypherX/cuisine-classification) · [My commit history](https://github.com/nithit-cypherX/cuisine-classification/commits?author=atichatz)
