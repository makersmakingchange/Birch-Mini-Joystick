# Birch Mini Joystick
The Birch Mini Joystick is a small, proportional joystick that has a sliding motion and can be used for adaptive gaming. It has a small range of motion of ±2mm and requires approximately 115 grams-force to fully deflect. It is low profile, with a height of 2.4 mm with the standard topper. This joystick has interchangable toppers and an optional camera mount adapter. The Birch Mini Joystick is available in two variants: a USB variant (U) and an analog, non-USB variant (A). The joystick and enclosure are the same in both variants and differ by the cable and internal electronics.

The USB variant (U) has a cable with a USB-A connector. It acts as a USB HID gamepad with a single joystick and is compatible with a variety of devices including PC and the USB ports of the Microsoft Xbox Adaptive Controller. The deadzone of this variant can be adjusted through a serial interface.

The analog, non-USB, variant (A) has a cable with a 3.5 mm TRRS audio plug (i.e., headphone jack). It is compatible with the X1 or X2 analog input ports on the Microsoft Xbox Adaptive controller as well as the [Enabled Controller](https://makersmakingchange.com/project/enabled-controller/).

The current version (v0.2) of the design is a fully functional and tested protoype. A number of updates are on the way:
- Integration of one or more switches for buttons
- Updated code for improved user response profiles
- Additional mounting options
- Additional topper options
- Basic mouse functionality

<img src="Photos/Birch-Mini-Joystick-U.jpeg" width="500" alt="Picture of the Birch Mini Joystick, USB variation, it is blue and small with MMC written on the side and an arrow on top.">

<img src="Photos/Birch-Mini-Joystick-A.jpeg" width="500" alt="Picture of the Birch Mini Joystick, analog (A) variation, it is blue and small with an arrow on top.">

<!---
## More info at
- [Makers Making Change Project Page](<Add link>)
- [Makers Making Change Forum Thread](<Add link>)
--->

<!--- 
## How to Obtain a Birch Mini Joystick
### 1. Do it Yourself (DIY) or Do it Together (DIT)

This is an open-source assistive technology, so anyone is free to build it. All of the files and instructions required to build the Birch Mini Joystick are contained within this repository. Refer to the Maker Checklist below.

### 2. Request a build of this device

If you would like to obtain a Birch Mini Joystick , you may submit a build request through the [MMC Library Page](https://makersmakingchange.com/project/device-name/). The requestor is responsible for the cost of materials and any shipping.

### 3. How to build this device for someone else

If you have the skills and equipment to build this device, and would like to donate your time to create the switch for someone who needs it, visit the [MMC Maker Wanted](https://makersmakingchange.com/maker-wanted/) section.
--->

## Getting Started

### 1. Confirm Which Variant Is Required
The Birch Mini Joystick comes in both USB (U) and non-USB (A) variants. The non-USB version uses a [TRRS](https://www.sparkfun.com/products/11580) lead to conncet to an existing gamepad such as the Microsoft Xbox Adaptive Controller (XAC) or [Enabled Controller](https://makersmakingchange.com/project/enabled-controller/). The USB version has its own microcontroller and emulates an HID gamepad allowing for direct PC use as well as some customisation of the joystick response profile. Ask the user which one they would like. There are separate sets of documentation for each joystick variant.

Other available joysticks can be found through the [Joystick Selection Guide](https://makersmakingchange.com/resource/analog-joystick-selection-guide/)

### 2. Read the Makers Checklist

The Makers Checklist contains a list of tasks to complete to build the device.

### 3. Order the Off-The-Shelf Components

The Bill of Materials lists all of the parts and components required to build the Birch Mini Joystick in the variation of your choice. The main joystick components needs to be ordered online. The rest of the off-the-shelf components are also online or may be available in smaller quantities at your local hardware store or dollar store.


### 4. Print the 3D Printable components

Print the components needed for the Birch Mini Joystick. Make sure to ask the user if they would like any of the optional prints such as toppers or mount adapters.

All of the files and individual print files can be in the [/Build_Files/3D_Print_Files](/Build_Files/3D_Print_Files/) folder.

### 5. Assemble the Birch Mini Joystick

Reference the Assembly Guide for the variation of the joystick you are building for the tools and steps required to build each portion.

## Files
### Documentation
| Document             | Version | [Birch Mini Joystick - U](/Documentation/Birch_Mini_Joystick-U) 														| [Birch Mini Joystick - A](/Documentation/Birch_Mini_Joystick-A)  |
|----------------------|---------|--------------------------------------------------------------------------------------------------------------------------------------|-------------------------|
| Design Rationale     | 0.2     | [Birch_Mini_Joystick_Design_Rationale](/Documentation/Birch_Mini_Joystick-U/Birch_Mini_Joystick_Design_Rationale_v0.2.pdf)       	| [Birch_Mini_Joystick_Design_Rationale](/Documentation/Birch_Mini_Joystick-A/Birch_Mini_Joystick_Design_Rationale_v0.2.pdf)      |
| Maker Checklist      | 0.2     | [Birch_Mini_Joystick-U_Maker_Checklist](/Documentation/Birch_Mini_Joystick-U/Birch_Mini_Joystick-U_Maker_Checklist_v0.2.pdf)     	| [Birch_Mini_Joystick-A_Maker_Checklist](/Documentation/Birch_Mini_Joystick-A/Birch_Mini_Joystick-A_Maker_Checklist_v0.2.pdf)     |
| Bill of Materials    | 0.2     | [Birch_Mini_Joystick-U_Bill_of_Materials](/Documentation/Birch_Mini_Joystick-U/Birch_Mini_Joystick-U_BOM_v0.2.xlsx)     		| [Birch_Mini_Joystick-A_Bill_of_Materials](/Documentation/Birch_Mini_Joystick-A/Birch_Mini_Joystick-A_BOM_v0.2.xlsx)     |
| 3D Printing Guide    | 0.2     | [Birch_Mini_Joystick-U_3D_Printing_Guide](/Documentation/Birch_Mini_Joystick-U/Birch_Mini_Joystick-U_3D_Printing_Guide_v0.2.pdf)     | [Birch_Mini_Joystick-A_3D_Printing_Guide](/Documentation/Birch_Mini_Joystick-A/Birch_Mini_Joystick-A_3D_Printing_Guide_v0.2.pdf)     |
| Assembly Guide       | 0.2     | [Birch_Mini_Joystick-U_Assembly_Guide](/Documentation/Birch_Mini_Joystick-U/Birch_Mini_Joystick-U_Assembly_Guide_v0.2.pdf)     	| [Birch_Mini_Joystick-A_Assembly_Guide](/Documentation/Birch_Mini_Joystick-A/Birch_Mini_Joystick-A_Assembly_Guide_v0.2.pdf)     | 
| User Guide           | 0.2     | [Birch_Mini_Joystick-U_User_Guide](/Documentation/Birch_Mini_Joystick-U/Birch_Mini_Joystick-U_User_Guide_v0.2.pdf)    		| [Birch_Mini_Joystick-A_User_Guide](/Documentation/Birch_Mini_Joystick-A/Birch_Mini_Joystick-A_User_Guide_v0.2.pdf)    |
| Changelog            | 0.2     | [Birch_Mini_Joystick-U_Changelog](/Documentation/Birch_Mini_Joystick-U/Birch_Mini_Joystick_Changelog_v0.2.pdf)     			| [Birch_Mini_Joystick-A_Changelog](/Documentation/Birch_Mini_Joystick-A/Birch_Mini_Joystick_Changelog_v0.2.pdf)     |

### Design Files
 - [CAD Files](/Design_Files)

### Build Files
 - [3D Printing Files](/Build_Files/3D_Print_Files)
 - [Firmware](/Build_Files/Software/OpenAT_Joystick_Software_Birch)

## License

Everything needed or used to design, make, test, or prepare the Birch Mini Joystick is licensed under the CERN 2.0 Weakly Reciprocal license <https://ohwr.org/project/cernohl/wikis/Documents/CERN-OHL-version-2> (CERN-OHL-W).

Accompanying material such as instruction manuals, videos, and other copyrightable works that are useful but not necessary to design, make, test, or prepare the Oak Compact Joystick are published under a Creative Commons Attribution-ShareAlike 4.0 license <https://creativecommons.org/licenses/by-sa/4.0/> (CC BY-SA 4.0).

## Attribution

Hardware and enclosure design: Tyler Fentie and Josie Versloot, Neil Squire

USB Variant software: Milad Hajihassan, Neil Squire

The USB variant software utilizes the [Adafruit TinyUSB Library for Arduino](https://github.com/adafruit/Adafruit_TinyUSB_Arduino) which is made available under an [MIT license](https://github.com/adafruit/Adafruit_TinyUSB_Arduino/blob/master/LICENSE).

The documentation template was created by Makers Making Change / Neil Squire and is used under a CC BY-SA 4.0 license. It is available at the following link: https://github.com/makersmakingchange/OpenAT-Template

---

## About Makers Making Change
<img src="https://www.makersmakingchange.com/wp-content/uploads/logo/mmc_logo.svg" width="500" alt="Makers Making Change Logo">

Makers Making Change is an initiative of [Neil Squire](https://www.neilsquire.ca/), a Canadian non-profit that helps people with disabilities.

We are committed to creating a network of volunteer makers who support people with disabilities in their communities through 3D printing assistive devices. Check out our library of free, open-source assistive technologies with parts and build instructions.

 - Website: [www.MakersMakingChange.com](https://www.makersmakingchange.com/)
 - GitHub: [https://github.com/makersmakingchange](https://github.com/makersmakingchange)
 - Twitter: [@makermakechange](https://twitter.com/makermakechange)
 - Instagram: [@makersmakingchange](https://www.instagram.com/makersmakingchange)



## Contact Us

For technical questions, to get involved, or share your experience we encourage you to visit the [MMC Website](https://www.makersmakingchange.com/), [MMC Forum](https://makersmakingchange.com/forum), or contact info@makersmakingchange.com
