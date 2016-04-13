# SensorTag-Experiment
Requirements and FAQs for the experiment of SensorTag

## Requirements
1.  Provide several real pictures of your SensorTag and identify all the chips of sensors in the pictures.  
You can find the following model pictures [here](http://www.ti.com/ww/en/wireless_connectivity/sensortag2015/tearDown.html).
![SensorTag-back](http://www.ti.com/ww/en/wireless_connectivity/sensortag2015/images/sensorTag-teardown-bluetooth-03.jpg)
![SensorTag-front](http://www.ti.com/ww/en/wireless_connectivity/sensortag2015/images/sensorTag-teardown-bluetooth-04.jpg)
2.  Describe the function and name of the sensor chip you used. You can find the information of the related sensors [here](http://www.ti.com/ww/en/wireless_connectivity/sensortag2015/tearDown.html).  
3.  Select an application for the sensor you used. Summary the description, results and potential development plan of your application in a final report, and 1 and 2 as well. 

  > i.e., I used the sensor of [TMP007](http://www.ti.com/product/tmp007) to measure the enviroment temperature in the Minhang campus of Shanghai Jiao Tong University.  

## FAQs
Q: I have a SensorTag around, how can I get started to view the sensor data?  
A: If you are an iOS user, this [article](https://developer.ibm.com/recipes/tutorials/find-your-sensortag-device-id-in-ios/) provides detailed descriptions. If you are an android user, similar operations should be performed.

Q: I want to fetch the sensor data from [IBM IoT Cloud](https://quickstart.internetofthings.ibmcloud.com/#/device/), how can I achieve that in my computer?  
A: You should do the following steps,  
(1) Ensure that your SensorTag with 'Push to cloud' turned on in 'Cloud View'.  
If you do not have a SensorTag around, you can use your computer to simulate as SensorTag, and this [article](https://developer.ibm.com/recipes/tutorials/use-the-simulated-device-to-experience-the-iot-foundation/) provides detailed descriptions.  

(2) Install IBM Python SDK for IoT in your computer.
* [Python 2.7/3.5](https://www.python.org/downloads)
* Upgrade [pip](https://bootstrap.pypa.io/get-pip.py)  
Download the get-pip.py and run in command lines: python get-pip.py  
* [IoT Python](https://github.com/ibm-messaging/iot-python)  
If you are not familiar with Python language, [Python Tutor](http://pythontutor.com/) can help you exercise Python programming so that you can master Python quickly, maybe in three days or a week.  

(3) Get DeviceID of your SensorTag, run in the command lines as below,  
> python simpleApp.py -I deviceID  

Q: How to deploy my application in [IBM Bluemix](https://www.ng.bluemix.net)?  
A: [Register](https://docs.internetofthings.ibmcloud.com/getting_started/register/index.html)  

## Helpful resources
* [Simplelink SensorTag](http://www.ti.com/ww/en/wireless_connectivity/sensortag2015)
* [TI E2E Community for Bluetooth Smart](http://e2e.ti.com/support/wireless_connectivity/f/538)
* [IBM IoT Foundation service](https://quickstart.internetofthings.ibmcloud.com/#/device/)
* [IBM Bluemix Doc](https://www.ng.bluemix.net/docs)
 * [Internet of Things Starter](https://www.ng.bluemix.net/docs/starters/IoT/iot500.html)
 * [SDK for Node.js](https://www.ng.bluemix.net/docs/#starters/nodejs/index.html#nodejs)
* [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)  
