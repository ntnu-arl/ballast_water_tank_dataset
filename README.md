# Ballast Water Tank Dataset

This repository contains the dataset collected from ballast tanks across three vessels. To maintain anonymity, the ships will be reffered to as "FPSO1", "FPSO2", and "Oil Tanker" (OT).

The dataset is collected using two platforms namely, [RMF-Owl](https://ieeexplore.ieee.org/document/9836115) a collision-tolerant aerial robot, and a handheld sensor setup called Mjolnir. The dataset for RMF-Owl consists of flights from autonomous exploration and inspection missions detailed (and beyond) in the corresponding publication ([link](https://arxiv.org/abs/2311.03838)) as well as additional manual flights.

# Equipment Description

RMF-Owl | Sensor Stick 
|:-------------------------:|:-------------------------:|
|![](images/rmf-owl.png)  |  ![](images/sensor_stick.png) |
|[Dataset](./rmf-owl.md) | [Dataset](./sensor_stick.md)|

## Sensor Setup
Sensor  | RMF-Owl         | Sensor Stick               
:------:|:---------------:|:---------------------:
LiDAR   | [Ouster OS0-64 (Rev-D)](https://ouster.com/products/hardware/os0-lidar-sensor)   | [Ouster OS0-64 (Rev-D)](https://ouster.com/products/hardware/os0-lidar-sensor)        
Camera*  | [Flir Blackfly S 0.4MP Color](https://www.flir.eu/products/blackfly-s-usb3/?vertical=machine+vision&segment=iis) | [Flir Blackfly S 0.4MP Mono](https://www.flir.eu/products/blackfly-s-gige/?model=BFS-PGE-04S2M-CS&vertical=machine+vision&segment=iis) (x2)   
IMU     | [Vectornav VN100](https://www.vectornav.com/products/detail/vn-100) | [Vectornav VN100](https://www.vectornav.com/products/detail/vn-100)   
Radar   | -               | [Texas Instruments IWR6843AOP-EVM Radar](https://www.ti.com/tool/IWR6843AOPEVM)

*For data privacy reasons the faces of people in the images are blurred.


# Summary of Missions

### RMF-Owl
| No. | Ship | Section | Autonomous | Multi-level | Duration (s) |
| --- | --- | --- | --- | --- | --- |
|1  | FPSO1 | side | Yes | No | 225 |
|2  | FPSO1 | side | Yes | No | 300 |
|3  | FPSO1 | side | Yes | No | 154 |
|4  | FPSO1 | side | No | Yes | 450 |
|5  | FPSO2 | side | Yes | No | 300 |
|6  | FPSO2 | side | Yes | No | 380 |
|7  | FPSO2 | bilge | Yes | No | 336 |
|8  | FPSO2 | double bottom | Yes | No | 200 |
|9  | FPSO2 | side | No | Yes | 258 |
|10 | FPSO2 | bilge, double bottom | No | No | 275 |
|11 | OT | side    | Yes | No | 214 |
|12 | OT | side    | Yes | No | 216 |
|13 | OT | side    | Yes | No | 354 |
|14 | OT | side    | Yes | No | 360 |
|15 | OT | side    | Yes | No | 370 |

### Mjolnir
| No. | Ship | Section | Autonomous | Multi-level | Duration (s) |
| --- | --- | --- | --- | --- | --- |
| 1  | FPSO1 | side | N/A | No | 268 |
| 2  | FPSO1 | side | N/A | No | 373 |
| 3  | FPSO1 | side | N/A | No | 357 |
| 4  | FPSO1 | side | N/A | No | 395 |


## Acknowledgements
We would like to acknowledge the support of the Research Council of Norway and our partners in the projects [SENTIENT](https://prosjektbanken.forskningsradet.no/en/project/FORISS/321435?Kilde=FORISS&distribution=Ar&chart=bar&calcType=funding&Sprak=no&sortBy=date&sortOrder=desc&resultCount=30&offset=120&TemaEmne.2=Nanoteknologi) (NO-321435) and [REDHUS](https://prosjektbanken.forskningsradet.no/en/project/FORISS/317773?Kilde=FORISS&distribution=Ar&chart=bar&calcType=funding&Sprak=no&sortBy=date&sortOrder=desc&resultCount=30&offset=60&TemaEmne.1=LTP2+Hav) (NO-317773) in this work.