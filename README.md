# Microcontroller_Fun_Projects
This repository consists of projects which I have done in my spare time. I am using a Arduino Uno Microcontroller with other eletrical components to simulate small projects. Some projects contained are:
1. LED_ON_AND_OFF 
2. Potentiometer_Reading
3. Face_Detection_Program
## Virtual environment
First a virtual environment must be set up for the programs so they can have 
### Run the virtual environment
You can install venv to your host Python by running this command in your terminal:
```
pip install virtualenv
```
To use venv in your project, in your terminal, create a new project folder, cd to the project folder in your terminal, and run the following command:
```
python<version> -m venv <virtual-environment-name>
```
On a mac, to activate your virtual environment, run the code below:
```
source env/bin/activate
```
Now libraries can be installed on the virtual environment. A requirements.txt can then be made by running:
```
pip freeze > requirements.txt
```
Instead of having to install each dependency one by one, they could just run the code below to install all your dependencies within their own copy of the project:
```
pip install -r requirements.txt
```
To deactivate your virtual environment, simply run the following code in the terminal:
```
deactivate
```
## LED_ON_OFF
Flashing the LED found at pin 13 using Python, Arduino IDE and a Arduino UNO microcontroller. This project was done using the tutorials on OpenCV.
## Potentiometer_Reading
A potentiometers output ADC values are read using Python, Arduino IDE and a Arduino UNO microcontroller. It is then shown visually on a image by changing the dimensions of a elipse. This project was done using the tutorials on OpenCV.
## Ultrasonic_Sensor
A ultrasonic sensor is used to sense distances between objects using output ADC values which are read using Arduino IDE and a Arduino UNO microcontroller. 
## Face detection program
A cvzone project used to flash a RGB light on a Arduino UNO using pycharm and Arduino IDE.