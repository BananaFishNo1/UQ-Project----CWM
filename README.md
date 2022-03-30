# UQ-Project----CWM
This is a exercise group project

/***************Fishing Man Team**************/

/**
Team leader: Ruihao Li 46313566
Team member: Xinyu Geng 45968624/Jianwei Ni 46294919/Haoxin Li 45995983
*/

About our application: https://deco3801-fishingman.uqcloud.net/

1. Based on the size of the mobile device, it is recommended to use it in the mobile browser or after the installation of the Android device. 
Although we have optimized the PC side, there may be display errors due to browser size changes.

2. We use UQzone as the proxy server and develop based on CodeIgniter PHP framework. 
Therefore, all our codes are distributed on the server in the MVC mode for easy reading and modification.

3. We use Hbuilder as the developer platform and encapsulate the web app.

4. Regarding the login test, please log in with the following account and password:
	Account Number: DECO7381
	Password: 123456 (this password is only used for the account test, the actual registration please follow the prompts).

5. Regarding Android device testing, please install ‘CWM.apk’ before testing. 
It should be noted that, because of UQzone's secondary login verification, you need to log in with your UQ account before you can log in to the application.

6. It needs to be declared that the pictures used in the entire development process are all copyright-free pictures, source: https://www.pexels.com/

7. Regarding the knowledge base, all knowledge comes from: 
Brisbane City Concil
https://www.brisbane.qld.gov.au/clean-and-green/rubbish-tips-and-bins

8. Code Path:
htdocs/demo/application/views
htdocs/demo/application/controllers
htdocs/demo/application/models

9. Database
We use Mysql database deployed on UQzone to store user data.

10. Scanning algorithm
In the jupyter notebook environment, load vgg16 for scanning algorithm training. 
Through multiple cross-validation, the recognition rate is calculated to reach 70%. 
Finally, export the ‘initial_version.h5’ algorithm identification file to use. 
