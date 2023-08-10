# Allied Vision Adapter Board CSI-2 for Nvidia Jetson Orin Nano Development Kit

![orin_nano_apapter_board](/Images/orin_nano_adapter_board.png)
This repository contains open hardware design files for an adapter board supporting the Allied Vision Alvium CSI-2 camera pinout to NVIDIA's Orin Nano Development Kit, created by Allied Vision.
The board allows the user to interface with one Alvium MIPI CSI-2 compatible camera over a Flexible Flat Cable (FFC) connector.

You can also purchase the adapter from [Allied Vision](https://www.alliedvision.com/en/products/accessories/interface-connections/#!?cameraInterfacefilter=10) or from our [distributors](https://www.alliedvision.com/en/avt-locations/avt-distributors/).

## Getting Started

These instructions will get you a copy of the design files to make your own adapter boards for development and testing purposes. 
The board can be produced and assembled using the provided design files. Please take a look at the mechanical layers for more information regarding the PCB stackup recommended for fabrication. 

More information is available on our website:

* [User Guide (PDF)](https://cdn.alliedvision.com/fileadmin/content/documents/products/accessories/embedded/user-guide/Jetson-Orin-Nano_Adapter_User-Guide.pdf)
* [Accessories webpage](https://www.alliedvision.com/en/products/accessories/interface-connections/#!?cameraInterfacefilter=10), 
* [Accessories download webpage](https://www.alliedvision.com/en/support/accessory-documentation/)
* [Alvium CSI-2 download webpage](https://www.alliedvision.com/en/support/technical-documentation/alvium-csi-2-documentation/) 

### Prerequisites

* A running installation of Altium.
* A PCB producer & PCBA manufacturer or some soldering skills.
* Supported SOMs:
	* NVIDIA Jetson Orin Nano Developer Kit 
	* All Raspberry Pi type 22-pin CSI-2 compatible boards (not tested, no driver available)
* One supported MIPI CSI-2 FPC cable
	* Allied Vision product numbers 12316, 12317, 12318, 18947
* One Allied Vision [Alvium CSI-2 camera](https://www.alliedvision.com/en/products/embedded-vision-cameras.html)

### Installing

Open the *CSI2-ORIN-NANO_Rev01.PrjPcb* project file in your Altium environment.

## Built With

* [Altium Designer 22](https://www.altium.com/altium-designer/de)
 
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
