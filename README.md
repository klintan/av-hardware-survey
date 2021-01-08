# Self driving car/Robotic hardware/sensor buying guide
There are a bunch of both courses and blog posts out there that tells you what types of sensors are important and most common in the self driving car perception stack. There are fewer which gives you practical advice and gives an exact specification of which sensor they use and how much they cost. 
Now as most of you already have guessed, most of the sensors are industrial grade and out of range for most regular people. Which is why this guide will focus on "entry level" sensors that are "cheap" and "medium level" sensors which are more performant but more expensive. 

Hopefully all of these sensors are possible to get a hold of for a regular person (aka no business).

It also contains a section on hardware setup for AV:s but it can be read/used for any kind of robotics system that needs a perception stack.

## Typical base hardware setup:

- Main Forward Camera: 150 m (about 492 feet) typically, condition dependent
- Wide Forward Camera: 60 m (about 197 feet) typically, condition dependent
- Narrow Forward Camera: 250 m (about 820 feet) typically, conditions dependent
- Forward Looking Side Camera: 80 m (about 262 feet) typically, condition dependent
- Rear View Camera: 50 m (about 164 feet) typically, condition dependent
- Rearward Looking Side Camera: 100 m (about 328 feet) typically, condition dependent
- Radar: 160 m (about 524 feet) typically, conditions dependent
- Ultrasonic: 8 m (about 26 feet) typically, condition dependent
- LIDAR: 200 m (about 656 feet) typically, condition dependent


## Cameras

*Listed prices are mostly for second hand equipment*

|  Name |  Resolution | Refresh rate |  Price  | Buying link  |  Level |  Comments |
|---|---|---|---|---|---|---|
|  ELP USB camera |  1280x720 |  30fps | 33USD  |  https://www.aliexpress.com/item/32861618476.html | Entry  | CS lens mount, USB  |
|  Leopard Imaging |  - |  - | 200 - 700USD  |  https://leopardimaging.com/product-category/usb30-cameras/usb30-box-cameras |  Medium/High | Some big brands use Leopard imaging cameras, industrial grade. LI-USB30 sometimes available on Ebay  |
|  Flir PointGrey Blackfly/Grasshopper |  - |  - |  50 - 1000USD |  https://www.ebay.com/sch/i.html?_from=R40&_trksid=p2380057.m570.l1311.R1.TR4.TRC2.A0.H0.Xpointgrey+.TRS0&_nkw=point+grey+camera&_sacat=0 | Medium/High | Some big brands use PointGrey, and Udacity Carla for instance.  |

## Lenses

You will need lenses for the cameras, for different use cases. In the Baidu Apollo setup, two 6 mm lenses and one 25 mm lens is used for the front facing cameras.

|  Name | Price  | Buying link  |  Level |  Comments | 
|---|---|---|---|---|
| 25 mm lens (CS-mount)  |  6 USD |  https://www.aliexpress.com/item/32813129966.html |  Entry |  |
| 6 mm lens (CS-mount) | 3 USD  |  https://www.aliexpress.com/item/32633024819.html | Entry  |  |
|   |   |   |   |   | 


## GPS/GLONASS


|  Name | Refresh rate  | Price  | Buying link  |  Level |  Comments | 
|---|---|---|---|---|---|
|  GlobalSat BU-353-S4 USB GPS Receiver | 5 Hz |  40 USD  |  https://www.thegpsstore.com/USGlobalSat-BU353-S4-USB-GPS-Receiver-P3219.aspx?gclid=Cj0KCQjw4qvlBRDiARIsAHme6ouhT1VkBXncsu2cn0sHCkJv9OfCNZAtqkjigDu8GIUxzPiZB_Ql0nsaAusgEALw_wcB | Entry  |   | 
| Emlid Reach RS+ (GPS+RTK)  | 5 Hz  | 800 USD  |  https://emlid.com/reachrs/#rs-order |  Medium |    |
| Swiftnav Duro/Piksi  |  10 Hz |  2295 USD |  https://www.swiftnav.com/store?category=Duro+Starter+Kit |  Medium/High |   |


## IMU


|  Name |  Refresh rate | Price | Buying link | Level | Comments |
|---|---|---|---|---|---|
|  SparkFun Razer 9-DOF |   |  36 USD |  https://www.sparkfun.com/products/14001 | Entry  |   | 
|  Lord Microstrain 3DM-GX5-xx |   | 300 USD   |  https://www.ebay.com/sch/i.html?_nkw=microstrain | Medium |   | 
|  Xsens MTI-xx |   |  300USD |  https://www.ebay.com/sch/i.html?_nkw=xsens&_sop=12 | Medium/High | Used by a lot of the big brands  | 
| TinkerForge IMU Brick 2.0 | | 65 USD | https://www.tinkerforge.com/en/shop/bricks/imu-v2-brick.html | Entry | | 

## LIDAR

This is now only 3D LIDAR. For the missing buying links, search Ebay for the model.

| Name |  Range | FOV  | Refresh rate | Price  | Buying link  |  Level |  Comments   |   | 
|---|---|---|---|---|---|---|---|---|
| LeddarTech M16  | 110m  | 19x3.0 degrees  | 6.25 Hz  | 500 USD  |   | Low/Medium  |  | |
| LeddarTech VU8 | 34m  |  100x3.0 degrees |   | 100 - 500 USD  |   |  Low/Medium  | | |
| BeneWake CE30 | 30m  |  60x4 degrees  | 30Hz  |  1000 - 1500 USD |   |  Low/Medium | |
| Livox Mid40/Mid-100  | 90m  |  38.4 circular | | 600 - 1500 USD  |  https://store.dji.com/product/livox-mid?vid=48991 | Low/Medium  |   | A good review https://msadowski.github.io/livox-mid40-review/ explaining the special circular FoV etc.|
| Velodyne VLP-16  |  100m |  360x30 degrees | 10Hz (varies)  | 2000 - 3000 USD  |   | Medium/High  | |


## Radar

|  Name |  Range | Price  |  Buying link | Comments |
|---|---|---|---|---|
|  Lexus Toyota 2015 - 2016 (88210-07010) |  2 - 150 m (?) | 100 USD  |  https://www.ebay.com/itm/FACTORY-OEM-2015-2019-TOYOTA-HIGHLANDER-ADAPTIVE-CRUISE-CONTROL-DISTANCE-SENSOR/143449107826?epid=658112985&hash=item21663bad72:g:g6wAAOSwkYZdyLjx | Short range radar |
|   |   |   |   | | 


## SONAR / Ultrasonic sensors

| Name  | Detecting distance | Price | Buying link  |  Comments |
|---|---|---|---|---|
|  Car Parking Sensors 4 Radars Kits 22mm Ultrasonic | 0.3 - 2m | 20USD |  https://www.aliexpress.com/item/33045825229.html?spm=a2g0o.productlist.0.0.65801263deosGH&algo_pvid=817b9f1f-c294-459c-bfb7-6f29adc523d2&algo_expid=817b9f1f-c294-459c-bfb7-6f29adc523d2-8&btsid=a40102de-f056-4ac1-94ed-838e0f0bb54d&ws_ab_test=searchweb0_0,searchweb201602_8,searchweb201603_53 |   |
|   |   |   |   |


## Wheel encoders



| Name  |  Price | Buying link  |  Comments |
|---|---|---|---|
| US Stock Encoder 600P  | 20 USD  |  https://www.ebay.com/itm/US-Stock-Encoder-600-P-R-5V-24V-Incremental-Rotary-AB-2-Phase-6mm-Shaft/371842303935?ssPageName=STRK%3AMEBIDX%3AIT&_trksid=p2060353.m1438.l2649 |   |
|   |   |   |   |

# References and resources

### General AV hardware stack
https://www.youtube.com/watch?v=V8LA0_bb9LI

### Radar
https://www.denso-ten.com/business/technicaljournal/pdf/23-2.pdf

https://github.com/frk2/toyoyta_radar_control_can




