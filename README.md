# YOLO Wildfire Object Detector

This repo includes a custom object detector trained to identify wildfires. It is a modification of https://github.com/AntonMu/TrainYourOwnYOLO YOLO custom object detector. 

## Getting started
### Installation
First, clone this repository with
```bash
git clone https://github.com/tanvithoria/wildfire_detection
mv wildfire_detection TrainYourOwnYOLO
cd TrainYourOwnYOLO/
```
Create Virtual **(Linux/Mac)** Environment:
```bash
python3 -m venv env
source env/bin/activate
```
Make sure that, from now on, you **run all commands from within your virtual environment**.

#### Install Required Packages [Windows, Mac or Linux]
Install required packages (from within your virtual environment) via:

```bash
pip install -r requirements.txt
```
If this fails, you may have to upgrade your pip version first with `pip install pip --upgrade`.

## Quick Start (Inference only)
To test the fire detector on test images located in [`TrainYourOwnYOLO/Data/Source_Images/Test_Images`](/Data/Source_Images/Test_Images) run the `WildFire_detect.py` script in the root folder with:

```bash
python WildFire_detect.py
```
