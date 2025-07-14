# Fingerprint Doorlock System Using ESP32
A System that can be use for doolocks. I used logic similar on how modern camera works through Cloud.
Features:
- Can Add or Delete user by Owner
- Generate Serial Number for unique ID of a doorlock

How the system flow:
- User will register their account first
- STEP1: User will then login. A prompt will appear saying that says connect the doorlock to the wifi and input the generated serial number
- Using a different device, User connects to the doorlock's Access Point (AP)
- User configure the doorlock's internet by connecting the Access Point IP to the user's wifi in the interface.
- STEP2: User will now Add the owner's name and input their fingerprint.
- STEP3: If all the steps are successfully completed, the user will deriect to the web app dashboard.
