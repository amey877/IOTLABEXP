
# Project Title
A brief description of what this project does and who it's for
## Description:
We are sending the data without connecting with the app it works as a iBeacon .When using a Non-Connectable advertising packet, the packet is broadcast over the Advertising channels to any Central devices that are Scanning. When received by a Central device, this packet type does not allow for any  Connection Initiation requests.
IBeacon is especially useful for deploying location-aware applications and monitoring user behavior within an area. It was introduced in iOS 7 and utilizes Bluetooth Low Energy (BLE) to send out advertisements that get discovered and utilized by other BLE-capable devices (especially smartphones).
The three main parts in an iBeacon advertising packet:
1 UUID(16 bytes):Specific to the app.
2 Major(2 bytes):  Define sub-region with UUID.
3 Minor (2 bytes): Defines a smaller region within the Major area.
## Installation:
1. nRF SDK
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
          a.nRF Connect for Desktop  
          b.nRF Connect for Phone  
          a.nRF Connect for Desktop:  
          visit  Link to  install nRF connect for Desktop https://www.nordicsemi.com/Products/Development-tools/nRF-Connect-for-desktop/Download#infotabs .  
    step 1 open the link and select the version for Desktop.  
    step 2.Save the .exe file to your hard drive.   
    step 3:Open the .exe file & run the file and complete the Installation.  
    b.nRF Connect for Phone:  
    Download from playstore.
3. Keil MDK-ARM Development kit :
   Visit https://www2.keil.com/mdk5/ for installing keil.

4. nrf Command line Tools:
   Visit  link to  install  nrf Command line Tools as  https://www.nordicsemi.com/Products/Development-tools/nRF-Command-Line-Tools/Download.


Documents:
1. Installing guide for nrf5sdk https://infocenter.nordicsemi.com/pdf/getting_started_nRF5SDK_ses.pdf
2. Installing guide for nrfconnect Desktop https://infocenter.nordicsemi.com/index.jsp?topic=/struct_nrftools/struct/nrftools_nrfconnect.html.

## Acknowledgements

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)


## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.


## Authors

- [@katherinepeterson](https://www.github.com/octokatherine)


## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

## Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Example Color | ![#0a192f](https://via.placeholder.com/10/0a192f?text=+) #0a192f |
| Example Color | ![#f8f8f8](https://via.placeholder.com/10/f8f8f8?text=+) #f8f8f8 |
| Example Color | ![#00b48a](https://via.placeholder.com/10/00b48a?text=+) #00b48a |
| Example Color | ![#00d1a0](https://via.placeholder.com/10/00b48a?text=+) #00d1a0 |


## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.


## Deployment

To deploy this project run

```bash
  npm run deploy
```


## Appendix

Any additional information goes here

