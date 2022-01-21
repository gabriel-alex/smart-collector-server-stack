# Sigfox to NodeRed

**Prerequisite** 
* Start all the services
* Having the NodeRed accessible from internet
* Setup the API on NodeRed

## Configuration Procedure

1. Connect to Sigfox Backend 
Go to [https://backend.sigfox.com/welcome/news](https://backend.sigfox.com/welcome/news) and connect with your login and password. 

2. Go to the device list in the "deviceType" tab  

![Device Type tab](.\Sigfox\Sigfox-callback1.png)

3. Select device you want to configure  

![Device List](.\Sigfox\Sigfox-callback2.png)

4. Go to callback configuration through the "Callback" link in the left menu

![Device List](.\Sigfox\Sigfox-callback3.png)

5. Add a new callback with the "new" button at the upper right coner of the page

![Device List](.\Sigfox\Sigfox-callback4.png)

6. Select a custom callback 

![Device List](.\Sigfox\Sigfox-callback5.png)

7. Add the parameters to connect to NodeRed

You have to provide the URL that point to the NodeRed service. Then, if the authentication has been activated, you have to provide here as a bearer token. 
Finally, you have to transfer the data that has been received by Sigfox. Once configured, you save it by clicking on "Ok" button. 
![Device List](.\Sigfox\Sigfox-callback6.png)