# OpenGesture using Habana DL1 Instances on AWS EC2
OpenGesture for Africa Sign Language Detection using Habana Gaudi Accelerators
# OpenGesture for African Sign Language 
Platform | Build Status |
-------- | ------------ |
AWS EC2 | [![Build status](https://ci.appveyor.com/api/projects/status/swutsp1bjcc56q64/branch/master?svg=true)](https://github.com/AfricaMachineIntelligence/opengesture)

<p align="center">
  <img width="460" height="300" src="https://github.com/TebogoNakampe/XRDrive-Sim/blob/master/Code/hand.gif">
</p>

## Audience

The code in this repository is authored for computer-vision and machine-learning developers and researchers interested in developing hand gesture applications using AWS EC2 DL1 instances.

# Data Collection

To train the OpenGesture Model data was collected using Intel RealSense D435.

#### Defining Data as Hand Gestures.
Depth                 |  Color
:-------------------------:|:-------------------------:
![](https://github.com/AfricaMachineIntelligence/OpenGesture/blob/main/Assets/11_Depth_adobespark%20(1).png)  |  ![](https://github.com/AfricaMachineIntelligence/OpenGesture/blob/main/Assets/11a_Color_adobespark_adobespark.png)

#### African Languages Labels

| ENGLISH      | SETSWANA       | ZULU               | XHOSA         |
| :---         |     :---:      |      :---:         |     :---:     |
| One          | Nngwe          | Kunye              | Inye          |
| Two          | Pedi           | Kubili             | Zimbini       |
| Three        | Tharo          | Kuthathu           | Zintathu      |
| Four         | Nne            | Kune               | Zine          |
| Five         | Tlhano         | Kuhlanu            | Zintlanu      |
| Six          | Thataro        | Isithupha          | Zintandathu   |
| Seven        | Supa           | Isikhombisa        | Isixhenxe     |
| Eight        | Robedi         | Isishiyagalombili  | Sisibhozo     |
| Nine         | Robongwe       | Isishiyagalolunye  | Lithoba       |


Download [OpenGesture Depth and Color Dataset](https://github.com/AfricaMachineIntelligence/opengesture3d-data)<br>

* [Image Classification Custom Model: OpenGesture4Habana](PlanetGesture-AWS-Habana.ipynb) - This notebook includes all the necessary scripts required to train a custom classifier the gesture.blob using TensorFlow and Keras for and also includes Intel OpenVINO Toolkit's model optimzer and inference engine plugins implementation code to create a blob using AWS EC2 DL1 instances.

## Running the OpenGesture for South African Sign Language 
* Preparation
	* Install Requirements
		```bash
		git clone https://github.com/TebogoNakampe/OpenGesture4Habana.git
		cd OpenGesture4Habana
		```
* Run
	* Use Jupyter notebook [Image Classification Custom Model: OpenGesture4Habana](PlanetGesture-AWS-Habana.ipynb) to train the OpenGesture Deep Learning Model with AWS EC2 DL1 instances.
