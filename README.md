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
Q: How to fetch the sensor data of [SensorTag](http://www.ti.com/ww/en/wireless_connectivity/sensortag2015) from [IBM IoT Platform](https://quickstart.internetofthings.ibmcloud.com/#/device/)?  

A: You should satisfy the following requirements:  
(1) Have [SensorTag](http://www.ti.com/ww/en/wireless_connectivity/sensortag2015) with Push to cloud selected in Cloud View  
If you do not  have a SensorTag, you can use your online computer to simulate the SensorTag in [this link](https://developer.ibm.com/recipes/tutorials/use-the-simulated-device-to-experience-the-iot-foundation/).  

(2) Install Python SDK for IoT
* [Python 2.7/3.5](https://www.python.org/)
* [PyPI](https://pypi.python.org/pypi)
* [IoT Python](https://github.com/ibm-messaging/iot-python)

(3) Get DeviceID of your SensorTag  


Q: How to deploy my application in [IBM Bluemix](https://www.ng.bluemix.net)?  

A: 

## Helpful resources
* [Simplelink SensorTag](http://www.ti.com/ww/en/wireless_connectivity/sensortag2015)
* [TI E2E Community for Bluetooth Smart](http://e2e.ti.com/support/wireless_connectivity/f/538)
* [IBM IoT Foundation service](https://quickstart.internetofthings.ibmcloud.com/#/device/)
* [IBM Bluemix Doc](https://www.ng.bluemix.net/docs)
 * [Internet of Things Starter](https://www.ng.bluemix.net/docs/starters/IoT/iot500.html)
 * [SDK for Node.js](https://www.ng.bluemix.net/docs/#starters/nodejs/index.html#nodejs)
* [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
