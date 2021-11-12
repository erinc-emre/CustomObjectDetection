# CustomObjectDetection
Senior Project Repository  
## Leaning Status

8/11 - Intro to TensorFlow for Deep Learning - https://classroom.udacity.com/courses/ud187 

4/17 - Stanford Computer Vision - http://cs231n.stanford.edu/ 

4/8 - Getting Started with AI on Jetson Nano - https://courses.nvidia.com/courses/course-v1:DLI+S-RX-02+V2/about 


# PROTECTION OF ELECTRICAL WIRES FROM BIRDS
## AIM:
Birds placed on electrical wires can be disabled or be injured in some cases. In addition to causing vital harm to the
birds, this can also damage power lines. Disruptions and interruptions in the electricity flow may occur as a result
of the instantaneous exit of high voltage and current from a line. This project will detect the devices to be placed in
the determined critical areas and the birds perched on the wires. If the system is detected that the bird has landed
on the wire, it will be ensured that the birds are removed using various methods without harming the birds.

## IMPACT and SCOPE:
Power lines have been in our lives for over 100 years. With the development of technology, our need for electrical
lines has also increased and various modern results have been developed for it. The most common and economical
solution was to increase the number of wires passing through the air and to ensure their strength. As a result of this
situation, there was a serious increase in the power lines and the bird problem gained serious importance. In this
direction, new solutions have started to be researched.

In this direction, electric wires were passed underground in crowded places, especially in city centers. In this way, the
problem of security and visual pollution caused by cables in the air was resolved. However, this is a very long and
costly solution. Since it was very costly and inefficient to use this solution between cities, new solutions were sought.
Today, the plastic coating is applied on the cables in important lines in the air, especially in the inner city lines. In this
way, the connection between the birds and the cables is insulated. Although insulating with plastic is less costly than
underground lines, it is not widely used because it adds an additional cost. In order to use insulated cables, old cables
must be removed and new cables must be inserted. Since the demand is limited, the cost is higher than normal cables
 - Today, various solutions are tried by keeping the cost to a minimum. The most common of these is to put plastic
parts moving with the wind (such as a wind rose) on the wires. The coverage of these parts is very limited and it
is very easy to be damaged by environmental factors.
 - Another common solution is to prevent birds from coming in using sound. This solution has negative effects on
birds and people around may be disturbed by the sound. In addition, its effectiveness is limited as the sound may
vary according to the weather.
 - With various lighting methods, it is possible to remove the birds. however, these lights can have different effects
on other animals in the environment. In addition, the light system must be placed on the entire line, which
requires a very high energy requirement. However, it is not preferred in the market as its efficiency is very low
during the day.
 - Putting a still fake wild animal is one of the most tried methods, but this method is very successful. Some birds
can understand this over time, or the paint of fake wild animals becomes obsolete due to wear over time.

## MATERIAL ve METHODS:
Thanks to today's technology, we can find very economical cameras and motors. Using this advantage, we
produce a new artificial intelligence solution. We place cameras at designated points. We also place special
vibration motors on the target wires. We connect cameras and motors to a private network. Motors and cameras
connect with our computers over this network. Our computers can be site-specific or centrally located. It can be
designed as Online - Offline according to the location of the system. These computers will take the live images
from the cameras and run the image processing algorithm specially designed for the project. If birds are detected
according to the results, a command will be sent to the motors and the birds will be cut off from the wires.
For camera systems, IP cameras suitable for outdoor use can be preferred. Depending on the use of the project,
cameras with various pixels, lenses or 360 degrees can be used. Various versions of these cameras have the feature of
transferring data via Ethernet cable or wirelessly. In this way, we will have flexibility in the project.
Since our computer choice is quite wide, the decision will be made after our image processing algorithm has been
performance tested on various computers. The tests are planned to be carried out on various systems, especially
NVIDIA Jetson, RaspberryPI. The computers must be suitable for the required network connection and be able to run
the image processing algorithm in an uninterrupted and efficient way.
The motors must be selected specifically according to the location and characteristics of the cable. Since the task of
the motors is to vibrate the wires, the thickness, length, material, etc. of the wires are very important. Various
solutions are being considered for the network connection of the selected motors. The power control of the motors can
be done by computers, or it can be controlled by placing a device next to the motors that can make a network
connection. This situation will be decided by testing depending on the resources and conditions in the projects.
The image processing algorithm will be developed using the Python 3 language. It is planned to use ready -made
datasets for this algorithm. However, when necessary, after the camera setup of the project, images from the real
project camera will be taken, labeled and the algorithm will be trained again. For the project, pre -trained YOLO,
CNN, Faster RCNN, etc. object detection algorithms will be tested and special changes will be made when
deemed necessary.

## EXPECTED BENEFITS:
This project plans to both facilitate the work of electricity companies and seriously reduce the human -caused
deaths of birds in nature.
 - As a result of the project, the problems experienced in the power lines will be prevented to a great extent.
 - Bird death and injury will be drastically reduced.
 - Solutions will be offered to electricity companies at affordable costs.
 - The workload of maintenance crews that look after power lines will be reduced.

## REFERENCES:
 - https://en.wikipedia.org/wiki/Electrical_wiring
 - https://www.powerandcables.com/product/cable-protection-covers/
 - https://sciencing.com/do-birds-sit-electrical-wires-6592687.html
 - https://sciencing.com/dont-birds-electrocuted-electric-wires-5180022.html
 - https://birdproofingguide.com/how-to-keep-birds-off-power-lines/
