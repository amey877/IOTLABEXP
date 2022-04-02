
# Project Title

A brief description of what this project does and who it's for
Description:
The scanning module handles the Bluetooth Low Energy scanning for your application. You can use it to find advertising devices and establish connections with them.By changing the device name you can narrow down the scan to devices of a specific type.Here we are changing the device name of the peripheral device(nrf52832) by sending through BLE to the central device(mobile phone) .The device name is sent through advertising packets to a central device with every advertisng interval.The central device(mobile phone) scans the advertsing device with a new device name.
Installation:
1 nRF SDK
Before you start developing, program and run a precompiled application on your development kit to ensure that the kit functions as expected and the communication between your computer and development kit works.
step1.Download the latest compatible version of the nRF5 SDK. The nRF5 SDK contains precompiled HEX files of the most common examples. Extract the zip file into a folder of your choice. For information about which SDK supports which IC revisions, check the compatibility matrices. 
step2.Power up the development kit:
Connect one end of a micro-USB 2.0 cable to the Universal Serial Bus (USB) connector on the kit and the other end to one of your PC's USB host ports. 
Slide the power switch to ON. 
Observe that LED1 starts blinking. 
step3.Open a file explorer and confirm that the development kit has appeared as a removable  
drive named JLINK.
step4.  In the folder where you extracted the nRF5 SDK, navigate to examples\ble_peripheral       
          \ble_app_hrs\hex. 
step5. Select the HEX file that corresponds to your development kit and copy it to the JLINK drive.         
step6. Download and install the Nordic nRF Toolbox app from Google Play or App Store
       The development kit will now restart and run the application. Note that while restarting, the 
        that while restarting, the JLINK drive will be disconnected.
step7. Open nRF Toolbox               
step8.Tap HRM.
step9.Tap Connect.
step10.Select Nordic_HRS
2. The nRF Connect SDK:
The recommended way to install the nRF Connect SDK is through an app are
 1.nRF Connect for Desktop
 2.nRF Connect for Phone
    1.nRF Connect for Desktop:
    visit  Link to  install nRF connect for Desktop https://www.nordicsemi.com/Products/Development-tools/nRF-Connect-for-desktop/Download#infotabs .
    step 1 open the link and select the version for Desktop.
    step 2.Save the .exe file to your hard drive. 
    step 3:Open the .exe file & run the file and complete the Installation.
    2.nRF Connect for Phone
    Download from playstore.
3. Keil MDK-ARM Development kit :
   Visit https://www2.keil.com/mdk5/ for installing keil.

4. nrf Command line Tools:
   Visit  link to  install  nrf Command line Tools as  https://www.nordicsemi.com/Products/Development-tools/nRF-Command-Line-Tools/Download.

Documents:
1. Installing guide for nrf5sdk https://infocenter.nordicsemi.com/pdf/getting_started_nRF5SDK_ses.pdf
2. Installing guide for nrfconnect Desktop https://infocenter.nordicsemi.com/index.jsp?topic=/struct_nrftools/struct/nrftools_nrfconnect.html.




