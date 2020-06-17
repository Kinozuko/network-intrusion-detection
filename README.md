# Network Instrusion Detection

This dataset was provided by [Kaggle](https://www.kaggle.com/sampadab17/network-intrusion-detection)

```
The dataset to be audited was provided which consists of a wide variety of intrusions simulated in a military network environment. It created an environment to acquire raw TCP/IP dump data for a network by simulating a typical US Air Force LAN. The LAN was focused like a real environment and blasted with multiple attacks. A connection is a sequence of TCP packets starting and ending at some time duration between which data flows to and from a source IP address to a target IP address under some well-defined protocol. Also, each connection is labelled as either normal or as an attack with exactly one specific attack type. Each connection record consists of about 100 bytes.
For each TCP/IP connection, 41 quantitative and qualitative features are obtained from normal and attack data (3 qualitative and 38 quantitative features) .The class variable has two categories:

* Normal
* Anomalous

```

* Colaboratory
* Jupyter
* Python script

In this repository we will create three models for a network instrusion detection, the models are:

* Naive bayes (87.69% accuracy)
* Linear SCV (92.93% accuracy)
* K-Neighbors (98.88% accuracy)

## Structure

```
.
├── .gitignore 
├── README.md
├── requirements.txt
├── data/
│   └── dataset.csv
├── jupyter/
│   └── nid.ipynb
├── script/
│   └── nid.py
├── models
│   ├── gnb_model
│   ├── neigh_model
│   └── svc_model
```

## Runing Project

### Installing Dependecies

* pip install -r requirements.txt

### Running Script

* python script/nid.py

### Running Jupyter Notebook

* jupyter notebook jupyter/nid.ipynb

### Running Colaboratory

* [See in Colaboratory](https://colab.research.google.com/drive/1omTEYcbPcWe46uSGH1YlXHAN-4aw63xL?usp=sharing)