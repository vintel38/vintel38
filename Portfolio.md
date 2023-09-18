# Vincent Arrigoni - Machine Learning Portfolio

[![Github](./img/github.png)](https://github.com/vintel38)

I am currently a double graduate aerospace engineer working at ArianeGroup on Ariane6 program and also deeply interested in Machine Learning technics. After one engineering diploma in France (equivalent Master) and the Master of Science of Politecnico di Milano in Space Engineering, I had my first professionnal experiences in French big and small aeronautical companies before moving to ArianeGroup. I am currently working on validation of the flight software of this Ariane6 rocket. For some years, I have been interested in Machine Learning technics and now I want to grow in this field. 

In 2023, I decided to enroll in OpenClassrooms Machine Learning Engineer formation to start a new professional chapter. This brought me the necessary knowledge in Machine Learning and the code practice needed to design, build and validate AI systems on real life cases. It also brought me the confidence necessary to take over AI products so today I am looking for freelance missions around Deep Learning products to gain hands-on experience. This document contains my project portfolio around Deep Learning activities I had over the last few years. 

## Projects

During this long path to the ML degree, I had possibilities to participate to several projects to test my Machine Learning building and coding capabilities. These projects pushed me to delve into new AI topics or ML frameworks to improve my capacities. 

- Satellite Imagery Processing Hackathon - [ESA Copernicus Masters](https://copernicus-masters.com/) 2021 : This competition enables participants to propose innovant ideas around Copernicus imagery to an assembly of official space organizations (ESA, CNES, DLR, AIRBUS) to tackle environnmental issues with a technical and economic point view. I proposed to identify and locate on Very High Resolution imagery buildings whose roof is particularly dark that feeds the Heat Island Phenomenon and can be white-painted to fight the large scale phenomenon. Once the opensource [INRIA dataset](https://project.inria.fr/aerialimagelabeling/) was preprocessed, I trained and used Mask RCNN algorithm of the [FAIR Detectron2](https://github.com/facebookresearch/detectron2) framework to infer on the position of these roofs. Then, the Google Maps API was used to reverse-geocode the position and find building addresses to prepare a possible territorial large scale plan. The jury underlined the technical and societal interest in [my solution](https://github.com/vintel38/RoofTop-Project) while the value proposition lacked structure. With this competition, I learnt to think the technical solution as part of a bigger project. 

- Dogs Breeds Image Classification hosted on [Huggingface Spaces](https://huggingface.co/spaces/vintel38/OCS-P7-IML) from OpenClassrooms MLE courses: From an [opensource dataset](http://vision.stanford.edu/aditya86/ImageNetDogs/) of dogs annotated pictures, the challenge was to acheive the highest score in term of classification accuracy to classify numerous dog breeds. I used Transfer Learning and fined-tuning on EfficientNetv4 implemented in Keras framework to acheive 97% accuracy classification over the different breed classes. This project taught me how to identify different ways that can be leveraged to improve at best the model performances. 

- Forecasting Mini-Course Sales on [Kaggle](https://www.kaggle.com/competitions/playground-series-s3e19) inside Playground Series - Season 3, Episode 19 inside OpenClassrooms MLE courses: From a provided sales dataset, the goal of the competition was to train a model and evaluate it to the task of predicting sales in future over a variety of sold item. I used [FAIR Prophet](https://facebook.github.io/prophet/) model to predict the sales of different products in a post-covid environment and I managed to land a score among the first third of the participants. 

## Frameworks and Code languages

| Framework    | Description |
| -------- | ------- |
| Tensorflow [![Tensorflow image](./img/tenforflow.png)](https://www.tensorflow.org/?hl=fr)  |  A popular Machine Learning library in Python which enables most of the ML algo now outhere and with which I have worked quite a bit   |
| Pytorch [![Pytorch image](./img./pytorch.png)](https://pytorch.org/) |  Another powerful Python Library which is largely in production and with which I run a few ML algorithms  |
| Scikit-Learn  [![scikit image](./img/scikit.png)](https://scikit-learn.org/)  |  A set of ML tools in Python to be able to quickly a baseline model on any task  |
| Keras  [![Keras image](./img/keras.png)](https://keras.io/)  |  A sub library of Tensorflow which gathers a large portion of Computer Vision Classification algorithms   |
| Google Colab  [![Colab image](./img/colab.png)](https://colab.research.google.com/?hl=fr)  |  A platform on Google servers to be able to emulate and execute Python code. I own a powerful Google Colab Pro account on this platform for more demanding computations  |
| Huggingface Spaces  [![HG image](./img/hugging.png)](https://huggingface.co/spaces)  |  A platform online that easily enables to have a graphical and interactive view of the AI solution that is being developed  |
| FAIR Detectron2  [![Detectron2](./img/detectron2.png)](https://ai.meta.com/tools/detectron2/)  |  A Faceboook framework that assembles a large number of Computer Vision SOTA algorithms in the different CV sub-domain |


Vincent Arrigoni 09/2023