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
|---|---|---|---|---|---|---|
| 25 mm lens (CS-mount)  |  6 USD |  https://www.aliexpress.com/item/32813129966.html |  Entry |  
| 6 mm lens (CS-mount) | 3 USD  |  https://www.aliexpress.com/item/32633024819.html | Entry  |  
|   |   |   |   |   | 


## GPS/GLONASS



|  Name | Refresh rate  | Price  | Buying link  |  Level |  Comments |   |
|---|---|---|---|---|---|---|
|  GlobalSat BU-353-S4 USB GPS Receiver |  40USD |   |   |   |   |   |
|   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |







